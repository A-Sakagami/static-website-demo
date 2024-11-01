+++
title = 'お問い合わせフォーム'
date = '2024-11-01T00:00:00+09:00'
draft = false
parent = ''
+++

<form action="https://formspree.io/f/your-form-id" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="_replyto" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Send</button>
</form>