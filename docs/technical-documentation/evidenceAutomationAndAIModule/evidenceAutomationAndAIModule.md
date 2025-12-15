# Evidence of the Automation and Artificial Intelligence Modules


## Evidence of the Automation Module (n8n)

This project contains automated workflows built using n8n, which centralize system workflows and demonstrate the integration of automation within Predictify (GitHub repository).

**The project was designed to:**
-Orchestrate automations related to notifications, reports, and integration processes.

-Define automated workflows that can be directly imported into an n8n instance and executed without manual intervention.


**The current automated workflows implement:**

-Webhooks from the backend, enabling the connection of events and data from the main application to n8n workflows.

-Email automation, facilitating the automatic sending of notifications to users or external systems.

-Automatic report generation, consolidating analyses or metrics without manual intervention.

-Automated notifications sent via email or other platforms such as Slack or Teams, depending on the imported configuration.


The repository and its workflows constitute clear evidence of an automation module in an implementation phase, capable of being executed within an n8n instance and integrated with other system components.

## Evidence of the Artificial Intelligence Module

This repository contains components related to the artificial intelligence logic of Predictify (GitHub repository).
Although it is currently in an early stage with limited visible development activity, the repository was created to:

-Group AI models or functions that are part of the system’s predictive logic.

-Serve as a foundation for integrating intelligent data processing with other components, such as the backend and automation workflows.


The existence of this repository demonstrates that the system architecture includes a dedicated artificial intelligence module, from which predictive models, AI API integrations, or automated analytical logic can be developed and versioned.

## Integration Between Automation, AI, and Backend
The integration between components is based on the use of:
-Webhooks and triggers to initiate automations from events generated in the backend.

-n8n workflows that consume data from the main application to perform automated actions (email generation, reports, notifications).

-An AI repository that centralizes AI models or logic that can be invoked by the backend or n8n workflows.


Although full integration between AI and automation may still be under development, the current structure demonstrates a modular design that allows these components to be progressively extended and interconnected.

