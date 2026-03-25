---
permalink: /projects/
title: "Projects"
layout: splash
---

<div class="projects-grid">
  <div class="project-card">
    <a href="/projects/project-1/">
      <img src="/assets/images/nurse.png" alt="Enabling the Next Generation of Nurses">
      <h3>Enabling the Next Generation of Nurses</h3>
      <p>A Mixed-Methods Case Study on Early-Career Nurse Enablement</p>
    </a>
  </div>

  <div class="project-card">
    <a href="/projects/project-2/">
      <img src="/assets/images/medicaid.jpeg" alt="Nudging Medicaid Enrollment with Behavioral Science">
      <h3>Nudging Medicaid Enrollment with Behavioral Science</h3>
      <p>A Case Study on Technology Adoption</p>
    </a>
  </div>

  <div class="project-card">
    <a href="/projects/project-3/">
      <img src="/assets/images/coder.jpeg" alt="When AI Meets Culture">
      <h3>When AI Meets Culture</h3>
      <p>How behavioral science revealed hidden friction in medical coding</p>
    </a>
  </div>

  <div class="project-card">
    <a href="/projects/project-4/">
      <img src="/assets/images/ai.jpeg" alt="Revamping Provider Workflows">
      <h3>Revamping Provider Workflows</h3>
      <p>How AI is transforming the future of healthcare</p>
    </a>
  </div>
</div>

<style>
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: #f5f5f5;
  border-radius: 8px;
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.project-card a {
  text-decoration: none;
  color: inherit;
  display: block;
}

.project-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.project-card h3 {
  padding: 1rem 1rem 0.5rem 1rem;
  margin: 0;
  text-align: center;
  font-size: 1.2rem;
}

.project-card p {
  padding: 0 1rem 1rem 1rem;
  margin: 0;
  text-align: center;
  font-size: 0.9rem;
  color: #666;
}
</style>
