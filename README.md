# Ek Tu Hi Nirankar
# Machine Learning Project- Machine Failure Prediction
## **Project Discription**
For an industry, machines are most important parts because they enables mass production, significantly boost productivity and efficiency, ensures high precision and consistant quality, and they can perform dangerous task to improve safety. These importance are only applicable if the machine is operational, If machine fails, they can lead to production disruptions, increase maintanance cost, safety concerns, and verious other problems. 
So, Machine failure are significant issue in the industrial sector.
Consequently, there is a growing need for a system that can predict machine failure before it fails. This can be possible by utelizing Machine Learning and data analysis technique. 

This project focuses on building a machine learning solution to predict potential machine failures or breakdowns based on various sensor readings and operational parameters. By leveraging predictive maintenance principles, the goal is to enable proactive interventions, thereby reducing costly downtime, optimizing maintenance schedules, and enhancing overall operational efficiency and safety.

## Dataset Discription-
The dataset that we have for this project is collected from various sensors on the machine which represent various operational parameters and failure types of machinery used in steel production. It includes the following key features:

* **ID**: A unique identifying sign to each record
* **Product ID:** Combination of machine type and identifier number
* **Type:** Represents the type of machine, aiding in understanding its operational characteristics, which may be related to machine failure.
Machine type included in this dataset:
  * **L (Low Machine):** These machines are primarily used for lightweight operations or tasks with minimal loads.
  * **M (Medium Machines):** Medium types of machines are versatile and capable of handling various types of tasks or moderate levels of loads.
  * **H (High Machine):** High type machines are designed for heavy duty operations or tasks with substantial loads.

* **Air temperature [K]:** Represents the ambient temperature around the machine, measured in Kelvin (K). Air temperature can be a crucial factor as machines may behave differently in varying ambient temperatures.

* **Process temperature [K]:** Represents the temperature of the process in which the machine is engaged. Certain processes can cause the machine to heat up, which leads to the machine failing.

* **Rotational speed [rpm]:** Indicates the rotational speed at which the machine operates, measured in rotation-per-minutes.
* **Torque[Nm]:** Measures the force that can cause the machine to rotate, measured in Newton meters. Higher torque indicates the higher load on the machine, which increases the possibility of machine failure.
* **Tool wear [Min]:** Represents the cumulative wear on the machine's cutting tool, measured in minutes. High tool wear might indicate the machine is due for maintenance.
* **Machine failure:** A binary indicator specifying whether the machine failed or not.

* **Other Failure modes:** The dataset includes the information about other potential causes of the machine failure. These are also a binary indicator:
  * **TWF (Tool Wear Failure):** Indicate whether machine failed due to tool wear.
  * **HDF (Heat Dissipation Failure):** Indicates whether the machine failed due to inability to dissipate heat.
  * **PWF(Power Failure):** Indicates whether the machine failed due to a Power problem.
  * **OSF (Overstrain Failure):** Indicates whether the machine failed due to being overstrained.
  * **RNF (Random Failure):** Indicates whether the machine failed due to random or unspecified reasons.
