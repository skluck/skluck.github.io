---
layout: page
title: About
permalink: about
icon: info_outline
---

Hello. I am a software developer based in SE Michigan.

I mostly focus on backend applications and services, but can work with frontend technologies and databases as well.

## Who the hell am I?

I write software. 

In **2006** I joined HFHS. I've written CRMs and patient-management systems for [Henry Ford Health System](http://www.henryford.com).

Then I joined Quicken Loans in **2012**. As an engineering lead I helped them launch the future of mortgage servicing with [MyQL Servicing](https://myql.com). Since then I've focused on building the foundation for PHP applications within QL. This includes deployment systems, CI, unit testing, enterprise system architecture and beyond.

Elixir is pretty cool, I've spent a lot of time exploring and learning about its ecosystem.

---

## Education

##### Wayne State University

- Bachelor of Science in Computer Science, 2010 (Magna Cum Laude)

---

## Skills

#### I know these really well.

- **PHP**
    - Slim
    - Symfony
    - Doctrine
    - PHP 7
- **MySQL**
- **AWS**
    - EC2, S3
    - Elastic Beanstalk, CodeDeploy
    - API / SDK
- **APIs**
    - REST
    - Hypermedia
- **Build / Deployment pipelines**
    - Grunt, Gulp
    - WinRM
    - GitHub / TFS API
    - Jenkins, Travis
- **CSS**
    - SASS
    - Responsive Design
    - Progressive Enhancement

#### I know these pretty well.

- **Elixir**
    - Plug
    - Phoenix
    - Erlang
- **Javascript**
    - JQuery
    - VueJS
- **Docker**
- **Postgres**
- [Consul](https://www.consul.io)
- Linuxy things
- OAuth2 / OpenID Connect

#### I know these less well, but enough to be dangerous.

- **Javascript**
    - ES6
    - React
    - Server-side rendering

#### I like these and am actively improving my knowledge.

- [Rethink DB](http://rethinkdb.com)

---

## Work Experience

### 2012 - Present

#### Quicken Loans • Detroit, MI • Principal Software Engineer

> ##### Role and Responsibilities
>
> - Lead developer on only engineering team within Center of Excellence.
> - Design, implement, and maintain PHP applications.
> - Maintain core shared PHP libraries for use throughout company. 
> - Mentor other engineers, define best practices.
> 
> ##### Major Projects
> 
> - **Deployment platform for on-premise and cloud**
>   - Built PHP and MySQL-based web frontend and agent job processor for deployments.
>   - Supports any unix-based app, with prototype support for Windows through WinRM. Deploys from GitHub to on-premise, AWS Elastic Beanstalk, CodeDeploy, or S3.
>   - Archives build for rollbacks, record audit trails, and provides runtime configuration through encrypted consul.io backend cluster.
>   - Builds are isolated to docker containers.
>   - Used for all environments, including production for over 50 apps and all public-facing web-tier projects.
> - **servicing.myql.com rewrite**
>   - Technical lead for rewrite of MyQL mortgage servicing. Functionality includes payment processing, document generation and upload.
>   - Set standard for 95% unit test coverage.
> - **PHP Frameworks**
>   - Primary maintainer for internal legacy framework and modernized it to allow greater application flexibility and developer choice.
>   - Built and open-sourced new microframework (Panthor). Write documentation and provide upgrade and migration guidance for developers.
> - **Maintain PHP library ecosystem**
>   - Provide SDKs for company services including logging, encryption, caching, CMS, and runtime configuration.
> - **Single Sign On solution for client accounts**
>   - Built prototype for replacement auth system for all QL systems.
>   - Supported strict OAuth2 spec, in addition to OpenID Connect and non-standard Single Sign Out functionality.
> - **Service Virtualization**
>   - Building Elixir and RethinkDB based mock engine and proxy for service mocking to allow apps to virtualize vendor or internal http services during failure states, load testing, and more.

### 2006 - 2012

#### Henry Ford Health System • Detroit, MI • Programmer Analyst

> ##### Role and Responsibilities
>
> - Built and maintained PHP/MySQL application for electronic medical records
> - Program several public-facing recruiting surveys for research studies
> - Collate and import polysomnogram data from multiple physical locations 
> - Responsibilities included:
>     - UX design
>     - Creating art assets
>     - PHP/MySQL backend
>     - HTML/CSS/JS frontend
