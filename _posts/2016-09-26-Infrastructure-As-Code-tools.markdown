---
layout: post
title:  "Imfrastructure as Code tools"
date:   2016-09-26 22:34:14 -0400
categories: Blog DevOps
---

# Infrastructure as Code tools

When updating your program of change to embrase the latest tools for Infrastructure as Code it is important to choose the right tools. However it is also important to find what works for your team. There is little point in using the industry hot tools just because everyone else is using them. A better approach is to start small and simple and use the minimum set to get results.

# How to choose the right Infrastructure as Code tools

What skills do your team already have, ask them. 

If they know Javascript/Java/C/C++ they will feel at home writing JSON; armed with that you can look for tools that use JSON like AWS Cloud Formation
If they have been playing with Python they may be more aligned with YAML (Cloud formation is adding support for YAML) so look for tools that rely on YAML definitions.
Ruby will help if you want to try Chef/Puppet
None or all of the above then looking at tools that use their own definition language could be the best way forward. Something like Terraform from Hashicorp.

## Upskill

Don't know GIT? use Codeacademy to larn it.
Want to use Chef but don't know any Ruby? Spend a day or two running through the Ruby Koans. 

# Example please

In a brown field site, start with a new project or refresh a single simple system.
Imagine you are going to refresh your Infrastrucure as Code tools for a simple 2 tier web application. 

* Step 0.5 is to understand your team, what they know, what they are good at, where they have a burning desire to take their careers and the business.
* Step 1 is to update your Architecture digrams and ensure your build docs are [complete? don't like this wording]
* Step 2 As a team choose your tool to trial and timebox the first itteration.
* Step 3 Take an itterative approach and build the first part of your system. I usually start wtih the database as it is the core of your application and usually has persistence. I recommend that unless you are already far down the automation path you start with a cloud / virtual / container application first as the complexity of building from bare metal could easily put you off further development.

