---
layout: archive
title: "People"
permalink: /people/
author_profile: false
---

{% include base_path %}

<section class="people-section" id="pi">
  <h2>Principal Investigator</h2>
  <div class="people-grid pi-grid">
    <article class="person-card pi-card">
      <img src="{{ '/images/profile.jpg' | relative_url }}" alt="Portrait of Lei Yang" loading="lazy">
      <h3><a href="/cv/">Lei Yang, Ph.D.</a></h3>
    </article>
  </div>
</section>

<section class="people-section" id="scientists">
  <h2>Research Scientists</h2>
  <div class="people-grid">
    <article class="person-card placeholder">
      <h3>We are recruiting</h3>
      <p class="person-role">Research Scientist</p>
      <p>Applicants with expertise in high-rate material characterization and computational mechanics are encouraged to contact us.</p>
    </article>
  </div>
</section>

<section class="people-section" id="postdocs">
  <h2>Postdoctoral Fellows</h2>
  <div class="people-grid">
    <article class="person-card placeholder">
      <h3>Open Position</h3>
      <p class="person-role">Postdoctoral Fellow</p>
      <p>Focus areas: dynamic fracture, high-fidelity simulations, AI for materials design.</p>
    </article>
  </div>
</section>

<section class="people-section" id="graduates">
  <h2>Graduate Students</h2>
  <div class="people-grid">
    <article class="person-card placeholder">
      <h3>Open position</h3>
      <p class="person-role">Ph.D. Student</p>
      <p class="person-edu">Background in Engineering</p>
      <p class="person-focus">Research interests in AI-driven materials design</p>
    </article>
    <article class="person-card placeholder">
      <h3>Open Position</h3>
      <p class="person-role">M.S. Student</p>
      <p class="person-edu">Background in Engineering</p>
      <p class="person-focus">Research interests in Geomechanics</p>
    </article>
  </div>
</section>

<section class="people-section" id="alumni">
  <h2>Alumni</h2>
  <p class="coming-soon">We will showcase alumni stories here as the group grows.</p>
</section>

<style>
.page__title {
  text-align: left;
  margin-bottom: 0.5em; /* Match default page title spacing */
}

.people-hero {
  margin-bottom: 1.5rem;
  font-size: 1rem;
  color: #444;
}

.people-hero a {
  color: #1f6feb;
}

.people-section {
  margin-top: 2.5rem;
}

.people-section:first-of-type {
  margin-top: 0; /* No extra spacing - matches default page title to paragraph spacing */
}

.people-section:first-of-type h2 {
  margin-top: 0; /* Remove h2's default margin-top for first section */
}

.people-section h2 {
  font-size: 1.4rem;
  color: #2c3e50;
  border-bottom: 1px solid #e0e0e0;
  padding-bottom: 0.4rem;
  margin-bottom: 1.2rem;
}

.people-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.25rem;
}

.alumni-grid {
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
}

.coming-soon {
  font-style: italic;
  color: #6b7280;
}
.pi-grid {
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  justify-items: center;
}

.pi-card {
  text-align: center;
  max-width: 260px;
  padding: 0;
  border: none;
  box-shadow: none;
  background: transparent;
}

.pi-card img {
  width: 220px;
  height: 260px;
  object-fit: cover;
  border-radius: 12px;
  margin-bottom: 0.75rem;
  box-shadow: 0 12px 24px rgba(15, 23, 42, 0.16);
}

.pi-card h3 {
  font-size: 1.15rem;
  color: #16213e;
  margin-bottom: 0;
}

.pi-card h3 a,
.pi-card h3 a:visited {
  color: inherit;
  text-decoration: none;
}

.person-card {
  border: 1px solid #e6e6e6;
  border-radius: 8px;
  padding: 1.25rem;
  background-color: #fff;
  box-shadow: 0 1px 3px rgba(15, 23, 42, 0.08);
}

.person-card h3 {
  margin: 0;
  font-size: 1.1rem;
  color: #16213e;
}

.person-role {
  font-weight: 500;
  color: #415a77;
  margin-top: 0.4rem;
  margin-bottom: 0.6rem;
}

.person-edu,
.person-focus {
  font-size: 0.95rem;
  color: #4a4a4a;
  margin-bottom: 0.5rem;
}

.person-card.placeholder {
  text-align: center;
  background: linear-gradient(135deg, #f9fbff, #f1f5ff);
  border-style: dashed;
}
</style>