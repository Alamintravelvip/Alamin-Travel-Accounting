
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#075c46">
<meta name="description" content="الأمين للسفريات والسياحة وخدمات الحج والعمرة في تعز اليمن. تذاكر طيران، تأشيرات، فنادق، حجوزات وبرامج العمرة والحج.">
<title>الأمين للسفريات والسياحة والحج والعمرة</title>

<style>
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
 margin:0;font-family:Tahoma,Arial,sans-serif;
 background:#fff;color:#252525;line-height:2
}
a{text-decoration:none;color:#087f5b}
.container{width:min(1100px,94%);margin:auto}
header{background:#075c46;padding:12px 0;border-bottom:3px solid #d6b45f}
.logo{text-align:center}
.logo img{width:170px;max-width:80%;height:auto}
nav{
 display:flex;flex-wrap:wrap;justify-content:center;
 align-items:center;gap:9px;padding:13px 0
}
nav a,.dropbtn{
 border:1px solid #f3d78c;background:#d6b45f;color:#173d2e;
 padding:9px 17px;border-radius:8px;font-weight:bold;
 font-size:16px;cursor:pointer
}
nav a:hover,.dropbtn:hover{background:#edcf80}
.dropdown{position:relative}
.dropmenu{
 display:none;position:absolute;top:100%;right:0;
 min-width:240px;background:#075c46;padding:9px;
 border:2px solid #d6b45f;border-radius:10px;z-index:99
}
.dropdown.active .dropmenu{display:block}
.dropmenu a{display:block;margin:5px 0;background:#087f5b;color:white}
.dropmenu a:hover{background:#d6b45f;color:#173d2e}
.hero-image{text-align:center;margin:20px auto}
.hero-image img{width:100%;border-radius:14px}
.hero{
 background:linear-gradient(135deg,#075c46,#0b9b6d);
 color:white;text-align:center;padding:35px 20px;
 border-radius:17px;margin:20px 0
}
.hero h1{font-size:28px;line-height:1.7;margin:0 0 12px}
.hero p{max-width:850px;margin:10px auto}
.buttons{display:flex;flex-wrap:wrap;justify-content:center;gap:10px;margin:20px 0}
.btn{
 display:inline-block;background:white;color:#087f5b;
 padding:10px 20px;border-radius:8px;font-weight:bold
}
.btn.gold{background:#d6b45f;color:#173d2e}
.btn.green{background:#087f5b;color:white}
section{margin:35px 0}
h2{
 color:#087f5b;font-size:25px;
 border-right:4px solid #d6b45f;padding-right:12px
}
h3{color:#087f5b;font-size:19px}
.about,.contact,.note{
 background:#f3faf6;border-radius:12px;padding:20px;
 border-right:5px solid #087f5b
}
.services{
 display:grid;grid-template-columns:repeat(2,minmax(0,1fr));
 gap:15px;margin:20px 0
}
.service{
 padding:20px;background:#fff;border:1px solid #e1ebe5;
 border-radius:13px;box-shadow:0 3px 12px #00000009
}
.service .icon{font-size:30px}
.service h3{margin:5px 0}
.service a{font-weight:bold}
ul{padding-right:25px}
li{margin:7px 0}
.contact a{font-weight:bold}
.faq{border-bottom:1px solid #ddd;padding:12px 0}
.cta{
 background:#075c46;color:white;text-align:center;
 padding:30px 18px;border:1px solid #d6b45f;
 border-radius:16px;margin:30px 0
}
.cta h2{color:white;border:0;padding:0}
.social{
 display:flex;flex-wrap:wrap;justify-content:center;gap:10px
}
.social a{
 background:white;border:1px solid #ddd;
 padding:8px 13px;border-radius:8px
}
footer{
 background:#f3faf6;border-top:3px solid #d6b45f;
 padding:22px;text-align:center;border-radius:12px
}
footer p{margin:7px}
.small{font-size:13px;color:#666}
@media(max-width:650px){
 .services{grid-template-columns:1fr}
 .hero{padding:25px 14px}
 .hero h1{font-size:23px}
 h2{font-size:21px}
 nav{gap:7px}
 nav a,.dropbtn{font-size:14px;padding:8px 11px}
 .dropdown{width:100%;text-align:center}
 .dropbtn{width:100%}
 .dropmenu{position:static;width:100%;text-align:right}
}
</style>
</head>

<body>

<header>
 <div class="container">
  <div class="logo">
   <a href="index.html">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi0ixukqiguECPSF_RynPgwNXoQwela4L7zZ0Xuj46P-HxbYUt2ZBDtos3_HQwVN-R-21vn3R5W9OSviyTzc8haw-xU0t8z_b9a3zD-o8282eytdW2erKtmwZZ1Kp6bKfUwn4yhO62jbhxCleJU-lYVKFB6VW5n1sxaeXtregJ-KVhN2GI/s1600/1001149405.png" alt="شعار الأمين للسفريات">
   </a>
  </div>

  <nav aria-label="القائمة الرئيسية">
   <a href="#home">الرئيسية</a>
   <a href="#about">من نحن</a>

   <div class="dropdown" id="servicesMenu">
    <button class="dropbtn" type="button" aria-expanded="false" onclick="toggleMenu()">خدماتنا ▾</button>
    <div class="dropmenu">
     <a href="#services">جميع الخدمات</a>
     <a href="https://www.alamintravelvip.com/p/blog-page_929.html">حجز تذاكر الطيران</a>
     <a href="https://www.alamintravelvip.com/p/blog-page_12.html">تأشيرات العمرة</a>
     <a href="https://www.alamintravelvip.com/p/blog-page_11.html">تأشيرات السعودية</a>
     <a href="https://www.alamintravelvip.com/p/blog-page.html">خدمات الحج والعمرة</a>
     <a href="https://www.alamintravelvip.com/p/20.html">برنامج العمرة</a>
     <a href="https://www.alamintravelvip.com/p/blog-page_37.html">باصات VIP</a>
     <a href="https://www.alamintravelvip.com/p/blog-page_19.html">السفر من اليمن للسعودية</a>
    </div>
   </div>

   <a href="https://www.alamintravelvip.com/p/blog-page_313.html">التسجيل للحج</a>
   <a href="https://www.alamintravelvip.com/p/blog-page_16.html">الحجز الإلكتروني</a>
   <a href="https://www.alamintravelvip.com/p/blog-page_60.html">اتصل بنا</a>
   <a href="accounting.html">نظام المحاسبة</a>
  </nav>
 </div>
</header>

<main class="container" id="home">

 <div class="hero-image">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEji5-3zrc-qQwcMJCziAwHd-O9qjqwCjCIo_c2IEYM17MFtZzxeaqLJ9vTPaJt43JVJFOFq987YlnjlhePKz8BmmlQANGJ-9lN-_DExk_ggSmHqGSrvWZ_nj0gsKPKq6K2hQeFKU7XZE3siXTQRbqfUQhYz8GwVlGlCv7WWivxHnDDWtVGREyTo7nsb1wU/s1983/file_000000000b988210be6e9180d293034a.png" alt="الأمين للسفريات والسياحة في تعز">
 </div>

 <div class="hero">
  <h1>الأمين للسفريات والسياحة وخدمات الحج والعمرة في تعز – اليمن</h1>
  <p>
   وجهتك لخدمات السفر وتذاكر الطيران وتأشيرات السعودية وحجوزات الفنادق
   ورحلات العمرة والحج. نسعى لخدمتك باهتمام ومساعدتك في معرفة الخيارات
   والأسعار والإجراءات المناسبة لطلبك.
  </p>
  <div class="buttons">
   <a class="btn" href="https://wa.me/967777818186">💬 تواصل عبر واتساب</a>
   <a class="btn gold" href="https://www.alamintravelvip.com/p/blog-page_16.html">طلب حجز خدمة</a>
   <a class="btn" href="#services">اكتشف خدماتنا</a>
  </div>
 </div>

 <section id="about">
  <h2>من نحن؟</h2>
  <div class="about">
   <p>
    الأمين للسفريات والسياحة وخدمات الحج والعمرة، جهة تسعى لتسهيل
    خدمات السفر والحجوزات والتأشيرات للمسافرين من اليمن.
   </p>
   <p>
    مقرنا في تعز – مفرق الذكرة – بداية شارع الستين.
    نستقبل استفسارات العملاء عبر الهاتف والواتساب ونسعى لتوضيح
    الخيارات والإجراءات والتفاصيل قبل تأكيد الحجز.
   </p>
   <a href="https://www.alamintravelvip.com/p/blog-page_65.html">اقرأ المزيد عنا ←</a>
  </div>
 </section>

 <section id="services">
  <h2>خدمات الأمين للسفريات والسياحة</h2>
  <p>نوفر مجموعة من خدمات السفر والسياحة للمسافرين من اليمن.</p>

  <div class="services">

   <div class="service">
    <span class="icon">✈️</span>
    <h3>حجز تذاكر الطيران</h3>
    <p>الاستفسار عن رحلات الطيران وخيارات الحجز ومواعيد السفر والأسعار المتاحة.</p>
    <a href="https://www.alamintravelvip.com/p/blog-page_929.html">تفاصيل حجز الطيران ←</a>
   </div>

   <div class="service">
    <span class="icon">🕋</span>
    <h3>تأشيرات العمرة</h3>
    <p>الاستفسار عن خدمات تأشيرات العمرة والمتطلبات والإجراءات المتاحة.</p>
    <a href="https://www.alamintravelvip.com/p/blog-page_12.html">تفاصيل تأشيرات العمرة ←</a>
   </div>

   <div class="service">
    <span class="icon">🛂</span>
    <h3>تأشيرات السعودية</h3>
    <p>الاستفسار عن خدمات التأشيرات والمتطلبات حسب نوع التأشيرة والأنظمة المعمول بها.</p>
    <a href="https://www.alamintravelvip.com/p/blog-page_11.html">استفسر عن التأشيرات ←</a>
   </div>

   <div class="service">
    <span class="icon">🏨</span>
    <h3>حجوزات الفنادق</h3>
    <p>الاستفسار عن خيارات الفنادق في مكة والمدينة وجدة والرياض.</p>
    <a href="https://wa.me/967777818186">استفسر عبر واتساب ←</a>
   </div>

   <div class="service">
    <span class="icon">🕌</span>
    <h3>رحلات وبرامج العمرة</h3>
    <p>خدمات الاستفسار عن رحلات وبرامج العمرة والإقامة والخدمات المرتبطة بها.</p>
    <a href="https://www.alamintravelvip.com/p/20.html">برنامج العمرة ←</a>
    <br>
    <a href="https://www.alamintravelvip.com/p/blog-page.html">خدمات الحج والعمرة ←</a>
   </div>

   <div class="service">
    <span class="icon">🚌</span>
    <h3>باصات VIP إلى السعودية</h3>
    <p>الاستفسار عن حجوزات باصات VIP من اليمن إلى السعودية.</p>
    <a href="https://www.alamintravelvip.com/p/blog-page_37.html">تفاصيل الباصات ←</a>
   </div>

   <div class="service">
    <span class="icon">🕋</span>
    <h3>التسجيل والحجز للحج</h3>
    <p>الاستفسار عن التسجيل والحجز والخدمات المتعلقة بالحج حسب البرامج والتعليمات المتاحة.</p>
    <a href="https://www.alamintravelvip.com/p/blog-page_313.html">التسجيل للحج ←</a>
   </div>

   <div class="service">
    <span class="icon">🌍</span>
    <h3>السفر من اليمن إلى السعودية</h3>
    <p>خدمات السفر والحجوزات للمسافرين من اليمن إلى السعودية.</p>
    <a href="https://www.alamintravelvip.com/p/blog-page_19.html">تفاصيل السفر ←</a>
   </div>

  </div>
 </section>

 <section>
  <h2>لماذا تختار الأمين للسفريات؟</h2>
  <ul>
   <li>مقرنا في تعز – مفرق الذكرة – بداية شارع الستين.</li>
   <li>الوضوح في التعامل وتوضيح تفاصيل الخدمة.</li>
   <li>سرعة متابعة الاستفسارات وطلبات العملاء.</li>
   <li>خيارات متنوعة حسب احتياجات المسافرين.</li>
   <li>تنوع خدمات السفر والتأشيرات والحج والعمرة.</li>
   <li>سهولة التواصل عبر الهاتف والواتساب.</li>
  </ul>
  <div class="note">
   <strong>نصيحتنا لك:</strong>
   اسأل عن السعر النهائي والخدمات المشمولة وشروط التعديل والإلغاء قبل تأكيد أي حجز.
  </div>
 </section>

 <section>
  <h2>كيف تحجز معنا؟</h2>
  <h3>1. حدد الخدمة</h3>
  <p>اختر الخدمة التي تحتاجها، سواء تذكرة طيران أو تأشيرة أو فندق أو رحلة عمرة.</p>
  <h3>2. أرسل تفاصيل طلبك</h3>
  <p>أرسل الوجهة والموعد وعدد المسافرين عبر واتساب.</p>
  <h3>3. تعرف على الخيارات والأسعار</h3>
  <p>نوضح لك الخيارات المتاحة والتكاليف والمتطلبات قبل إتمام الحجز.</p>
  <h3>4. تأكيد الحجز</h3>
  <p>بعد مراجعة التفاصيل والاتفاق عليها يتم استكمال إجراءات الحجز.</p>
  <div class="buttons">
   <a class="btn green" href="https://www.alamintravelvip.com/p/blog-page_16.html">نظام الحجز الإلكتروني</a>
   <a class="btn green" href="https://wa.me/967777818186">تواصل معنا</a>
  </div>
 </section>

 <section id="contact">
  <h2>موقع الشركة وطرق التواصل</h2>
  <div class="contact">
   <p><strong>الاسم:</strong> الأمين للسفريات والسياحة وخدمات الحج والعمرة.</p>
   <p><strong>المحافظة:</strong> تعز – اليمن.</p>
   <p><strong>العنوان:</strong> مفرق الذكرة – بداية شارع الستين.</p>
   <p><strong>الهاتف والواتساب:</strong> <a href="tel:+967777818186">+967 777 818 186</a></p>
   <div class="buttons">
    <a class="btn green" href="https://maps.app.goo.gl/4kNeUtdWncjXmsdY7" target="_blank" rel="noopener">موقعنا على خرائط Google</a>
    <a class="btn green" href="https://wa.me/967777818186">واتساب</a>
   </div>
  </div>
 </section>

 <section>
  <h2>الأسئلة الشائعة</h2>

  <div class="faq">
   <h3>أين يقع الأمين للسفريات؟</h3>
   <p>في محافظة تعز، مفرق الذكرة، بداية شارع الستين في اليمن.</p>
  </div>
  <div class="faq">
   <h3>هل توفرون تذاكر طيران؟</h3>
   <p>يمكنك الاستفسار عن الرحلات والأسعار من خلال <a href="https://www.alamintravelvip.com/p/blog-page_929.html">صفحة حجز الطيران</a>.</p>
  </div>
  <div class="faq">
   <h3>هل يمكن الاستفسار عن تأشيرات السعودية؟</h3>
   <p>نعم، يمكنك التواصل معنا للاستفسار عن أنواع التأشيرات والمتطلبات المتاحة.</p>
  </div>
  <div class="faq">
   <h3>هل يمكن حجز الفنادق؟</h3>
   <p>يمكنك الاستفسار عن الفنادق في مكة والمدينة وجدة والرياض عبر واتساب.</p>
  </div>
  <div class="faq">
   <h3>كيف أتواصل للحجز؟</h3>
   <p>عبر الرقم <a href="tel:+967777818186">+967 777 818 186</a>.</p>
  </div>
 </section>

 <section class="cta">
  <h2>جاهز ترتب سفرك؟</h2>
  <p>تواصل مع الأمين للسفريات والسياحة واستفسر عن خدماتنا.</p>
  <div class="buttons">
   <a class="btn gold" href="https://wa.me/967777818186?text=%D8%A7%D9%84%D8%B3%D9%84%D8%A7%D9%85%20%D8%B9%D9%84%D9%8A%D9%83%D9%85%D8%8C%20%D8%A3%D8%B1%D9%8A%D8%AF%20%D8%A7%D9%84%D8%A7%D8%B3%D8%AA%D9%81%D8%B3%D8%A7%D8%B1">احجز عبر واتساب الآن</a>
   <a class="btn" href="tel:+967777818186">اتصل بنا</a>
  </div>
 </section>

 <section>
  <h2>تابعنا على وسائل التواصل الاجتماعي</h2>
  <div class="social">
   <a href="https://www.facebook.com/alamintravel" target="_blank" rel="noopener">Facebook</a>
   <a href="https://www.instagram.com/alamintravelvip" target="_blank" rel="noopener">Instagram</a>
   <a href="https://www.youtube.com/@alamintravelvip" target="_blank" rel="noopener">YouTube</a>
   <a href="https://www.tiktok.com/@alamintravelvip" target="_blank" rel="noopener">TikTok</a>
   <a href="https://www.linkedin.com/company/alamintravel" target="_blank" rel="noopener">LinkedIn</a>
   <a href="https://www.twitter.com/alamintravelvip" target="_blank" rel="noopener">X</a>
   <a href="https://www.pinterest.com/alamintravelvip" target="_blank" rel="noopener">Pinterest</a>
  </div>
 </section>

 <footer>
  <p><strong>الأمين للسفريات والسياحة وخدمات الحج والعمرة</strong></p>
  <p>الموقع الرسمي: <a href="https://www.alamintravelvip.com/">www.alamintravelvip.com</a></p>
  <p>الهاتف والواتساب: <a href="tel:+967777818186">+967 777 818 186</a></p>
  <p>
   <a href="https://www.alamintravelvip.com/p/blog-page_65.html">من نحن</a> |
   <a href="https://www.alamintravelvip.com/p/blog-page_60.html">اتصل بنا</a> |
   <a href="https://www.alamintravelvip.com/p/blog-page_46.html">سياسة الخصوصية</a> |
   <a href="https://www.alamintravelvip.com/p/blog-page_2.html">الشروط والأحكام</a> |
   <a href="https://www.alamintravelvip.com/p/blog-page_13.html">سياسة الإلغاء والاسترداد</a>
  </p>
  <p class="small">جميع الحقوق محفوظة للأمين للسفريات والسياحة وخدمات الحج والعمرة.</p>
 </footer>

</main>

<script>
function toggleMenu(){
 const menu=document.getElementById('servicesMenu');
 const button=menu.querySelector('.dropbtn');
 const active=menu.classList.toggle('active');
 button.setAttribute('aria-expanded',String(active));
}
document.addEventListener('click',function(e){
 const menu=document.getElementById('servicesMenu');
 if(!menu.contains(e.target)){
  menu.classList.remove('active');
  menu.querySelector('.dropbtn').setAttribute('aria-expanded','false');
 }
});
</script>

</body>
</html>
