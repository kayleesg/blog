---
title: "My first 2 weeks at SecureSet"
date: 2021-09-16
---

<h2>Classes we took</h2>
<ul>
  <li>Systems Foundations</li>
  <li>Network Foundations</li>
</ul>

<h3>Systems Foundations</h3>
<p>This was the beginning of our journey into Cyber Security. We talked about the CIA Triad and defined the security principles of the CIA Triad. For example, I wrote this little description of what it meant to me:</p>
<pre>
<code>Confidentiality is keeping something secret. For example, it's like taking a friend to the center of the Earth and closing off the rest of the world so you can tell them a secret. No one else will know that we're having the conversation and no one else can see or hear your conversation.

Integrity is making sure that what you get is true. For example, failing to keep integrity is like when your twin gives your best friend a worm and says it's an apple. The twin looks and sounds just like you, but the best friend knows that the twin is lying. If the twin upgraded their hacking skills and disguised the banana as an apple, your best friend wouldn't know until they've taken a bite. Yuck! To mitigate, you and your best friend should have a secret handshake that you can practice in the center of the Earth.

Availability is making sure that data is available. For example, your best friend moved to another country and they don't have a phone or computer access. They aren't available to you anymore. So you mitigate this by sending them a phone with an international phone plan. Now your friend is available and you guys can talk about your rotten twin everyday.</code>
</pre>
<p>In addtion, we discussed the Ethics of Ethical Hacking, Bug Bouty Programs, the Windows GUI, PowerPoint (a set-up for future lessons), and tips on studying for our success.</p>

<h3>Network Foundations</h3>
<p>This was the beginning of our network cram. This class was quite challenging for all of us.</p>
<p>Our first hurdle was figuring out the Wireshark tool. We had to capture packets and then examine and follow them. It was interesting but we lost sight of <i>why</i> we were capturing packets.</p>
<p>It wasn't until we started going over the OSI Model did it start to make sense. We started seeing the patterns in the packet captures fairly quickly.</p>
<p>Once we started feeling confident with the packet captures, <b>a lab was thrown at us that almost made me quit</b>. The lab required us to have two virtual machines running on their own isolated networks. Our goal was to use a local proxy to log into once VM from another using SecureShell (SSH). Below is a small diagram of what was required of us:</p>

<img src="Net Foundations Set Up.png">

<h3>How we solved this huge problem</h3>
<p>I'm not to give away the answer because SecureSet might come after me, but I will note a couple of things:</p>
<ol>
  <li>Netcat is your friend</li>
  <li>Look up FIFO's (or Named Pipes), and how they work</li>
</ol>
<br />
<p>I don't want to spoil this lab for future cohorts, but I do want to throw a couple of crumbs that might help another student someday.</p>
<h4>The lab above hit us on the second week of the 20 week program and I was ready to quit</h4>
<h3>But we made it through and I learned a lot</h3>
<p>For instance, I am a little more confident in my networking ability. I spent <i>a lot</i> of time on this problem. I had lots of headaches with it, but once the whole class got it down, we were a little drained and a lot more confident.</p>
<h3>What else did we learn in the first two weeks?</h3>
<p>We went over the OSI Model and picked apart a TCP Frame (Check out the difference between a TCP Frame and packet here:</p>
<img src="PDU and Layer Addressing.png">
<br />
<p>We talked about the different networking devices and where they fit on the OSI Model.</p>
<p>We talked about how to "hack" Google Searches to optimize them for researching. For more information, check out this article: <a href="https://www.acunetix.com/websitesecurity/google-hacking/">What is a Google Hack?</a></p>
<p>Finally, we talked about DoS/DDoS attacks. We played with hping3 to a DoS on VM that we had running. Although hping3 isn't powerful enough to bring a server down, it's still interesting to see how it works in theory.</p>

