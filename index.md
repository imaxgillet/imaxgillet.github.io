---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>
.intro-row{display:flex; align-items:flex-start; gap:1rem; flex-wrap:wrap;}
.intro-text{flex:1; font-size:1.2rem; line-height:1.6; min-width:220px;}
.intro-pic{flex:0 0 140px; max-width:30%; order:-1;}
.intro-pic img{width:100%; border-radius:50%;}

/* ---- overrides to remove large bottom whitespace ----
   Targets common theme selectors used to vertically center the home page.
   Adjust or remove !important if you add the rule into your main CSS. */
.layout-home .site-main,
.layout-home main,
.home .site-main,
main.site-main {
  min-height: 0 !important;
  display: block !important;
  align-items: flex-start !important;
  padding-bottom: 1.5rem !important;
}

/* optional: tighten footer spacing if needed */
footer, .site-footer {
  padding-top: 1rem;
  padding-bottom: 1rem;
}
</style>

<div class="intro-row">
  <div class="intro-text">
    <p>Welcome! My name is Max Gillet. I am currently a PhD student in Finance at the University of Chicago, Booth School of Business. Before that, I was a business economist at the Chicago Fed. My research interests include unconventional monetary policy, housing, and macrofinance more broadly.</p>
  </div>

  <div class="intro-pic">
    <img src="{{ '/assets/ai_profile.png' | relative_url }}" alt="Max Gillet — profile" />
    <div style="text-align:center; font-size:0.85rem; color:#666; margin-top:.5rem;"></div>
  </div>
</div>
