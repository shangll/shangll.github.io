
---
layout: archive
title: "Collaborators"
permalink: /collaborators/
author_profile: true
---

<style>
.collaborators-page .page__title {
  display: none !important;
}

.collaborators-container {
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px 0 50px;
}

.collaborators-header {
  margin-bottom: 36px;
}

.collaborators-header h1 {
  font-size: 34px;
  margin-bottom: 8px;
}

.collaborators-header p {
  color: #777;
  font-size: 16px;
}

.collaborator-grid {
  display: grid;
  grid-template-columns:
    repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
}

.collaborator-card {
  background: #fff;
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  padding: 24px;
  transition: all 0.2s ease;
}

.collaborator-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
}

.collaborator-card h2 {
  font-size: 21px;
  margin: 0 0 8px;
  padding-left: 12px;
  border-left: 4px solid #ff8f00;
}

.collaborator-card .position {
  color: #777;
  font-size: 14px;
  margin-bottom: 14px;
}

.collaborator-card .institution {
  font-size: 15px;
  line-height: 1.6;
  margin-bottom: 16px;
}

.collaborator-card a {
  color: #1a73e8;
  text-decoration: none;
}

.collaborator-card a:hover {
  text-decoration: underline;
}

.collaborators-back {
  margin-top: 36px;
  font-size: 15px;
}

@media (max-width: 600px) {
  .collaborators-header h1 {
    font-size: 27px;
  }
}
</style>

<div class="collaborators-container">

  <div class="collaborators-header">
    <h1>Collaborating Labs</h1>
    <p>
      Research collaborators and academic partners
    </p>
  </div>

  <div class="collaborator-grid">

    <!-- Collaborator 1 -->
    <div class="collaborator-card">
      <h2>Prof. Cheng-Ta Yang</h2>
      <div class="position">
        Professor · Department of Psychology
      </div>
      <div class="institution">
        National Cheng Kung University<br>
        Taiwan
      </div>
      <a href="https://vcmlab.psychology.ncku.edu.tw/"
         target="_blank"
         rel="noopener noreferrer">
        Laboratory Website →
      </a>
    </div>

    <!-- Collaborator 2 -->
    <div class="collaborator-card">
      <h2>Dr. Lu-Chun Yeh</h2>
      <div class="position">
        Department of Mathematics and Computer Science
      </div>
      <div class="institution">
        Justus Liebig University Giessen<br>
        Germany
      </div>
      <a href="https://sites.google.com/view/lu-chun-yeh"
         target="_blank"
         rel="noopener noreferrer">
        Personal Website →
      </a>
    </div>

  </div>

  <div class="collaborators-back">
    <a href="{{ '/lab/' | relative_url }}">
      ← Back to VRC Lab
    </a>
  </div>

</div>
