---
layout: post
title:  "My OSCP Journey"
date:   2019-12-08
excerpt: "My thoughts and approach to OSCP Exam"
tag:
- OSCP 
- Pentesting
- Beginner
- Offensive Security
- Exam Preparation 
comments: true
---

If you're searching for KeyWords *"My OSCP Journey "* on Google, there are possibly 2000 + blogs with the same name, so why have I taken the trouble to post yet another one? It's because so many friends, colleagues and LinkedIn Connections have asked me about the manner in which I planned my OSCP.Perhaps because they could relate more to me. Hence,I thought of jotting down my journey of passing the OSCP. 
Probably there are *n* number of good ways to get to OSCP, I'll list what worked for me. Hopefully, in some ways it will inspire you. So let's start without any additional ado.


## My Background

Before going further, let's talk a bit about my professional background. I’ve been in the security field for the final 6+ years. After finishing my graduation in Electronics and Communication, I did CCNA certification in 2013. This helped me to have a sound understanding of Networking Concepts. Then for the first 3 years of my job, I worked extensively in Network Security such as Firewalls, Routers, Switches, VPN, SSL Certificates and Proxies. It was during my third year when I began learning about the basic Linux to complete my day-to-day operations. Then for the following 3 years, I worked extensively on Web Application Security, Web Application Firewalls, DDoS Mitigation. While working for Akamai, I got in-depth knowledge of TCP/IP Layer, DNS, and HTTP/HTTPS. During this time, I started learning beginner level Python, SQL, XSS, RFI, and LFI.
All in all, if I desire to summarize my background before attempting OSCP, it would be network security, web application security and basic knowledge of Python and Shell Scripting. In other languages such as C, Ruby, JS it would be sufficient to interpret the logic of the code.

## Before Booking the Exam

Approximately 2-3 Months before booking the exam, I started working on refreshing the basics of Linux and upgrading my knowledge on it, practicing more on python codes, reading more about Web Application Security and OWASP Top 10. (Hacker’s Handbook, 2nd Edition Helped me). Additionally, I started solving challenges on OverTheWire (Bandit and Natas). Solving OverTheWire challenges will yield you a mindset to solve similar problems. In Summary, below were the resources that I had used before booking the exam:
   *<a href="https://linuxjourney.com/">Linux Journey</a>
   *<a href="https://overthewire.org/wargames/">OverTheWire(Bandit and Natas)</a>
   *<a href="http://automatetheboringstuff.com/">Python Programming(Link Included)</a>
   * Understanding the Basics of Assembly Language.
          
But If I could go back in that time, I would have done a few of the <a href="https://www.vulnhub.com/">VulnHub</a>, <a href="https://www.hackthebox.eu/">HackTheBox machines</a> and would have watched <a href="https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA">IPPSec</a> on YouTube. I would highly recommend watching the IPPSec video whenever you get time, trust me every time you will learn a new trick which will aid you in the exam. Just before booking the exam, just ask yourself:

          1. Are you feeling comfortable with Linux to perform a search, grip, moving, copying, understanding various system processes?
          2. What if you have an only Command Line (Linux and Windows) to perform all the work, will you be able to do it comfortably?
          3. Will you be able to spot a malicious chunk of code that you have downloaded?
          4. Can you explain the working of a program in terms of assembly in plain English?
          
**If you are satisfied with the responses to the above questions, then go ahead and book the exam.**

#### Heading 4

##### Heading 5

###### Heading 6

### Body text

Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

![Smithsonian Image](https://mmistakes.github.io/minimal-mistakes/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H2O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times (That’s a citation). Underline.Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and CSS are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

{% highlight css %}
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
{% endhighlight %}

## Buttons

Make any link standout more when applying the `.btn` class.

{% highlight html %}
<a href="#" class="btn btn-success">Success Button</a>
{% endhighlight %}

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>

## KBD

You can also use `<kbd>` tag for keyboard buttons.

{% highlight html %}
<kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd>
{% endhighlight %}

Press <kbd>W</kbd><kbd>A</kbd><kbd>S</kbd><kbd>D</kbd> to move your car. **Midtown Maddness!!**

## Notices

**Watch out!** You can also add notices by appending `{: .notice}` to a paragraph.
{: .notice}
