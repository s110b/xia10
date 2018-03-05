---
layout: page
title: Contact
permalink: /contact/
seo:
  type: person
---

You can use this form [below]({{ page.url }}#contact) or send me an email to: [{{ site.social-links.email }}](mailto:{{ site.social-links.email }})

<br/>

<form id="contact" action="https://formspree.io/{{ site.social-links.email }}" method="POST">
  <input type="text" name="name" placeholder="Name" maxlength="50" required>
  <input type="email" name="email" placeholder="Email" maxlength="254" required>
  <input type="tel" name="telNo" placeholder="Phone number" maxlength="254">
  <textarea name="body" placeholder="Message" maxlength="400" required></textarea>
  <input class="w3-button w3-right w3-border" type="submit" value="Send">
</form>
