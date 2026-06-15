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



## Job Market Paper

### Natural Disasters and Slow Recoveries: New Evidence from Chile

(with Lissette Briones)

We study the macroeconomic responses of Chilean regions to natural disasters—floods and wildfires—using local projections and a combination of public and novel administrative data. We document persistent GDP losses, temporary declines in consumption, and a delayed recovery in investment, accompanied by rising employment but falling wages and effective hours. These dynamics contrast with U.S. county-level evidence and point to the importance of disaster size, as well as institutional and financial conditions, in shaping post-disaster recoveries in emerging economies. We interpret the evidence through four mechanisms: destruction of productive capital, tighter financial conditions that constrain rebuilding, production reallocation, and household wealth losses that depress consumption while supporting low-wage reconstruction employment.
These patterns suggest limited regional resilience, as disruptions to productive capacity propagate through local production networks and delay recovery. Embedding these mechanisms into a real business cycle model with financial frictions, we show that financial constraints are quantitatively central: absent these frictions, post-disaster losses in economic activity during the first years would be reduced by about one half. Our findings highlight the role of targeted financial and reconstruction policies in mitigating the long-run economic costs of climate-related disasters. 

## Working Papers

### The Ambiguity Costs of Climate Change

(with Frances C. Moore and Benjamin Collier)

Develops a framework to quantify the economic costs of climate-change-induced ambiguity and tail risks in U.S. insurance markets. The project examines how uncertainty about future climate damages affects insurance pricing and welfare.

### Publications

#### The Credit Channel in Chile through the Lens of a Semi-Structural Model

(with Francisco Arroyo Marioli and Juan Sebastián Becerra)

Published in the Latin American Journal of Central Banking, 2022

Estimates a semi-structural macroeconomic model with a banking sector for the Chilean economy. The paper incorporates credit dynamics, interest rate spreads, and loan-loss provisions into the Central Bank of Chile’s forecasting framework to quantify the role of the credit channel in business cycle fluctuations and policy transmission.

[Paper](https://www.sciencedirect.com/science/article/pii/S2666143822000102)


