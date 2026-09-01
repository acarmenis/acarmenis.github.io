<script setup lang="ts">
import Navbar from './components/Navbar.vue'
import ProjectCard from './components/ProjectCard.vue'
import { projects } from './data/projects'
</script>

<template>
  <div class="wrap">
    <Navbar />

    <main>

      <!-- =====================================================
           HERO
           ===================================================== -->

      <section class="hero">

        <div>

          <div class="eyebrow">Senior Java Software Engineer</div>

          <h1>Building reliable backend systems that scale.</h1>

          <p>
            Senior Java Backend Engineer with 16+ years of experience architecting
            and delivering robust enterprise systems across government, financial,
            and complex business domains.
          </p>

          <p>
            Strong expertise in Java-based backend development, API design,
            distributed systems, persistence, security, database architecture,
            and enterprise integrations, with hands-on specialization in
            Spring Boot and Quarkus.
          </p>

          <div class="hero-philosophy">
            I don't treat backend engineering as simply implementing requirements.
            I first understand the domain, the existing architecture, and the wider
            impact of a change. I then make deliberate technical decisions and
            validate them through testing, review, and production-oriented thinking.
          </div>

          <div class="actions">
            <a class="btn primary" href="/assets/cv.pdf" download>
              Download CV ↓
            </a>

            <a class="btn" href="#engineering">
              How I Engineer
            </a>

            <a
              class="btn"
              href="https://www.linkedin.com/in/andreas-karmenis-9a515853/"
              target="_blank"
              rel="noreferrer"
            >
              LinkedIn ↗
            </a>
          </div>

        </div>


        <div class="terminal">

          <div class="dots">
            <i />
            <i />
            <i />
          </div>

          <pre><span class="m">$</span> whoami
<span class="g">andreas-karmenis</span>

<span class="m">role:</span>
  Senior Java Software Engineer

<span class="m">focus:</span>
  Java 21
  Spring Boot / Quarkus
  REST / OpenAPI
  Hibernate / JPA
  Oracle / PostgreSQL
  Keycloak / OIDC
  Docker / Maven

<span class="m">approach:</span>
  understand → design → build
  test → review → deliver

