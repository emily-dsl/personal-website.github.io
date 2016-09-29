---
layout: post
title:  "Cloud Formation Infrastructure as Code"
date:   2017-09-26 22:34:14 -0400
categories: AWS CloudFormation
---

# This is awful junk. needs to be broken up into multiple articles.

# Cloud Formation Infrastructure as Code

There are many options for building infrastructure in AWS. I am going to concentrate on Cloud Formation for this article because it is Amazon native (limits the scope), well documented, and does just about anything you need (although not always what you want).

## What is Infrastructure as Code?

I'm not going to reword others here, it is easy to go read up on the full defition and there are some great books (Available on Amazon :) 

So for now if you don't know take this as the simplified meaning.

* Infrastrcutre as Code is the Codification, version controled, and repeatable code/scripts/configs that generate your infrastructure.

The important bits in my humble opinion.
* Version control
* Repeatable
* Code generates infrastructure

## Best bits and Limitations

To make the most of Cloud Formation your IT assests need to be desposable. Data needs to be stored in RDS/S3/Elastic Filesystem created in Cloud Formation templates separate from the majority of the system. In my experience Cloud formation is great at creating reslient infrastrcture as long as you code it write.

When system breaks terminate it. 