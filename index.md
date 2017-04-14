---
layout: default
title: "Kluck Engineering"
---

<!-- Sidebar -->
<section id="sidebar">
    <div class="inner">
        <nav>
            <ul>
                <li><a href="#intro">Intro</a></li>
                <li><a href="#what">Projects and prototypes</a></li>
                <li><a href="#oss">Open Source</a></li>
                <li><a href="#who">Who am I?</a></li>
            </ul>
        </nav>
    </div>
</section>

<!-- Wrapper -->
<div id="wrapper">

<!-- Intro -->
<section id="intro" class="wrapper style1 fullscreen fade-up">
    <div class="inner">
        <h1 class="major">Kluck.Engineering</h1>
        <p>
            Projects, prototypes and sometimes writings by a software engineer in Detroit.
        </p>

        <ul class="actions">
            <li><a href="#what" class="button scrolly">Projects</a></li>
            <li><a href="#oss" class="button scrolly">Open Source</a></li>
            <li><a href="#who" class="button scrolly">About Me</a></li>
        </ul>
    </div>
</section>


<!-- What - Projects and Prototypes -->
<section id="what" class="wrapper style2 fade-up">
    <div class="inner">
        <h2>Projects and Prototypes</h2>
        <p>
            I like to experiment (mostly with javascript or single page apps) and create small
            tools and prototypes on GitHub.
        </p>
    </div>
</section>

<!-- Open Source -->
<section id="oss" class="wrapper style3 spotlights">
    <div class="inner">
        <h2>Open Source</h2>
        <p>
            In addition to the small projects mentioned <a href="#what" class="scrolly">elsewhere</a>,
            I also maintain many production-stable open source projects.
        </p>
    </div>

    {% for project in site.data.oss %}
        <section>
            <a href="#" class="image"><img src="images/pic01.jpg" alt="" data-position="center center"></a>
            <div class="content">
                <div class="inner">
                    <h2>{{ project.name }}</h2>
                    <p>{{ project.description }}</p>

                    <div class="table-wrapper">
                        <table>
                            <tbody>
                                {% for repo in project.repos %}
                                    <tr>
                                        <td>{{ repo.name }}</td>
                                        <td><a href="https://github.com/{{ repo.repo }}">{{ repo.repo }}</a></td>
                                    </tr>
                                {% endfor %}
                            </tbody>
                        </table>
                    </div>

                </div>
            </div>
        <section>
    {% endfor %}

</section>

<!-- Who -->
<section id="who" class="wrapper style1 fade-up">
    <div class="inner">
        <h2>Who am I?</h2>

        <p>
            Hello. I am a fullstack software developer based in SE Michigan.

            I mostly focus on backend applications and services, but can work with frontend
            technologies and databases as well.
        </p>
        <p>
            In <b>2006</b> I joined HFHS. I’ve written CRMs and patient-management systems for
            <a href="http://www.henryford.com">Henry Ford Health System.</a><br><br>

            Then I joined Quicken Loans in <b>2012</b>. As an engineering lead I helped them
            launch the future of mortgage servicing with <a href="https://myql.com">MyQL Servicing.</a>
            Since then I’ve
            focused on building the foundation for PHP applications within QL. This includes
            deployment systems, CI, unit testing, enterprise system architecture and beyond.<br><br>

            <a href="http://elixir-lang.org">Elixir</a> is pretty cool, I’ve spent a lot of time exploring and learning about its ecosystem.
        </p>

        <hr>

        <div class="split style1">
            <section>
                <h3>{{ site.job.title }} ({{ site.job.company}})</h3>
                <ul class="alt">
                    {% for responsibility in site.job.responsibilities %}
                        <li>{{ responsibility }}</li>
                    {% endfor %}
                </ul>
            </section>

            <section>
                <ul class="contact">
                    <li>
                        <h3>Location</h3>
                        <span>
                            {{ site.location.city }}<br />
                            {{ site.location.country }}
                        </span>
                    </li>
                    <li>
                        <h3>Email</h3>
                        {{ site.email }}
                    </li>
                    <li>
                        <h3>GitHub</h3>
                        <ul class="icons">
                            <li><a href="{{ site.github_url }}" class="fa-github"> github.com/skluck</a></li>
                        </ul>
                    </li>
                </ul>
            </section>
        </div>
    </div>
</section>

</div>
