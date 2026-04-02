---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<style>
.intro-row{display:flex; align-items:flex-start; gap:1.5rem; flex-wrap:wrap;}
.intro-text{flex:1; min-width:240px;}
.intro-pic{flex:0 0 156px; max-width:31%; order:-1;}
.intro-pic img{width:100%; border-radius:50%;}
.intro-lead{
  font-size:1.15rem;
  line-height:1.7;
  margin-bottom:.9rem;
}
.intro-note{
  color:#5f6b7a;
  margin-bottom:1.1rem;
}
.quick-links{
  display:flex;
  gap:.65rem;
  flex-wrap:wrap;
  margin:0;
  padding:0;
  list-style:none;
}
.quick-links a{
  display:inline-block;
  padding:.4rem .85rem;
  border:1px solid #d7dfe8;
  border-radius:999px;
  background:#fafbfd;
  text-decoration:none;
}
.quick-links a:hover{
  background:#f2f5f8;
  text-decoration:none;
}

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
    <p class="intro-lead">Welcome. My name is Max Gillet. I am a PhD student in Finance at the University of Chicago Booth School of Business. Before that, I was a business economist at the Chicago Fed.</p>
    <p class="intro-note">My research interests include unconventional monetary policy, housing, and macrofinance.</p>
    <ul class="quick-links">
      <li><a href="{{ '/research/' | relative_url }}">Research</a></li>
      <li><a href="{{ '/assets/resume.pdf' | relative_url }}">Curriculum Vitae</a></li>
      <li><a href="{{ '/contact/' | relative_url }}">Contact</a></li>
    </ul>
  </div>

  <div class="intro-pic">
    <img src="{{ '/assets/ai_profile.png' | relative_url }}" alt="Max Gillet — profile" />
    <div style="text-align:center; font-size:0.85rem; color:#666; margin-top:.5rem;"></div>
  </div>
</div>
