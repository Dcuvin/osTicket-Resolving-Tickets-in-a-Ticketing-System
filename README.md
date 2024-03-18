<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configurations</h1>

<h2>Goal: Demonstratethe creation, triaging, and solving of tickets within osTicket</h2>

This lab demonstrates the necessary changes I make to configure osTicket so it can be used as a proper ticketing system. I will then create a series of tickets that corresponding to each SLA level.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10 Pro</b> (21H2)
<a href="https://imgur.com/NMeNbmV"><img src="https://i.imgur.com/NMeNbmV.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/Ip9TKsN"><img src="https://i.imgur.com/Ip9TKsN.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/WiryPYr"><img src="https://i.imgur.com/WiryPYr.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/CBtaKFv"><img src="https://i.imgur.com/CBtaKFv.png" title="source: imgur.com" /></a>
<p>For the first example, I will sign-in as User jack_hill and create A Sev-A ticket where the entire banking system is down. For the second example, I will sign-in as User jill_hill and create a Sev-B ticket where the entire accounting department is in dire need of upgrade. Finally I will sign-in back as jack_hill and create a Sev-C ticket claiming slow performance on the CFO's laptop.</p>

<a href="https://imgur.com/PLHRr9X"><img src="https://i.imgur.com/PLHRr9X.png" title="source: imgur.com" /></a>

<p>Next I'll sign-out and re-sign-in as one of the Agents that I created, in this case john_doe, and I'll review the severity of the tickets and assign them to proper teams. Operating as Agent John Doe, I replied to the ticket submitted by Jack Hill. I escalated the priority level form Normal to Emergency, updated the SLA Plan from Default to SEV-A, and transferred the ticket to System Administrators. </p>

<a href="https://imgur.com/wt8o1qK"><img src="https://i.imgur.com/wt8o1qK.png" title="source: imgur.com" /></a>

<p> While still being signed in as Agent John Doe, I'll review the ticket submitted by Jill Hill  claiming that her entire department is having issues with their current tablets. Since this seems like a widespread issue, I will change the priority ticket to High, but it does not seem to be business critical, so I will update the SLA to Sev-C and proceed to warmly hand this off to Jane Doe</p>

<a href="https://imgur.com/4S3VcD5"><img src="https://i.imgur.com/4S3VcD5.png" title="source: imgur.com" /></a>
<a href="https://imgur.com/Btafcbs"><img src="https://i.imgur.com/Btafcbs.png" title="source: imgur.com" /></a>

<p>I'll sign-out from John Doe and sign back in as Jane Doe and proceed to respond and resolve the ticket assigned to me. All tickets will be resolved at this point.</p>


