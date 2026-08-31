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
            Senior Java Backend Engineer with 15+ years of experience architecting 
            and delivering robust enterprise systems for government, financial, 
            and complex business domains. Strong expertise in Java-based backend development, 
            API design, distributed systems, persistence, security, database architecture, 
            and enterprise integrations. Proven ability to translate complex business 
            requirements into scalable, maintainable technical solutions, 
            while driving architectural decisions, code quality, testing, and long-term system sustainability.
          </p>

          <div class="hero-philosophy">
            My approach to backend engineering goes beyond implementation. 
            I first understand the business domain, existing architecture,
            and the wider impact of a change before making design decisions. 
            I favor simple, robust solutions that integrate naturally with the system, 
            and I validate them through comprehensive testing and critical review. 
            Every solution is evaluated not only for correctness, but also for maintainability, 
            security, performance, reliability, and its behavior in production.
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
            <i/>
            <i/>
            <i/>
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
                <span class="tag">Java</span>
                <span class="tag">Quarkus</span>
                <span class="tag">REST</span>
                <span class="tag">OpenAPI</span>
                <span class="tag">Keycloak</span>
                <span class="tag">JPA</span>
                <span class="tag">Oracle</span>
              </div>
            </div>
          </article>


          <article class="experience-item">
            <div class="experience-date">MAR 2025 — FEB 2026</div>

            <div>
              <h3>Senior Java Developer · Universal Tankers Corporation</h3>

              <p>
                Java and Spring Boot application development in a multi-technology
                environment, working with REST APIs, Groovy, Rails, Angular, Oracle,
                PostgreSQL and Keycloak.
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
            <div class="experience-date">NOV 2022 — DEC 2024</div>

            <div>
              <h3>Senior Java Developer · UniSystems</h3>

              <p>
                Delivered scalable Java applications for major public-sector and
                enterprise projects, including Greek eJustice, Cyprus eJustice and
                the UK Emissions Trading Scheme.
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
            <div class="experience-date">JUL 2018 — APR 2019</div>
            <div>
              <h3>Java Software Engineer · Municipal Water & Sewerage Enterprise</h3>
              <p>
                Developed and enhanced Java-based enterprise systems supporting municipal
                water and sewerage operations, translating business requirements into
                reliable software solutions while collaborating with cross-functional teams.
              </p>
              <div class="tags">
                <span class="tag">Java</span><span class="tag">Backend</span>
                <span class="tag">Government</span><span class="tag">Utilities</span>
                <span class="tag">Enterprise</span>
              </div>
            </div>
          </article>
          
          <article class="experience-item">
            <div class="experience-date">MAY 2014 — MAR 2018</div>
            <div>
              <h3>Java Developer · Wirecard</h3>
              <p>
                Developed high-performance Java applications within a global digital
                payments environment, working on financial systems supporting cashless
                payment processes and integrations across online, mobile and point-of-sale
                channels.
              </p>
              <div class="tags">
                <span class="tag">Java</span><span class="tag">Fintech</span>
                <span class="tag">Payments</span><span class="tag">Enterprise</span>
                <span class="tag">Financial Systems</span>
              </div>
            </div>
          </article>
          
          <article class="experience-item">
            <div class="experience-date">MAY 2012 — MAY 2014</div>
            <div>
              <h3>Java Full Stack Developer · Xite Agency</h3>
              <p>
                Designed and implemented full-stack web applications, combining Java and
                PHP backend development with frontend functionality and database-driven
                solutions for web and digital projects.
              </p>
              <div class="tags">
                <span class="tag">Java</span><span class="tag">PHP</span>
                <span class="tag">JavaScript</span><span class="tag">Web</span>
                <span class="tag">Full Stack</span>
              </div>
            </div>
          </article>
          
          <article class="experience-item">
            <div class="experience-date">FEB 2011 — DEC 2011</div>
            <div>
              <h3>Java Full Stack Developer · Municipality of Kos</h3>
              <p>
                Developed Java-based web applications supporting municipal digital
                services, focusing on reliable backend functionality, user-facing
                workflows and integration with public-sector processes.
              </p>
              <div class="tags">
                <span class="tag">Java</span><span class="tag">Government</span>
                <span class="tag">Web</span><span class="tag">Backend</span>
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
          not just the code. It means understanding the domain, challenging assumptions, 
          balancing constraints, and making sound technical decisions that stand up over time. 
          The measure of good engineering is not whether software works today, 
          but whether it remains reliable, maintainable, and resilient as the system evolves.
        </p>


        <!-- ENGINEERING FLOW -->

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


        <!-- ENGINEERING CARDS -->

        <div class="engineering-grid">

          <article class="engineering-card">

            <div class="engineering-number">01</div>

            <h3>Understand the problem</h3>

            <p>
              I begin by understanding the business problem and the domain before deciding how the code should be structured. 
              A clear understanding of the domain leads to better models, clearer responsibilities, and more predictable behaviour.
            </p>

            <ul class="engineering-list">
              <li>Clarify requirements, constraints, and business rules</li>
              <li>Identify edge cases, ambiguities, and exceptional scenarios</li>
              <li>Understand existing workflows and system behaviour</li>
              <li>Define actors, responsibilities, and domain boundaries</li>
              <li>Challenge assumptions before committing to an implementation</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">02</div>

            <h3>Explore the existing system</h3>

            <p>
              Before introducing a change, I first understand how the existing system works and where 
              the change naturally belongs. Good changes should fit the architecture rather than work around it.
            </p>

            <ul class="engineering-list">
              <li>Trace the request through the application</li>
              <li>Understand the existing architecture and flow</li>
              <li>Inspect related entities, repositories, and services</li>
              <li>Follow established conventions and patterns</li>
              <li>Identify dependencies, coupling, and potential side effects</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">03</div>

            <h3>Plan the change</h3>

            <p>
              A seemingly small requirement can have a broader impact across the system. 
              Before implementation, I consider the complete change, its dependencies, and its potential consequences.
            </p>

            <ul class="engineering-list">
              <li>API and contract impact</li>
              <li>Database and schema changes</li>
              <li>Migration and deployment strategy</li>
              <li>Security and authorization implications</li>
              <li>Backward compatibility and existing consumers</li>
              <li>Testing and verification requirements</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">04</div>

            <h3>Design before over-engineering</h3>

            <p>
              I prefer the simplest design that satisfies the requirements while
              keeping responsibilities clear and allowing the system to evolve.
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
              Implementation turns the design into working software, while keeping the broader system, 
              its constraints, and its existing conventions in view.
            </p>

            <ul class="engineering-list">
              <li>Readable and maintainable Java</li>
              <li>Consistent project conventions and patterns</li>
              <li>Explicit error handling</li>
              <li>Robust input validation</li>
              <li>Security-aware implementation</li>
            </ul>

          </article>


          <article class="engineering-card">

            <div class="engineering-number">06</div>

            <h3>Verify behaviour</h3>

            <p>
              I validate the behaviour that matters, using tests as a means of establishing 
              correctness rather than treating coverage alone as a measure of quality..
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
           ENGINEERING IN PRACTICE
           ===================================================== -->

      <section id="practice">

        <div class="eyebrow">Engineering in Practice</div>

        <h2>How I reason about everyday backend changes.</h2>

        <p class="lead">
         Good engineering decisions often happen before the code is written. 
          I use a set of practical questions to challenge assumptions, 
          understand the impact of a change, and arrive at a design that fits the system.
        </p>


        <div class="practice-grid">

          <!-- DATABASE -->

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


          <!-- JPA -->

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


          <!-- API -->

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


          <!-- TRANSACTION -->

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
           CODE REVIEW
           ===================================================== -->

      <section id="code-review">

        <div class="eyebrow">Code Review</div>

        <h2>I review code for engineering problems, not preferences.</h2>

        <p class="lead">
          Code review is a quality and architecture checkpoint. I look for problems
          that can affect correctness, performance, security, reliability and future
          maintainability — not simply differences in personal coding style.
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


          <!-- REVIEW EXAMPLE 1 -->

          <article class="review-card">
 
            <div class="review-card-header">
              <span class="review-label warning">JPA / PERFORMANCE</span>
              <span class="review-label">01</span>
            </div>

            <div class="code-review-grid">

              <div>

                <span class="code-label">Potential problem</span>

                  <p>
                    These are examples of the kinds of issues I look for during backend code reviews: not just whether the code works, but whether its behaviour, performance, and architectural boundaries are appropriate.
                  </p>
                
                <pre><code>@OneToMany(
    fetch = FetchType.EAGER
)
private Set&lt;Document&gt; documents;</code></pre>

              </div>

              <div>

                <span class="code-label">Review</span>

                <p>
                  EAGER relationships can trigger unnecessary database loading and make query behaviour harder to control. 
                  Depending on the surrounding query and relationship structure, they can also contribute to N+1 queries, 
                  larger result sets, and unnecessary memory usage.
                </p>

                <span class="code-label">Preferred direction</span>

                <pre><code>@OneToMany(
    fetch = FetchType.LAZY
)
private Set&lt;Document&gt; documents;</code></pre>

                <p class="review-note">
                  Fetch the data explicitly for the use case that requires it instead
                  of making every query pay the cost.
                </p>

              </div>

            </div>

          </article>


          <!-- REVIEW EXAMPLE 2 -->

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
                  Calling a transactional method from within the same CDI bean bypasses the CDI proxy, 
                  so the transactional interceptor is not applied through that invocation path.
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


          <!-- REVIEW EXAMPLE 3 -->

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
                  business rules and the indexes or constraints that Oracle will
                  create or use.
                </p>

                <p class="review-note">
                  Explicit constraint names make database changes easier to identify,
                  troubleshoot and maintain across environments.
                </p>

              </div>

            </div>

          </article>

        </div>

      </section>


      <!-- =====================================================
           TECHNICAL DECISION MAKING
           ===================================================== -->

      <section id="decisions">

        <div class="eyebrow">Technical Decision Making</div>

        <h2>I make trade-offs explicit.</h2>

        <p class="lead">
          There is rarely one universally correct technical solution. I prefer to
          make the constraints and trade-offs visible before choosing an approach.
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
              I choose technologies and patterns based on the problem, existing
              architecture, team capability and operational constraints.
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
           PRODUCTION MINDSET
           ===================================================== -->

      <section id="production">

        <div class="eyebrow">Production Mindset</div>

        <h2>The code is not finished when it compiles.</h2>

        <p class="lead">
          Backend software ultimately runs in a real environment with real users,
          real data and real failures. I consider those conditions during development.
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
          I use AI to accelerate engineering work across research, implementation, 
          testing, and review, but treat its output as input rather than authority. 
          I apply my own engineering judgment to validate solutions and remain 
          accountable for the architectural, security, business, and production decisions behind the software.
        </p>


        <div class="ai-grid">

          <div class="card ai-card">
            <span class="ai-icon">01</span>

            <h3>Explore</h3>

            <p>
              Compare implementation approaches, investigate APIs, identify edge
              cases and explore unfamiliar technical areas.
            </p>
          </div>


          <div class="card ai-card">
            <span class="ai-icon">02</span>

            <h3>Plan</h3>

            <p>
              Challenge assumptions, identify dependencies and think through
              architecture, persistence and testing implications.
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
              Challenge implementation decisions, identify potential bugs,
              performance issues and missing scenarios.
            </p>
          </div>


          <div class="card ai-card">
            <span class="ai-icon">05</span>

            <h3>Test</h3>

            <p>
              Generate test ideas, edge cases and failure scenarios that are then
              validated and refined by the engineer.
            </p>
          </div>


          <div class="card ai-card">
            <span class="ai-icon">06</span>

            <h3>Learn</h3>

            <p>
              Use AI to accelerate exploration of unfamiliar technologies,
              documentation and alternative approaches.
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
           ENGINEERING PRINCIPLES
           ===================================================== -->

      <section id="principles">

        <div class="eyebrow">Engineering Principles</div>

        <h2>Principles behind the work.</h2>

        <p class="lead">
          A few principles I use when making day-to-day engineering decisions.
        </p>


        <div class="principles-grid">

          <article class="principle">
            <span>01</span>

            <h3>Understand before implementing.</h3>

            <p>
              The best implementation starts with understanding the domain,
              requirements and constraints.
            </p>
          </article>


          <article class="principle">
            <span>02</span>

            <h3>Prefer simple solutions.</h3>

            <p>
              Complexity should solve a real problem. Abstractions should earn
              their place in the system.
            </p>
          </article>


          <article class="principle">
            <span>03</span>

            <h3>Design for change.</h3>

            <p>
              Good backend code should be understandable and adaptable as
              business requirements evolve.
            </p>
          </article>


          <article class="principle">
            <span>04</span>

            <h3>Review problems, not preferences.</h3>

            <p>
              Technical feedback should be backed by correctness, maintainability,
              performance, security or another meaningful engineering concern.
            </p>
          </article>


          <article class="principle">
            <span>05</span>

            <h3>Production is the real test.</h3>

            <p>
              Reliability, security, observability and data integrity matter
              beyond the development environment.
            </p>
          </article>


          <article class="principle">
            <span>06</span>

            <h3>Own the result.</h3>

            <p>
              Engineering responsibility extends beyond implementation to testing,
              deployment, operation and continuous improvement.
            </p>
          </article>

        </div>

      </section>


      <!-- =====================================================
           WORK
           ===================================================== -->

      <section id="work">

        <div class="eyebrow">Selected work</div>

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
             I engineer reliable backend systems that turn complex business requirements 
             into well-defined domain models, maintainable services, and predictable APIs. 
              My strongest area is Java backend engineering, with a particular focus on 
              enterprise systems where reliability, security, data integrity, and long-term maintainability are critical.
            </p>

            <p class="lead">
              I hold an M.Sc. in Advanced Software Development Technologies and am currently 
              pursuing a second M.Sc. in Cybersecurity, with a focus on Cybersecurity, 
              Blockchain, and secure software systems, at the University of Piraeus. 
              I have experience across government, fintech, intellectual property, transportation,
              and enterprise software. I bring a product-aware engineering mindset to backend 
              development—understanding not only how systems should be built, but why they exist and how they should serve the business.
            </p>

            <a class="btn primary" href="/assets/cv.pdf" download>
              Read full CV ↓
            </a>

          </div>


          <div class="facts">

            <div class="fact">
              <strong>15+</strong>
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

        <div class="eyebrow">Technical stack</div>

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
               <div class="csm-1">M.Sc. — Cybersecurity · <span class="csm-cp">Currently pursuing ..</span></div>  
               <div class="csm-2">Focus on Cybersecurity, Blockchain and secure software systems. </div>
            </h3>

            <p>
              University of Piraeus · 
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
            <span class="education-label">Technical Vocational Education</span>

            <h3>
              Application Engineer and Computer Networks
            </h3>

            <p>
              Technical Vocational School of Athens · 3-year technical studies · GPA 9.82/10
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
              For opportunities, collaboration or technical conversations,
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