<span class="b">status:</span> building things that last.</pre>

        </div>

      </section>


      <!-- =====================================================
           EXPERIENCE
           ===================================================== -->

      <section id="experience">

        <div class="eyebrow">Experience</div>

        <h2>Enterprise software, from fintech to government.</h2>

        <p class="lead">
          16+ years of Java development across large-scale, business-critical
          systems, public-sector platforms, financial services, and complex
          enterprise environments.
        </p>


        <div class="timeline">

          <article class="experience-item current">

            <div class="experience-date">
              FEB 2026 — PRESENT
            </div>

            <div>

              <h3>Senior Java Software Engineer · Byte</h3>

              <p>
                Engineering a mission-critical government application for ASEP
                (Supreme Council for Civil Personnel Selection), the independent
                Greek authority responsible for civil service recruitment and
                personnel selection. The platform supports nationwide public-sector
                processes where reliability, security, data integrity, and
                long-term maintainability are essential.
              </p>

              <p>
                Responsible for backend development and technical design using
                Java, Quarkus, REST, OpenAPI, Keycloak, JPA, Oracle, Liquibase,
                and enterprise integration patterns.
              </p>

              <div class="tags">
                <span class="tag">Java 21</span>
                <span class="tag">Quarkus</span>
                <span class="tag">REST</span>
                <span class="tag">OpenAPI</span>
                <span class="tag">Keycloak</span>
                <span class="tag">JPA</span>
                <span class="tag">Oracle</span>
                <span class="tag">Liquibase</span>
              </div>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              MAR 2025 — FEB 2026
            </div>

            <div>

              <h3>Senior Java Developer · Universal Tankers Corporation</h3>

              <p>
                Engineered enterprise software supporting the worldwide
                operations of a tanker shipping company, spanning vessel and crew
                scheduling, personnel management, procurement and supplies,
                ticketing, cargo management, and voyage planning.
              </p>

              <p>
                Worked across a complex multi-technology environment, developing
                and integrating Java and Spring Boot services with REST APIs,
                Groovy, Rails, Angular, Oracle, PostgreSQL, and Keycloak.
              </p>

              <div class="tags">
                <span class="tag">Java 21</span>
                <span class="tag">Spring Boot</span>
                <span class="tag">REST</span>
                <span class="tag">Groovy</span>
                <span class="tag">Oracle</span>
                <span class="tag">PostgreSQL</span>
                <span class="tag">Keycloak</span>
              </div>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              NOV 2022 — DEC 2024
            </div>

            <div>

              <h3>Senior Java Developer · UniSystems</h3>

              <p>
                Engineered large-scale Java applications for critical public-sector
                and government systems, including nationwide eJustice platforms
                for Greece and Cyprus.
              </p>

              <p>
                Contributed to the digital transformation of judicial processes
                across both countries, as well as the UK Emissions Trading Scheme,
                working on complex enterprise systems where reliability, security,
                scalability, and long-term maintainability were essential.
              </p>

              <div class="tags">
                <span class="tag">Java</span>
                <span class="tag">Spring</span>
                <span class="tag">Microservices</span>
                <span class="tag">REST</span>
                <span class="tag">Oracle</span>
              </div>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              JAN 2022 — OCT 2022
            </div>

            <div>

              <h3>Java Developer · European Patent Office</h3>

              <p>
                Developed enterprise applications supporting European patent and
                intellectual property operations within the European Patent Office,
                contributing to robust Java services, reliable integrations, and
                high-performance applications in a large-scale international
                public-sector environment.
              </p>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              MAY 2019 — DEC 2021
            </div>

            <div>

              <h3>Java Developer · EUIPO / Greek Ministry</h3>

              <p>
                Contributed to the digital transformation and modernization of
                trademark services, integrating applications, databases, and the
                broader enterprise ecosystem to support reliable and scalable
                intellectual property operations.
              </p>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              JUL 2018 — APR 2019
            </div>

            <div>

              <h3>
                Java Software Engineer · Municipal Water & Sewerage Enterprise
              </h3>

              <p>
                Developed and enhanced Java-based enterprise systems supporting
                essential public-sector water and sewerage services, translating
                business requirements into reliable software solutions and
                collaborating across technical and business teams.
              </p>

              <div class="tags">
                <span class="tag">Java</span>
                <span class="tag">Backend</span>
                <span class="tag">Government</span>
                <span class="tag">Utilities</span>
                <span class="tag">Enterprise</span>
              </div>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              MAY 2014 — MAR 2018
            </div>

            <div>

              <h3>Java Developer · Wirecard</h3>

              <p>
                Developed and maintained enterprise Java applications within a
                global financial services and payments environment supporting
                banks, credit card transactions, merchants, and point-of-sale
                systems.
              </p>

              <p>
                Worked across POS, mobile, telephone, and web payment channels,
                integrating distributed financial services and contributing to
                high-performance, reliable payment infrastructure at global scale.
              </p>

              <div class="tags">
                <span class="tag">Java</span>
                <span class="tag">Fintech</span>
                <span class="tag">Payments</span>
                <span class="tag">Enterprise</span>
                <span class="tag">Financial Systems</span>
              </div>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              MAY 2012 — MAY 2014
            </div>

            <div>

              <h3>Java Full Stack Developer · Xite Agency</h3>

              <p>
                Designed, developed, and maintained web applications and websites,
                working across Java and PHP backends, frontend functionality, and
                database-driven solutions.
              </p>

              <div class="tags">
                <span class="tag">Java</span>
                <span class="tag">PHP</span>
                <span class="tag">JavaScript</span>
                <span class="tag">Web</span>
                <span class="tag">Full Stack</span>
              </div>

            </div>

          </article>


          <article class="experience-item">

            <div class="experience-date">
              FEB 2011 — DEC 2011
            </div>

            <div>

              <h3>Java Full Stack Developer · Local Government</h3>

              <p>
                Developed and maintained Java-based web applications supporting
                public-sector and municipal services. Worked across backend
                functionality, user-facing workflows, database integration, and
                business processes, translating operational requirements into
                reliable digital solutions.
              </p>

              <div class="tags">
                <span class="tag">Java</span>
                <span class="tag">Government</span>
                <span class="tag">Web</span>
                <span class="tag">Backend</span>
                <span class="tag">Public Sector</span>
              </div>

            </div>

          </article>

        </div>

      </section>


      <!-- =====================================================
           HOW I ENGINEER
           ===================================================== -->

      <section id="engineering">

        <div class="eyebrow">How I Engineer</div>

        <h2>Don't just look at what I built. Look at how I think.</h2>

        <p class="lead">
          Senior backend engineering is about owning the problem and the system,
          not just the code. It means understanding the domain, challenging
          assumptions, balancing constraints, and making sound technical decisions
          that stand up over time.
        </p>


        <div class="engineering-flow">

          <div class="flow-step">
            <span>01</span>
            <strong>Understand</strong>
            <small>Domain & requirements</small>
          </div>

          <div class="flow-arrow">→</div>

          <div class="flow-step">
            <span>02</span>
            <strong>Explore</strong>
            <small>Existing system</small>
          </div>

          <div class="flow-arrow">→</div>

          <div class="flow-step">
            <span>03</span>
            <strong>Plan</strong>
            <small>Impact & constraints</small>
          </div>

          <div class="flow-arrow">→</div>

          <div class="flow-step">
            <span>04</span>
            <strong>Design</strong>
            <small>Architecture & contracts</small>
          </div>

          <div class="flow-arrow">→</div>

          <div class="flow-step">
            <span>05</span>
            <strong>Build</strong>
            <small>Implementation</small>
          </div>

          <div class="flow-arrow">→</div>

          <div class="flow-step">
            <span>06</span>
            <strong>Verify</strong>
            <small>Tests & review</small>
          </div>

          <div class="flow-arrow">→</div>

          <div class="flow-step">
            <span>07</span>
            <strong>Deliver</strong>
            <small>Deploy & observe</small>
          </div>

        </div>


        <div class="engineering-grid">

          <article class="engineering-card">

            <div class="engineering-number">01</div>

            <h3>Understand the problem</h3>

            <p>
              I begin with the business problem and domain before deciding how
              the code should be structured.
            </p>

            <ul class="engineering-list">
              <li>Clarify requirements and business rules</li>
              <li>Identify edge cases and ambiguity</li>
              <li>Understand existing workflows</li>
              <li>Define responsibilities and boundaries</li>
              <li>Challenge assumptions early</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">02</div>

            <h3>Explore the existing system</h3>

            <p>
              Before introducing a change, I understand how the current system
              works and where the change naturally belongs.
            </p>

            <ul class="engineering-list">
              <li>Trace requests through the application</li>
              <li>Inspect entities, repositories, and services</li>
              <li>Follow established conventions</li>
              <li>Identify coupling and dependencies</li>
              <li>Consider side effects</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">03</div>

            <h3>Plan the change</h3>

            <p>
              Small requirements can have large consequences. I consider the
              complete change before implementation.
            </p>

            <ul class="engineering-list">
              <li>API and contract impact</li>
              <li>Database and schema changes</li>
              <li>Migration strategy</li>
              <li>Security implications</li>
              <li>Backward compatibility</li>
              <li>Testing requirements</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">04</div>

            <h3>Design before over-engineering</h3>

            <p>
              I prefer the simplest design that satisfies the requirements while
              keeping responsibilities clear.
            </p>

            <ul class="engineering-list">
              <li>Clear domain boundaries</li>
              <li>Appropriate service responsibilities</li>
              <li>Predictable API contracts</li>
              <li>Explicit transaction boundaries</li>
              <li>Appropriate abstractions</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">05</div>

            <h3>Implement with the system in mind</h3>

            <p>
              Implementation turns the design into working software while keeping
              the wider system and its constraints in view.
            </p>

            <ul class="engineering-list">
              <li>Readable and maintainable Java</li>
              <li>Consistent project conventions</li>
              <li>Explicit error handling</li>
              <li>Robust validation</li>
              <li>Security-aware implementation</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">06</div>

            <h3>Verify behaviour</h3>

            <p>
              I validate the behaviour that matters rather than treating coverage
              alone as a measure of quality.
            </p>

            <ul class="engineering-list">
              <li>Unit tests</li>
              <li>Integration tests</li>
              <li>REST/API tests</li>
              <li>Security scenarios</li>
              <li>Failure and edge cases</li>
            </ul>

          </article>

        </div>

      </section>


      <!-- =====================================================
           BACKEND ARCHITECTURE
           ===================================================== -->

      <section id="architecture">

        <div class="eyebrow">Backend Architecture</div>

        <h2>Designing systems around clear boundaries.</h2>

        <p class="lead">
          My backend designs typically separate API contracts, application
          behaviour, domain responsibilities, persistence, and infrastructure.
          The exact architecture depends on the system, but the goal remains the
          same: clear responsibilities, predictable behaviour, and controlled
          dependencies.
        </p>


        <div class="architecture-diagram">

          <div class="architecture-side security-side">

            <span>SECURITY</span>
            <strong>Keycloak / OIDC</strong>
            <small>Authentication · Authorization</small>

          </div>


          <div class="architecture-main">

            <div class="architecture-layer">
              <span>01</span>
              <strong>REST API</strong>
              <small>OpenAPI · DTOs · Validation · HTTP contracts</small>
            </div>

            <div class="architecture-connector">↓</div>

            <div class="architecture-layer">
              <span>02</span>
              <strong>Application / Services</strong>
              <small>Use cases · Business workflows · Transactions</small>
            </div>

            <div class="architecture-connector">↓</div>

            <div class="architecture-layer">
              <span>03</span>
              <strong>Domain</strong>
              <small>Business rules · Responsibilities · Invariants</small>
            </div>

            <div class="architecture-connector">↓</div>

            <div class="architecture-layer">
              <span>04</span>
              <strong>Persistence</strong>
              <small>JPA · Hibernate · Repositories · Query strategy</small>
            </div>

            <div class="architecture-connector">↓</div>

            <div class="architecture-layer">
              <span>05</span>
              <strong>Database</strong>
              <small>Oracle · PostgreSQL · Constraints · Migrations</small>
            </div>

          </div>


          <div class="architecture-side integration-side">

            <span>INTEGRATION</span>
            <strong>External Systems</strong>
            <small>REST · SOAP · Messaging · Enterprise services</small>

          </div>

        </div>


        <div class="architecture-principles">

          <article class="card">
            <span class="architecture-card-number">01</span>
            <h3>Contracts first</h3>
            <p>
              APIs should expose deliberate contracts rather than leaking internal
              persistence models into consumers.
            </p>
          </article>

          <article class="card">
            <span class="architecture-card-number">02</span>
            <h3>Responsibilities stay clear</h3>
            <p>
              Controllers, services, domain logic, and persistence should have
              understandable responsibilities.
            </p>
          </article>

          <article class="card">
            <span class="architecture-card-number">03</span>
            <h3>Persistence is a design concern</h3>
            <p>
              Query behaviour, fetching, transactions, constraints, and database
              performance are considered part of backend design.
            </p>
          </article>

          <article class="card">
            <span class="architecture-card-number">04</span>
            <h3>Security surrounds the system</h3>
            <p>
              Authentication and authorization are considered alongside API and
              business design rather than added as an afterthought.
            </p>
          </article>

        </div>

      </section>


      <!-- =====================================================
           TECHNICAL LEADERSHIP
           ===================================================== -->

      <section id="leadership">

        <div class="eyebrow">Technical Leadership</div>

        <h2>Senior engineering is also about technical ownership.</h2>

        <p class="lead">
          Leadership does not require a management title. In engineering, it also
          means taking responsibility for technical direction, identifying risks,
          improving quality, communicating trade-offs, and helping the team make
          better decisions.
        </p>


        <div class="leadership-grid">

          <article class="leadership-card">
            <span>01</span>
            <h3>Technical direction</h3>
            <p>
              Contribute to architectural discussions and help determine how
              requirements should translate into maintainable technical solutions.
            </p>
          </article>

          <article class="leadership-card">
            <span>02</span>
            <h3>Design ownership</h3>
            <p>
              Think beyond individual classes and consider API contracts,
              persistence, transactions, integrations, and system-wide impact.
            </p>
          </article>

          <article class="leadership-card">
            <span>03</span>
            <h3>Code quality</h3>
            <p>
              Use code review to identify correctness, architecture, performance,
              security, and maintainability problems before they reach production.
            </p>
          </article>

          <article class="leadership-card">
            <span>04</span>
            <h3>Risk awareness</h3>
            <p>
              Identify technical and operational risks early, especially around
              data integrity, migrations, transactions, security, and integrations.
            </p>
          </article>

          <article class="leadership-card">
            <span>05</span>
            <h3>Engineering communication</h3>
            <p>
              Explain technical decisions in terms of constraints, trade-offs,
              consequences, and business impact.
            </p>
          </article>

          <article class="leadership-card">
            <span>06</span>
            <h3>Long-term thinking</h3>
            <p>
              Prefer solutions that remain understandable and changeable for the
              engineers who will maintain the system later.
            </p>
          </article>

        </div>

      </section>


      <!-- =====================================================
           ENGINEERING IN PRACTICE
           ===================================================== -->

      <section id="practice">

        <div class="eyebrow">Engineering in Practice</div>

        <h2>How I reason about everyday backend changes.</h2>

        <p class="lead">
          Good engineering decisions often happen before the code is written.
          I use practical questions to challenge assumptions, understand impact,
          and arrive at a design that fits the system.
        </p>


        <div class="practice-grid">

          <article class="practice-card">

            <div class="practice-header">
              <span class="practice-label">DATABASE CHANGE</span>
              <span class="practice-number">01</span>
            </div>

            <h3>"Add a new field."</h3>

            <div class="thought-process">

              <div>Does it change the API contract?</div>
              <span>↓</span>

              <div>Can existing rows handle the new value?</div>
              <span>↓</span>

              <div>Should it be nullable?</div>
              <span>↓</span>

              <div>Does it require a default?</div>
              <span>↓</span>

              <div>Does it need an index or constraint?</div>
              <span>↓</span>

              <div>Does Liquibase need a migration?</div>
              <span>↓</span>

              <div>Do existing queries and tests change?</div>

            </div>

          </article>


          <article class="practice-card">

            <div class="practice-header">
              <span class="practice-label">JPA / HIBERNATE</span>
              <span class="practice-number">02</span>
            </div>

            <h3>"Return related entities from an API."</h3>

            <div class="thought-process">

              <div>What data does the endpoint actually need?</div>
              <span>↓</span>

              <div>What is the relationship?</div>
              <span>↓</span>

              <div>How is it fetched?</div>
              <span>↓</span>

              <div>Could this introduce N+1 queries?</div>
              <span>↓</span>

              <div>Should fetching be explicit?</div>
              <span>↓</span>

              <div>What SQL will Hibernate execute?</div>
              <span>↓</span>

              <div>How large can the result become?</div>

            </div>

          </article>


          <article class="practice-card">

            <div class="practice-header">
              <span class="practice-label">REST API</span>
              <span class="practice-number">03</span>
            </div>

            <h3>"Add an endpoint."</h3>

            <div class="thought-process">

              <div>What resource is being exposed?</div>
              <span>↓</span>

              <div>What is the contract?</div>
              <span>↓</span>

              <div>What validation is required?</div>
              <span>↓</span>

              <div>Who is allowed to call it?</div>
              <span>↓</span>

              <div>What happens on invalid input?</div>
              <span>↓</span>

              <div>What happens when the resource does not exist?</div>
              <span>↓</span>

              <div>How will the API evolve?</div>

            </div>

          </article>


          <article class="practice-card">

            <div class="practice-header">
              <span class="practice-label">TRANSACTION</span>
              <span class="practice-number">04</span>
            </div>

            <h3>"Update several pieces of data."</h3>

            <div class="thought-process">

              <div>What must succeed or fail together?</div>
              <span>↓</span>

              <div>Where should the transaction boundary be?</div>
              <span>↓</span>

              <div>What happens if the second operation fails?</div>
              <span>↓</span>

              <div>Are there concurrency concerns?</div>
              <span>↓</span>

              <div>Is the persistence context behaving as expected?</div>
              <span>↓</span>

              <div>Can the operation be safely retried?</div>

            </div>

          </article>

        </div>

      </section>


      <!-- =====================================================
           TECHNICAL DECISIONS
           ===================================================== -->

      <section id="decisions">

        <div class="eyebrow">Technical Decision Making</div>

        <h2>I make trade-offs explicit.</h2>

        <p class="lead">
          There is rarely one universally correct technical solution. I prefer
          to make constraints and trade-offs visible before choosing an approach.
        </p>


        <div class="decision-model">

          <div>
            <span>01</span>
            <strong>Problem</strong>
            <small>What are we solving?</small>
          </div>

          <b>→</b>

          <div>
            <span>02</span>
            <strong>Constraints</strong>
            <small>What limits the solution?</small>
          </div>

          <b>→</b>

          <div>
            <span>03</span>
            <strong>Alternatives</strong>
            <small>What options exist?</small>
          </div>

          <b>→</b>

          <div>
            <span>04</span>
            <strong>Trade-offs</strong>
            <small>What do we gain and lose?</small>
          </div>

          <b>→</b>

          <div>
            <span>05</span>
            <strong>Decision</strong>
            <small>What fits the system?</small>
          </div>

        </div>


        <div class="decision-grid">

          <article class="card">
            <h3>Simple over clever</h3>
            <p>
              Complexity should solve a real problem. Abstractions and patterns
              should earn their place in the codebase.
            </p>
          </article>

          <article class="card">
            <h3>Context over fashion</h3>
            <p>
              Technologies and patterns should fit the problem, architecture,
              team capability, and operational constraints.
            </p>
          </article>

          <article class="card">
            <h3>Evolution over perfection</h3>
            <p>
              Good design should allow the system to evolve without requiring
              unnecessary upfront complexity.
            </p>
          </article>

        </div>

      </section>


      <!-- =====================================================
           CODE REVIEW
           ===================================================== -->

      <section id="code-review">

        <div class="eyebrow">Code Review</div>

        <h2>I review code for engineering problems, not preferences.</h2>

        <p class="lead">
          Code review is a quality and architecture checkpoint. I look for
          problems that can affect correctness, performance, security, reliability,
          and future maintainability — not simply differences in coding style.
        </p>


        <div class="review-principles">

          <div class="review-item">
            <span>01</span>
            <strong>Correctness</strong>
            <p>Does the implementation actually satisfy the requirement?</p>
          </div>

          <div class="review-item">
            <span>02</span>
            <strong>Architecture</strong>
            <p>Does the change belong in this layer and responsibility?</p>
          </div>

          <div class="review-item">
            <span>03</span>
            <strong>Persistence</strong>
            <p>What happens at the JPA, Hibernate and database level?</p>
          </div>

          <div class="review-item">
            <span>04</span>
            <strong>Performance</strong>
            <p>Are queries, fetching and data access appropriate?</p>
          </div>

          <div class="review-item">
            <span>05</span>
            <strong>Security</strong>
            <p>Could the implementation expose or incorrectly authorize data?</p>
          </div>

          <div class="review-item">
            <span>06</span>
            <strong>Transactions</strong>
            <p>Are consistency and transaction boundaries correct?</p>
          </div>

          <div class="review-item">
            <span>07</span>
            <strong>Maintainability</strong>
            <p>Will another engineer understand and safely change it?</p>
          </div>

          <div class="review-item">
            <span>08</span>
            <strong>Testing</strong>
            <p>Are important behaviours and failure scenarios covered?</p>
          </div>

        </div>


        <div class="review-examples">

          <div class="eyebrow">Examples</div>

          <h3>What a review looks like in practice.</h3>


          <article class="review-card">

            <div class="review-card-header">
              <span class="review-label warning">JPA / PERFORMANCE</span>
              <span class="review-label">01</span>
            </div>

            <div class="code-review-grid">

              <div>

                <span class="code-label">Potential problem</span>

                <pre><code>@OneToMany(
    fetch = FetchType.EAGER
)
private Set&lt;Document&gt; documents;</code></pre>

              </div>

              <div>

                <span class="code-label">Review</span>

                <p>
                  EAGER relationships can trigger unnecessary database loading
                  and make query behaviour harder to control. Depending on the
                  surrounding query and relationship structure, they can also
                  contribute to N+1 queries, larger result sets, and unnecessary
                  memory usage.
                </p>

                <span class="code-label">Preferred direction</span>

                <pre><code>@OneToMany(
    fetch = FetchType.LAZY
)
private Set&lt;Document&gt; documents;</code></pre>

                <p class="review-note">
                  Fetch the data explicitly for the use case that requires it
                  instead of making every query pay the cost.
                </p>

              </div>

            </div>

          </article>


          <article class="review-card">

            <div class="review-card-header">
              <span class="review-label warning">TRANSACTIONS</span>
              <span class="review-label">02</span>
            </div>

            <div class="code-review-grid">

              <div>

                <span class="code-label">Potential problem</span>

                <pre><code>@Scheduled(every = "24h")
