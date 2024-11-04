---
permalink: /
layout: "archive"
title: ""              # page title shown in tab, with suffix the website name, e.g., "Research - Yannis Cabossioras"
author_profile: false  # display author info on the left sidebar
redirect_from: 
  - /about/
  - /about.html
excerpt: Yannis Cabossioras -- Job market candidate in finance from NYU Stern. I work on small-business lending questions. Broadly, my research interest are banking, financial intermediation, corporate finance, industrial organization.
seo_title: Yannis Cabossioras
seo_description: Yannis Cabossioras -- Job market candidate in finance from NYU Stern. I work on small-business lending questions. Broadly, my research interest are banking, financial intermediation, corporate finance, industrial organization.
---

{% include base_path %}

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

<div class="container">
    <div class="left-column">
      <img src   = "/images/profile.jpeg"
           alt   = "Yannis Cabossioras"
           title = "Yannis Cabossioras"
           style = "border-radius: 10px;"/>
    </div>
    <div class="right-column">
      <h1 class="adjust-title"> Welcome! </h1>
      <p>
        I am a 6th year Ph.D. candidate in Finance at NYU Stern and a Normalien from the École Normale Supérieure Paris-Saclay.<br>
        <!-- I hold a M.Sc. in Economics from Paris School of Economics and a B.Sc. in Economics from Université Paris 1 Panthéon-Sorbonne. -->
        <br>
        I study small-business lending using administrative credit data. More broadly, my research focuses on the effect of credit market imperfections on firms' access to credit and their real outcomes.<br>
        <br>
        <b>I will be on the 2024-2025 job market.</b><br>
        <br>        
        <b>Research interests:</b> banking, financial intermediation, corporate finance, industrial organization<br>
        <br>
        <!-- In my job market paper, I explore how lenders specialized in certain industries adjust their interest rates over their relationship with small businesses. The invest-harvest behavior observed is consistent with the presence of borrower switching costs and lender holdup power in corporate credit markets.<br> -->
        <br>
        <a href="/files/Cabossioras_CV.pdf" style="text-decoration:none" target="_blank">
          <i class="fas fa-file icon-pad-right"></i>
          Curriculum Vitae
        </a><br>
        <a href="mailto:yannis.cabossioras@stern.nyu.edu" style="text-decoration:none">
          <i class="fas fa-envelope icon-pad-right"></i>
          yannis.cabossioras@stern.nyu.edu
        </a>
      </p>
    </div>
  </div>



<p>
  <br>
  <h1 class="adjust-title"> Working Papers </h1>
  <ti3>Bank Specialization and Credit Relationships in Small-Business Lending</ti3><br>
  <b class="color2">[Job Market Paper]</b><br>
  <i>with <a href="https://sites.google.com/view/joris-tielens/homepage" style="text-decoration:none" target="_blank">Joris Tielens</a></i><br>
  <small>November 2024</small><br>
  <!-- <small>
    <i class="fas fa-scroll">           </i> Paper    <vdiv>|</vdiv>
    <i class="fas fa-magnifying-glass"> </i> Appendix <vdiv>|</vdiv>
    <i class="fas fa-person-chalkboard"></i> Slides   <vdiv>|</vdiv>
    <i class="fas fa-quote-right">      </i> Citation
  </small><br> -->
  <div class="abstract">
    <span>Abstract:</span> We document that banks leverage their industry specialization to build and retain relationships with small businesses, using micro-level data on the universe of corporate credit in Belgium. In the relationship-building phase, banks charge lower rates in their industries of specialization. In the relationship-retaining phase, lenders subsequently raise rates faster in specialized industries, until they charge similar rates regardless of their level of specialization. Specialized banks internalize the intertemporal value of credit relationships, combining both industry knowledge and market power to extract value from their relationships. Small businesses benefit from bank specialization in the long run through higher growth in investment, profitability, productivity, and equity value.
  </div>
  <br>
  <br>
  <h1 class="adjust-title"> Work In Progress </h1>
  <ti3>Bank Lending in the Presence of Borrower Linkages: Evidence from the Belgian Production Network</ti3><br>
  <i>with <a href="https://sites.google.com/view/joris-tielens/homepage" style="text-decoration:none" target="_blank">Joris Tielens</a></i><br>
  <!-- <small>August 2024</small><br> -->
  <div class="abstract">
    <span>Abstract:</span> We establish that banks internalize firm production networks when making lending decisions. We formulate a parsimonious model of bank lending with production networks and find that banks cross-subsidize suppliers at the expense of their customers by offering lower and higher rates respectively. This cross-subsidization benefits customers on net by keeping the supplier's marginal cost down and thus the intermediate input price that the customer purchases from its suppliers. We merge credit registry data and firm-level data on the near-universe of business-to-business transactions in Belgium to get an exhaustive map between a firm's credit relationships and its supply chain linkages. We find that lenders charge a lower interest rate to suppliers and a higher average interest rate across customers, consistent with our model.
  </div>
  <hr>
  <ti3>The Dynamics of Reference Dependence in the Housing Market</ti3><br>
  <i>with <a href="https://neilthakral.github.io/#research" style="text-decoration:none" target="_blank">Neil Thakral</a></i><br>
  <!-- <small>August 2024</small><br> -->
  <div class="abstract">
    <span>Abstract:</span> We study the effect of past price movements on selling decisions in the housing market to draw implications about the presence of reference dependence on this market. Using data on the universe of private housing transactions in Singapore, we test a commonly used assumption that homeowners use their unit's purchase price as a reference point when making selling decisions. We decompose a unit's cumulative price change since purchase into a series of annual potential gains and estimate how the timing of these gains affects the homeowner's decision to sell. We rule out the null of the purchase price being a reference point and find that gains occurring early in a homeowner's tenure are the most predictive of selling decisions. Homeowners prefer to hold on to their properties after recent gains, consistent with the presence of momentum on housing markets.
  </div>
</p>






