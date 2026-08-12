<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

<ul>
  <li>
    <p>We will walk through the different stages a ticket goes through once it is created until it is resolved and closed.</p>
    <ul>
      <li><strong>Intake:</strong> The initial step where a ticket is created by the user or an agent.</li>
      <li><strong>Assignment and Communication:</strong> The ticket is assigned to a department or agent, and communication with the user begins.</li>
      <li><strong>Working the Issue:</strong> The assigned agent works on resolving the issue or provides updates.</li>
      <li><strong>Resolution:</strong> The problem is resolved, and the ticket is closed after verifying the solution with the user.</li>
    </ul>
  </li>
  
   <li><strong>Prioritizing Tickets Based on Severity and SLAs (Service Level Agreements)</strong>
    <p>SLAs are critical to ensuring that tickets are resolved within an agreed-upon timeframe, depending on the severity of the issue. We will demonstrate how different severity levels align with specific SLAs to prioritize and resolve tickets effectively:</p>
    <ul>
      <li><strong>Sev-A (1 hour, 24/7):</strong> This is the highest priority for critical issues, such as when the entire mobile or online banking system is down. The SLA requires a resolution within 1 hour, and the ticket is immediately escalated to the SysAdmins team for 24/7 handling.</li>
      <li><strong>Sev-B (4 hours, 24/7):</strong> These are important but less urgent issues, like the accounting department needing an Adobe upgrade. The SLA ensures a 4-hour response and resolution time, still available around the clock.</li>
      <li><strong>Sev-C (8 hours, business hours):</strong> This represents lower-priority issues, such as the CFO's laptop running slowly. The SLA guarantees a 8-hour resolution, but only within standard business hours.</li>
    </ul>
    <p>By adhering to these SLAs, osTicket ensures that critical issues are dealt with immediately while balancing lower-priority tasks efficiently.</p>
  </li>

  <li><strong>Triaging Tickets: Identifying or Escalating Issues</strong>
    <p>In this step, we’ll show how tickets are evaluated to either solve the problem directly or escalate it to a higher level of support if needed. Triaging is key to managing workflow efficiently and avoiding delays.</p>
  </li>

  <li><strong>Solving Problems and Closing Tickets</strong>
    <p>Finally, we’ll demonstrate how the problem is addressed, the solution is provided to the user, and the ticket is marked as closed once the issue is fully resolved. Following SLAs ensures that the time to resolution is tracked and met.</p>
  </li>
</ul>
