Website: https://www.formsandflows.nl/kookaburra

# Kookaburra
<p align="center"> <img src="https://github.com/user-attachments/assets/9262bd76-f647-4876-b4cb-33c5b117961a" width=600px></p>

Kookaburra is an open-source project providing an extensible automation platform for business solutions to support application managers - functional and technical - in their day-to-day work.

Organizations using Kookaburra will be able to automate many actions. This can be by custom created automations - called add-on automations - tailored for specific situations as well as by built-in automations. The number of built-in automations will grow over time.

Developers will benefit from the automation platform too when implemented. It will save them time to develop application management functionalities which are already available in the organization via Kookaburra - and thus configuration - and approved to be used.

<p align="center"> <img src="https://github.com/user-attachments/assets/80f2f3d8-652c-46ea-8b42-078b0254626a" width=400px></p>

Kookaburra is built with the Microsoft Power Platform. A managed and unmanaged Power Platform solution are provided. Although the main targets are business solutions using the Microsoft Power Platform, Kookaburra can be useful for non-Power Platform business solutions too!

Kookaburra consists of three main components:
* Automations, either built-in or add-on. An automation belongs to one of the following automation types:
  * Health
  * Metrics
  * Activity
* A scheduling engine to run automation instances.
* Insights in how automation instances were run.

![KKB_HLD-1_v2](https://github.com/user-attachments/assets/50c920ce-3859-4282-8ded-ef864b7a7b23)

These three main components are translated technically into three modules:
* Agent
  * The scheduling engine to run the automation instances.
  * All cloud flows related to the built-in automations.
* Console
  * Configuration and Insights
* Supervisor
  * Configuration and Insights

The agent and console modules are installed locally, meaning in a Power Platform environment containing one or more business solutions to manage. The supervisor module can be implemented in such an environment too but can also have its own Power Platform environment.

Kookaburra can me implemented for a single business solution but with the supervisor module, it can span many environments and many business solutions too. This allows for several types of implementations ranging from one team being responsible for all business solutions to a completely distributed implementation with many teams being responsible for their own business solutions.

Kookaburra has 3 main apps:
* configuration app
  * This app is used to configure Kookaburra like adding business solutions and configuring automation instances.
  * This is a canvas app.
* console app
  * This app is used for insights on automation instance runs.
  * This is a canvas app.
* data app
  * This app is used for raw data insights.
  * This is a model-driven app.

Below, a screenshot of the console app with demo (!) data is shown. When all goes well, runs only show green dots ;)

![KKB_Console](https://github.com/user-attachments/assets/c1efbcb3-7f10-4dbc-b537-c20693ff8c59)

Links to content pages can be found on the content page Documentation.

All sources can be found on this GitHub repository.

Release notes are provided on the content page Releases.

If Kookaburra is useful to you, I would very much appreciate it if you bought me a coffee (https://www.buymeacoffee.com/rickbakker) 👍

And with that, I wish you a lot of fun managing your business solutions with Kookaburra 👊

Rick
