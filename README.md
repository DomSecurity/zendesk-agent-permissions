<p align="center">
<img src="https://i.imgur.com/M5nEeiK.png" height="65%" width="65%" alt="osTicket logo"/>
</p>

<h1>Adding an Agent and Define their Permissions</h1>
In this lab we will be adding an agent/s and defining their permissins. This lab will help us have a better understanding of adding an agent & giving access in Zendesk.<br />

<h2>Environments and Technologies Used</h2>

- Zendesk (software)

<h2>Operating Systems Used </h2>

- Mac OS

<h2>Lab Steps</h2>
<p>
</p>
<p>
In this excerise, we'll be having a better understanding of agent access in Zendesk, adding an agent, and define permissions using groups and ticket access. We'll start with adding a new agent by hovering the mouse over 'Add' then selecting 'User'. Here's where we'll add new user, but under 'User type' instead of selecting 'End user', we'll select 'Staff member'. Under 'Staff member' we'll selct role to be 'Agent'. Then click on 'Add'.
</p>

<p>
<img src="https://i.imgur.com/VsE4cav.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/cZHtFf3.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
  
After adding new user, it'll then bring us to the Agent profile page where we be able to review agent access. On the Agent profile, we'll also be able to make changes to their emails, password, and much more. This is mainly so that the Agent be able to log in and have access. But now that we're here, we'll first start with which group the agent will be in. 
<br />
All new agents must belong to at least one group and by default that's the support group. Groups collect agents together allowing admins to maage agent ticket assignment and access to tools like Views and Macros, at a group level. Tickets can also be assigned to either a group, or an agent within a group.
<br />

<p>
<img src="https://i.imgur.com/hZrTijX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Here we created a new group and named it 'Merchant Agents'. And we'll assign this agent to have access to both 'Support' group and 'Merchant Agents'. So that they'll have access to tickets that customers who send general requests to the support team but mainly specializes in helping Merchants. 
</p>


<p>
<img src="https://i.imgur.com/33l5yGH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Now we'll focus on the agent 'Access' and 'Comments'. For this agent we set the 'Access' to 'Tickets in agent's groups' only because this agent is no admin and we don't want them having admin access, like 'Tickets in agent's org'. Plus agent will also be able to have access to 'Assigned ticket only', not just the one's in agents group. And for 'Comments' we set to 'Notes and replies' so this agent can directly apply to customers. If this agent was just with the internal billing team then we would give them access to 'Notes only'. Now for 'Alias', that's just for if agent does not want their real name to be shown the customer. For 'Signature', is just for like a signature agent will have at the bottom of ever email sent out to customer. Some organizations will have their logo or some sort.
</p>

<p>
<img src="https://i.imgur.com/wvYFJQY.png" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
