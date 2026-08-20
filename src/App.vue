<script setup lang="ts">
import Navbar from './components/Navbar.vue'
import ProjectCard from './components/ProjectCard.vue'
import { projects } from './data/projects'
</script>
<template>
<div class="wrap">
<Navbar/>
<main>
<section class="hero">
<div><div class="eyebrow">Software Engineer · Backend</div><h1>Building reliable systems, APIs & backend platforms.</h1><p>I design and build production-oriented Java backend services with a focus on clean architecture, data, security and maintainability.</p><div class="actions"><a class="btn primary" href="/assets/cv.pdf" download>Download CV ↓</a><a class="btn" href="#work">View selected work</a></div></div>
<div class="terminal"><div class="dots"><i/><i/><i/></div><pre><span class="m">$</span> whoami

<span class="g">software-engineer</span>

<span class="m">focus:</span>
  Java 21
  Quarkus
  REST APIs
  Hibernate / JPA
  Oracle / PostgreSQL
  Liquibase
  Docker
  Keycloak / OIDC

<span class="b">status:</span> building things that last.</pre></div>
</section>

<section id="work"><div class="eyebrow">Selected work</div><h2>Projects that show how I think.</h2><p class="lead">Focus on the problem, architecture and impact — not just the technology list.</p><div class="grid"><ProjectCard v-for="p in projects" :key="p.title" v-bind="p"/></div></section>

<section id="about"><div class="about"><div><div class="eyebrow">About</div><h2>Backend first. Product aware.</h2><p class="lead">I enjoy turning complex business requirements into clear domain models, maintainable services and predictable APIs. My strongest area is backend engineering, especially Java-based enterprise systems.</p><a class="btn primary" href="/assets/cv.pdf" download>Read full CV ↓</a></div><div class="facts"><div class="fact"><strong>Java</strong><span>Modern JVM development</span></div><div class="fact"><strong>Quarkus</strong><span>Cloud-native Java</span></div><div class="fact"><strong>Data</strong><span>SQL · Oracle · PostgreSQL</span></div><div class="fact"><strong>Architecture</strong><span>APIs · Domain · Persistence</span></div></div></div></section>

<section id="stack"><div class="eyebrow">Technical stack</div><h2>The tools behind the work.</h2><div class="grid"><div class="card"><h3>Backend</h3><p>Java 21 · Quarkus · Spring · REST · Hibernate ORM · Panache · MapStruct</p></div><div class="card"><h3>Data</h3><p>Oracle · PostgreSQL · JPA · SQL · Liquibase · database indexing</p></div><div class="card"><h3>Platform</h3><p>Docker · Maven · OpenAPI · Keycloak · OIDC · automated testing</p></div></div></section>

<section id="contact"><div class="contact"><div><div class="eyebrow">Let's connect</div><h2>Have a backend problem worth solving?</h2><p class="lead">For opportunities, collaboration or technical conversations, find me here.</p></div><div class="actions"><a class="btn primary" href="https://www.linkedin.com/" target="_blank">LinkedIn ↗</a><a class="btn" href="https://github.com/" target="_blank">GitHub ↗</a></div></div></section>
</main>
<footer><span>© {{ new Date().getFullYear() }} · Software Engineer</span><span>Vue 3 · Vite · TypeScript</span></footer>
</div>
</template>