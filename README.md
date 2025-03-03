Version 1.0.0 will be released soon. The preview release is not available for download anymore.

# Kookaburra

<p align="center"> <img src="https://github.com/user-attachments/assets/43b1e8b5-539f-4dfb-8b5b-9a26c4f0ba71" width=600px></p>

Kookaburra is an open-source project for an **extensible automation platform for business solutions** to support application managers – functional and technical – in their day-to-day work.

Organizations using Kookaburra will be able to automate many actions. This can be by custom created (add-on) automations tailored to specific situations as well as by built-in automations. A goal for Kookaburra is to grown the number of built-in automations over time.

Developers will benefit from the automation platform too when implemented. It will save them time to develop application management functionalities which are already available in the organization via configuration and approved to be used.

<p align="center"> <img src="https://github.com/user-attachments/assets/ef103893-fe28-4a17-9ad7-6dea760523c1" width=400px></p>

The automation platform is built with the Microsoft Power Platform and is offered via a managed and unmanaged solution. Although the main targets are business solutions using the Microsoft Power Platform, Kookaburra can be useful for non-Power Platform business solutions too!

Kookaburra consists of three main components:
* Automations, either built-in or add-on. An automation belongs to one of the following automation types:
  * Health
  * Metrics
  * Activity
* A scheduling engine to run automation instances.
* Insights in how automation instances were run.

![KKB_HLD-1](https://github.com/user-attachments/assets/dee1ab0d-37a7-4fa9-9d73-0c6dc8ce0416)

These three main components are translated technically into three modules:

* Agent
  * The scheduling engine to run the automation instances.
* Console
  * Configuration and Insights
* Supervisor
  * Configuration and Insights

The agent and console modules are installed locally, meaning in a Power Platform environment containing one or more business solution(s) to manage. The supervisor module can be implemented in such an environment too but can also have its own Power Platform environment.

Kookaburra can me implemented for a single business solution but with the supervisor module, it can span many environments and many business solutions too. This allows for several types of implementations ranging from one team being responsible for all business solutions to a completely distributed implementation with many teams being responsible for their own business solutions.
