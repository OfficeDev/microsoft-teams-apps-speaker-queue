---
page_type: sample
languages:
- PowerApps
products:
- office-teams
description: Speaker Queue is a Teams meetings extensibility app template created to improve your meetings and control time assigned for each topic/speaker 
urlFragment: microsoft-teams-apps-speaker-queue
---

# Speaker Queue App Template

| [Overview](https://github.com/OfficeDev/microsoft-teams-apps-speaker-queue/wiki) | [Deployment guide](https://github.com/OfficeDev/microsoft-teams-apps-speaker-queue/wiki/Deployment-Guide) | [Frequently Asked Questions](https://github.com/OfficeDev/microsoft-teams-apps-speaker-queue/wiki/Frequently-Asked-Questions) |
| ---- | ---- | ---- |

Speaker Queue is a Teams meetings extensibility application created to improve your meetings. It can be used to define topics and control the time assigned to each speaker during online meetings. The application uses Microsoft dataverse to store information about your meeting and associate the set of topics that are going to be used to coordinate speaker while the meeting happens.

## Requirements

You will need permissions to load a Microsoft dataverse solution into Teams as well as Teams administrator permissions to publish the application manifest to all users in your company.

The application uses only Microsoft dataverse for teams and standard Power Apps connectors. No Power Apps premium licenses are required to use the app in your environment. 

Guest users may use the application if they have appropriate Power Apps licenses assigned to them. External users invited to the meeting (not part of the tenant) will not be able to see or interact with the Speaker Queue app.  

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
