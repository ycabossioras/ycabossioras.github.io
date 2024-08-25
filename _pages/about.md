---
permalink: /
layout: "archive"
title: ""              # page title shown in tab, with suffix the website name, e.g., "Research - Yannis Cabossioras"
author_profile: false  # display author info on the left sidebar
redirect_from: 
  - /about/
  - /about.html
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
        I am a 6th year Ph.D. candidate in Finance at NYU Stern.<br>
        <br>
        My research focuses on.<br>
        <br>
        <b>Research interests:</b> banking, financial intermediation, corporate finance, industrial organization<br>
        <br>
        <b>I will be on the 2024-2025 job market.</b><br>
        <br>
        <a href="/files/CV_cabossioras.pdf" style="text-decoration:none" target="_blank">
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
  <ti3>Bank Specialization and Holdup Behavior: Evidence and Real Effects from Small Business Lending</ti3><br>
  <b class="color2">[Job Market Paper]</b><br>
  <i>with <a href="https://sites.google.com/view/joris-tielens/homepage" style="text-decoration:none" target="_blank">Joris Tielens</a></i><br>
  <small>August 2024</small><br>
  <small>
    <i class="fas fa-scroll">           </i> Paper    <vdiv>|</vdiv>
    <i class="fas fa-magnifying-glass"> </i> Appendix <vdiv>|</vdiv>
    <i class="fas fa-person-chalkboard"></i> Slides   <vdiv>|</vdiv>
    <i class="fas fa-quote-right">      </i> Citation
  </small><br>
  <div class="abstract">
    <span>Abstract:</span> We study the pricing behavior of lenders holding specialized portfolios in certain industries and draw implications for small business lending. Using regulatory credit registry data on the universe of corporate credit in Belgium, we show that banks adopt invest-harvest strategies in their industries of specialization. Firms funded by specialized banks are initially charged lower interest rates and subsequently experience larger rate increases over the course of their relationship. Specialized-financed firms end up paying higher rates after 10 years compared to firms borrowing from diversified banks. We leverage granular bank-assessed default probabilities to address concerns about borrower selection and risk premia relevant to small business lending. We interpret these findings as evidence of banks having better knowledge in their industry of specialization and firms facing relatively higher costs of switching from a relationship with a specialized lender. While banks exert stronger holdup power in their preferred industries, firms overall benefit from such relationships with increased profitability, productivity, and liquidity.
  </div>
  <br>
  <br>
  <h1 class="adjust-title"> Work In Progress </h1>
  <ti3>Bank Lending in the Presence of Borrower Linkages: Evidence from the Belgian Production Network</ti3><br>
  <i>with <a href="https://sites.google.com/view/joris-tielens/homepage" style="text-decoration:none" target="_blank">Joris Tielens</a></i><br>
  <!-- <small>August 2024</small><br> -->
  <hr>
  <ti3>The Dynamics of Reference Dependence in the Housing Market</ti3><br>
  <i>with <a href="https://neilthakral.github.io/#research" style="text-decoration:none" target="_blank">Neil Thakral</a></i><br>
  <!-- <small>August 2024</small><br> -->
</p>






<small>August 2024</small>

