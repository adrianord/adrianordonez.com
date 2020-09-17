---
title: "HomeLab Overview 2020"
date: 2020-09-16T22:18:26-05:00
draft: true
categories:
  - HomeLab
  - System Administration
tags:
  - homelab
  - sysadmin
---

<img src="https://f002.backblazeb2.com/file/blog-adrianordonez-com/homelab-overview-2020/DSC05512.JPG"
title="Server Rack Full"
height="1000"
alt="Server Rack Full"/>

I started acquiring hardware for my personal HomeLab about two years ago, and have redone the set up several times as I
have learned more and more about the best practices of the industry. This post is meant to be a starting point to
illustrate where I am at with my HomeLab, future plans I have, and gather ideas from the community.

My HomeLab is heavily influenced by my work place's infrastructure and as such is heavily built on VMWare's software
suites. All my VMWare licenses come from [VMUG Advantage's EvalExperience]. I highly suggest it, it's \$200 a year
annually and is a great investment for learning an enterprise grade virtualization solution without the limitations of
ESXi free. It's pretty much required if you want to do any sort of orchestration on ESXi. For anyone wondering,
EvalExperience gives you 12 CPU at 32 cores per CPU. I have not seen any instance limits so far, but I have so far used
8 CPUs across 4 instances.

[vmug advantage's evalexperience]: https://www.vmug.com/vmug2019/membership/evalexperience
