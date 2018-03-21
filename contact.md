---
layout: page
title: Contact
permalink: /contact/
seo:
  type: person
---

You can use this form [below]({{ page.url }}#contact) or send me an email to: [{{ site.social-links.email }}](mailto:{{ site.social-links.email }})
<br/>
<form id="gform" class="contact-form" action="https://script.google.com/macros/s/AKfycbyBhqS3oy0K6qYzFxR7XuKOY8FKglotc-kjtKEYu7fK4W0JpUhR/exec" method="POST">
  <input id="honeypot" type="text" name="honeypot" value="" />
  <input type="text" name="name" placeholder="Name" maxlength="50" required>
  <input type="email" name="email" placeholder="Email" maxlength="254" required>
  <input type="tel" name="telNo" placeholder="Phone number (optional)" maxlength="20">
  <input type="text" onfocus="(this.type='date')" name="date" placeholder="Date of the event (optional)">
  <textarea name="message" placeholder="Message" maxlength="400" required></textarea>
  <input class="w3-button w3-right w3-border" type="submit" value="Send">
</form>
<div style="display:none;" id="thankyou_message">
  <h3>Thank you for contacting me!
    I will get back to you soon!</h3>
</div>
<script data-cfasync="false" type="text/javascript" src="{{ site.baseurl }}{% link /assets/vendor/form-submission-handler.js %}"></script>
