---
layout: page
title: "Contact"
subtitle: "連絡"
permalink: /contact/
---

### Subscribe

<form class="contact-form" action="https://formsubmit.co/kesem.contact@gmail.com" method="POST">
  <input type="hidden" name="_subject" value="New subscriber">
  <input type="hidden" name="_captcha" value="false">
  <div class="contact-field">
    <label for="subscribe-email">Email</label>
    <input id="subscribe-email" class="contact-input" type="email" name="email" placeholder="you@example.com" required>
  </div>
  <button class="contact-button" type="submit">Subscribe</button>
</form>
<p class="contact-note">No automated list yet. This will send your email to me so I can add you manually. Prefer email? Write to <a class="contact-inline-link" href="mailto:kesem.contact@gmail.com">kesem.contact@gmail.com</a>.</p>

### Send a message

<form class="contact-form" action="https://formsubmit.co/kesem.contact@gmail.com" method="POST">
  <input type="hidden" name="_subject" value="New message from the Contact page">
  <input type="hidden" name="_captcha" value="false">
  <div class="contact-field">
    <label for="contact-name">Name</label>
    <input id="contact-name" class="contact-input" type="text" name="name" placeholder="Your name" required>
  </div>
  <div class="contact-field">
    <label for="contact-email">Email</label>
    <input id="contact-email" class="contact-input" type="email" name="email" placeholder="you@example.com" required>
  </div>
  <div class="contact-field">
    <label for="contact-message">Message</label>
    <textarea id="contact-message" class="contact-textarea" name="message" placeholder="Write your message here..." required></textarea>
  </div>
  <button class="contact-button" type="submit">Send message</button>
</form>

<style>
  .contact-form {
    display: grid;
    gap: 12px;
    max-width: 520px;
  }
  .contact-field {
    display: flex;
    flex-direction: column;
    gap: 6px;
  }
  .contact-input,
  .contact-textarea {
    padding: 10px 12px;
    border: 1px solid #cfcfcf;
    border-radius: 6px;
    font: inherit;
  }
  .contact-textarea {
    min-height: 140px;
    resize: vertical;
  }
  .contact-button {
    background: #36454f;
    color: #ffffff;
    border: none;
    border-radius: 6px;
    padding: 10px 16px;
    width: fit-content;
    cursor: pointer;
  }
  .contact-button:hover {
    filter: brightness(0.95);
  }
  .contact-note {
    margin-top: 8px;
    color: #666666;
  }
  .contact-inline-link {
    color: #36454f;
    text-decoration: none;
  }
  .contact-inline-link:hover {
    text-decoration: underline;
  }
</style>
