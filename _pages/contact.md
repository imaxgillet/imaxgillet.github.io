---
layout: page
title: Contact
permalink: /contact/
---

You can visit my <a href="{{ site.social_links.linkedin }}" target="_blank">LinkedIn</a> or <a href="{{ site.social_links.github }}" target="_blank">GitHub</a> pages. 

Feel free to email me at: <span id="email"></span>
<script>
  const user = "imaxgillet";
  const domain = "gmail.com";
  document.getElementById("email").innerHTML = `<a href="mailto:${user}@${domain}">${user}@${domain}</a>`;
</script> 
<NOSCRIPT>
    <img src='{{ site.baseurl }}/assets/email.png' height="30" width="130">
</NOSCRIPT>