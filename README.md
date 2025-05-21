<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>تواصل معي - RamyGames</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Fira+Code&display=swap');

  * {
    box-sizing: border-box;
  }

  body {
    font-family: 'Fira Code', monospace;
    background: #222831;
    color: #eeeeee;
    margin: 0;
    padding: 40px 10px;
    direction: rtl;
  }

  .container {
    max-width: 500px;
    margin: auto;
    background: #393e46;
    border-radius: 12px;
    padding: 25px 20px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.7);
  }

  h2 {
    text-align: center;
    color: #00adb5;
    margin-bottom: 25px;
    font-weight: 900;
    font-size: 30px;
  }

  form {
    display: flex;
    flex-direction: column;
  }

  label {
    margin-top: 18px;
    margin-bottom: 6px;
    font-weight: 700;
    color: #eeeeee;
  }

  input, textarea, input[type="file"] {
    background: #222831;
    border: 2px solid #00adb5;
    border-radius: 8px;
    padding: 10px 14px;
    color: #eeeeee;
    font-size: 16px;
    font-family: 'Fira Code', monospace;
    transition: border-color 0.3s ease;
  }

  input:focus, textarea:focus, input[type="file"]:focus {
    outline: none;
    border-color: #00ffe7;
  }

  textarea {
    min-height: 100px;
    resize: vertical;
  }

  ::placeholder {
    color: #7f8a93;
    font-style: italic;
  }

  button {
    margin-top: 28px;
    background: #00adb5;
    color: #222831;
    font-weight: 900;
    padding: 14px;
    font-size: 18px;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    transition: background 0.3s ease;
    text-transform: uppercase;
  }

  button:hover {
    background: #00ffe7;
    color: #000;
  }

  /* كوميديا بسيطة في الوصف */
  .fun-text {
    margin-top: 12px;
    font-size: 0.9em;
    color: #a1eafb;
    font-style: italic;
  }
</style>
</head>
<body>
  <div class="container">
    <h2>تواصل معي يا مخترع المستقبل!</h2>
    <form action="https://formsubmit.co/Ramygames40@gmail.com" method="POST" enctype="multipart/form-data">
      <input type="hidden" name="_captcha" value="false" />
      <input type="hidden" name="_next" value="https://example.com/thanks.html" />

      <label for="email">بريدك الإلكتروني (لو تبي أرسل لك رسالة، أو بس أعرف إنك موجود):</label>
      <input type="email" id="email" name="email" placeholder="مثلاً: ramy@games.com" required />

      <label for="message">مشروعك أو نكتة تضحكنا فيها (لو ما عندك مشروع):</label>
      <textarea id="message" name="message" placeholder="اكتب هنا أي شيء تحب..."></textarea>

      <label for="file">مرفقات؟ صورة أو فيديو عشان توري المشروع أو تضحكنا؟ (اختياري):</label>
      <input type="file" id="file" name="file" accept="image/*,video/*" />

      <button type="submit">ارسلها وخلني أشوف العبقرية</button>
    </form>
    <p class="fun-text">إذا احتجت مساعدة في مشروع، اكتبها هنا.. أو حتى لو بغيت تسوي لعبتنا القادمة!</p>
  </div>
</body>
</html>
