---
title: "I installed scrcpy on my Windows 10 desktop"
date: 2022-01-06
---

<h1>Happy New Year!</h1>
<h4>This year I am focusing on my studies than ever before. I've been learning with TCM Security and I start college for Computer Science!</h4>
<h4>I think this year is gonna be pretty exciting.</h4>

<h3>And to start off the New Year, I decided to try getting open source software to run on my Windows desktop. I've done it on my Linux desktops, so how hard could it be?</h3>
<br><br>
<h3>Issue #1: I had to look online for some extra steps</h3>
<p>I found this 1 minute guide on how to do it: <a href="https://www.smartprix.com/bytes/how-to-set-up-scrcpy-for-mirorring-phone-on-windows/#:~:text=Step%201%3A%20Download%20the%20latest,folder%20you%20extracted%20for%20adb.&text=Step%204%3A%20Now%20just%20open,pop%2Dup%20on%20your%20PC.">How to set-up Scrcpy for mirroring phone on Windows PC</a></p>
<p>Armed with this guide, I set off with the first step of setting-up ADB. I'd run <code>./adb.exe devices</code> and......... nothing shows under the list.</p>
<img src="https://kayleesg.github.io/kayleesgblog/no-devices-here.png">

<h2>Troubleshooting to the rescue!</h2>
<p>I decided to double check:</p>
<ul>
<li>That my phone was plugged in .......... Check</li>
<li>That developer mode was on ..... Check</li>
<li>That USB Debugging was on ...... And check</li>
</ul>
<p>With those checks out of the way, I realized that I never got the prompt to do file transfers. Normally, when you plug an Android phone into a computer, the phone and the computer start to talk. I realized that I never got the request from my phone to start talking to my computer. My phone wasn't recognizing my computer.</p>
<p>So, to the internet I go to find answers. Obviously, you guys are smarter than me and would have realized that there was something wrong with the cable. Well, my first instinct was that there was something wrong with my computer.</p>
<h2>(－‸ლ)</h2>
<p>I discover that the cable is to blame and I get a new one plugged in. Problem 1 solved, my phone now recognizes my computer.</p>
<p>It doesn't take me long to realize that my phone is still not being seen by the ADB. So, I find this article: <a href="https://stackoverflow.com/questions/22450478/android-device-not-recognized-by-adb?rq=1#:~:text=Enable%20USB%20debugging%20and%20open%20Device%20Manager%20and%20keep%20it%20opened.&text=1)%20Connect%20your%20device%20and,%22Android%20Composite%20ADB%20Interface%22.">Android Device not recognized by adb</a></p>
<p>Bottom line, the solution was to use PTP mode over MTP. PTP is just used with pictures while MTP transfers all media. It didn't hurt to try so I did ... and it worked.</p>
<p>After that, the next couple of steps worked without a hitch.</p>
<br>
<h4>So, with my first adventure in open source software on a Windows desktop I just have a couple things for future me:</h4>
<h3>Layer 1 troubleshooting holds the answer to 99% of problems. The internet is vast and someone has tried to do the same thing as you. Never give up, and definitiely never panic if something isn't going the way you want it to.</h3>
<h1>Happy 2022 everyone!</h1>
