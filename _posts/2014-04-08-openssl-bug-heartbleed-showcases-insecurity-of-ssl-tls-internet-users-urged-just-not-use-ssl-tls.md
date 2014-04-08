---
layout: post
title: "OpenSSL Bug _Heartbleed_ Showcases Insecurity of SSL/TLS, Internet Users
       Urged to Just Not Use SSL/TLS"
date: 2014-04-08T13:33:11+0000
dateline: Oulu, Finland
lead:
    image: http://i.imgur.com/g5hirtD.jpg
    caption: _Heartbleed_ bug logo placed on a jaunty angle — possibly the only
             bug with a logo.
---

A team of security engineers at Codenomicon, one security engineer at Google and
no security engineers at Yahoo! discovered a critical bug in the OpenSSL, a
popular library for tinfoil hat-wearing and the facilitation of terrorist
communications. This critical bug caused the leak of memory contents to
attackers, disclosing sensitive information such as _Geocities_ guest book
entries.

The bug in the C library has been fixed since Monday, but committed without a
unit test of any kind. _SF Bay Beat_ is unable to confirm if the patch has in
fact closed the exploit or created three more buffer overflow holes.

With the recent spate of SSL bugs with catchy names and single-use websites
(such as [gotofail](https://gotofail.com/)), internet users are encouraged to
point fingers at the NSA and make use of the Chrome extension
[HTTPSNowhere](http://avengingsyndrome.github.io/HTTPSNoWhere/). This add-on
alleviates both the effort required from system administrators to patch
vulnerable software, and the effort required from hackers to write ridiculously
hacky and non-production-ready exploit code. Security researchers are also
investigating alternatives to the protocol, such as two-pass ROT-13.

This move has been welcomed by internet bloggers, one of who objected to Gmail's
use of mandatory HTTPS — saying that it "went too far" and "removed consumer
choice".
