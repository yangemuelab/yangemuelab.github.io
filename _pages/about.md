---
permalink: /
title: "Welcome to EMUE Lab!"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<div class="home-intro-media">
  <img src="/images/ImpactLoading.jpg" alt="Impact Loading Scenarios in Life and Lab">
  <p>"EMUE - Extreme Mechanics for Underground Engineering"</p>
</div>

<div class="home-intro-text">
  <p>
    Welcome to the EMUE Lab in the College of Civil and Transportation Engineering at Shenzhen University. Our mission is to <strong>see, understand, predict, and design the behavior of structural materials (rocks, concrete, and high-performance composites) under extreme loading conditions</strong>, through a combination of experiments, physics-based theoretical and computational modeling, artifical intelligence, and additive manufacturing. Our goal is to ensure the success and safety of real-world applications in critical sectors where extreme loading scenarios prevail. We are particularly interested in applying our foundamental research to <strong>underground engineering</strong>, but our research also has wide applications in defense, energy, and space. You can explore our current work on our <a href="/research/">Research</a> and <a href="/publications/">Publications</a> pages.
  </p>
</div>

<div class="home-cta-banner">
  <h3><i class="fas fa-user-plus"></i> Join the Team</h3>
  <p>We are actively seeking <strong>researchers, postdoctoral fellows, and graduate students</strong> to join our group in <strong>Fall 2026</strong>.</p>
  <a href="/opportunities/" class="btn btn--teal">See Opportunities</a>
</div>

<h2 class="home-section-title">
  <i class="fas fa-bullhorn"></i> Latest News
</h2>

<div class="home-news-container">

  <div class="news-item">
    <div class="news-date">Dec 2025</div>
    <div class="news-content">
      <strong>Postdoc Completed:</strong> Dr. Lei Yang has completed his postdoctoral training in the Hopkins Extreme Materials Institute (HEMI) at Johns Hopkins University.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">Nov 2025</div>
    <div class="news-content">
      <strong>New Position:</strong> Dr. Lei Yang has accepted a Research Assistant Professor position in the Department of Mechanical Engineering at Hong Kong Polytechnic University.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">Nov 2025</div>
    <div class="news-content">
      <strong>Award:</strong> Dr. Lei Yang received the “Excellent Young Scientists Fund Program (Overseas)” from the Chinese Government.
    </div>
  </div>

  <div class="news-item">
    <div class="news-date">May 2025</div>
    <div class="news-content">
      <strong>New Paper:</strong> Our work on "A mechanism‐based constitutive model for competent rocks subjected to impact loading" was published in <i>JGR: Solid Earth</i>.
    </div>
  </div>

</div>


<style>
/* --- HOMEPAGE STYLES --- */

/* Define standard colors for consistency */
:root {
    --brand-purple: #54278f;
    --brand-teal: #00BFA5;
    --brand-teal-dark: #008c7a;
    --brand-purple-pale: #f4effc; /* Light purple wash for banner bg */
    --text-dark: #2c3e50;
    --text-medium: #4a4a4a;
    --border-light: #e5e7eb;
}

/* Intro Media Section */
.home-intro-media {
  text-align: center;
  margin-bottom: 2rem;
  margin-top: 0;
}

.home-intro-media img {
  max-width: 100%;
  height: auto;
  margin-bottom: 10px;
  border-radius: 4px; /* Optional: slight rounding for modernity */
}

.home-intro-media p {
  font-size: 0.9em;
  font-style: italic;
  color: #7f8c8d; /* Keep standard caption gray */
  margin: 0;
}

/* Intro Text Section */
.home-intro-text p {
  font-size: 1.0em;
  line-height: 1.6;
  color: var(--text-dark); /* Standard dark gray text */
  margin-bottom: 1.5em;
}

.home-intro-text strong {
    color: #1a202c; /* Slightly darker for emphasis */
}

/* Inline links set to Teal */
.home-intro-text a {
    color: var(--brand-teal) !important;
    text-decoration: none;
    font-weight: 500;
}
.home-intro-text a:hover {
    color: var(--brand-teal-dark) !important;
    text-decoration: underline;
}


/* Call to Action (CTA) Banner */
.home-cta-banner {
  background-color: var(--brand-purple-pale); /* Pale purple background */
  border-left: 5px solid var(--brand-purple); /* Solid purple accent border */
  padding: 25px;
  margin: 35px 0;
  border-radius: 6px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}

.home-cta-banner h3 {
  margin-top: 0;
  margin-bottom: 15px;
  color: var(--brand-purple); /* Heading is purple brand color */
  display: flex;
  align-items: center;
  gap: 10px;
}

.home-cta-banner p {
  margin-bottom: 20px;
  color: var(--text-medium);
  font-size: 1.05rem;
}

/* Custom Teal Button for CTA */
.btn--teal {
    background-color: var(--brand-teal) !important;
    border-color: var(--brand-teal) !important;
    color: #fff !important;
    padding: 0.75rem 1.5rem;
    font-weight: 600;
    transition: all 0.2s ease;
}

.btn--teal:hover {
    background-color: var(--brand-teal-dark) !important;
    border-color: var(--brand-teal-dark) !important;
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(0, 191, 165, 0.2);
}


/* Latest News Section Headers */
.home-section-title {
  border-bottom: 2px solid var(--border-light);
  padding-bottom: 10px;
  margin-top: 40px;
  margin-bottom: 30px;
  color: var(--brand-purple); /* Consistent purple heading */
  display: flex;
  align-items: center;
  gap: 10px;
}


/* News Items */
.home-news-container {
    margin-top: 20px;
}

.news-item {
  display: flex;
  gap: 20px; /* Increased gap slightly for cleaner look */
  margin-bottom: 25px;
  align-items: baseline;
}

.news-date {
  min-width: 85px;
  text-align: right;
  color: #7f8c8d; /* Medium gray for dates */
  font-weight: 600;
  font-size: 0.9em;
  padding-top: 3px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.news-content {
  /* Replaced Navy border with bright Teal accent border */
  border-left: 3px solid var(--brand-teal);
  padding-left: 20px;
  color: var(--text-medium);
  line-height: 1.5;
}

.news-content strong {
    color: var(--text-dark);
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .news-item {
    flex-direction: column;
    gap: 5px;
  }
  .news-date {
    text-align: left;
    padding-bottom: 5px;
  }
  .news-content {
      border-left-width: 4px; /* Slightly thicker border on mobile for visibility */
  }
}
</style>