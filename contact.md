--- 
title: Contact 
layout: contact 
description: Contact Us 
--- 
# Contact Us 

Got a question or want to connect with the LDT4SSC team? Use the form below, send us an email directly, or follow our updates on LinkedIn and subscribe to our newsletter.

<p align="left" style="display: flex; gap: 12px; flex-wrap: wrap;">

  <!-- Email -->
  <a href="mailto:info@ldt4ssc.eu" target="_blank" style="
    display: inline-block;
    padding: 10px 18px;
    background-color: #1F75D6; /* Tech Blue */
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    white-space: nowrap;
  ">
    Send us an email
  </a>

  <!-- LinkedIn -->
  <a href="https://www.linkedin.com/company/ldt4ssc-project/" target="_blank" style="
    display: inline-block;
    padding: 10px 18px;
    background-color: #29A329; /* Eco Green */
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    white-space: nowrap;
  ">
    Follow us on LinkedIn
  </a>

  <!-- Newsletter -->
  <a href="https://shorturl.at/pzMGK" target="_blank" style="
    display: inline-block;
    padding: 10px 18px;
    background-color: #F5B400; /* Optimistic Yellow */
    color: black; /* contrast on yellow */
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    white-space: nowrap;
  ">
    Subscribe to our newsletter
  </a>

</p>

<section class="contact-form-panel">
  <div class="contact-form-panel__intro">
    <h2>Send a message</h2>
    <p>Your message will be forwarded to <a href="mailto:info@ldt4ssc.eu">info@ldt4ssc.eu</a>.</p>
  </div>

  <form
    class="contact-form"
    action="https://formsubmit.co/info@ldt4ssc.eu"
    method="POST"
  >
    <input type="hidden" name="_subject" value="New message from the LDT4SSC contact page">
    <input type="hidden" name="_next" value="https://ldt4ssc.eu/contact-success/">
    <input type="hidden" name="_captcha" value="false">
    <input type="hidden" name="_template" value="table">
    <input type="text" name="_honey" class="contact-form__honeypot" tabindex="-1" autocomplete="off">

    <div class="contact-form__grid">
      <div class="contact-form__field">
        <label for="contact-name">Name</label>
        <input id="contact-name" name="name" type="text" class="form-control" required>
      </div>

      <div class="contact-form__field">
        <label for="contact-email">Email</label>
        <input id="contact-email" name="email" type="email" class="form-control" required>
      </div>
    </div>

    <div class="contact-form__field">
      <label for="contact-organisation">Organisation</label>
      <input id="contact-organisation" name="organisation" type="text" class="form-control">
    </div>

    <div class="contact-form__field">
      <label for="contact-subject">Subject</label>
      <input id="contact-subject" name="subject" type="text" class="form-control" required>
    </div>

    <div class="contact-form__field">
      <label for="contact-message">Message</label>
      <textarea id="contact-message" name="message" class="form-control" rows="6" required></textarea>
    </div>

    <div class="contact-form__actions">
      <button type="submit" class="button contact-form__submit">Send message</button>
      <p class="contact-form__note">Submitting this form uses FormSubmit to deliver your message by email.</p>
    </div>
  </form>
</section>
