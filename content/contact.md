+++
title = 'お問い合わせフォーム'
date = '2024-11-01T16:00:00+09:00'
draft = false
+++

<head>
 <link rel="shortcut icon" type="image/x-icon" href="static\img\favicon.ico">
</head>
<form action="https://formspree.io/f/mpwzprjy" method="POST">
<label for="name" style="display: block; margin-bottom: 0.5em;">Name:</label>
  <input type="text" id="name" name="name" required style="width: 100%; padding: 0.5em; margin-bottom: 1em; border: 1px solid #ccc; border-radius: 4px;">

  <label for="email" style="display: block; margin-bottom: 0.5em;">Email:</label>
  <input type="email" id="email" name="_replyto" required style="width: 100%; padding: 0.5em; margin-bottom: 1em; border: 1px solid #ccc; border-radius: 4px;">

  <label for="message" style="display: block; margin-bottom: 0.5em;">Message:</label>
  <textarea id="message" name="message" required style="width: 100%; padding: 0.5em; margin-bottom: 1em; border: 1px solid #ccc; border-radius: 4px; height: 150px;"></textarea>

  <button type="submit" style="width: 100%; padding: 0.7em; background-color: #007BFF; color: white; border: none; border-radius: 4px; cursor: pointer;">Send</button>
</form>
