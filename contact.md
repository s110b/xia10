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
  <input type="email" name="_replyto" placeholder="Email" maxlength="254" required>
  <textarea name="body" placeholder="Message" maxlength="400" required></textarea>
  <input class="btn right-btn" type="submit" value="Send">
</form>
