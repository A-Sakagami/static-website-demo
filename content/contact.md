+++
title = 'お問い合わせフォーム'
date = '2024-11-01T16:00:00+09:00'
draft = false
+++

<form id= "contactForm" action="https://formspree.io/f/mpwzprjy" method="POST">
<label for="name" style="display: block; margin-bottom: 0.5em;">Name:</label>
  <input type="text" id="name" name="name" required style="width: 100%; padding: 0.5em; margin-bottom: 1em; border: 1px solid #ccc; border-radius: 4px;">

  <label for="email" style="display: block; margin-bottom: 0.5em;">Email:</label>
  <input type="email" id="email" name="_replyto" required style="width: 100%; padding: 0.5em; margin-bottom: 1em; border: 1px solid #ccc; border-radius: 4px;">

  <label for="message" style="display: block; margin-bottom: 0.5em;">Message:</label>
  <textarea id="message" name="message" required style="width: 100%; padding: 0.5em; margin-bottom: 1em; border: 1px solid #ccc; border-radius: 4px; height: 150px;"></textarea>
 
  <button type="button" style="width: 100%; padding: 0.7em; background-color: #007BFF; color: white; border: none; border-radius: 4px; cursor: pointer;" id="sendButton">Send</button>


</form>
<script>
  document.getElementById('sendButton').addEventListener('click', function () {
    const userConfirmed = confirm('この内容で送信してよろしいですか？');
    if (userConfirmed) {
      // ここでフォーム送信の実装を追加してください。
      //document.getElementById('contactForm').submit();
      alert('送信されました！');
    }
    // キャンセルの場合は何も行わず、画面にとどまる
 });
</script>
