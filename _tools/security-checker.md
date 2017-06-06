---
layout: tool
title: SensioLabs Security Checker
authors: [Fabien Potencier]
license: MIT License
license-url: https://github.com/sensiolabs/security-checker/blob/master/LICENSE
website: https://security.sensiolabs.org/
demo: https://security.sensiolabs.org/check
source: https://github.com/sensiolabs/security-checker 
packagist: sensiolabs/security-checker
docker: phpqa/security-checker
command: security-checker 
tags: [security, composer, vulnerabilities checker, cli, online service] 
comments: true
---

[{{ page.title }}]({{ site.url }}{{ page.url }}) is a command line tool that checks if your
application uses dependencies with known security vulnerabilities.
 
<!--more--> 

It uses the [SensioLabs Security Check Web service][1] and the [Security Advisories Database][2].

[1]: http://security.sensiolabs.org/
[2]: https://github.com/FriendsOfPHP/security-advisories
[3]: http://get.sensiolabs.org/security-checker.phar