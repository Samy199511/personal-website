<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>موقعي الشخصي</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>مرحبا بك في موقعي الشخصي</h1>
    <p>أنا مطور ومهتم بتقديم خدماتي عبر منصة مستقل</p>
  </header>

  <section id="about">
    <h2>من أنا؟</h2>
    <p>أنا مبتدئ طموح في عالم البرمجة، أعمل على تطوير نفسي ومساعدة العملاء.</p>
  </section>

  <section id="skills">
    <h2>مهاراتي</h2>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>GitHub</li>
      <li>تصميم صفحات بسيطة</li>
    </ul>
  </section>

  <section id="contact">
    <h2>تواصل معي</h2>
    <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
      <label for="name">اسمك:</label>
      <input type="text" id="name" name="name" required><br>

      <label for="email">بريدك الإلكتروني:</label>
      <input type="email" id="email" name="email" required><br>

      <label for="message">رسالتك:</label>
      <textarea id="message" name="message" required></textarea><br>

      <button type="submit">إرسال</button>
    </form>
  </section>

  <footer>
    <p>© جميع الحقوق محفوظة 2025</p>
  </footer>
</body>
</html>
