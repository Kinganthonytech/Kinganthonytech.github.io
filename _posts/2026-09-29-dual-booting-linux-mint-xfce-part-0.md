---
layout: post
title: "Dual Booting Linux on a Machine That Barely Runs Windows — Part 0: A Series Introduction"
date: 2026-09-29 20:15:00 +0100
description: "Why I dual booted Linux Mint XFCE on a Pentium N3710 laptop in Nigeria, and what the process actually felt like."
tags: [linux, dual-boot, linux-mint, xfce, beginner]
---

# Dual Booting Linux on a Machine That Barely Runs Windows
## A Series Introduction

**A personal account of what the process actually felt like — 
the constraints, the dead ends, and the improvisation — 
not a step-by-step tutorial.**

There's a particular kind of frustration that comes from 
watching your laptop struggle to keep up with you and not 
being able to do the most basic things you need it to do.

Not a dramatic crash. Not freezing or a blank screen. Just 
a slow, quiet suffocation — 3GB of RAM already consumed 
before you could open a single browser tab, battery power 
draining faster, a screen that occasionally flickers like 
it's sending you a message.

That was me. Running Windows 11 on an HP laptop with an 
Intel Pentium N3710, 8GB RAM and a 256GB SSD. The hardware 
wasn't broken. It was just being suffocated by an operating 
system that wanted more than it could give.

So I did something about it.

---

> **How to Read This Series**
> 
> This is a psychological narrative. It 
> documents what dual booting Linux actually felt like on 
> budget hardware under real infrastructure constraints — 
> the frustration, the improvisation, the mistakes, and 
> the breakthroughs.
> 
> If you want to understand what the process is really like 
> when the tutorials don't match your reality, keep reading.

---

## What I Did

I installed Linux Mint XFCE 22.3 alongside Windows 11 as a 
dual boot setup.

Not as a total replacement of Windows but alongside it. 
Because regardless of the suffocation, I still had very much 
use for it. Linux was to be my intended main
operating system while Windows was to be on standby for 
Windows-specific operations alone — things Linux won't be 
able to do or simulate.

I want to be clear about something upfront: I am not a 
Linux expert. I had never touched BIOS settings before 
this. I had never installed an operating system myself. I 
had never used a terminal to verify a file's integrity or 
troubleshoot a kernel graphics error while staring at a 
giant wall of text I barely understood. I am just a regular 
laptop user like you who simply wanted to optimize my 
hardware and get the most out of it.

I figured it out anyway.

---

## What This Series Is About

This is a four-part documentation of that entire experience 
— the decisions, the process, the failures, the 
troubleshooting, and the outcome.

It is also written from a specific context: I am based in 
Nigeria, dealing with infrastructure constraints — unstable 
power, unreliable internet, and the additional friction that 
comes with building a tech career from West Africa. If this 
sounds like your situation, this series was written with you 
in mind too.

---

## What You Will Find in Each Part

**Part 0 — Why I Did This** *(You are here)*
The context, the constraints, and the decision to stop 
complaining and start acting.

**Part 1 — From Windows Frustration to a Verified ISO**
The decision to switch, the hardware context, disk 
partitioning, downloading Linux Mint through torrent, and 
verifying the ISO with a SHA256 checksum.

**Part 2 — BIOS, Boot Failures and the Troubleshooting**
Ventoy setup, using unconventional boot media, entering BIOS 
for the first time, two boot failures, kernel errors, and 
how I diagnosed the actual problem.

**Part 3 — Installation, GRUB and the Performance Verdict**
Booting into the live environment, the installation process, 
the GRUB dual boot menu, and the real performance numbers — 
what changed and whether it was worth it.

---

## A Quick Note on How This Is Written

Each article documents what actually happened — including 
the mistakes and the moments where I had no idea what I was 
doing. Where I made an error, I say so. Where the correct 
procedure differs from what I did, I say that too.

That's the only kind of technical writing I'm interested in 
producing.

---

*Continue to [Part 1 — From Windows Frustration to a 
Verified ISO]({% post_url 2026-09-29-dual-booting-linux-mint-xfce-part-1 %})*

*[Part 2]({% post_url 2026-09-29-dual-booting-linux-mint-xfce-part-2 %}) | [Part 3]({% post_url 2026-09-29-dual-booting-linux-mint-xfce-part-3 %})*