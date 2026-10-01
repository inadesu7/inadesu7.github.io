---
layout: page
title: Contact
permalink: /contact/
---

## Our Contact Information

**Address:**  
{{ site.data.organisation.address }}

**Phone:**  
[{{ site.data.organisation.telephone }}](tel:{{ site.data.organisation.telephone | replace: ' ', '' }})

**Email:**  
[{{ site.data.organisation.email }}](mailto:{{ site.data.organisation.email }})

---

## Send a Message

<div data-fs-success class="alert alert-success">
  <strong>Success!</strong> Your message has been received. We'll get back to you as soon as possible.
</div>
<div data-fs-error class="alert alert-danger">
  <strong>Error:</strong> There was a problem submitting your form. Please try again or contact us directly.
</div>

<form id="contact-form" class="custom-form contact-form">
  <div class="row mb-3">
    <div class="col-lg-6 col-12 mb-3">
      <label for="name" class="form-label">Full Name *</label>
      <input type="text" id="name" name="name" class="form-control" placeholder="Your full name" required>
    </div>
    <div class="col-lg-6 col-12 mb-3">
      <label for="email" class="form-label">Email *</label>
      <input type="email" id="email" name="email" class="form-control" placeholder="your@email.com" required data-fs-field>
      <span data-fs-error="email" class="text-danger small"></span>
    </div>
  </div>

  <div class="mb-3">
    <label for="subject" class="form-label">Subject *</label>
    <input type="text" id="subject" name="subject" class="form-control" placeholder="How can we help?" required>
  </div>

  <div class="mb-3">
    <label for="message" class="form-label">Message *</label>
    <textarea id="message" name="message" class="form-control" rows="6" placeholder="Your message..." required data-fs-field></textarea>
    <span data-fs-error="message" class="text-danger small"></span>
  </div>

  <div class="mb-3">
    <label for="inquiry-type" class="form-label">Inquiry Type</label>
    <select id="inquiry-type" name="inquiry-type" class="form-select">
      <option value="">-- Select --</option>
      <option value="volunteer">Volunteer Opportunity</option>
      <option value="partnership">Partnership Proposal</option>
      <option value="donation">Donation Question</option>
      <option value="general">General Inquiry</option>
      <option value="media">Media/Press</option>
      <option value="other">Other</option>
    </select>
  </div>

  <button type="submit" class="custom-btn btn" data-fs-submit-btn>Send Message</button>
</form>

<script>
  window.formspree =
    window.formspree ||
    function () {
      (formspree.q = formspree.q || []).push(arguments);
    };
  formspree("initForm", {
    formElement: "#contact-form",
    formId: "meaodllp",
  });
</script>
<script src="https://unpkg.com/@formspree/ajax@1" defer></script>


