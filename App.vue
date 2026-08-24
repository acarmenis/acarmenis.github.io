<script setup lang="ts">
import Navbar from './components/Navbar.vue'
import ProjectCard from './components/ProjectCard.vue'
import { projects } from './data/projects'
</script>

<template>
  <div class="wrap">
    <Navbar />

    <main>
      <section class="hero">
        <div>
          <div class="eyebrow">Senior Java Software Engineer</div>
          <h1>Building reliable backend systems that scale.</h1>
          <p>
            Java backend engineer with 15+ years of experience building enterprise,
            government and financial systems. Focused on clean architecture,
            APIs, persistence, security and maintainable software.
          </p>

          <div class="actions">
            <a class="btn primary" href="/assets/cv.pdf" download>Download CV ↓</a>
            <a class="btn" href="#experience">Experience</a>
            <a class="btn" href="https://www.linkedin.com/in/andreas-karmenis-9a515853/" target="_blank" rel="noreferrer">LinkedIn ↗</a>
          </div>
        </div>

        <div class="terminal">
          <div class="dots"><i/><i/><i/></div>
          <pre><span class="m">$</span> whoami
<span class="g">andreas-karmenis</span>

<span class="m">current:</span>
  Senior Java Software Engineer

<span class="m">focus:</span>
  Java 21
  Spring Boot / Quarkus
  REST / OpenAPI
  Hibernate / JPA
  Oracle / PostgreSQL
  Keycloak / OIDC
  Docker / Maven

