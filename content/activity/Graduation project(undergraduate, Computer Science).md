---
date: 2015-05-28
title: Graduation project(undergraduate, Computer Science)
highlight: "true"
---

**Analysis and Implementation of Remote Code Execution through Flash Player Vulnerability and Crafted Web Site**

Implementation of [CVE-2014-0515](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-0515). Not bad that I explored some innerwork of Flash player.

Here's a brief procedure about how my work operates.

1. The attacker runs a web server and builds a site that uses the malicious flash player file.
2. A victim connects to the site. Note that anyone can be a victim if he/she connects to the site without patched Flash Player.
3. After the victim elicits files including .html and .swf from the server, the victim's browser launches the malicious flash file automatically.
4. Finally, the victim's computer gets compromised, giving the attacker availability of Remote Code Execution(RCE).

Among a tons of available executable codes, I chose to launch the calculator simply. This is the snapshot when the victim opens the site.
<img src="/activity/Graduation project(undergraduate, Computer Science)/result.png" class="img">

[poster.pdf](/activity/Graduation project(undergraduate, Computer Science)/poster.pdf)

[FinalReport_Jiman_Hwang.pdf](/activity/Graduation project(undergraduate, Computer Science)/FinalReport_Jiman_Hwang.pdf)
