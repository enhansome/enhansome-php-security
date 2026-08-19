<br/>
<div align="center">

A curated list of awesome PHP Security related resources.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

*List inspired by the [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,536 | 🐛 102 | 📅 2026-08-18 list thing.*

Supported by: [GuardRails.io](https://www.guardrails.io)

</div>

# Contents

* [Tools](#projects)
  * [Web Framework Hardening](#web-framework-hardening)
  * [Static Code Analysis](#static-code-analysis)
  * [Vulnerabilities and Security Advisories](#vulnerabilities-and-security-advisories)
* [Educational](#educational)
  * [Hacking Playground](#hacking-playground)
  * [Guides](#guides)
* [Companies](#companies)
* [Contributing](#contributing)

# Tools

## Web Framework Hardening

* [Snuffleupagus](https://snuffleupagus.rtfd.io) - Security mondule for PHP7/8, the successsor to [suhosin](http://suhosin.org/stories/index.html).
* [Secure-Headers](https://github.com/BePsvPT/secure-headers) ⭐ 551 | 🐛 2 | 🌐 PHP | 📅 2026-07-21 - Add security related headers to HTTP response.

## Static Code Analysis

* [phpcs-security-audit](https://github.com/FloeDesignTechnologies/phpcs-security-audit) ⭐ 728 | 🐛 27 | 🌐 PHP | 📅 2023-01-05 - phpcs-security-audit is a set of PHP\_CodeSniffer rules that finds vulnerabilities and weaknesses related to security in PHP code.
  * `docker pull guardrails/phpcs-security-audit`
* [SonarPHP](https://github.com/SonarSource/sonar-php) ⭐ 431 | 🐛 1 | 🌐 Java | 📅 2026-08-18 from [SonarQube](https://github.com/SonarSource/sonarqube) ⭐ 10,906 | 🐛 0 | 🌐 Java | 📅 2026-08-18 - A static code analyser for PHP language used as an extension for the SonarQube platform (200+ rules, Supports up to PHP 8, Import of unit test and coverage results, Support of custom rules)
* [Exakat](https://github.com/exakat/exakat) ⭐ 380 | 🐛 47 | 🌐 PHP | 📅 2022-03-24 - *Exakat* is a PHP static code analysis, with serious [Security reviews](https://exakat.readthedocs.io/en/latest/Rulesets.html#security).
* [Parse](https://github.com/psecio/parse) ⭐ 380 | 🐛 18 | 🌐 PHP | 📅 2018-08-07 - The *Parse* scanner is a static scanning tool to review your PHP code for potential security-related issues.
* [progpilot](https://github.com/designsecurity/progpilot) ⭐ 366 | 🐛 4 | 🌐 PHP | 📅 2025-08-17 - A static analyzer for security purposes.
* [Enlightn](https://www.laravel-enlightn.com/) - Enlightn is a static and dynamic analysis tool to improve the security of Laravel applications.
* [Snyk Code](https://snyk.io/product/snyk-code/) PHP support (beta) and available in Snyk free tier

## Vulnerabilities and Security Advisories

* [roave/security-advisories](https://github.com/Roave/SecurityAdvisories) ⭐ 2,913 | 🐛 1 | 📅 2026-08-18 - Add this dependency to disallow known/vulnerable installation of packages directly through `composer update`
* [Security Advisories](https://github.com/FriendsOfPHP/security-advisories) ⭐ 2,137 | 🐛 2 | 🌐 PHP | 📅 2026-08-18 - A database of PHP security advisories.
* [security-checker](https://github.com/sensiolabs/security-checker) ⚠️ Archived - PHP frontend for security.symfony.com.
  * `docker pull guardrails/security-checker`
* [php-malware-detector](https://github.com/ollyxar/php-malware-detector) ⭐ 130 | 🐛 0 | 🌐 PHP | 📅 2018-12-18 - PHP malware detector
* [Symfony Security Monitoring](https://security.symfony.com/) - PHP security vulnerabilities monitoring.
* [Snyk Open Source](https://snyk.io/product/open-source-security-management/) - Package manager scanner with a free tier

# Awesome Educational with stars

## Hacking Playground

* [DVWA](https://github.com/ethicalhack3r/DVWA) ⭐ 13,509 | 🐛 7 | 🌐 PHP | 📅 2026-08-07 - Damn Vulnerable Web Application (DVWA) is a PHP/MySQL web application that is damn vulnerable.
* [Insecure PHP Example](https://github.com/rickogden/insecure-php-example) ⭐ 8 | 🐛 0 | 🌐 PHP | 📅 2024-02-28 - This is an example application built using Silex for routing to provide examples of SQL Injection, plain text passwords and XSS.

## Guides

* [Official PHP Security Manual](http://php.net/manual/en/security.php)
* [Survive The Deep End: PHP Security](https://phpsecurity.readthedocs.io/en/latest/)
* [Security Tips for a PHP Application](https://dev.to/restoreddev/security-tips-for-a-php-application-4e9a)
* [Awesome-AppSec: PHP-Section](https://github.com/paragonie/awesome-appsec#php) ⭐ 7,033 | 🐛 40 | 🌐 PHP | 📅 2025-02-22
* [The 2018 Guide to Building Secure PHP Software](https://paragonie.com/blog/2017/12/2018-guide-building-secure-php-software)

# Companies

* [GuardRails](https://www.guardrails.io) - A GitHub App that gives you instant security feedback in your Pull Requests.
* [RIPS](https://www.ripstech.com) - RIPS is the leading security analysis solution for PHP
* [Snyk](https://snyk.io) - A developer-first solution that automates finding & fixing vulnerabilities in your dependencies.
* [Sqreen](https://sqreen.io) - Automated security for your web apps - real time application security protection.
* [Paragon Initiative Enterprises](https://paragonie.com) - PHP Security and Cryptography consultants, open source library publishers.

# Contributing

Found an awesome project, package, article, other type of resources related to PHP Security? Submit a pull request!
Just follow the [guidelines](/CONTRIBUTING.md). Thank you!

## Inspiration

This awesome list was inspired by [awesome-nodejs-security](https://github.com/lirantal/awesome-nodejs-security) ⭐ 3,023 | 🐛 8 | 📅 2026-08-14 and [awesome-ruby-security](https://github.com/pxlpnk/awesome-ruby-security) ⭐ 474 | 🐛 1 | 📅 2024-02-22.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
