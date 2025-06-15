<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>أكاديمية الصفوة – Al Safwa Academy</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Cairo', sans-serif;
      background-color: #ffffff;
      color: #1a1a1a;
    }
    header {
      background-color: #0d47a1;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      width: 80px;
      height: auto;
      margin-bottom: 10px;
    }
    header h1 {
      margin: 5px 0 0;
      font-size: 2rem;
    }
    header h2 {
      margin: 5px 0 0;
      font-size: 1.2rem;
      font-family: 'Poppins', sans-serif;
    }
    .hero {
      padding: 50px 20px;
      text-align: center;
      background: linear-gradient(to left, #0d47a1, #1976d2);
      color: white;
    }
    .hero h3 {
      font-size: 2rem;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }
    .hero a {
      background-color: #ffc107;
      color: #0d47a1;
      text-decoration: none;
      padding: 15px 30px;
      border-radius: 10px;
      font-weight: bold;
      transition: 0.3s;
    }
    .hero a:hover {
      background-color: #e6ac00;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .section-title {
      text-align: center;
      font-size: 1.8rem;
      color: #0d47a1;
      margin-bottom: 20px;
    }
    .section-text {
      font-size: 1.1rem;
      line-height: 1.8;
      text-align: justify;
    }
    form {
      background: #f5f5f5;
      padding: 20px;
      border-radius: 10px;
    }
    label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }
    input, select, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      margin-top: 20px;
      background-color: #0d47a1;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      background-color: #1565c0;
    }
    .contact {
      background-color: #f0f0f0;
      padding: 20px;
      border-radius: 10px;
    }
    .contact p {
      margin: 10px 0;
      font-size: 1.1rem;
    }
  </style>
</head>
<body>
  <header>
    <img src="https://chat.openai.com/cdn-cgi/imagedelivery/Xs8CwM7voDGHK1_B5l7zOg/file-SuTzkcaLGxpEGr7dLbiAkT/public" alt="Logo">
    <h1>أكاديمية الصفوة</h1>
    <h2>Al Safwa Academy</h2>
  </header>

  <section class="hero">
    <h3>سجّل الآن للعام الدراسي الجديد</h3>
    <p>نقدّم جميع المواد الدراسية للمرحلتين الابتدائية والإعدادية مع نخبة من أفضل المعلمات، والدراسة أونلاين عبر Zoom</p>
    <a href="#register">احجز الآن</a>
  </section>

  <section>
    <h3 class="section-title">عن الأكاديمية</h3>
    <p class="section-text">
      أكاديمية الصفوة هي منصة تعليمية إلكترونية تهدف إلى تقديم تجربة تعليمية متميزة عبر الإنترنت، من خلال نخبة من المعلمات المتخصصات في شرح المواد الدراسية للمرحلتين الابتدائية والإعدادية، بطريقة مبسطة وتفاعلية.
    </p>
  </section>

  <section>
    <h3 class="section-title">نظام التعليم</h3>
    <p class="section-text">
      يتم تقديم الحصص من خلال برنامج Zoom، ويُراعى في الشرح التفاعل مع الطلاب، والمتابعة المستمرة، وحل الواجبات، مع تقديم اختبارات دورية لتقييم المستوى.
    </p>
  </section>

  <section>
    <h3 class="section-title">المواد المتوفرة</h3>
    <p class="section-text">
      تشمل المواد التي نقوم بتدريسها: اللغة العربية، اللغة الإنجليزية، الرياضيات، العلوم، الدراسات الاجتماعية، وغيرها حسب احتياجات كل مرحلة دراسية.
    </p>
  </section>

  <section id="register">
    <h3 class="section-title">نموذج تسجيل الطالب</h3>
    <form>
      <label>اسم الطالب:</label>
      <input type="text" placeholder="أدخل الاسم الكامل" required>

      <label>المرحلة الدراسية:</label>
      <select required>
        <option value="">-- اختر المرحلة --</option>
        <option>ابتدائي</option>
        <option>إعدادي</option>
      </select>

      <label>رقم ولي الأمر:</label>
      <input type="tel" placeholder="رقم الهاتف للتواصل" required>

      <label>المواد المطلوبة:</label>
      <textarea placeholder="اذكر المواد التي ترغب في دراستها" rows="3"></textarea>

      <label>وسيلة التواصل المفضلة:</label>
      <select required>
        <option value="">-- اختر وسيلة --</option>
        <option>رسائل واتساب</option>
        <option>مكالمة هاتفية</option>
        <option>فيسبوك ماسنجر</option>
      </select>

      <button type="submit">إرسال</button>
    </form>
  </section>

  <section>
    <h3 class="section-title">تواصل معنا</h3>
    <div class="contact">
      <p><strong>📞 رقم الهاتف:</strong> 01224453111</p>
      <p><strong>💬 واتساب:</strong> 01224453111</p>
      <p><strong>📧 البريد الإلكتروني:</strong> afafzezo2013@gmail.com</p>
      <p><strong>📍 فيسبوك:</strong> صفحة "أكاديمية الصفوة" الرسمية</p>
    </div>
  </section>

</body>
</html>
th ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
