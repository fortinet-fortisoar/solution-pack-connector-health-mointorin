| [Home](https://github.com/fortinet-fortisoar/solution-pack-connector-health-monitoring/blob/release/1.0.0/README.md) |
|----------------------------------------------------------------------------------------------------------------------|

# Contents

The **Connector Health Monitoring** solution pack contains the following resources.

## Connectors

| Name     | Description                 |
|:---------|:----------------------------|
| SMTP     | Helps send emails from a specified email address to designated alert recipients |
| Exchange | Provides a robust, platform-independent, and simple interface for communicating with Microsoft Exchange 2007-2016 Server or Office 365 using Exchange Web Services (EWS) |

> **NOTE:** You can configure either of the connectors

## Playbook Collection

| Playbook Collection Name              |
|:--------------------------------------|
| 10 - SP - Connector Health Monitoring |

| Playbook Name                  | Description                                                                                                                       |
|:-------------------------------|:-------------------------------------------------------------------------------------------------------------------------------|
| Notify Connector Health Status | This playbook notifies the connector health via email. It can be set to run at predefined intervals using FortiSOAR schedules. |
| Check Connector Health Status  | This playbook checks the connector health status.                                                                                 |

>**WARNING:** We recommend that you clone these playbooks before customizing to avoid loss of information while upgrading the solution pack.
