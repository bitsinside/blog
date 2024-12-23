---
date: '2024-12-22T23:30:04+05:30'
title: 'Hello World'
description: "My self hosting journey in 2024"
tags: ["SelfHost"]
slug: "Helloworld"
---
## Introduction

Since starting my homelab journey in December of this year, I've been attempting to self-host certain services that I find useful in my daily life.

Here I wanto to share the list of service that I am self host.

## My mini homelab

My home lab setup currently consists of three primary components, a Mikrotik [hEX S](https://mikrotik.com/product/hex_s) (poor man's router), an old laptop (which I used to self-host stuff before purchasing Raspberry Pi), and a Raspberry Pi 5 named `Devtest`.  

## About Devtest

`Devtest` is where most services run. The majority of the services running on `Devtest` are in Docker containers. I also attached a 1TB hard disk, which I'm utilizing as NAS.

 **Service on Devtest**

* [Docker](https://www.docker.com/) - platform to run containers
* [Wiki.js](https://js.wiki/) - for documentation purpose
* [Tailscale](https://tailscale.com/) - VPN to access my homelab
* [tcptunnel](https://en.wikipedia.org/wiki/Tunneling_protocol) - It's a small service that I wrote in C to portforward internal services to external ones using tailscale.
* [NMS](https://en.wikipedia.org/wiki/Network_monitoring) - A network monitoring service that I wrote in C, Go Lang, and SQLite that will scan IP/MAC addresses on a periodic basis and display device lists in a dashboard (not fully finished yet), so it will accomplish the job that I planned. Currently, it runs on a Docker container.

## About an old Laptop

Old laptop runs Ubuntu OS and I use it for coding and browsing, It also has tailscale node, where I can access my laptop's internal services remotely vai my Phone.

## Conclusion

Overall, I'm enjoying my homelab and self-hosting, and I'm forward to explore more in the coming year(s).
Until next time, happy homelabbing 🖖.
