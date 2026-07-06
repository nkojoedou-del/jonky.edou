---
layout: default
title: Home
---

<div class="hero">
  <div>
    <h1>Hi — I'm {{ site.author.name }}.<br/>I design secure systems & build defensive tools.</h1>
    <p>I'm a cybersecurity engineer focused on threat-hunting, secure tooling, and privacy-first design. This portfolio highlights projects, CTF write-ups, and audits.</p>
    <div class="cta">
      <a class="btn" href="{{ '/projects' | relative_url }}">View Projects</a>
      <a class="btn secondary" href="{{ '/about' | relative_url }}">About Me</a>
    </div>
  </div>
  <aside class="card">
    <h4>Highlights</h4>
    <div class="tech-list">
      <span class="chip">Go</span><span class="chip">Rust</span><span class="chip">Python</span><span class="chip">Linux</span><span class="chip">Docker</span><span class="chip">Kubernetes</span>
    </div>
    <div style="margin-top:16px">
      <h4>Quick Links</h4>
      <div><a href="{{ '/ctf' | relative_url }}" class="chip">CTF Write-ups</a></div>
    </div>
  </aside>
</div>

<section class="projects">
  <article class="project">
    <h3>Threat Scanner</h3>
    <p class="muted">An automated scanner that detects suspicious configurations.</p>
    <pre>git clone https://github.com/you/threat-scanner</pre>
  </article>
  <article class="project">
    <h3>Audit Toolkit</h3>
    <p class="muted">Tools for quick host and network auditing.</p>
  </article>
</section>

<section style="margin-top:28px">
  <a class="btn" href="{{ '/about/' | relative_url }}">Full profile & certifications</a>
</section>
