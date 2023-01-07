# Open-Source Emergency Management Software (OSEMS)

### Problem Statement: 
While there is a standardized framework for organizing around emergency management (FEMA's National Incident Management System), there is no standardized application for on-the-ground operations inside of an emergency management situation. What is designed to be a plug-and-play system can break down when communication is not streamlined, role assignment/responsibility is unclear, and/or there is incomplete information storage and sharing.

### Goals:
- Consolidated training and resource links
- Streamlined preparation & organization
- Shortest-possible-time between incident and stood-up imt
- Improved communication during emergency

### Features:
- Admin panel for emergency management coordinator: easy update and retrieval of currently-trained staff and their contact information; IMT template development and generation; fast generation and deployment
- Featureful dashboard for IMT staff, incl. role responsibilities, contact information, issue tracking, external resources
- Issue tracking/prioritzation/triage system
- Out-of-the box functionality, as well as significant customization - custom roles, resources, data, tools, external connections, etc.
- Full web functionality, as well as local-only set-up in case of no internet access

### Parking Lot:
- Api for organizational IT people to link to proprietary/sensitive data (could be for contact information from hr, asset data, supplies inventory)
- Easy, clear way to build new tools/add-ons
- Easy & dynamic data upload; can this be automated? proprietary system is updated, automatically upload to system
- How to store the server locally to allow for case of no internet (or have a toggle to access that locally)
- Built-in optional apis/data streams