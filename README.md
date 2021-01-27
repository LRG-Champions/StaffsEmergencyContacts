# Staffs Emergency Contacts Application

| [Documentation](https://github.com/LRG-Champions/template/wiki) | [Deployment Guide](https://github.com/LRG-Champions/StaffsEmergencyContacts/wiki/Deployment-Guide) | [Solution Overview](https://github.com/LRG-ChampionsStaffsEmergencyContacts/wiki/Solution-Overview) |
| ---- | ---- | ---- |

Staffs Emergency Contacts Application is a PowerApp linked to a SharePoint list.  This allows officers to contact other officers via the smartphone PowerApp.

This application is used by corporate officers from Staffordshire County Council and partner organisations who may need to be contacted in the event of a county-wide emergency. It is part of the resilience planning process.

The previous paper-based list comprised 113 contacts (this number fluctuates with staff turnover and role changes), along with their job function, work location, personal, home and work phone numbers.

The new application has been developed using the Office 365 PowerApps software, combined with an electronic version of the data held within a Sharepoint list. The PowerApp provides the interface to the Sharepoint datasource, and the entire application is deployed to mobile devices – typically work mobile phones. At no point is any of this data stored on a mobile device, it is only referenced via a data connection to the corporate electronic Sharepoint list.

In Staffordshire the application is deployed within the secure framework of the InTune security software. Access to the application is also controlled via separate Active Directory groups for both the mobile device interface and the data in the Sharepoint list. At no point is personal data held or recorded on a mobile device.  InTune also prevents data from being copied and pasted between applications on the local device.

### Key features
* **Contact fellow officers:** Contact fellow Emergency contact officers by phone or text
* **Self-service update:** Update your own contact details via self-service

## Get started

**If you are new to github, you can take one of the many excellent beginner courses [here](https://lab.github.com/)**

Begin with the [Solution Overview](https://github.com/LRG-Champions/template/wiki/Solution-Overview) to read about what the app does and how it works.

When you're ready to try out Staffs Emergency Contacts Application, or to use it in your own organization, follow the steps in the [Deployment Guide](https://github.com/LRG-Champions/template/wiki/Deployment-Guide).

## Feedback

Please report bugs and other code issues [here](https://github.com/LRG-Champions/StaffsEmergencyContacts/issues).


## Contributing

See guidelines for contributing [here](https://github.com/LRG-Champions/template/blob/main/CONTRIBUTING.md)
