---
title: Windows Defender Advanced Threat Protection portal overview
description: Use the Windows Defender ATP portal to monitor your enterprise network and assist in responding to alerts to potential advanced persistent threat (APT) activity or data breaches.
keywords: Windows Defender ATP portal, portal, cybersecurity threat intelligence, dashboard, alerts queue, machines list, settings, machine management, advanced attacks
search.product: eADQiWindows 10XVcnh
ms.prod: w10
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
ms.author: macapara
author: mjcaparas
ms.localizationpriority: high
ms.date: 04/17/2018
---

# Windows Defender Advanced Threat Protection portal overview

**Applies to:**

- Windows 10 Enterprise
- Windows 10 Education
- Windows 10 Pro
- Windows 10 Pro Education
- Windows Defender Advanced Threat Protection (Windows Defender ATP)

[!include[Prerelease information](prerelease.md)]

>Want to experience Windows Defender ATP? [Sign up for a free trial.](https://www.microsoft.com/en-us/WindowsForBusiness/windows-atp?ocid=docs-wdatp-portaloverview-abovefoldlink) 

Enterprise security teams can use the Windows Defender ATP portal to monitor and assist in responding to alerts of potential advanced persistent threat (APT) activity or data breaches.

You can use the [Windows Defender ATP portal](https://securitycenter.windows.com/) to:
- View, sort, and triage alerts from your endpoints
- Search for more information on observed indicators such as files and IP Addresses
- Change Windows Defender ATP settings, including time zone and review licensing information.

## Windows Defender ATP portal
When you open the portal, you’ll see the main areas of the application:

 ![Windows Defender Advanced Threat Protection portal](images/dashboard.png)

- (1) Navigation pane
- (2) Main portal
- (3) Search, Community center, Time settings, Help and support, Feedback

> [!NOTE]
> Malware related detections will only appear if your machines are using [Windows Defender Antivirus](https://technet.microsoft.com/library/mt622091(v=vs.85).aspx) as the default real-time protection antimalware product.

You can navigate through the portal using the menu options available in all sections. Refer to the following table for a description of each section.

Area | Description
:---|:---
(1) Navigation pane | Use the navigation pane to move between the **Dashboards**, **Alerts queue**, **Automated investigations**, **Machines list**, **Service health**, **Advanced hunting**, and **Settings**.
**Dashboards**	| Access the Security operations, the Secure Score, or Threat analytics dashboard.
**Alerts** | View separate queues of new, in progress, resolved alerts, alerts assigned to you.
**Automated investigations** | Displays a list of automated investigations that's been conducted in the network, the status of each investigation and other details such as when the investigation started and the duration of the investigation.
**Machines list** | Displays the list of machines that are onboarded to Windows Defender ATP, some information about them, and the corresponding number of alerts.
**Service health** | Provides information on the current status of the Window Defender ATP service. You'll be able to verify that the service health is healthy or if there are current issues.
**Advanced hunting** | Advanced hunting allows you to proactively hunt and investigate across your organization using a powerful search and query tool.
**Settings** |	Shows the settings you selected during onboarding and lets you update your industry preferences and retention policy period. You can also set other configuration settings such as email notifications, activate the preview experience, enable or turn off advanced features, SIEM integration, threat intel API, build Power BI reports, and set baselines for the Secure Score dashboard.
**(2) Main portal** | Main area where you will see the different views such as the Dashboards, Alerts queue, and Machines list.
**(3) Search, Community center, Time settings,  Help and support, Feedback** | **Search** - Provides access to the search bar where you can search for file, IP, machine, URL, and user. Displays the Search box: the drop-down list allows you to select the entity type and then enter the search query text. </br></br> **Community center** -Access the Community center to learn, collaborate, and share experiences about the product. </br></br>  **Time settings** - Gives you access to the configuration settings where you can set time zones and view license information. </br></br>  **Help and support** - Gives you access to the Windows Defender ATP guide, Microsoft support, and Premier support.</br></br> **Feedback** - Access the feedback button to provide comments about the portal. 

## Windows Defender ATP icons
The following table provides information on the icons used all throughout the portal:

Icon | Description
:---|:---
![ATP logo icon](images\atp-logo-icon.png)| Windows Defender ATP logo
![Alert icon](images\alert-icon.png)| Alert – Indication of an activity correlated with advanced attacks.
![Detection icon](images\detection-icon.png)| Detection – Indication of a malware threat detection.
![Active threat icon](images\active-threat-icon.png)| Active threat – Threats actively executing at the time of detection.
![Remediated icon](images\remediated-icon.png)| Remediated – Threat removed from the machine.
![Not remediated icon](images\not-remediated-icon.png)| Not remediated – Threat not removed from the machine.
![Thunderbolt icon](images\atp-thunderbolt-icon.png)| Indicates events that triggered an alert in the **Alert process tree**.
![Machine icon](images\atp-machine-icon.png)| Machine icon
![Windows Defender AV events icon](images\atp-windows-defender-av-events-icon.png)| Windows Defender Antivirus events
![Application Guard events icon](images\atp-Application-Guard-events-icon.png)| Windows Defender Application Guard events
![Device Guard events icon](images\atp-Device-Guard-events-icon.png)| Windows Defender Device Guard events
![Exploit Guard events icon](images\atp-Exploit-Guard-events-icon.png)| Windows Defender Exploit Guard events
![SmartScreen events icon](images\atp-Smart-Screen-events-icon.png)| Windows Defender SmartScreen events
![Firewall events icon](images\atp-Firewall-events-icon.png)| Windows Firewall events
![Response action icon](images\atp-respond-action-icon.png)| Response action
![Process events icon](images\atp-process-event-icon.png)| Process events
![Network communication events icon](images\atp-network-communications-icon.png)| Network events
![File observed events icon](images\atp-file-observed-icon.png)| File  events
![Registry events icon](images\atp-registry-event-icon.png)| Registry events
![Module load DLL events icon](images\atp-module-load-icon.png)| Load DLL events
![Other events icon](images\atp-Other-events-icon.png)| Other events
![Access token modification icon](images\atp-access-token-modification-icon.png)| Access token modification
![File creation icon](images\atp-file-creation-icon.png)| File creation
![Signer icon](images\atp-signer-icon.png)| Signer
![File path icon](images\atp-File-path-icon.png)| File path
![Command line icon](images\atp-command-line-icon.png)| Command line
![Unsigned file icon](images\atp-unsigned-file-icon.png)| Unsigned file
![Process tree icon](images\atp-process-tree.png)| Process tree
![Memory allocation icon](images\atp-memory-allocation-icon.png)| Memory allocation
![Process injection icon](images\atp-process-injection.png)| Process injection
![Powershell command run icon](images\atp-powershell-command-run-icon.png)| Powershell command run
![Community center icon](images\atp-community-center.png) | Community center 
![Notifications icon](images\atp-notifications.png) | Notifications
![No threats found](images\no-threats-found.png) | Automated investigation - no threats found
![Failed icon](images\failed.png) | Automated investigation - failed
![Partially remediated icon](images\partially-investigated.png) | Automated investigation - partially investigated
![Termindated by system](images\terminated-by-system.png) | Automated investigation - terminated by system
![Pending icon](images\pending.png) | Automated investigation - pending
![Running icon](images\running.png) | Automated investigation - running
![Remediated icon](images\remediated.png) | Automated investigation - remediated 
![Partially investigated icon](images\partially_remediated.png) | Automated investigation - partially remediated


## Related topics
- [Understand the Windows Defender Advanced Threat Protection portal](use-windows-defender-advanced-threat-protection.md)
- [View the Security operations dashboard](security-operations-dashboard-windows-defender-advanced-threat-protection.md)
- [View the Secure Score dashboard and improve your secure score](secure-score-dashboard-windows-defender-advanced-threat-protection.md)
- [View the Threat analytics dashboard and take recommended mitigation actions](threat-analytics-dashboard-windows-defender-advanced-threat-protection.md)