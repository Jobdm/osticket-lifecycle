<p align="center">
<img src="https://i.imgur.com/tuJ3zhI.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 Pro

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

| Terms | Descriptions |
| ------| -------------|
| `Assigned` | Tickets that have been assigned to either an Agent or a Team while also being in the Department or Help Topic listed in the column, or tickets that were assigned to the Agent listed in the column, within the timeframe chosen.
|`Working the Issue(s)` | Communicates with the requesting party letting them the status of the ticket(s) and steps that will be taken to reach a potential resolution
| `Resolution` | Ticket was resolved in order to resolve or close the Ticket. This may or may meet the requesting parties desired end result. |

## Lifecycle Stages

Below is what the End-User will experience when they create a ticket.

<p align="center">
<img src="https://i.imgur.com/5Ln19eJ.png" height="65%" width="65%" alt="end-user experience"/>
</p>

After filling out the online form the End-User receives a notification letting them know that their ticket/request has been received.

<p align="center">
<img src="https://i.imgur.com/KDzN5qe.png" height="65%" width="65%" alt="check request submission"/>
</p>

<br />

#### Intake: 
When an admin logs in they can see live tickets. Help Desk agents and Queue managers will be able to assign tickets to agents (including themselves) as well as assign the appropriate priority and SLAs.

<p align="center">
<img src="https://i.imgur.com/esCbokc.png" height="65%" width="65%" alt="helpdesk dashboard"/>
</p>

<br />

#### Working the issues:
We are going to tackle `ticket #704724 - Entire banking system is down`. We start by making the following adjustments:<br/>
<ol>
    <li><b>Priority - Emergency:</b> The entire mobile banking system being down is costing the bank money.</li>
    <li><b>Department - System Administrator:</b> The System Administrators department handle these types of issues.</li>
    <li><b>Assignee - John Johnson:</b> John assigns himself the ticket so he can route the issue to the System Administrator department and make the department aware of the issue.</li>
    <li><b>SLA Plan - Sev-A:</b> The severity of the issue is very high. It needs to be solved ASAP.</li>
</ol>

<p align="center">
<img src="https://i.imgur.com/xRwfn7w.png" height="65%" width="65%" alt="changing priority"/>
</p>

<br />

##### Resolution:
 We transfer the ticket to `System Administrator` department. We informed the End-User that Systems Administration have been notified of the issue and that we would reach out once the banking system was back up and running. We then mark the ticket as `resolved`.

<p align="center">
  <img src="https://i.imgur.com/nxTxjud.png" height="65%" width="65%" alt="ticket updates"/>
  </p>
<hr>
<p align="center"><b>That's all I have for this. :smile:
</b></p>
