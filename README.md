# EWS Editor for Dynamics 365

Please see the **[Releases](https://github.com/DJB9k/EWS-Editor-for-D365/releases)** section to download the binary executable. 

See **[Which Version Should I Choose?](https://github.com/DJB9k/EWS-Editor-for-D365/wiki/Which-Version-Should-I-Choose%3F)** to determine which build should be downloaded based on the version of Dynamics 365.

**About**:

EWS Editor for Dynamics 365 is based off the original EWS Editor source and is designed to provide troubleshooting tools to help resolve Exchange server integration issues related to Server Side Synchronization and the E-mail Router. Below are the features available in the latest release:

+ Natively inspect Dynamics 365 Extended Properties (crmid, crmLinkState, etc) in any EWS Editor grid that contains items linked to 				Dynamics 365. 

+ Retrieve ExchangeSyncIdMapping records for any given Appointment, Contact, or Task in any EWS Editor Grid that contains items linked to 	Dynamics 365. 

+ Validate e-mails for promotion to Dynamics 365 by performing the CheckIncomingEmailRequest API. 

+ Inspect the Mailbox Synchronization State, Mailbox Alerts, and other details in a thematically grouped interface. 

+ Perform Mailbox diagnostics to check for misconfigured or stuck mailboxes with Server Side Synchronization. 

+ Troubleshoot and anticipate ACT Synchronization issues between Dynamics 365 and Exchange Server. 

+ Simulate various Exchange Web Service APIs commonly used by Dynamics 365. 

+ Test and Troubleshoot Autodiscover issues when resolving Dynamics 365 mailbox e-mail addresses. 

+ Filter folder grids based on custom search parameters, as well as built-in filtering for Dynamics 365 items. 

+ Download MailApp manifests deployed to a mailbox via the MailApp Manager. The MailApp Manager also allows users to install or remove MailApps, as well as install the D365 Debug Addin. 

+ Scan folder items for errors that can occur when deserializing successful Exchange responses for items.

+ Remove unwanted items using the Mailbox Cleanup Wizard. 

The tool works across all supported configurations of Dynamics 365 / CRM 2016 and Exchange Server as outlined here: 

https://technet.microsoft.com/en-us/library/dn531050.aspx

For usage instructions, please see the wiki.
