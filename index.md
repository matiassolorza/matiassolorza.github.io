---
layout: minimal
title: "Home"
---

<style>
.profile {
  display: flex;
  gap: 40px;
  align-items: flex-start;
}

.profile-photo {
  width: 320px;
  height: auto;
  flex-shrink: 0;
}

.profile-text {
  flex: 1;
}

.desktop-name {
  font-size: 52px;
  font-weight: 300;
  margin: 0 0 30px 0;
}

.mobile-name {
  display: none;
}

@media (max-width: 768px) {

  .profile {
    flex-direction: column;
    align-items: center;
    gap: 0;
  }

  .desktop-name {
  font-size: 52px;
  font-weight: 300;
  margin: 0 0 20px 0;
}

.mobile-name {
  display: none;
}

  .profile-photo {
    width: 320px;
  }

  .profile-text {
    width: 100%;
  }

  .desktop-title {
  text-align: center;
  }
 
}
</style>

<div class="profile">

  <div>


<img
  class="profile-photo"
  src="/images/LinkedinMS.png"
  alt="Matías Solorza">

<h1 class="mobile-name">
  Matías Solorza
</h1>


  </div>

<div class="profile-text">

<h1 class="desktop-name">
    Matías Solorza
  </h1>

<p style="margin-top:0;">
  PhD Candidate in Economics<br>
  University of California, Davis
</p>

<p>
  I am a PhD candidate in Economics at the University of California, Davis.
  My research lies at the intersection of macroeconomics and climate economics.
  I study how natural disasters and climate risks shape investment, financial
  markets, regional recovery, and long-run economic development.
</p>

<p>
  <a href="mailto:{{ site.email }}">Email</a> |
  <a href="https://www.linkedin.com/in/matias-solorza-510427127">
    LinkedIn
  </a>
</p>


  </div>

</div>

## Research

### Natural Disasters and Slow Recoveries: New Evidence from Chile

(with Lissette Briones)

Work in progress analyzing the persistence of negative macroeconomic shocks from natural disasters in Chile, focusing on how capital destruction and financial frictions delay regional recovery.

### The Ambiguity Costs of Climate Change

(with Frances C. Moore and Benjamin Collier)

Work in progress on quantifying the economic costs of climate change-driven ambiguity and tail risks in US insurance markets.
