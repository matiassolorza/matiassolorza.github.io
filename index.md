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
        My research lies at the intersection of macroeconomics, climate economics, and finance. I study how natural disasters, climate risk, and financial frictions affect investment, adaptation and long-run economic development. Using administrative microdata, empirical methods, and quantitative macroeconomic models, I examine the economic consequences of extreme events and the mechanisms that shape resilience to climate-related shocks.
      </p>

      <p>
        <a href="/files/CV.pdf">CV</a> |

        <!--

            <a href="/files/JMP.pdf">Job Market Paper</a> |
        
        Este bloque está oculto.
        Puedes escribir varias líneas.
        No se mostrará en la página.
        -->
               
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

We study the macroeconomic responses of Chilean regions to natural disasters—floods and wildfires—using local projections and a combination of public and novel administrative data. We document persistent output losses, weak investment recovery, declining commercial debt, and lower wages following disaster events. These patterns are difficult to reconcile with standard reconstruction dynamics, which predict a rapid recovery after capital destruction.
To understand the sources of persistence, we develop a real business cycle model with capital destruction, financial frictions, labor distortions, and productivity disruptions. The model is disciplined by the post-disaster dynamics of GDP and investment and reproduces the observed persistence in economic activity. Our results show that no single mechanism explains slow recoveries. Capital destruction accounts for the initial decline in output, while financial conditions and productivity disruptions shape the subsequent recovery path. More broadly, slow recoveries emerge from the interaction of reconstruction needs, financing conditions, and persistent disruptions to productive capacity. These findings suggest that effective disaster recovery policies must address not only physical reconstruction, but also the financial and productivity barriers that hinder regional recovery after climate-related shocks.

### The Ambiguity Costs of Climate Change

(with Frances C. Moore and Benjamin Collier)

Develops a framework to quantify the economic costs of climate-change-induced ambiguity and tail risks in U.S. insurance markets. The project examines how uncertainty about future climate damages affects insurance pricing and welfare.

### Publications

#### The Credit Channel in Chile through the Lens of a Semi-Structural Model

(with Francisco Arroyo Marioli and Juan Sebastián Becerra)

Published in the Latin American Journal of Central Banking, 2022

Estimates a semi-structural macroeconomic model with a banking sector for the Chilean economy. The paper incorporates credit dynamics, interest rate spreads, and loan-loss provisions into the Central Bank of Chile’s forecasting framework to quantify the role of the credit channel in business cycle fluctuations and policy transmission.

[Paper](https://www.sciencedirect.com/science/article/pii/S2666143822000102)


