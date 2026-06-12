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

.hero {
  max-width: 800px;
  margin: 0 auto;
}

.desktop-name {
  font-size: 52px;
  font-weight: 300;
  margin: 0 0 30px 0;
  text-align: center;
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
    display: none;
  }

  .mobile-name {
    display: block;
    font-size: 40px;
    font-weight: 300;
    margin: 25px 0;
    text-align: center;
  }

  .profile-photo {
    width: 320px;
    max-width: 100%;
  }

  .profile-text {
    width: 100%;
  }
}
</style>

<div class="hero">

  <h1 class="desktop-name">
    Matías Solorza
  </h1>

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
        <a href="https://www.linkedin.com/in/matías-solorza-510427127">
          LinkedIn
        </a>
      </p>

    </div>

  </div>

</div>



## Research

### Natural Disasters and Slow Recoveries: New Evidence from Chile

(with Lissette Briones)

Work in Progress

Examines the persistence of regional economic declines following natural disasters in Chile. Using administrative and economic data, we study how capital destruction and financial frictions affect recovery dynamics and contribute to prolonged output losses.

### The Ambiguity Costs of Climate Change

(with Frances C. Moore and Benjamin Collier)

Work in Progress

Develops a framework to quantify the economic costs of climate-change-induced ambiguity and tail risks in U.S. insurance markets. The project examines how uncertainty about future climate damages affects insurance pricing and welfare.
