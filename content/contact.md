+++
title = 'お問い合わせフォーム'
date = '2024-11-01T16:00:00+09:00'
draft = false
+++

<form action="https://formspree.io/f/mpwzprjy" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="_replyto" required>

  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>

  <button type="submit">Send</button>
</form>
