---
title: "RMCCDC My First Qualifier"
date: 2022-02-26
---

<h2>Rocky Mountain Collegiate Cyber Defense Competition (or RMCCDC)</h2>
<h5>Is a competition to test a teams ability to defend a network from external attacks by a "red team".</h5>
<p>This was my first competition and I was excited to see what the experience would be like. Our team, the "blue team", consisted of eight members of the University of Colorado, Colorado Spring's Mountain Lions Cyber Club, a club dedicated to the knowledge and advancement in the cybersecurity field.</p>
<p>The competition consisted of a number of virtual machines that was connected to the internet through a Palo Alto firewall. I kept calling it a router since all of our traffic was being routed through the box.</p>
<p>The competition only lasted a few short hours. However, in that time, the blue teams are constantly bombarded with various types of attacks from the "red team" as well as tasks that are directed by management (called Injects).</p>
<p>The goal of the competition is to keep your services running that are being hosted on the various virtual machines. Services included things like a web page and an email server and some others that I'm not sure I can disclose. If one of the services stops broadcasting out to the internet, your team loses points.</p>
<p>One of the mistakes that my team made was not understanding that the Palo Alto machine was fair game for the red team. Twice our machine went down for unknown reasons that cost us a lot of points.</p>
<p>Below is a list of things that my team and I did well in this year's cometition:</p>
<ul>
  <li>When services were down, we kept a level head and didn't panic. We dicovered that the scoring system was a bit slow to update, meaning that the score wasn't accurate to the second.</li>
  <li>Tasks were delegated well among the team members. The injects were difficult but we managed them.</li>
  <li>Communication was strong within the team. When a task was complete, we notified the rest of the team.</li>
  <li>Our leadership was also strong. In addition to delegating tasks, the leadership was fantastic in requesting updates regularly.</li>
</ul>
<p>Below is a list of the things that I learned from this competition that I hope to improve on for the next competition:</p>
<ul>
  <li>The Palo Alto machine (or router) is fair game for the red team. Understand how to change the password on a Palo Alto machine.</li>
  <li>All of the machines come with a default password associated with the root or admin accounts. Make sure to change those passwords immediately.</li>
  <li>Splunk is not configured. Understand how to configure a Splunk SIEM so intrusions can be monitored and documented.</li>
  <li>Injects have to be in pdf form. More importantly, it needs to be in business memo form. <a href="https://www.dummies.com/article/business-careers-money/business/business-communication/how-to-format-a-business-memorandum-197798">How to format a business memo</a></li>
  <li>Understand how to secure web and email servers. A default Apache web page vulnerability was discovered and remediated. Understand how to spot this vulnerability and how to mitigate.</li>
</ul>
