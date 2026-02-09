---
title: "Contact"
weight: 4
header_menu: true
---

We'd love to hear from you, whether you're interested in classes, venue hire, or collaboration.

<form class="contact-form" hx-post="https://form-worker.srv-cf.workers.dev/f/lila-arts-centre/submit" hx-target="#form-response" hx-swap="innerHTML" hx-disabled-elt="button">
  <label for="name">Name</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email</label>
  <input type="email" id="email" name="email" required>

  <label for="subject">Subject</label>
  <select id="subject" name="subject" required>
    <option value="">Select a topic...</option>
    <option value="classes">Class Enquiry</option>
    <option value="venue">Venue Booking</option>
    <option value="collaboration">Collaboration</option>
    <option value="other">Other</option>
  </select>

  <label for="message">Message</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Send Message</button>
</form>
<div id="form-response"></div>

----

##### Visit Us

**Lila Arts Centre**
5/6, Thirumalai Pillai Road
Satyamurthy Nagar, T. Nagar
Chennai, Tamil Nadu 600017

##### Connect

{{< icon name="instagram" brand=true >}} [@lilaartscentre](https://instagram.com/lilaartscentre)

{{< icon name="envelope" >}} [hello@lilaartscentre.com](mailto:hello@lilaartscentre.com)
