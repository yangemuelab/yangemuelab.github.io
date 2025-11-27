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
      <a href="/cv/"><img src="{{ '/images/profile.jpg' | relative_url }}" alt="Portrait of Lei Yang" loading="lazy"></a>
      <h3>Lei Yang, Ph.D.</h3>
    </article>
  </div>
</section>

<section class="people-section" id="scientists">
  <h2>Research Scientists</h2>
  <div class="people-grid">
    <article class="person-card">
      <img src="{{ '/images/bio-photo.jpg' | relative_url }}" alt="Portrait" class="person-photo" loading="lazy">
      <h3>Name 1</h3>
      <p class="person-role">Research Scientist</p>
      <p class="person-focus">Research focus area</p>
      <p class="person-email"><a href="mailto:email1@example.com">email1@example.com</a></p>
    </article>
    <article class="person-card">
      <img src="{{ '/images/bio-photo-2.jpg' | relative_url }}" alt="Portrait" class="person-photo" loading="lazy">
      <h3>Name 2</h3>
      <p class="person-role">Research Scientist</p>
      <p class="person-focus">Research focus area</p>
      <p class="person-email"><a href="mailto:email2@example.com">email2@example.com</a></p>
    </article>
  </div>
</section>

<section class="people-section" id="postdocs">
  <h2>Postdoctoral Fellows</h2>
  <div class="people-grid">
    <article class="person-card">
      <img src="{{ '/images/bio-photo.jpg' | relative_url }}" alt="Portrait" class="person-photo" loading="lazy">
      <h3>Name 1</h3>
      <p class="person-role">Postdoctoral Fellow</p>
      <p class="person-focus">Research focus area</p>
      <p class="person-email"><a href="mailto:email1@example.com">email1@example.com</a></p>
    </article>
    <article class="person-card">
      <img src="{{ '/images/bio-photo-2.jpg' | relative_url }}" alt="Portrait" class="person-photo" loading="lazy">
      <h3>Name 2</h3>
      <p class="person-role">Postdoctoral Fellow</p>
      <p class="person-focus">Research focus area</p>
      <p class="person-email"><a href="mailto:email2@example.com">email2@example.com</a></p>
    </article>
  </div>
</section>

<section class="people-section" id="graduates">
  <h2>Graduate Students</h2>
  <div class="people-grid">
    <article class="person-card">
      <img src="{{ '/images/bio-photo.jpg' | relative_url }}" alt="Portrait" class="person-photo" loading="lazy">
      <h3>Name 1</h3>
      <p class="person-role">Ph.D. Student</p>
      <p class="person-edu">Background in Engineering</p>
      <p class="person-focus">Research interests in AI-driven composite design</p>
      <p class="person-email"><a href="mailto:email1@example.com">email1@example.com</a></p>
    </article>
    <article class="person-card">
      <img src="{{ '/images/bio-photo-2.jpg' | relative_url }}" alt="Portrait" class="person-photo" loading="lazy">
      <h3>Name 2</h3>
      <p class="person-role">M.S. Student</p>
      <p class="person-edu">Background in Engineering</p>
      <p class="person-focus">Research interests in Geomechanics</p>
      <p class="person-email"><a href="mailto:email2@example.com">email2@example.com</a></p>
    </article>
  </div>
</section>

<section class="people-section" id="alumni">
  <h2>Alumni</h2>
  <p class="coming-soon">We will showcase alumni stories here as the group grows.</p>
</section>

<style>
/* --- UPDATED PEOPLE PAGE STYLES (CONSISTENT HEADINGS) --- */

/* Define Color Variables for consistency */
:root {
    --brand-teal: #00BFA5;
    --brand-teal-dark: #008c7a;
    --brand-teal-pale: #E0F7FA; /* A very light wash */
    
    /* Neutral Grays for Text Hierarchy (No Purple) */
    --heading-dark: #2c3e50; /* Professional Dark Slate for section headers */
    --text-dark: #1a202c;    /* Deep Charcoal for primary names */
    --text-medium: #4a4a4a;  /* Medium gray for roles and descriptions */
    --border-light: #e5e7eb; /* Standard light gray border used on other pages */
}

.page__title {
  text-align: left;
  margin-bottom: 0.5em;
}

.people-section {
  margin-top: 2.5rem;
}

.people-section:first-of-type {
  margin-top: 0;
}

.people-section:first-of-type h2 {
  margin-top: 0;
}

/* --- Section Headings (CONSISTENT WITH OTHER PAGES) --- */
.people-section h2 {
  /* Matched size and weight to Opportunities page */
  font-size: 1.375rem; 
  font-weight: 600;
  /* Matched color */
  color: var(--heading-dark); 
  /* Matched standard gray border */
  border-bottom: 2px solid var(--border-light); /* PREVIOUS: #d5dbee */
  /* Matched spacing */
  padding-bottom: 0.75rem; /* PREVIOUS: 0.4rem */
  margin-bottom: 1.25rem; /* PREVIOUS: 1.2rem */
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

/* --- Principal Investigator (PI) Specific Styles --- */
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
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: block;
}

.pi-card a {
  display: inline-block;
  text-decoration: none;
}

.pi-card a:hover img {
  transform: translateY(-2px);
  box-shadow: 0 16px 32px rgba(15, 23, 42, 0.2);
}

/* PI Name */
.pi-card h3 {
  font-size: 1.1rem;
  color: var(--text-dark);
  margin-bottom: 0;
  font-weight: 700; /* Bolder for PI */
}

/* --- General Person Card Styles --- */
.person-card {
  border: 1px solid #e6e6e6;
  border-radius: 8px;
  padding: 1.25rem;
  background-color: #fff;
  box-shadow: 0 1px 3px rgba(15, 23, 42, 0.08);
  text-align: center;
  transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
}

.person-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 18px rgba(15, 23, 42, 0.16);
  /* Border turns Teal on hover for modern interaction feel */
  border-color: var(--brand-teal);
}

.person-photo {
  width: 180px;
  height: 180px;
  object-fit: cover;
  border-radius: 50%;
  margin: 0 auto 1rem auto;
  display: block;
  box-shadow: 0 4px 8px rgba(15, 23, 42, 0.12);
}

/* Person Name */
.person-card h3 {
  margin: 0;
  font-size: 1.05rem;
  color: var(--text-dark);
  font-weight: 600;
}

/* Person Role */
.person-role {
  font-weight: 500;
  color: var(--text-medium);
  margin-top: 0.4rem;
  margin-bottom: 0.6rem;
}

/* Person Education & Focus text */
.person-edu,
.person-focus {
  font-size: 0.95rem;
  color: var(--text-medium);
  margin-bottom: 0.5rem;
  line-height: 1.5;
}

/* Email Link Container */
.person-email {
  margin-top: 0.75rem;
  margin-bottom: 0;
  font-size: 0.9rem;
}

/* Email Link - Using your existing Teal colors via variables */
.person-email a {
  color: var(--brand-teal);
  text-decoration: none;
  transition: color 0.2s ease;
  font-weight: 500;
}

.person-email a:hover {
  color: var(--brand-teal-dark);
  text-decoration: underline;
}

/* Placeholder style for alumni or future posts */
.person-card.placeholder {
  text-align: center;
  background: linear-gradient(135deg, #ffffff, var(--brand-teal-pale));
  border-style: dashed;
  border-color: #bfcde9;
}
</style>