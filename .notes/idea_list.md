# Ideas List
## ConnectWise Manage/PSA
### EntraID/365 Contact Sync
Ensures live updates ensuring CWPSA contacts are identical to client's EntraID user list. This is important to provision/de-activate DeskDirector (Idea 11 Portal) user accounts on user movement, and reduces the risk of tickets being lodged by unknown users or tech confusion.
### CWPSA Source-of-truth for all contacts/approvers/roles
With the above sync and with additional tagging/custom field notation of specific roles or permissions for specific client contacts, we would be able to leverage this to direct automatic approvals to the correct contact. It's current location in SharePoint is hard to work with.
### AI-assisted summary following ticket closure
Rewst workflow that runs following service ticket completion, to help build out a callable dataset that summarises ticket troubleshooting steps and ultimate resolution. This could be ingested and become searchable by an AI agent to allow technicians to pull actions or resolutions on previous tickets that may help speed up a resolution. One way would be to append an internal note following ticket closure that lists contact, devices affected, systems or software, actions taken by the technician, and the ultimate fix.
### Automation custom fields 
Custom fields in CWPSA to indicate to technicians if an automated workflow is running, what workflow this is, and if the ticket resolution was automation-assisted for reporting purposes.
### Triaging - Auto-dispatch
Consult to determine methodology, and allow Rewst to dispatch tickets appropriately. This could leverage information such as company (and assigned squad), priority, services impacts, technician skills matrix, technician assigned ticket load, and potentially the summary bot as noted above. Would need alot of determination from management, but possible.

## Rewst/Automation
### User onboarding
The most streamlined way would be to consult with clients to create employee 'personas.' These are user access and configuration templates, where a new user can be fully configured based on a job role (i.e. Office Manager, Level 1 Technician, Electrical Engineer). The flow can fully configure the user object, groups, mailboxes/dl lists, security groups, calendars, Idea 11 tooling config, ending with sending the user welcome emails and SMS the user their inital login password prior to their start date. Any automation failures become tasks on the ticket that must be completed before closure.
### Offboarding
Similar to the above, however these can be scheduled in Rewst to fire at the specified date and time as submitted on the form. Advisories on submission and successful completion to submitter. Any automation failures become tasks on the ticket that must be completed before closure.
### Zero-touch automation
Build out a package of Rewst flows that handle simple tasks that do not need input from engineers, that can be run directly from the Idea 11 Portal. This can include, group, mailbox, dist list changes, app installs (depending on stack), creation of new groups/mailboxes, sharepoint permissions, guest user invitations, password changes (this may not pass the pub test), disk cleanups, service restarts etc. Would free up significant CSE time. Lots of ideas in Rewst Crates. Appears you can embed the Rewst form URL into DD, which would reduce complexity.

# Nice-to-haves
## MSA Advisory Agent


