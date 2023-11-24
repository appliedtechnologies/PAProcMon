# Introduction
With apptech PAProcMon, all Power Automate Flows of a Microsoft Power Platform Environment (e.g. development, integration/test, production) are continuously monitored. The monitoring can be realised for any time intervals and runs automatically. The statuses, key figures, statuses or conditions to be monitored are defined in advance. If a status or condition occurs, the tool sends notifications and alerts to those responsible.

# Procedure
![image](https://github.com/appliedtechnologies/PAProcMon/assets/65557623/6ca191b4-991c-4ac0-97fa-00169e2b3f86)

The monitoring process begins with a Power Automate Flow, which is used to set the desired time intervals for monitoring. This flow then calls up a subflow (also known as a child flow) for the calculated time intervals. This child flow collects the process data for monitoring. If necessary, a connection to the corresponding application or interface is first established so that the process data can then be collected and saved. The data is then analysed with regard to previously defined conditions, states or key figures. If tolerance values are exceeded or certain conditions occur, further child flows are triggered, which send suitable alarms.

# More information
* https://appliedtechnologies.de/2023/01/30/power-automate-flow-monitoring-mit-pa-proc-mon/