<span class="b">status:</span> building things that last.</pre>
        </div>
      </section>

      <section id="experience">
        <div class="eyebrow">Experience</div>
        <h2>Enterprise software, from fintech to government.</h2>
        <p class="lead">
          A career focused on Java development across large-scale, business-critical
          systems and public-sector platforms.
        </p>

        <div class="timeline">
          <article class="experience-item current">
            <div class="experience-date">FEB 2026 — PRESENT</div>
            <div>
              <h3>Senior Java Software Engineer · Byte</h3>
              <p>
                Backend development using Java, Quarkus, REST, OpenAPI, Keycloak,
                JPA and Oracle, with a focus on secure and maintainable enterprise APIs.
              </p>
              <div class="tags">
                <span class="tag">Java</span><span class="tag">Quarkus</span>
                <span class="tag">REST</span><span class="tag">OpenAPI</span>
                <span class="tag">Keycloak</span><span class="tag">JPA</span>
                <span class="tag">Oracle</span>
              </div>
            </div>
          </article>

          <article class="experience-item">
            <div class="experience-date">MAR 2025 — PRESENT</div>
            <div>
              <h3>Senior Java Developer · Universal Tankers Corporation</h3>
              <p>
                Java and Spring Boot application development in a multi-technology
                environment, working with REST APIs, Groovy, Rails, Angular, Oracle,
                PostgreSQL and Keycloak.
              </p>
              <div class="tags">
                <span class="tag">Java 21</span><span class="tag">Spring Boot</span>
                <span class="tag">REST</span><span class="tag">Groovy</span>
                <span class="tag">Oracle</span><span class="tag">PostgreSQL</span>
                <span class="tag">Keycloak</span>
              </div>
            </div>
          </article>

          <article class="experience-item">
            <div class="experience-date">NOV 2022 — DEC 2024</div>
            <div>
              <h3>Senior Java Developer · UniSystems</h3>
              <p>
                Delivered scalable Java applications for major public-sector and
                enterprise projects, including Greek eJustice, Cyprus eJustice and
                the UK Emissions Trading Scheme.
              </p>
              <div class="tags">
                <span class="tag">Java</span><span class="tag">Spring</span>
                <span class="tag">Microservices</span><span class="tag">REST</span>
                <span class="tag">Oracle</span>
              </div>
            </div>
          </article>

          <article class="experience-item">
            <div class="experience-date">JAN 2022 — OCT 2022</div>
            <div>
              <h3>Java Developer · European Patent Office</h3>
              <p>
                Contributed to application development with an emphasis on robust
                services and reliable system performance.
              </p>
            </div>
          </article>

          <article class="experience-item">
            <div class="experience-date">MAY 2019 — DEC 2021</div>
            <div>
              <h3>Java Developer · EUIPO / Greek Ministry</h3>
              <p>
                Worked on digital transformation, technology-stack modernization
                and integration of services, databases and the surrounding ecosystem.
              </p>
            </div>
          </article>

          <article class="experience-item">
            <div class="experience-date">MAY 2014 — MAR 2018</div>
            <div>
              <h3>Java Developer · Wirecard</h3>
              <p>
                Developed high-performance Java applications for financial and
                payment-related systems.
              </p>
            </div>
          </article>
        </div>
      </section>

      <section id="work">
        <div class="eyebrow">Selected work</div>
        <h2>Systems and domains I've worked on.</h2>
        <p class="lead">
          A selection of enterprise and personal work that reflects my backend
          engineering experience.
        </p>
        <div class="grid">
          <ProjectCard v-for="p in projects" :key="p.title" v-bind="p"/>
        </div>
      </section>

      <section id="about">
        <div class="about">
          <div>
            <div class="eyebrow">About</div>
            <h2>Backend first. Product aware.</h2>
            <p class="lead">
              I enjoy turning complex business requirements into clear domain models,
              maintainable services and predictable APIs. My strongest area is Java
              backend engineering, particularly enterprise systems where reliability,
              security and data matter.
            </p>
            <p class="lead">
              I hold an M.Sc. in Advanced Software Development Technologies and
              have worked across government, fintech, intellectual property,
              transportation and enterprise software.
            </p>
            <a class="btn primary" href="/assets/cv.pdf" download>Read full CV ↓</a>
          </div>

          <div class="facts">
            <div class="fact"><strong>15+</strong><span>Years in software development</span></div>
            <div class="fact"><strong>Java</strong><span>Core backend expertise</span></div>
            <div class="fact"><strong>M.Sc.</strong><span>Advanced Software Development Technologies</span></div>
            <div class="fact"><strong>Enterprise</strong><span>Government · fintech · business systems</span></div>
          </div>
        </div>
      </section>

      <section id="stack">
        <div class="eyebrow">Technical stack</div>
        <h2>The tools behind the work.</h2>

        <div class="grid">
          <div class="card">
            <h3>Backend</h3>
            <p>Java · Spring · Spring Boot · Quarkus · REST · SOAP · Microservices · Hibernate · JPA</p>
          </div>
          <div class="card">
            <h3>Data</h3>
            <p>Oracle · PostgreSQL · MySQL · MongoDB · SQL · Liquibase · Database design</p>
          </div>
          <div class="card">
            <h3>Security & APIs</h3>
            <p>Keycloak · OIDC · OpenAPI · Authentication · Authorization · API design</p>
          </div>
          <div class="card">
            <h3>Engineering</h3>
            <p>Maven · Git · Jenkins · Docker · Jira · Agile · Scrum · Automated testing</p>
          </div>
          <div class="card">
            <h3>Frontend</h3>
            <p>Angular · Vue.js · Thymeleaf · JavaScript · HTML · CSS</p>
          </div>
          <div class="card">
            <h3>Other</h3>
            <p>Kafka · JasperReports · Groovy · Rails · MapStruct</p>
          </div>
        </div>
      </section>

      <section id="education">
        <div class="eyebrow">Education</div>
        <h2>Academic foundation.</h2>

        <div class="education-grid">
          <div class="card">
            <span class="education-label">M.Sc.</span>
            <h3>Advanced Software Development Technologies</h3>
            <p>University of Piraeus · GPA 9.35 / 10</p>
          </div>
          <div class="card">
            <span class="education-label">B.Sc.</span>
            <h3>IT Engineering</h3>
            <p>TEI of Athens · GPA 7.5 / 10</p>
          </div>
          <div class="card">
            <span class="education-label">Certificate</span>
            <h3>Android Programming</h3>
            <p>National Technical University of Athens</p>
          </div>
        </div>
      </section>

      <section id="contact">
        <div class="contact">
          <div>
            <div class="eyebrow">Let's connect</div>
            <h2>Have a backend problem worth solving?</h2>
            <p class="lead">
              For opportunities, collaboration or technical conversations, find me here.
            </p>
          </div>
          <div class="actions">
            <a class="btn primary" href="https://www.linkedin.com/in/andreas-karmenis-9a515853/" target="_blank" rel="noreferrer">LinkedIn ↗</a>
            <a class="btn" href="https://github.com/acarmenis" target="_blank" rel="noreferrer">GitHub ↗</a>
            <a class="btn" href="mailto:a.karmenis@outlook.com">Email ↗</a>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <span>© {{ new Date().getFullYear() }} · Andreas Karmenis</span>
      <span>Vue 3 · Vite · TypeScript</span>
    </footer>
  </div>
</template>
