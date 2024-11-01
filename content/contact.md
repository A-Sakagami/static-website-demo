+++
title = 'お問い合わせフォーム'
date = '2024-11-01T00:00:00+09:00'
draft = false
+++

{{< rawhtml >}}
<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/mpwzprjy"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
{{< /rawhtml >}}