---
layout: nmap
title: nmap
date: 2018-05-04 17:37:49
tags:
---

## 网络探测、端口扫描工具N
> 例子
```/bin/bash
  # nmap -A -T4 scanme.nmap.org playground

  Starting nmap ( http://www.insecure.org/nmap/ )
  Interesting ports on scanme.nmap.org (205.217.153.62):
  (The 1663 ports scanned but not shown below are in state: filtered)
  port    STATE  SERVICE VERSION
  22/tcp  open   ssh     OpenSSH 3.9p1 (protocol 1.99)
  53/tcp  open   domain
  70/tcp  closed gopher
  80/tcp  open   http    Apache httpd 2.0.52 ((Fedora))
  113/tcp closed auth
  Device type: general purpose
  Running: Linux 2.4.X|2.5.X|2.6.X
  OS details: Linux 2.4.7 - 2.6.11，Linux 2.6.0 - 2.6.11
  Uptime 33。908 days (since Thu Jul 21 03:38:03 2005)

  Interesting ports on playground。nmap。或者g (192.168.0.40):
  (The 1659 ports scanned but not shown below are in state: closed)
  port     STATE SERVICE       VERSION
  135/tcp  open  msrpc         Microsoft Windows RPC
  139/tcp  open  netbios-ssn
  389/tcp  open  ldap?
  445/tcp  open  microsoft-ds  Microsoft Windows XP microsoft-ds
  1002/tcp open  windows-icfw?
  1025/tcp open  msrpc         Microsoft Windows RPC
  1720/tcp open  H.323/Q.931   CompTek AquaGateKeeper
  5800/tcp open  vnc-http      RealVNC 4.0 (Resolution 400x250; VNC TCP port: 5900)
  5900/tcp open  vnc           VNC (protocol 3.8)
  MAC Address: 00:A0:CC:63:85:4B (Lite-on Communications)
  Device type: general purpose
  Running: Microsoft Windows NT/2K/XP
  OS details: Microsoft Windows XP Pro RC1+ through final release
  Service Info: OSs: Windows，Windows XP

  Nmap finished: 2 IP addresses (2 hosts up) scanned in 88.392 seconds
```