void process() {
    updateRecords();
}

@Transactional
void updateRecords() {
    // database updates
}</code></pre>

              </div>

              <div>

                <span class="code-label">Review</span>

                <p>
                  Transactional interception depends on how the method is invoked.
                  Calling a transactional method from within the same CDI bean
                  bypasses the CDI proxy, so the transactional interceptor is not
                  applied through that invocation path.
                </p>

                <span class="code-label">Preferred direction</span>

                <pre><code>@Scheduled(every = "24h")
void process() {
    recordService.updateRecords();
}</code></pre>

                <p class="review-note">
                  Keep the transactional operation in another CDI-managed service
                  when proxy interception is required.
                </p>

              </div>

            </div>

          </article>


          <article class="review-card">

            <div class="review-card-header">
              <span class="review-label warning">DATABASE / MIGRATION</span>
              <span class="review-label">03</span>
            </div>

            <div class="code-review-grid">

              <div>

                <span class="code-label">Migration</span>

                <pre><code>&lt;addUniqueConstraint
    tableName="PERSON"
    columnNames="VAT"
    constraintName="UK_PERSON_VAT"/&gt;</code></pre>

              </div>

              <div>

                <span class="code-label">Review</span>

                <p>
                  A schema change should be reviewed together with existing data,
                  business rules, and the indexes or constraints that Oracle will
                  create or use.
                </p>

                <p class="review-note">
                  Explicit constraint names make database changes easier to
                  identify, troubleshoot, and maintain across environments.
                </p>

              </div>

            </div>

          </article>

        </div>

      </section>


      <!-- =====================================================
           ENGINEERING OUTCOMES
           ===================================================== -->

      <section id="outcomes">

        <div class="eyebrow">Engineering Outcomes</div>

        <h2>From technical decisions to real system outcomes.</h2>

        <p class="lead">
          Engineering value is not measured by how much code is written.
          It is measured by whether the resulting system becomes more reliable,
          maintainable, understandable, and capable of supporting the business.
        </p>


        <div class="outcomes-grid">

          <article class="outcome-card">

            <div class="outcome-header">
              <span>01</span>
              <strong>Government platform</strong>
            </div>

            <div class="outcome-step">
              <span>Problem</span>
              <p>
                A business requirement affects API behaviour, domain rules,
                persistence, validation, and existing workflows.
              </p>
            </div>

            <div class="outcome-step">
              <span>Decision</span>
              <p>
                Trace the existing flow first, identify the natural ownership
                of the change, and evaluate API, database, security, and
                compatibility impact.
              </p>
            </div>

            <div class="outcome-step">
              <span>Outcome</span>
              <p>
                A targeted change that fits the existing architecture instead
                of introducing unnecessary coupling or duplicated logic.
              </p>
            </div>

          </article>


          <article class="outcome-card">

            <div class="outcome-header">
              <span>02</span>
              <strong>Persistence and performance</strong>
            </div>

            <div class="outcome-step">
              <span>Problem</span>
              <p>
                A backend endpoint needs related data without unnecessarily
                loading an entire object graph.
              </p>
            </div>

            <div class="outcome-step">
              <span>Decision</span>
              <p>
                Analyse the relationship, query behaviour, fetching strategy,
                result size, and actual data required by the use case.
              </p>
            </div>

            <div class="outcome-step">
              <span>Outcome</span>
              <p>
                More predictable persistence behaviour and a query strategy
                aligned with the endpoint's actual requirements.
              </p>
            </div>

          </article>


          <article class="outcome-card">

            <div class="outcome-header">
              <span>03</span>
              <strong>Database evolution</strong>
            </div>

            <div class="outcome-step">
              <span>Problem</span>
              <p>
                A domain change requires a database schema modification while
                existing data and environments must remain consistent.
              </p>
            </div>

            <div class="outcome-step">
              <span>Decision</span>
              <p>
                Consider nullability, defaults, existing rows, indexes,
                constraints, migration ordering, and application compatibility.
              </p>
            </div>

            <div class="outcome-step">
              <span>Outcome</span>
              <p>
                A migration that is deliberate, traceable, and safer to deploy
                across environments.
              </p>
            </div>

          </article>


          <article class="outcome-card">

            <div class="outcome-header">
              <span>04</span>
              <strong>Transaction boundaries</strong>
            </div>

            <div class="outcome-step">
              <span>Problem</span>
              <p>
                Several database operations must behave as one consistent unit.
              </p>
            </div>

            <div class="outcome-step">
              <span>Decision</span>
              <p>
                Identify what must succeed or fail together and place the
                transaction boundary at the appropriate service level.
              </p>
            </div>

            <div class="outcome-step">
              <span>Outcome</span>
              <p>
                More predictable consistency and fewer hidden transactional
                assumptions inside scheduled or service-driven operations.
              </p>
            </div>

          </article>

        </div>

      </section>


      <!-- =====================================================
           PRODUCTION MINDSET
           ===================================================== -->

      <section id="production">

        <div class="eyebrow">Production Mindset</div>

        <h2>The code is not finished when it compiles.</h2>

        <p class="lead">
          Backend software ultimately runs in a real environment with real users,
          real data, real dependencies, and real failures. I consider those
          conditions during development.
        </p>


        <div class="production-grid">

          <div class="production-item">
            <strong>Reliability</strong>
            <span>What happens when dependencies fail?</span>
          </div>

          <div class="production-item">
            <strong>Security</strong>
            <span>Who can access and modify the data?</span>
          </div>

          <div class="production-item">
            <strong>Performance</strong>
            <span>How does the solution behave as data grows?</span>
          </div>

          <div class="production-item">
            <strong>Observability</strong>
            <span>Can we understand what happened in production?</span>
          </div>

          <div class="production-item">
            <strong>Data integrity</strong>
            <span>Can partial failures leave inconsistent state?</span>
          </div>

          <div class="production-item">
            <strong>Evolution</strong>
            <span>Can the system safely change tomorrow?</span>
          </div>

        </div>

      </section>


      <!-- =====================================================
           AI ASSISTED ENGINEERING
           ===================================================== -->

      <section id="ai-engineering">

        <div class="eyebrow">AI-Assisted Engineering</div>

        <h2>AI accelerates engineering. It doesn't replace judgment.</h2>

        <p class="lead">
          I use AI to accelerate research, implementation, testing, and review,
          but treat its output as input rather than authority. I remain accountable
          for the architectural, security, business, and production decisions
          behind the software.
        </p>


        <div class="ai-grid">

          <div class="card ai-card">
            <span class="ai-icon">01</span>
            <h3>Explore</h3>
            <p>
              Compare implementation approaches, investigate APIs, identify edge
              cases, and explore unfamiliar technical areas.
            </p>
          </div>

          <div class="card ai-card">
            <span class="ai-icon">02</span>
            <h3>Plan</h3>
            <p>
              Challenge assumptions, identify dependencies, and think through
              architecture, persistence, and testing implications.
            </p>
          </div>

          <div class="card ai-card">
            <span class="ai-icon">03</span>
            <h3>Implement</h3>
            <p>
              Accelerate repetitive development while keeping the resulting code
              aligned with project conventions and architecture.
            </p>
          </div>

          <div class="card ai-card">
            <span class="ai-icon">04</span>
            <h3>Review</h3>
            <p>
              Challenge implementation decisions and identify potential bugs,
              performance issues, and missing scenarios.
            </p>
          </div>

          <div class="card ai-card">
            <span class="ai-icon">05</span>
            <h3>Test</h3>
            <p>
              Generate test ideas, edge cases, and failure scenarios that are
              then validated and refined by the engineer.
            </p>
          </div>

          <div class="card ai-card">
            <span class="ai-icon">06</span>
            <h3>Learn</h3>
            <p>
              Accelerate exploration of unfamiliar technologies, documentation,
              and alternative approaches.
            </p>
          </div>

        </div>


        <div class="ai-boundary">

          <div>
            <div class="eyebrow">Human responsibility</div>

            <h3>
              What I don't outsource to AI.
            </h3>
          </div>

          <div class="boundary-list">
            <span>Architecture</span>
            <span>Business Decisions</span>
            <span>Security</span>
            <span>Database Design</span>
            <span>Production Responsibility</span>
            <span>Final Code Review</span>
          </div>

        </div>

      </section>


      <!-- =====================================================
           WORK
           ===================================================== -->

      <section id="work">

        <div class="eyebrow">Selected Work</div>

        <h2>Systems and domains I've worked on.</h2>

        <p class="lead">
          A selection of enterprise and personal work that reflects my backend
          engineering experience.
        </p>

        <div class="grid">

          <ProjectCard
            v-for="p in projects"
            :key="p.title"
            v-bind="p"
          />

        </div>

      </section>


      <!-- =====================================================
           ABOUT
           ===================================================== -->

      <section id="about">

        <div class="about">

          <div>

            <div class="eyebrow">About</div>

            <h2>Backend first. Product aware.</h2>

            <p class="lead">
              I engineer reliable backend systems that turn complex business
              requirements into well-defined domain models, maintainable services,
              and predictable APIs.
            </p>

            <p class="lead">
              My strongest area is Java backend engineering, with a particular
              focus on enterprise systems where reliability, security, data
              integrity, and long-term maintainability are critical.
            </p>

            <p class="lead">
              I hold an M.Sc. in Advanced Software Development Technologies and
              am currently pursuing a second M.Sc. in Cybersecurity, with a focus
              on Cybersecurity, Blockchain, and secure software systems, at the
              University of Piraeus.
            </p>

            <p class="lead">
              I have experience across government, fintech, intellectual property,
              transportation, and enterprise software. I bring a product-aware
              engineering mindset to backend development — understanding not only
              how systems should be built, but why they exist and how they should
              serve the business.
            </p>

            <a class="btn primary" href="/assets/cv.pdf" download>
              Read full CV ↓
            </a>

          </div>


          <div class="facts">

            <div class="fact">
              <strong>16+</strong>
              <span>Years in software development</span>
            </div>

            <div class="fact">
              <strong>Java</strong>
              <span>Core backend expertise</span>
            </div>

            <div class="fact">
              <strong>M.Sc.</strong>
              <span>Advanced Software Development Technologies</span>
            </div>

            <div class="fact">
              <strong>Enterprise</strong>
              <span>Government · fintech · business systems</span>
            </div>

          </div>

        </div>

      </section>


      <!-- =====================================================
           STACK
           ===================================================== -->

      <section id="stack">

        <div class="eyebrow">Technical Stack</div>

        <h2>The tools behind the work.</h2>

        <div class="grid">

          <div class="card">
            <h3>Backend</h3>
            <p>
              Java · Spring · Spring Boot · Quarkus · REST · SOAP ·
              Microservices · Hibernate · JPA
            </p>
          </div>

          <div class="card">
            <h3>Data</h3>
            <p>
              Oracle · PostgreSQL · MySQL · MongoDB · SQL · Liquibase ·
              Database design
            </p>
          </div>

          <div class="card">
            <h3>Security & APIs</h3>
            <p>
              Keycloak · OIDC · OpenAPI · Authentication · Authorization ·
              API design
            </p>
          </div>

          <div class="card">
            <h3>Engineering</h3>
            <p>
              Maven · Git · Jenkins · Docker · Jira · Agile · Scrum ·
              Automated testing
            </p>
          </div>

          <div class="card">
            <h3>Frontend</h3>
            <p>
              Angular · Vue.js · Thymeleaf · JavaScript · HTML · CSS
            </p>
          </div>

          <div class="card">
            <h3>Other</h3>
            <p>
              Kafka · JasperReports · Groovy · Rails · MapStruct
            </p>
          </div>

        </div>

      </section>


      <!-- =====================================================
           EDUCATION
           ===================================================== -->

      <section id="education">

        <div class="eyebrow">Education</div>

        <h2>Academic foundation.</h2>

        <div class="education-grid">

          <div class="card">

            <span class="education-label">M.Sc.</span>

            <h3>
              <div class="csm-1">
                M.Sc. — Cybersecurity ·
                <span class="csm-cp">Currently pursuing</span>
              </div>

              <div class="csm-2">
                Focus on Cybersecurity, Blockchain and secure software systems.
              </div>
            </h3>

            <p>
              University of Piraeus
            </p>

          </div>


          <div class="card">

            <span class="education-label">M.Sc.</span>

            <h3>
              Advanced Software Development Technologies
            </h3>

            <p>
              University of Piraeus · GPA 9.35 / 10
            </p>

          </div>


          <div class="card">

            <span class="education-label">B.Sc.</span>

            <h3>
              IT Engineering
            </h3>

            <p>
              TEI of Athens · GPA 7.5 / 10
            </p>

          </div>


          <div class="card">

            <span class="education-label">
              Technical Vocational Education
            </span>

            <h3>
              Application Engineer and Computer Networks
            </h3>

            <p>
              Technical Vocational School of Athens ·
              3-year technical studies · GPA 9.82 / 10
            </p>

          </div>


          <div class="card">

            <span class="education-label">Certificate</span>

            <h3>
              Android Programming
            </h3>

            <p>
              National Technical University of Athens
            </p>

          </div>

        </div>

      </section>


      <!-- =====================================================
           CONTACT
           ===================================================== -->

      <section id="contact">

        <div class="contact">

          <div>

            <div class="eyebrow">Let's connect</div>

            <h2>
              Have a backend problem worth solving?
            </h2>

            <p class="lead">
              For opportunities, collaboration, or technical conversations,
              find me here.
            </p>

          </div>


          <div class="actions">

            <a
              class="btn primary"
              href="https://www.linkedin.com/in/andreas-karmenis-9a515853/"
              target="_blank"
              rel="noreferrer"
            >
              LinkedIn ↗
            </a>

            <a
              class="btn"
              href="https://github.com/acarmenis"
              target="_blank"
              rel="noreferrer"
            >
              GitHub ↗
            </a>

            <a
              class="btn"
              href="https://gitlab.com/com.carmenis"
              target="_blank"
              rel="noreferrer"
            >
              GitLab ↗
            </a>

            <a
              class="btn"
              href="mailto:a.karmenis@outlook.com"
            >
              Email ↗
            </a>

          </div>

        </div>

      </section>

    </main>


    <footer>

      <span>
        © {{ new Date().getFullYear() }} · Andreas Karmenis
      </span>

      <span>
        Vue 3 · Vite · TypeScript
      </span>

    </footer>

  </div>
</template>
