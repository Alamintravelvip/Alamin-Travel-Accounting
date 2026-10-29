<!-- شاشة تسجيل الدخول المؤمنة -->
<div id="alaminLoginGate" style="position:fixed;inset:0;z-index:999999;background:linear-gradient(135deg,#f2f4f7,#e4e7ec);display:flex;align-items:center;justify-content:center;padding:20px;direction:rtl;font-family:Arial,Tahoma,sans-serif">
<div style="width:100%;max-width:430px;background:#fff;padding:30px 25px;border-radius:20px;box-shadow:0 10px 40px rgba(0,0,0,0.12);text-align:center;border-top:5px solid #b00000">
<div style="width:120px;height:120px;margin:0 auto 15px;border-radius:50%;display:flex;align-items:center;justify-content:center;border:3px solid #eee;overflow:hidden"><img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiu3TtYlgT73xNqR8L4QMrRacAhPWSuGbcuQhbkjk6aNRK58PNfKwk_1VGsNGrlTmWJ6_4-ChXPMI2-Bx0sziJ9glcpAUQgED9MAXozV13omWclxgAIHwC5CJwtH2Bv9nKBgkVkMLvMSCkleJ4zt9vCCqRoqQopo7doJl8Mx9VzL8WvcfI8zC2LiQJXyTs/s1254/1001145304.png" alt="شعار الأمين" style="width:100%;height:100%;object-fit:contain"></div>
<h2 style="color:#b00000;margin:0 0 5px;font-size:22px">الأمين للسفريات والسياحة</h2><p style="line-height:1.6;color:#666;font-size:13px;margin-bottom:20px">وخدمات الحج والعمرة<br>تسجيل الدخول إلى النظام الموحد</p>
<div style="text-align:right;margin-bottom:15px"><label for="alaminLoginUsername" style="font-weight:800;font-size:13px">اسم المستخدم</label><input id="alaminLoginUsername" autocomplete="off" style="width:100%;box-sizing:border-box;padding:12px;margin-top:6px;border:2px solid #ddd;border-radius:10px;font-size:15px"></div>
<div style="text-align:right;margin-bottom:15px"><label for="alaminLoginPassword" style="font-weight:800;font-size:13px">كلمة المرور</label><input id="alaminLoginPassword" type="password" autocomplete="new-password" style="width:100%;box-sizing:border-box;padding:12px;margin-top:6px;border:2px solid #ddd;border-radius:10px;font-size:16px;text-align:center"></div>
<div id="alaminLoginError" style="display:none;color:#b00000;background:#fff0f0;padding:10px;border-radius:8px;margin-bottom:12px;font-weight:700;font-size:13px"></div>
<button id="alaminLoginButton" type="button" style="width:100%;border:0;border-radius:10px;background:#b00000;color:white;padding:14px;font-size:17px;font-weight:900;cursor:pointer">🔐 تسجيل الدخول</button>
</div></div>

<style>
.alamin-booking{max-width:960px;margin:25px auto;padding:25px;background:#fff;border-radius:22px;box-shadow:0 8px 30px rgba(0,0,0,0.08);direction:rtl;font-family:Arial,Tahoma,sans-serif;color:#202020;border:1px solid #e5e5e5}
.alamin-booking *{box-sizing:border-box}

/* ترويسة النظام الرسمية الاحترافية مع الأرقام الثلاثة في اليسار */
.alamin-enterprise-header{display:flex;flex-wrap:wrap;justify-content:space-between;align-items:center;background:#f8f9fa;border:1px solid #e1e4e8;border-radius:16px;padding:18px 22px;margin-bottom:22px;box-shadow:0 3px 10px rgba(0,0,0,0.02);gap:15px}
.alamin-brand-box{display:flex;align-items:center;gap:15px}
.alamin-brand-logo{width:65px;height:65px;background:#fff;border-radius:50%;padding:3px;border:2px solid #ddd;overflow:hidden;display:flex;align-items:center;justify-content:center}
.alamin-brand-logo img{width:100%;height:100%;object-fit:contain}
.alamin-brand-title h1{font-size:21px;margin:0 0 4px;font-weight:900;color:#111}
.alamin-brand-title h1 span{color:#b00000}
.alamin-brand-title p{margin:0;color:#666;font-size:12px;font-weight:700}

/* الأرقام الثلاثة في أقصى اليسار بشكل مرتب وراقي */
.alamin-top-contacts{background:#fff;border:2px solid #d0d7de;border-radius:12px;padding:10px 15px;text-align:left;direction:ltr;box-shadow:0 2px 6px rgba(0,0,0,0.04)}
.alamin-top-contacts .c-label{font-size:9.5px;color:#555;font-weight:800;text-transform:uppercase;margin-bottom:2px;display:block;text-align:right}
.alamin-top-contacts .c-numbers{font-size:13px;font-weight:900;color:#b00000;letter-spacing:0.5px}

/* شريط الأيقونات والأقسام الاحترافي (بنظام الشركات الكبرى) */
.alamin-top-navbar{display:flex;flex-wrap:wrap;justify-content:center;gap:8px;background:#212529;padding:12px 15px;border-radius:14px;box-shadow:0 4px 15px rgba(0,0,0,0.15);margin-bottom:25px}
.alamin-top-navbar button{border:0;border-radius:9px;background:rgba(255,255,255,0.08);color:#fff;padding:9px 14px;font:800 13px Arial,Tahoma,sans-serif;cursor:pointer;display:flex;align-items:center;gap:7px;transition:all 0.2s ease}
.alamin-top-navbar button:hover{background:#b00000;transform:translateY(-1px);box-shadow:0 4px 10px rgba(176,0,0,0.4)}
.alamin-top-navbar button span{font-size:15px}

.alamin-section{margin-top:20px;padding:22px;border:1px solid #e1e4e8;border-radius:16px;background:#fafbfc}
.alamin-section h2{margin:0 0 18px;padding-bottom:10px;border-bottom:2px solid #eaecef;font-size:19px;color:#24292e;font-weight:900;display:flex;align-items:center;gap:8px}
.alamin-row{display:grid;grid-template-columns:1fr 1fr;gap:16px}.alamin-field{margin-bottom:16px}.alamin-field label{display:block;margin-bottom:7px;font-weight:800;font-size:13.5px;color:#24292e;line-height:1.4}.required{color:#b00000}
.alamin-field input,.alamin-field select,.alamin-field textarea{width:100%;min-height:50px;padding:10px 14px;border:2px solid #d1d5db;border-radius:10px;background:#fff;color:#111;font:600 16px Arial,Tahoma,sans-serif;transition:border-color 0.2s}
.alamin-field input[type=date],.alamin-field input[type=time]{direction:ltr;text-align:left}.alamin-field textarea{min-height:100px;resize:vertical}.alamin-field input:focus,.alamin-field select:focus,.alamin-field textarea:focus{border-color:#b00000;outline:none}
.ticket-number{background:#f3f4f6!important;font-size:20px!important;font-weight:900!important;color:#b00000!important;text-align:center;direction:ltr}
.payment-box{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}.payment-option{padding:14px;border:2px solid #d1d5db;border-radius:11px;text-align:center;font-weight:800;cursor:pointer;background:#fff}.payment-option input{width:auto;min-height:auto}
.review-box{display:none;margin-top:20px;padding:20px;border-radius:14px;background:#fff;border:2px solid #d1d5db}.review-box.active{display:block}.review-box h3{color:#b00000;margin-top:0}.review-line{padding:8px 0;border-bottom:1px solid #f0f0f0;line-height:1.6;font-size:14.5px}

.alamin-ticket-wrapper{display:none;margin-top:25px}.alamin-ticket-wrapper.active{display:block}
/* مقاس التذكرة العرضية: العرض 21 سم والارتفاع 7 سم */
.bus-ticket{width:21cm;min-height:7cm;margin:auto;background:#fff;border:2px solid #111;color:#111;font-family:Arial,Tahoma,sans-serif;overflow:hidden;direction:rtl;font-size:11px;}

.ticket-header{display:grid;grid-template-columns:120px 1fr 180px;align-items:stretch;min-height:65px;border-bottom:2px solid #111}
.ticket-logo{width:120px;min-height:65px;display:flex;align-items:center;justify-content:center;overflow:hidden;border-left:2px solid #111;padding:3px}
.ticket-logo img{display:block;width:100%;height:100%;max-height:55px;object-fit:contain}
.company-title{display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:4px}
.company-title h3{margin:0;font-size:16px;font-weight:900;line-height:1.3}
.company-title p{margin:2px;font-size:11px;font-weight:700}
.ticket-qr-area{display:flex;flex-direction:column;align-items:center;justify-content:center;gap:3px;border-right:2px solid #111;padding:4px}
.qr-box{width:45px;height:45px;border:1px solid #111;display:flex;align-items:center;justify-content:center;overflow:hidden}
.qr-box img{width:100%;height:100%;object-fit:contain}
.ticket-number-head{text-align:center;font-size:10px;font-weight:900}
.ticket-number-head span{display:block;font-size:8px}

.ticket-badge{padding:4px 8px;border-bottom:2px solid #111;text-align:center;font-size:12px;font-weight:900;color:#fff;background:#111}
.ticket-badge.vip{background:#b00000}
.ticket-badge.normal{background:#278b4b}

.ticket-grid{display:grid;grid-template-columns:repeat(5,1fr);background:#111;gap:1px;border-bottom:1px solid #111}
.grid-item{min-height:35px;padding:3px 5px;background:white;display:flex;flex-direction:column;justify-content:center}
.grid-item span{display:block;margin-bottom:1px;font-size:8.5px;font-weight:800;color:#555}
.grid-item strong{font-size:10.5px;font-weight:900;line-height:1.2;word-break:break-word}

.ticket-notes{padding:4px 8px;min-height:30px;border-bottom:1px solid #111;background:#f5f5f5}
.ticket-notes-title{display:block;font-size:9px;font-weight:900}
.ticket-notes-content{font-size:9.5px;font-weight:700;white-space:pre-wrap}

.ticket-bottom-notice,.branches-footer{padding:4px 8px;text-align:center;font-size:8.5px;font-weight:700;line-height:1.3}
.ticket-bottom-notice{background:#eee;border-bottom:1px solid #111}
.branches-footer{background:#fff}

.primary-btn,.whatsapp-btn,.print-btn{width:100%;border:0;border-radius:12px;padding:16px;margin-top:14px;font:900 17px Arial,Tahoma,sans-serif;cursor:pointer}
.primary-btn{background:#b00000;color:#fff}
.whatsapp-btn{background:#25D366;color:#fff}
.print-btn{background:#333;color:#fff}
.direct-whatsapp{display:block;text-align:center;text-decoration:none;padding:14px;margin:18px 0;border-radius:12px;background:#25D366;color:#fff;font-weight:900;font-size:16px}

.notice{padding:12px 14px;background:#f8f9fa;border-right:4px solid #b00000;color:#555;line-height:1.7;border-radius:8px;font-size:13.5px}
.success{display:none;margin-top:16px;padding:15px;background:#eff9f1;border:1px solid #b9dfc0;color:#155b20;text-align:center;font-weight:800;border-radius:10px}

.sales-report{padding:22px;border:2px solid #e3e3e3;border-radius:18px;background:#fafafa;direction:rtl}
.sales-report h2{color:#b00000;font-size:22px}
.sales-report p{line-height:1.8;color:#555}
.sales-report-filters{display:grid;grid-template-columns:1fr 1fr;gap:14px;margin:18px 0}
.sales-report label{display:block;font-weight:800;margin-bottom:7px}
.sales-report input,.sales-report select{width:100%;min-height:48px;padding:10px;border:2px solid #ddd;border-radius:10px;font-size:16px;direction:ltr}
.sales-report-actions{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.sales-report-actions button{border:0;border-radius:10px;padding:14px;font-size:16px;font-weight:900;cursor:pointer}
#showSalesReport,#showFinancialReport,#saveExpenseBtn,#saveNewUserBtn,#saveVoucherBtn,#saveUmrahBtn,#saveOwnerSettingsBtn{background:#b00000;color:#fff}
#printSalesReport,#printFinancialReport,#printExpensesReport,#printVouchersReport,#printUmrahReport{background:#333;color:#fff}
.sales-report-summary{display:flex;flex-wrap:wrap;gap:12px;margin:18px 0}
.sales-report-stat{flex:1;min-width:150px;background:#fff;border:1px solid #ddd;border-radius:10px;padding:14px;text-align:center}
.sales-report-stat span{display:block;color:#555;margin-bottom:7px;font-size:13px;font-weight:800}
.sales-report-stat strong{font-size:20px;color:#b00000}
.sales-report-table-wrap{width:100%;overflow-x:auto;margin-top:15px}
.sales-report-table{width:100%;border-collapse:collapse;background:#fff;font-size:13px}
.sales-report-table th,.sales-report-table td{border:1px solid #ccc;padding:9px 8px;text-align:center;white-space:nowrap}
.sales-report-table th{background:#333;color:#fff}
.sales-report-empty{padding:18px;text-align:center;color:#666;background:#fff;border:1px solid #ddd;border-radius:10px}

.financial-edit{width:110px!important;min-height:38px!important;padding:6px!important;direction:ltr!important;text-align:center!important}
.financial-save{border:0;border-radius:7px;background:#1769aa;color:#fff;padding:9px 11px;font-weight:900;cursor:pointer}
.financial-save:disabled{opacity:.6;background:#888;cursor:not-allowed}
.financial-note{background:#fff8e8;border:1px solid #ead6a2;padding:12px;border-radius:10px;line-height:1.8}

.alamin-drawer-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.5);z-index:99991}
.alamin-drawer-overlay.active{display:block}
.alamin-drawer{display:none;position:fixed;z-index:99992;inset:0 0 0 auto;width:min(100%,1050px);height:100%;overflow:auto;background:#fff;padding:22px;box-shadow:-5px 0 25px rgba(0,0,0,0.2);direction:rtl}
.alamin-drawer.active{display:block}
.drawer-top{display:flex;align-items:center;justify-content:space-between;gap:10px;border-bottom:2px solid #eee;padding-bottom:12px;margin-bottom:18px}
.drawer-top h2{font-size:22px;margin:0;color:#b00000;font-weight:900}
.drawer-close{border:0;background:#333;color:white;border-radius:9px;padding:10px 16px;font-weight:900;cursor:pointer}

.archive-search{width:100%;padding:13px;border:2px solid #ddd;border-radius:10px;font-size:16px;margin-bottom:14px}
.archive-table-wrap{overflow-x:auto}
.archive-table{width:100%;border-collapse:collapse;font-size:13px}
.archive-table th,.archive-table td{border:1px solid #ddd;padding:9px;text-align:center;white-space:nowrap}
.archive-table th{background:#333;color:#fff}
.archive-action{border:0;border-radius:7px;padding:8px 10px;margin:2px;color:#fff;font-weight:800;cursor:pointer}
.archive-view{background:#1769aa}
.archive-delete{background:#b00000}
.archive-empty{text-align:center;padding:18px;background:#f8f8f8;border-radius:10px;color:#666;font-weight:700}
.permission-checkbox{display:flex;align-items:center;gap:10px;margin-bottom:10px;font-weight:700;font-size:14.5px}
.permission-checkbox input{width:20px;height:20px;accent-color:#b00000}

@media(max-width:650px){.alamin-booking{margin:8px;padding:15px}.alamin-enterprise-header{flex-direction:column;text-align:center}.alamin-brand-box{flex-direction:column}.alamin-top-contacts{width:100%;text-align:center}.alamin-top-contacts .c-label{text-align:center}.alamin-row,.payment-box,.sales-report-filters,.sales-report-actions{grid-template-columns:1fr}.bus-ticket{width:100%!important;min-width:0!important}.alamin-ticket-wrapper{overflow-x:auto;padding-bottom:10px}.alamin-drawer{padding:15px}}

/* ==========================================================
   تنسيق التقارير والكشوفات المضغوطة للشركات الكبرى عند الطباعة
   ========================================================== */
@media print{
  @page{size:A4 landscape; margin: 8mm;}
  html,body{margin:0!important;padding:0!important;background:white!important;-webkit-print-color-adjust:exact;print-color-adjust:exact}
  body *{visibility:hidden!important}
  
  .sales-report, .sales-report * { visibility:visible!important; }
  .sales-report { position:absolute!important; left:0!important; top:0!important; width:100%!important; background:#fff!important; border:none!important; box-shadow:none!important; padding:0!important; margin:0!important; }
  
  .no-print, .alamin-top-navbar, .alamin-drawer, .alamin-drawer-overlay, .drawer-top, .sales-report-filters, .sales-report-actions { display:none!important; }
  
  .sales-report-table { font-size: 9.5px !important; width: 100% !important; border-collapse: collapse !important; }
  .sales-report-table th, .sales-report-table td { padding: 4px 5px !important; border: 1px solid #333 !important; }
  .sales-report-table th { background: #222 !important; color: #fff !important; font-size: 10px !important; }
  .sales-report-summary { display: flex !important; gap: 5px !important; margin: 8px 0 !important; }
  .sales-report-stat { padding: 6px !important; font-size: 10px !important; border: 1px solid #444 !important; }
  .sales-report-stat strong { font-size: 13px !important; }
}
</style>

<div class="alamin-drawer-overlay no-print" id="drawerOverlay"></div>

<div class="alamin-drawer no-print" id="archiveDrawer">
<div class="drawer-top"><h2>🎫 أرشيف التذاكر الصادرة</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<input id="archiveSearch" class="archive-search" type="search" placeholder="ابحث برقم التذكرة أو اسم المسافر أو الجواز أو الجوال">
<div id="archiveResults"></div>
</div>

<div class="alamin-drawer no-print" id="salesDrawer">
<div class="drawer-top"><h2>📊 التقارير المالية والإحصائية</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<div id="salesReportSection" class="sales-report">
<h2>📊 تقرير مبيعات التذاكر الصادرة</h2>
<p>حدد الفترة حسب تاريخ إصدار التذكرة، ثم اعرض الكشف أو اطبعه.</p>
<div class="sales-report-filters">
<div><label for="salesStartDate">من تاريخ الإصدار</label><input id="salesStartDate" type="date"></div>
<div><label for="salesEndDate">إلى تاريخ الإصدار</label><input id="salesEndDate" type="date"></div>
</div>
<div class="sales-report-actions"><button id="showSalesReport" type="button">🔎 عرض التقرير</button><button id="printSalesReport" type="button">🖨️ طباعة كشف المبيعات المضغوط</button></div>
<div class="sales-report-summary">
<div class="sales-report-stat"><span>عدد التذاكر الصادرة</span><strong id="salesTicketCount">0</strong></div>
<div class="sales-report-stat"><span>إجمالي الريال اليمني</span><strong id="salesTotalYER">0</strong></div>
<div class="sales-report-stat"><span>إجمالي الريال السعودي</span><strong id="salesTotalSAR">0</strong></div>
<div class="sales-report-stat"><span>إجمالي الأسعار</span><strong id="salesTotalAmount">0</strong></div>
</div>
<div id="salesReportResults"><div class="sales-report-empty">حدد الفترة ثم اضغط عرض التقرير.</div></div>
</div>
</div>

<div class="alamin-drawer no-print" id="financialDrawer">
<div class="drawer-top"><h2>💰 الخزينة الكبرى والصندوق العام</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<div id="financialReportSection" class="sales-report">
<h2>💰 حركة الصندوق والخزينة العامة</h2>
<p>مرتبط بكل أقسام النظام (مبيعات الباصات، حجوزات العمرة، سندات القبض، المصروفات، وسندات الصرف).</p>
<div class="financial-note">معادلة رصيد الصندوق الفعلي الصحيحة لكل عملة: (إجمالي مبيعات التذاكر - إجمالي سداد الشركات) + (العمرة والزيارات + سندات القبض) - (المصروفات اليومية + سندات الصرف).</div>
<div class="sales-report-filters">
<div><label for="financialStartDate">من التاريخ</label><input id="financialStartDate" type="date"></div>
<div><label for="financialEndDate">إلى التاريخ</label><input id="financialEndDate" type="date"></div>
</div>
<div class="sales-report-actions"><button id="showFinancialReport" type="button">🔎 تحديث الصندوق</button><button id="printFinancialReport" type="button">🖨️ طباعة تقرير الصندوق</button></div>

<!-- تصميم الأعمدة المستقلة: عمود للريال اليمني وعمود للريال السعودي -->
<div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;margin:20px 0;">

<!-- العمود الأول: الريال اليمني -->
<div style="background:#fff;border:2px solid #ccc;border-radius:15px;padding:15px;">
<h3 style="color:#b00000;text-align:center;border-bottom:2px solid #b00000;padding-bottom:8px;margin-top:0;">🇾🇪 حركة الريال اليمني</h3>
<div style="display:flex;flex-direction:column;gap:12px;margin-top:12px;">
<div class="sales-report-stat"><span>إجمالي مبيعات التذاكر (يمني)</span><strong id="boxSalesYER">0</strong></div>
<div class="sales-report-stat"><span>إجمالي سداد الشركات (يمني)</span><strong id="boxPaidYER">0</strong></div>
<div class="sales-report-stat" style="background:#eef6ff;border:2px solid #1769aa"><span>إجمالي العمولة المستحقة (يمني)</span><strong id="boxCommYER" style="color:#1769aa">0</strong></div>
<div class="sales-report-stat"><span>إجمالي العمرة والزيارات (يمني)</span><strong id="boxUmrahYER">0</strong></div>
<div class="sales-report-stat"><span>إجمالي سندات القبض (يمني)</span><strong id="boxRecYER">0</strong></div>
<div class="sales-report-stat" style="background:#fff8e8;border:2px solid #d48806"><span>إجمالي المصروفات (يمني)</span><strong id="boxExpYER" style="color:#d48806">0</strong></div>
<div class="sales-report-stat" style="background:#fff8e8;border:2px solid #d48806"><span>إجمالي سندات الصرف (يمني)</span><strong id="boxPayYER" style="color:#d48806">0</strong></div>
<div style="background:linear-gradient(135deg,#e6f4ea,#cbf0d8);border:3px solid #155b20;border-radius:12px;padding:14px;text-align:center;margin-top:5px">
<span style="display:block;color:#155b20;font-size:14px;font-weight:900;margin-bottom:5px">✨ رصيد الصندوق الفعلي (يمني)</span>
<strong id="finNetYER" style="font-size:24px;color:#155b20;font-weight:900">0</strong>
</div>
</div>
</div>

<!-- العمود الثاني: الريال السعودي -->
<div style="background:#fff;border:2px solid #ccc;border-radius:15px;padding:15px;">
<h3 style="color:#1769aa;text-align:center;border-bottom:2px solid #1769aa;padding-bottom:8px;margin-top:0;">🇸🇦 حركة الريال السعودي</h3>
<div style="display:flex;flex-direction:column;gap:12px;margin-top:12px;">
<div class="sales-report-stat"><span>إجمالي مبيعات التذاكر (سعودي)</span><strong id="boxSalesSAR">0</strong></div>
<div class="sales-report-stat"><span>إجمالي سداد الشركات (سعودي)</span><strong id="boxPaidSAR">0</strong></div>
<div class="sales-report-stat" style="background:#eef6ff;border:2px solid #1769aa"><span>إجمالي العمولة المستحقة (سعودي)</span><strong id="boxCommSAR" style="color:#1769aa">0</strong></div>
<div class="sales-report-stat"><span>إجمالي العمرة والزيارات (سعودي)</span><strong id="boxUmrahSAR">0</strong></div>
<div class="sales-report-stat"><span>إجمالي سندات القبض (سعودي)</span><strong id="boxRecSAR">0</strong></div>
<div class="sales-report-stat" style="background:#fff8e8;border:2px solid #d48806"><span>إجمالي المصروفات (سعودي)</span><strong id="boxExpSAR" style="color:#d48806">0</strong></div>
<div class="sales-report-stat" style="background:#fff8e8;border:2px solid #d48806"><span>إجمالي سندات الصرف (سعودي)</span><strong id="boxPaySAR" style="color:#d48806">0</strong></div>
<div style="background:linear-gradient(135deg,#e6f4ea,#cbf0d8);border:3px solid #155b20;border-radius:12px;padding:14px;text-align:center;margin-top:5px">
<span style="display:block;color:#155b20;font-size:14px;font-weight:900;margin-bottom:5px">✨ رصيد الصندوق الفعلي (سعودي)</span>
<strong id="finNetSAR" style="font-size:24px;color:#155b20;font-weight:900">0</strong>
</div>
</div>
</div>

</div>

<div id="financialCompanySummary"></div>
<div id="financialReportResults"><div class="sales-report-empty">حدد الفترة ثم اضغط تحديث الصندوق.</div></div>
</div>
</div>

<!-- شاشة المصروفات اليومية -->
<div class="alamin-drawer no-print" id="expensesDrawer">
<div class="drawer-top"><h2>💸 إدارة النثريات والمصروفات</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<div class="sales-report">
<h2>تسجيل المصروفات والخرجيات اليومية</h2>
<p>قم بتسجيل النثريات، المصروفات التشغيلية، والخرجيات اليومية الخاصة بالمكتب.</p>
<div class="alamin-section" style="margin-top:10px;background:#fff">
<div class="alamin-row">
<div class="alamin-field"><label>📅 تاريخ المصروف <span class="required">*</span></label><input id="expenseDate" type="date"></div>
<div class="alamin-field"><label>🏷️ بند المصروف / البيان <span class="required">*</span></label><input id="expenseTitle" placeholder="مثل: ضيافة، كهرباء، إيجار، أدوات..."></div>
</div>
<div class="alamin-row">
<div class="alamin-field"><label>💰 المبلغ <span class="required">*</span></label><input id="expenseAmount" type="number" min="0" step="any" placeholder="اكتب المبلغ"></div>
<div class="alamin-field"><label>💱 العملة <span class="required">*</span></label><select id="expenseCurrency"><option value="YER">ريال يمني</option><option value="SAR">ريال سعودي</option></select></div>
</div>
<div class="alamin-field"><label>👤 اسم الموظف المسجل</label><input id="expenseEmployee" placeholder="اسم الموظف أو القائم بالصرف"></div>
<div class="alamin-field"><label>📝 ملاحظات تفصيلية</label><textarea id="expenseNotes" placeholder="أي تفاصيل أخرى تخص المصروف"></textarea></div>
<button id="saveExpenseBtn" class="primary-btn" type="button" style="margin-top:5px">➕ إضافة وحفظ المصروف</button>
</div>
<div class="sales-report-filters" style="margin-top:20px">
<div><label for="filterExpStart">من تاريخ</label><input id="filterExpStart" type="date"></div>
<div><label for="filterExpEnd">إلى تاريخ</label><input id="filterExpEnd" type="date"></div>
</div>
<div class="sales-report-actions"><button id="printExpensesReport" type="button">🖨️ طباعة تقرير المصروفات مع الإجماليات</button></div>
<div class="sales-report-summary">
<div class="sales-report-stat"><span>إجمالي مصروفات يمني</span><strong id="expTotalYER">0</strong></div>
<div class="sales-report-stat"><span>إجمالي مصروفات سعودي</span><strong id="expTotalSAR">0</strong></div>
</div>
<div id="expensesTableContainer" style="margin-top:15px"><div class="sales-report-empty">لا توجد مصروفات مسجلة بعد.</div></div>
</div>
</div>

<!-- شاشة قسم العمرة والحج -->
<div class="alamin-drawer no-print" id="umrahDrawer">
<div class="drawer-top"><h2>🕋 قسم العمرة والحج والزيارات</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<div class="sales-report">
<h2>تسجيل حجوزات وبرامج العمرة والزيارات</h2>
<p>سجل بيانات المعتمرين والزوار وحجوزاتهم لترتبط تلقائياً بالصندوق العام.</p>
<div class="alamin-section" style="margin-top:10px;background:#fff">
<div class="alamin-row">
<div class="alamin-field"><label>📅 تاريخ التسجيل <span class="required">*</span></label><input id="umrahDate" type="date"></div>
<div class="alamin-field"><label>👤 اسم المعتمر / الزائر / الزبون <span class="required">*</span></label><input id="umrahPassenger" placeholder="اسم المسافر الكامل"></div>
</div>
<div class="alamin-row">
<div class="alamin-field"><label>🛂 رقم الجواز <span class="required">*</span></label><input id="umrahPassport" maxlength="8" placeholder="رقم الجواز"></div>
<div class="alamin-field"><label>📱 رقم الجوال <span class="required">*</span></label><input id="umrahPhone" placeholder="رقم الهاتف"></div>
</div>
<div class="alamin-row">
<div class="alamin-field"><label>🕋 الحملة أو البرنامج <span class="required">*</span></label><input id="umrahCampaign" placeholder="مثل: حملة النور، برنامج عمرة، زيارات..."></div>
<div class="alamin-field"><label>💰 سعر الحجز <span class="required">*</span></label><input id="umrahPrice" type="number" min="0" step="any" placeholder="المبلغ الإجمالي"></div>
</div>
<div class="alamin-row">
<div class="alamin-field"><label>💱 عملة السعر <span class="required">*</span></label><select id="umrahCurrency"><option value="YER">ريال يمني</option><option value="SAR">ريال سعودي</option></select></div>
<div class="alamin-field"><label>💳 حالة السداد <span class="required">*</span></label><select id="umrahPayment"><option value="تم السداد">تم السداد بالكامل</option><option value="دفع جزئي / آجل">دفع جزئي أو آجل</option></select></div>
</div>
<div class="alamin-field"><label>📝 ملاحظات البرنامج</label><textarea id="umrahNotes" placeholder="تفاصيل التأشيرة، الفندق، أو النقل"></textarea></div>
<button id="saveUmrahBtn" class="primary-btn" type="button" style="margin-top:5px">➕ حفظ وتسجيل حجز العمرة والزيارات</button>
</div>
<div class="sales-report-filters" style="margin-top:20px">
<div><label for="filterUStart">من تاريخ</label><input id="filterUStart" type="date"></div>
<div><label for="filterUEnd">إلى تاريخ</label><input id="filterUEnd" type="date"></div>
</div>
<div class="sales-report-actions"><button id="printUmrahReport" type="button">🖨️ طباعة تقرير العمرة والزيارات</button></div>
<div class="sales-report-summary">
<div class="sales-report-stat"><span>عدد حجوزات العمرة والزيارات</span><strong id="umrahCount">0</strong></div>
<div class="sales-report-stat"><span>إجمالي يمني (عمرة)</span><strong id="umrahTotalYER">0</strong></div>
<div class="sales-report-stat"><span>إجمالي سعودي (عمرة)</span><strong id="umrahTotalSAR">0</strong></div>
</div>
<div id="umrahTableContainer" style="margin-top:15px"><div class="sales-report-empty">لا توجد حجوزات عمرة أو زيارات مسجلة بعد.</div></div>
</div>
</div>

<!-- شاشة سندات القبض والصرف النقدية العامة -->
<div class="alamin-drawer no-print" id="vouchersDrawer">
<div class="drawer-top"><h2>🧾 السندات النقدية العامة</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<div class="sales-report">
<h2>إصدار سند قبض أو سند صرف نقدي</h2>
<p>تسجيل الإيرادات والمصروفات النقدية العامة غير المرتبطة بالتذاكر والعمرة.</p>
<div class="alamin-section" style="margin-top:10px;background:#fff">
<div class="alamin-row">
<div class="alamin-field"><label>📑 نوع السند <span class="required">*</span></label><select id="vType"><option value="قبض">سند قبض (إيراد وارد)</option><option value="صرف">سند صرف (مصروف صادر)</option></select></div>
<div class="alamin-field"><label>📅 التاريخ <span class="required">*</span></label><input id="vDate" type="date"></div>
</div>
<div class="alamin-row">
<div class="alamin-field"><label>👤 اسم المستفيد / الدافع <span class="required">*</span></label><input id="vParty" placeholder="اسم الشخص أو الجهة"></div>
<div class="alamin-field"><label>💰 المبلغ <span class="required">*</span></label><input id="vAmount" type="number" min="0" step="any" placeholder="اكتب المبلغ"></div>
</div>
<div class="alamin-row">
<div class="alamin-field"><label>💱 العملة <span class="required">*</span></label><select id="vCurrency"><option value="YER">ريال يمني</option><option value="SAR">ريال سعودي</option></select></div>
<div class="alamin-field"><label>🏷️ البيان / السبب <span class="required">*</span></label><input id="vReason" placeholder="مثل: دفع إيجار المكتب، سلفة موظف..."></div>
</div>
<div class="alamin-field"><label>📝 ملاحظات إضافية</label><textarea id="vNotes" placeholder="أي تفاصيل أخرى"></textarea></div>
<button id="saveVoucherBtn" class="primary-btn" type="button" style="margin-top:5px">➕ حفظ وإصدار السند</button>
</div>
<div class="sales-report-filters" style="margin-top:20px">
<div><label for="filterVStart">من تاريخ</label><input id="filterVStart" type="date"></div>
<div><label for="filterVEnd">إلى تاريخ</label><input id="filterVEnd" type="date"></div>
</div>
<div class="sales-report-actions"><button id="printVouchersReport" type="button">🖨️ طباعة تقرير السندات</button></div>
<div class="sales-report-summary">
<div class="sales-report-stat"><span>إجمالي مقبوضات يمني</span><strong id="vTotRecYER" style="color:#155b20">0</strong></div>
<div class="sales-report-stat"><span>إجمالي مقبوضات سعودي</span><strong id="vTotRecSAR" style="color:#155b20">0</strong></div>
<div class="sales-report-stat"><span>إجمالي مدفوعات يمني</span><strong id="vTotPayYER" style="color:#b00000">0</strong></div>
<div class="sales-report-stat"><span>إجمالي مدفوعات سعودي</span><strong id="vTotPaySAR" style="color:#b00000">0</strong></div>
</div>
<div id="vouchersTableContainer" style="margin-top:15px"><div class="sales-report-empty">لا توجد سندات مسجلة بعد.</div></div>
</div>
</div>

<!-- شاشة إدارة المستخدمين والصلاحيات وتعديل بيانات المالك -->
<div class="alamin-drawer no-print" id="usersDrawer">
<div class="drawer-top"><h2>👥 شؤون الموظفين والصلاحيات</h2><button class="drawer-close" type="button" data-close-drawer>✖ إغلاق</button></div>
<div class="sales-report">
<div class="alamin-section" style="margin-top:10px;background:#fff;border:2px solid #b00000">
<h3 style="color:#b00000;margin-bottom:12px">⚙️ تعديل بيانات حساب المالك (اسم المستخدم وكلمة المرور)</h3>
<p style="color:#555;font-size:14px;margin-bottom:15px">يمكنك هنا تغيير اسم المستخدم وكلمة المرور الخاصة بك كمدير ومالك للنظام.</p>
<div class="alamin-row">
<div class="alamin-field"><label>👤 اسم المستخدم الجديد للمالك <span class="required">*</span></label><input id="ownerNewUsername" placeholder="اكتب اسم المستخدم الجديد"></div>
<div class="alamin-field"><label>🔑 كلمة المرور الجديدة للمالك <span class="required">*</span></label><input id="ownerNewPassword" type="password" placeholder="اكتب كلمة المرور الجديدة"></div>
</div>
<button id="saveOwnerSettingsBtn" class="primary-btn" type="button">💾 حفظ وتحديث بيانات المالك</button>
</div>

<h2 style="margin-top:25px">إنشاء حساب موظف جديد وتحديد صلاحياته</h2>
<p>قم بإضافة اسم مستخدم وكلمة مرور للموظف، وحدد الأقسام التي يمكنه الوصول إليها.</p>
<div class="alamin-section" style="margin-top:10px;background:#fff">
<div class="alamin-row">
<div class="alamin-field"><label>👤 اسم مستخدم الموظف <span class="required">*</span></label><input id="newUsername" placeholder="مثال: ali_travel"></div>
<div class="alamin-field"><label>🔑 كلمة مرور الموظف <span class="required">*</span></label><input id="newPassword" type="password" placeholder="كلمة المرور للموظف"></div>
</div>
<div class="alamin-field"><label>🏷️ اسم الموظف أو العضو <span class="required">*</span></label><input id="newFullName" placeholder="الاسم الكامل"></div>
<div style="margin:20px 0;background:#f9f9f9;padding:15px;border-radius:10px">
<h3 style="color:#b00000;margin-bottom:12px">صلاحيات النظام للموظف:</h3>
<div class="permission-checkbox"><input type="checkbox" id="permSales" checked> <span>عرض تقارير المبيعات</span></div>
<div class="permission-checkbox"><input type="checkbox" id="permFinancial"> <span>الصندوق العام والخزنة</span></div>
<div class="permission-checkbox"><input type="checkbox" id="permExpenses"> <span>إدارة وتسجيل المصروفات اليومية</span></div>
<div class="permission-checkbox"><input type="checkbox" id="permUmrah" checked> <span>قسم العمرة والحج</span></div>
<div class="permission-checkbox"><input type="checkbox" id="permVouchers"> <span>سندات القبض والصرف</span></div>
<div class="permission-checkbox"><input type="checkbox" id="permDelete"> <span>حذف التذاكر أو السجلات</span></div>
</div>
<button id="saveNewUserBtn" class="primary-btn" type="button">➕ حفظ وإنشاء حساب الموظف</button>
</div>
<h3 style="color:#b00000;margin-top:25px">قائمة الموظفين المسجلين</h3>
<div id="usersListContainer" style="margin-top:15px"><div class="sales-report-empty">لا توجد حسابات إضافية مسجلة بعد.</div></div>
</div>
</div>

<div class="alamin-booking" id="alaminBooking">

<!-- الترويسة الإدارية الرسمية الفخمة -->
<div class="alamin-enterprise-header">
<div class="alamin-brand-box">
<div class="alamin-brand-logo">
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiu3TtYlgT73xNqR8L4QMrRacAhPWSuGbcuQhbkjk6aNRK58PNfKwk_1VGsNGrlTmWJ6_4-ChXPMI2-Bx0sziJ9glcpAUQgED9MAXozV13omWclxgAIHwC5CJwtH2Bv9nKBgkVkMLvMSCkleJ4zt9vCCqRoqQopo7doJl8Mx9VzL8WvcfI8zC2LiQJXyTs/s1254/1001145304.png" alt="شعار الأمين">
</div>
<div class="alamin-brand-title">
<h1>حجز تذاكر <span>الأمين للسفريات</span></h1>
<p>وخدمات الحج والعمرة - النظام الإداري الموحد</p>
</div>
</div>
<!-- الأرقام الثلاثة في أقصى اليسار -->
<div class="alamin-top-contacts">
<span class="c-label">أرقام التواصل المعتمدة</span>
<div class="c-numbers">777818186 - 737108450 - 713680004</div>
</div>
</div>

<!-- شريط الأيقونات والأقسام الاحترافي -->
<div class="alamin-top-navbar no-print">
<button type="button" id="openArchive"><span>🎫</span> أرشيف التذاكر</button>
<button type="button" id="openSalesDrawer"><span>📊</span> تقارير المبيعات</button>
<button type="button" id="openFinancialDrawer"><span>💰</span> الخزينة والصندوق</button>
<button type="button" id="openExpensesDrawer"><span>💸</span> النثريات والمصروفات</button>
<button type="button" id="openUmrahDrawer"><span>🕋</span> العمرة والزيارات</button>
<button type="button" id="openVouchersDrawer"><span>🧾</span> السندات النقدية</button>
<button type="button" id="openUsersDrawer" style="background:#1769aa;display:none"><span>👥</span> إدارة الموظفين</button>
</div>

<!-- التواصل المباشر -->
<a class="direct-whatsapp" href="https://wa.me/967777818186" target="_blank" rel="noopener">💬 التواصل المباشر عبر واتساب (خدمة العملاء)</a>

<div id="busService">
<form id="busForm">
<div class="alamin-section"><h2>🚌 تفاصيل رحلة الباص</h2><div class="alamin-row">
<div class="alamin-field"><label>📍 من <span class="required">*</span></label><select id="busFrom" required><option value="">اختر مدينة المغادرة</option><option>تعز</option><option>تعز المدينة</option><option>صنعاء</option><option>عدن</option><option>إب</option><option>ذمار</option><option>الحديدة</option><option>مأرب</option><option>لحج</option><option>أبين</option><option>شبوة</option><option>حضرموت</option><option>الرياض</option><option>جدة</option><option>مكة المكرمة</option><option>المدينة المنورة</option><option>الطائف</option><option>خميس مشيط</option><option>أبها</option><option>جيزان</option><option>نجران</option><option>الدمام</option><option>أخرى</option></select></div>
<div class="alamin-field"><label>📍 إلى <span class="required">*</span></label><select id="busTo" required><option value="">اختر الوجهة</option><option>الرياض</option><option>جدة</option><option>مكة المكرمة</option><option>المدينة المنورة</option><option>الطائف</option><option>خميس مشيط</option><option>أبها</option><option>جيزان</option><option>نجران</option><option>الدمام</option><option>تعز</option><option>تعز المدينة</option><option>صنعاء</option><option>عدن</option><option>إب</option><option>ذمار</option><option>الحديدة</option><option>مأرب</option><option>لحج</option><option>أبين</option><option>شبوة</option><option>حضرموت</option><option>أخرى</option></select></div></div>
<div class="alamin-field"><label>🚌 الشركة الناقلة <span class="required">*</span></label><select id="busCompany" required><option value="">اختر الشركة الناقلة</option><option>باصات المتصدر</option><option>باصات البركة</option><option>باصات سماء حراء</option><option>باصات نجمة المسافر</option><option>باصات ترحيب</option><option>باصات صقور</option><option>باصات الأفضل</option></select></div></div>

<div class="alamin-section"><h2>🎫 بيانات التذكرة والمسافر</h2>
<div class="alamin-row"><div class="alamin-field"><label>رقم التذكرة</label><input class="ticket-number" id="busTicketNumber" readonly value=""></div><div class="alamin-field"><label>👤 اسم المسافر <span class="required">*</span></label><input id="busPassenger" placeholder="اكتب الاسم الكامل" required></div></div>
<div class="alamin-row"><div class="alamin-field"><label>🛂 رقم الجواز <span class="required">*</span></label><input id="busPassport" maxlength="8" pattern="[0-9]{8}" required></div><div class="alamin-field"><label>📱 رقم الجوال <span class="required">*</span></label><input id="busPhone" maxlength="9" pattern="[0-9]{9}" required type="tel"></div></div>
<div class="alamin-row"><div class="alamin-field"><label>⚧ الجنس <span class="required">*</span></label><select id="busGender" required><option value="">اختر الجنس</option><option>ذكر</option><option>أنثى</option></select></div><div class="alamin-field"><label>📍 مكان الميلاد <span class="required">*</span></label><input id="busBirthPlace" required></div></div>
<div class="alamin-row"><div class="alamin-field"><label>🎂 تاريخ الميلاد <span class="required">*</span></label><input id="busBirthDate" type="date" required></div><div class="alamin-field"><label>🛂 تاريخ إصدار الجواز <span class="required">*</span></label><input id="busPassportIssueDate" type="date" required></div></div>
<div class="alamin-row"><div class="alamin-field"><label>📅 تاريخ الرحلة <span class="required">*</span></label><input id="busDate" type="date" required></div><div class="alamin-field"><label>🕐 وقت الحضور <span class="required">*</span></label><input id="busArrival" type="time" required></div></div>
<div class="alamin-row"><div class="alamin-field"><label>🕐 وقت الرحلة</label><input id="busTripTime" type="time"></div><div class="alamin-field"><label>💺 رقم المقعد</label><input id="busSeat" placeholder="رقم المقعد إن وجد"></div></div>
<div class="alamin-row"><div class="alamin-field"><label>💰 السعر <span class="required">*</span></label><input id="busPrice" placeholder="اكتب السعر" required type="number" min="0"></div><div class="alamin-field"><label>💱 عملة السعر <span class="required">*</span></label><select id="busCurrency" required><option value="YER">ريال يمني</option><option value="SAR">ريال سعودي</option></select></div></div>
<div class="alamin-field"><label>🚌 نوع التذكرة</label><select id="busTicketType"><option value="VIP">VIP</option><option value="عادي">عادي</option></select></div>
<div class="alamin-field"><label>📝 ملاحظات</label><textarea id="busNotes" placeholder="اكتب أي ملاحظات تخص الحجز أو المسافر"></textarea></div></div>
<div class="alamin-section"><h2>💳 الدفع</h2><div class="payment-box"><label class="payment-option"><input name="busPayment" required type="radio" value="تم السداد"> تم السداد</label><label class="payment-option"><input name="busPayment" type="radio" value="سيتم السداد"> سيتم السداد</label></div><div class="notice" style="margin-top:12px">يُسجّل الحجز مرة واحدة عند إصدار التذكرة. تغيير حالة الدفع لا ينشئ حجزًا أو مبلغًا جديدًا.</div></div>
<button class="primary-btn" type="submit">🎫 مراجعة وتأكيد حجز التذكرة</button>
</form>

<div class="review-box" id="busReview"><h3>🔎 مراجعة بيانات التذكرة</h3><div id="busReviewContent"></div><button class="whatsapp-btn" id="sendBusWhatsApp" type="button">📲 تأكيد الحجز وإرسال الطلب عبر واتساب</button><button class="print-btn" id="showBusTicket" type="button">🎫 إصدار التذكرة</button></div>

<div class="alamin-ticket-wrapper" id="alaminTicketWrapper"><div class="bus-ticket" id="ticketMainContainer">
<div class="ticket-header"><div class="ticket-logo"><img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiu3TtYlgT73xNqR8L4QMrRacAhPWSuGbcuQhbkjk6aNRK58PNfKwk_1VGsNGrlTmWJ6_4-ChXPMI2-Bx0sziJ9glcpAUQgED9MAXozV13omWclxgAIHwC5CJwtH2Bv9nKBgkVkMLvMSCkleJ4zt9vCCqRoqQopo7doJl8Mx9VzL8WvcfI8zC2LiQJXyTs/s1254/1001145304.png" alt="شعار الأمين للسفريات والسياحة"></div><div class="company-title"><h3>الأمين للسفريات والسياحة</h3><p>وخدمات الحج والعمرة</p></div><div class="ticket-qr-area"><div class="qr-box" id="ticketQR">QR<br>رمز الحجز</div><div class="ticket-number-head" id="ticketHeaderNumber"><span>رقم التذكرة</span>-</div></div></div>
<div class="ticket-badge vip" id="ticketBadgeType">تذكرة سفر سياحي (VIP)</div>
<div class="ticket-grid">
<div class="grid-item"><span>اسم المسافر</span><strong id="t-passenger-name">-</strong></div><div class="grid-item"><span>رقم التذكرة</span><strong id="t-ticket-no">-</strong></div><div class="grid-item"><span>رقم الجواز</span><strong id="t-passport">-</strong></div><div class="grid-item"><span>رقم الجوال</span><strong id="t-phone">-</strong></div><div class="grid-item"><span>الجنس</span><strong id="t-gender">-</strong></div>
<div class="grid-item"><span>تاريخ الميلاد</span><strong id="t-birth-date">-</strong></div><div class="grid-item"><span>مكان الميلاد</span><strong id="t-birth-place">-</strong></div><div class="grid-item"><span>إصدار الجواز</span><strong id="t-passport-issue">-</strong></div><div class="grid-item"><span>خط الرحلة</span><strong><span id="t-from" style="display:inline">-</span> ← <span id="t-to" style="display:inline">-</span></strong></div><div class="grid-item"><span>الشركة الناقلة</span><strong id="t-company">-</strong></div>
<div class="grid-item"><span>تاريخ الرحلة</span><strong id="t-trip-date">-</strong></div><div class="grid-item"><span>يوم الرحلة</span><strong id="t-day">-</strong></div><div class="grid-item"><span>وقت الرحلة</span><strong id="t-time">-</strong></div><div class="grid-item"><span>وقت الحضور</span><strong id="t-attendance">-</strong></div><div class="grid-item"><span>المقعد</span><strong id="t-seat">-</strong></div>
<div class="grid-item"><span>السعر</span><strong id="t-price">-</strong></div><div class="grid-item"><span>حالة الدفع</span><strong id="t-payment">-</strong></div><div class="grid-item"><span>العنوان</span><strong>اليمن، تعز، مفرق الذكرة، بداية شارع الستين</strong></div><div class="grid-item"><span>الوكيل</span><strong>الوكيل الأمين للسفريات والسياحة</strong></div><div class="grid-item"><span>تاريخ الإصدار</span><strong id="t-issue-date">-</strong></div></div>
<div class="ticket-notes"><span class="ticket-notes-title">📝 ملاحظات</span><div class="ticket-notes-content" id="t-notes">لا توجد ملاحظات</div></div>
<div class="ticket-bottom-notice">يرجى الحضور إلى نقطة التجمع قبل موعد الرحلة بوقت كافٍ والتأكد من صحة جميع بيانات التذكرة قبل السفر.<br>التذكرة شخصية ويجب إبرازها مع الوثائق المطلوبة عند السفر.</div>

<!-- الأرقام الثلاثة كاملة في ذيل التذكرة -->
<div class="branches-footer"><strong>العنوان:</strong> اليمن، تعز، مفرق الذكرة، بداية شارع الستين<br><strong>أرقام التواصل:</strong> 777818186 - 737108450 - 713680004<br><strong>خدمة العملاء:</strong> 777818186<br>تم الإصدار بواسطة: الوكيل الأمين للسفريات والسياحة - نظام حجز الباصات الإلكتروني</div>
</div><button class="print-btn no-print" id="downloadTicketPDF" type="button">📥 تحميل التذكرة PDF</button><button class="print-btn no-print" id="printTicket" type="button">🖨️ طباعة التذكرة</button></div>
</div>
<div class="success" id="successMessage">تم تجهيز الطلب بنجاح. سيتم فتح واتساب لإرسال الطلب.</div>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script>
(function(){
"use strict";
var LOGO="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiu3TtYlgT73xNqR8L4QMrRacAhPWSuGbcuQhbkjk6aNRK58PNfKwk_1VGsNGrlTmWJ6_4-ChXPMI2-Bx0sziJ9glcpAUQgED9MAXozV13omWclxgAIHwC5CJwtH2Bv9nKBgkVkMLvMSCkleJ4zt9vCCqRoqQopo7doJl8Mx9VzL8WvcfI8zC2LiQJXyTs/s1254/1001145304.png";

var usersStorageKey="alamin_system_users_v5";
function getDefaultUsers(){
return [{username:"الأمين للسفريات والسياحة",password:"1165",fullName:"مدير النظام (المالك)",isAdmin:true,permissions:{sales:true,financial:true,expenses:true,umrah:true,vouchers:true,delete:true}}];
}
function getUsers(){try{var u=JSON.parse(localStorage.getItem(usersStorageKey));if(Array.isArray(u)&&u.length){return u;}return getDefaultUsers();}catch(e){return getDefaultUsers();}}
function setUsers(arr){localStorage.setItem(usersStorageKey,JSON.stringify(arr));}

var currentUser=null;
var loginGate=document.getElementById("alaminLoginGate"),usernameInput=document.getElementById("alaminLoginUsername"),passwordInput=document.getElementById("alaminLoginPassword"),loginError=document.getElementById("alaminLoginError");

function attemptLogin(){
var uName=usernameInput.value.trim().toLowerCase(),pass=passwordInput.value;
var users=getUsers();
var found=users.find(function(u){return u.username.toLowerCase()===uName&&u.password===pass;});
if(!found){
loginError.textContent="اسم المستخدم أو كلمة المرور غير صحيحة.";
loginError.style.display="block";
passwordInput.value="";
return;
}
currentUser=found;
loginGate.style.display="none";
applyPermissionsUI();
}
document.getElementById("alaminLoginButton").addEventListener("click",attemptLogin);
passwordInput.addEventListener("keydown",function(e){if(e.key==="Enter")attemptLogin();});
usernameInput.addEventListener("keydown",function(e){if(e.key==="Enter")passwordInput.focus();});

function applyPermissionsUI(){
if(!currentUser)return;
var btnSales=document.getElementById("openSalesDrawer");
var btnFin=document.getElementById("openFinancialDrawer");
var btnExp=document.getElementById("openExpensesDrawer");
var btnUmrah=document.getElementById("openUmrahDrawer");
var btnVouch=document.getElementById("openVouchersDrawer");
var btnUsers=document.getElementById("openUsersDrawer");

if(currentUser.isAdmin){
if(btnSales)btnSales.style.display="flex";
if(btnFin)btnFin.style.display="flex";
if(btnExp)btnExp.style.display="flex";
if(btnUmrah)btnUmrah.style.display="flex";
if(btnVouch)btnVouch.style.display="flex";
if(btnUsers)btnUsers.style.display="flex";
}else{
var p=currentUser.permissions||{};
if(btnSales)btnSales.style.display=p.sales?"flex":"none";
if(btnFin)btnFin.style.display=p.financial?"flex":"none";
if(btnExp)btnExp.style.display=p.expenses?"flex":"none";
if(btnUmrah)btnUmrah.style.display=p.umrah?"flex":"none";
if(btnVouch)btnVouch.style.display=p.vouchers?"flex":"none";
if(btnUsers)btnUsers.style.display="none";
}
}

var whatsappNumber="967777818186",ticketKey="rihlati_next_ticket_number",startingTicketNumber=202211,issuedRecordsKey="alamin_issued_bus_tickets_v1",issuedTicketNumber="",currentBookingTicket="",archiveViewMode=false;
document.getElementById("busTicketNumber").value="";
function val(id){var e=document.getElementById(id);return e?e.value.trim():""}
function payment(){var e=document.querySelector('input[name="busPayment"]:checked');return e?e.value:"غير محدد"}
function currency(){return val("busCurrency")||"YER"}
function currencyName(c){return c==="SAR"?"ريال سعودي":"ريال يمني"}
function priceWithCurrency(price,c){return (price==null||price==="")?"-":Number(price).toLocaleString("en-US",{maximumFractionDigits:2})+" "+currencyName(c||"YER")}

/* تحويل الوقت تلقائياً إلى نظام 12 ساعة مع كتابة ص أو م */
function fmtTime(v){
if(!v)return "";
var m=/^([0-9]{1,2}):([0-9]{2})$/.exec(v);
if(!m)return v;
var hours=parseInt(m[1],10);
var minutes=m[2];
var suffix=hours>=12?"م":"ص";
hours=hours%12;
if(hours===0)hours=12;
return String(hours).padStart(2,"0")+":"+minutes+" "+suffix;
}

function getIssueDate(){var d=new Date();return String(d.getDate()).padStart(2,"0")+"/"+String(d.getMonth()+1).padStart(2,"0")+"/"+d.getFullYear()}
function getISODate(){var d=new Date();return d.getFullYear()+"-"+String(d.getMonth()+1).padStart(2,"0")+"-"+String(d.getDate()).padStart(2,"0")}
function escapeHTML(v){return String(v==null?"":v).replace(/[&<>"']/g,function(c){return {"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]})}
function getRecords(){try{var a=JSON.parse(localStorage.getItem(issuedRecordsKey)||"[]");return Array.isArray(a)?a:[]}catch(e){return []}}
function setRecords(a){localStorage.setItem(issuedRecordsKey,JSON.stringify(a))}

var expensesStorageKey="alamin_daily_expenses_v1";
function getExpenses(){try{var x=JSON.parse(localStorage.getItem(expensesStorageKey)||"[]");return Array.isArray(x)?x:[]}catch(e){return []}}
function setExpenses(arr){localStorage.setItem(expensesStorageKey,JSON.stringify(arr))}

var umrahStorageKey="alamin_umrah_bookings_v1";
function getUmrah(){try{var u=JSON.parse(localStorage.getItem(umrahStorageKey)||"[]");return Array.isArray(u)?u:[]}catch(e){return []}}
function setUmrah(arr){localStorage.setItem(umrahStorageKey,JSON.stringify(arr))}

var vouchersStorageKey="alamin_general_vouchers_v1";
function getVouchers(){try{var v=JSON.parse(localStorage.getItem(vouchersStorageKey)||"[]");return Array.isArray(v)?v:[]}catch(e){return []}}
function setVouchers(arr){localStorage.setItem(vouchersStorageKey,JSON.stringify(arr))}

function nextTicket(){var n=parseInt(localStorage.getItem(ticketKey),10);if(!Number.isFinite(n)||n<startingTicketNumber)n=startingTicketNumber;localStorage.setItem(ticketKey,String(n+1));issuedTicketNumber=String(n);document.getElementById("busTicketNumber").value=issuedTicketNumber;return issuedTicketNumber}
function validateNumbers(){if(!/^[0-9]{8}$/.test(val("busPassport"))){alert("يرجى إدخال رقم الجواز كاملًا.");document.getElementById("busPassport").focus();return false}if(!/^[0-9]{9}$/.test(val("busPhone"))){alert("يرجى إدخال رقم الجوال كاملًا.");document.getElementById("busPhone").focus();return false}if(val("busPrice")===""||Number(val("busPrice"))<0){alert("يرجى إدخال سعر صحيح.");document.getElementById("busPrice").focus();return false}return true}
document.getElementById("busPassport").addEventListener("input",function(){this.value=this.value.replace(/\D/g,"").slice(0,8)});
document.getElementById("busPhone").addEventListener("input",function(){this.value=this.value.replace(/\D/g,"").slice(0,9)});
document.getElementById("busDate").min=getISODate();
document.getElementById("busDate").addEventListener("change",function(){var d=this.value?new Date(this.value+"T00:00:00"):null;var days=["الأحد","الاثنين","الثلاثاء","الأربعاء","الخميس","الجمعة","السبت"];window.busDayValue=d?days[d.getDay()]:""});

function makeRecord(ticket,oldRecord){
return {ticket:String(ticket),issueDate:oldRecord&&oldRecord.issueDate?oldRecord.issueDate:getISODate(),issueDateDisplay:oldRecord&&oldRecord.issueDateDisplay?oldRecord.issueDateDisplay:getIssueDate(),passenger:val("busPassenger"),passport:val("busPassport"),phone:val("busPhone"),gender:val("busGender"),birthDate:val("busBirthDate"),birthPlace:val("busBirthPlace"),passportIssueDate:val("busPassportIssueDate"),from:val("busFrom"),to:val("busTo"),company:val("busCompany"),tripDate:val("busDate"),day:window.busDayValue||oldRecord&&oldRecord.day||"",tripTime:fmtTime(val("busTripTime"))||"غير محدد",arrival:fmtTime(val("busArrival"))||"غير محدد",seat:val("busSeat")||"غير محدد",price:val("busPrice"),currency:currency(),payment:payment(),ticketType:val("busTicketType"),notes:val("busNotes")||"لا توجد ملاحظات",carrierPaid:oldRecord&&oldRecord.carrierPaid!==undefined?oldRecord.carrierPaid:"",isLocked:oldRecord&&oldRecord.isLocked?true:false}}
function updateSavedTicketPayment(){
if(!currentBookingTicket)return;
var a=getRecords(),i=a.findIndex(function(r){return String(r.ticket)===String(currentBookingTicket)});
if(i<0)return;
a[i].payment=payment();
try{setRecords(a)}catch(e){alert("تعذر تحديث حالة الدفع في المتصفح.");return}
renderSales();renderArchive();renderFinancial();
if(!archiveViewMode){document.getElementById("t-payment").textContent=a[i].payment}
}
function saveTicket(record){
var a=getRecords(),i=a.findIndex(function(r){return String(r.ticket)===String(record.ticket)});
if(i>=0){
var old=a[i];
record.issueDate=old.issueDate||record.issueDate;record.issueDateDisplay=old.issueDateDisplay||record.issueDateDisplay;
record.carrierPaid=old.carrierPaid!==undefined?old.carrierPaid:"";
record.isLocked=old.isLocked?true:false;
a[i]=record;
}else{a.push(record)}
try{setRecords(a)}catch(e){alert("تعذر حفظ سجل التذكرة في المتصفح.");return false}
renderSales();renderArchive();renderFinancial();return true
}
function loadTicket(record){
var map={"t-passenger-name":"passenger","t-ticket-no":"ticket","t-passport":"passport","t-phone":"phone","t-gender":"gender","t-birth-date":"birthDate","t-birth-place":"birthPlace","t-passport-issue":"passportIssueDate","t-from":"from","t-to":"to","t-company":"company","t-trip-date":"tripDate","t-day":"day","t-time":"tripTime","t-attendance":"arrival","t-seat":"seat","t-payment":"payment","t-issue-date":"issueDateDisplay","t-notes":"notes"};
Object.keys(map).forEach(function(id){document.getElementById(id).textContent=record[map[id]]||"-"});
document.getElementById("t-price").textContent=priceWithCurrency(record.price,record.currency);
document.getElementById("ticketHeaderNumber").innerHTML="<span>رقم التذكرة</span>"+escapeHTML(record.ticket);
var badge=document.getElementById("ticketBadgeType");badge.className="ticket-badge "+(record.ticketType==="VIP"?"vip":"normal");badge.textContent=record.ticketType==="VIP"?"تذكرة سفر سياحي (VIP)":"تذكرة سفر (عادي)";
var qr="الأمين للسفريات والسياحة\nرقم التذكرة: "+record.ticket+"\nالمسافر: "+(record.passenger||"")+"\nمن: "+(record.from||"")+"\nإلى: "+(record.to||"")+"\nتاريخ الرحلة: "+(record.tripDate||"")+"\nالسعر: "+priceWithCurrency(record.price,record.currency);
document.getElementById("ticketQR").innerHTML='<img alt="QR Code" src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data='+encodeURIComponent(qr)+'">';
document.getElementById("alaminTicketWrapper").classList.add("active");
}
function fillFormFromRecord(r){
var map={busFrom:"from",busTo:"to",busCompany:"company",busTicketNumber:"ticket",busPassenger:"passenger",busPassport:"passport",busPhone:"phone",busGender:"gender",busBirthPlace:"birthPlace",busBirthDate:"birthDate",busPassportIssueDate:"passportIssueDate",busDate:"tripDate",busTripTime:"tripTime",busArrival:"arrival",busSeat:"seat",busPrice:"price",busCurrency:"currency",busTicketType:"ticketType",busNotes:"notes"};
Object.keys(map).forEach(function(id){var el=document.getElementById(id);if(el)el.value=r[map[id]]==null?"":r[map[id]]});
var radio=document.querySelector('input[name="busPayment"][value="'+(r.payment==="تم السداد"?"تم السداد":"سيتم السداد")+'"]');if(radio)radio.checked=true;
issuedTicketNumber=String(r.ticket);currentBookingTicket=String(r.ticket);window.busDayValue=r.day||"";
}
function getFiltered(){
var s=document.getElementById("salesStartDate").value,e=document.getElementById("salesEndDate").value;
if(s&&e&&s>e){alert("تاريخ البداية يجب أن يكون قبل تاريخ النهاية أو مساويًا له.");return null}
return getRecords().filter(function(r){return (!s||r.issueDate>=s)&&(!e||r.issueDate<=e)}).sort(function(a,b){return (a.issueDate||"").localeCompare(b.issueDate||"")||Number(a.ticket)-Number(b.ticket)})
}
function totals(a){
var yer=0,sar=0;
a.forEach(function(r){var n=Number(r.price)||0;if(r.currency==="SAR")sar+=n;else yer+=n});
return {yer:yer,sar:sar}
}
function numberFormat(n){return (Number(n)||0).toLocaleString("en-US",{maximumFractionDigits:2})}
function renderSales(){
var a=getFiltered();if(a===null)return;
var t=totals(a),target=document.getElementById("salesReportResults");
document.getElementById("salesTicketCount").textContent=a.length;
document.getElementById("salesTotalYER").textContent=numberFormat(t.yer)+" ريال يمني";
document.getElementById("salesTotalSAR").textContent=numberFormat(t.sar)+" ريال سعودي";
document.getElementById("salesTotalAmount").textContent=numberFormat(t.yer)+" يمني / "+numberFormat(t.sar)+" سعودي";
if(!a.length){target.innerHTML='<div class="sales-report-empty">لا توجد تذاكر صادرة في الفترة المحددة.</div>';return}
var h='<div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>رقم التذكرة</th><th>تاريخ الإصدار</th><th>المسافر</th><th>الجواز</th><th>الجوال</th><th>خط الرحلة</th><th>الشركة</th><th>تاريخ الرحلة</th><th>وقت الرحلة</th><th>السعر والعملة</th><th>الدفع</th></tr></thead><tbody>';
a.forEach(function(r){h+="<tr><td>"+escapeHTML(r.ticket)+"</td><td>"+escapeHTML(r.issueDateDisplay||r.issueDate)+"</td><td>"+escapeHTML(r.passenger)+"</td><td>"+escapeHTML(r.passport)+"</td><td>"+escapeHTML(r.phone)+"</td><td>"+escapeHTML("من "+(r.from||"")+" إلى "+(r.to||""))+"</td><td>"+escapeHTML(r.company)+"</td><td>"+escapeHTML(r.tripDate)+"</td><td>"+escapeHTML(r.tripTime)+"</td><td>"+escapeHTML(priceWithCurrency(r.price,r.currency))+"</td><td>"+escapeHTML(r.payment)+"</td></tr>"});
target.innerHTML=h+"</tbody></table></div>"
}
document.getElementById("showSalesReport").addEventListener("click",renderSales);
document.getElementById("salesStartDate").addEventListener("change",renderSales);
document.getElementById("salesEndDate").addEventListener("change",renderSales);

function getFinancialFiltered(){
var s=document.getElementById("financialStartDate").value,e=document.getElementById("financialEndDate").value;
if(s&&e&&s>e){alert("تاريخ البداية يجب أن يكون قبل تاريخ النهاية أو مساويًا له.");return null}
return getRecords().filter(function(r){return (!s||r.issueDate>=s)&&(!e||r.issueDate<=e)}).sort(function(a,b){return (a.issueDate||"").localeCompare(b.issueDate||"")||Number(a.ticket)-Number(b.ticket)})
}

function getFinancialFilteredExpenses(){
var s=document.getElementById("financialStartDate").value,e=document.getElementById("financialEndDate").value;
return getExpenses().filter(function(ex){return (!s||ex.date>=s)&&(!e||ex.date<=e)});
}

function getFinancialFilteredUmrah(){
var s=document.getElementById("financialStartDate").value,e=document.getElementById("financialEndDate").value;
return getUmrah().filter(function(u){return (!s||u.date>=s)&&(!e||u.date<=e)});
}

function getFinancialFilteredVouchers(){
var s=document.getElementById("financialStartDate").value,e=document.getElementById("financialEndDate").value;
return getVouchers().filter(function(v){return (!s||v.date>=s)&&(!e||v.date<=e)});
}

function financeTotals(a){
var t={count:a.length,salesYER:0,salesSAR:0,paidYER:0,paidSAR:0,umrahYER:0,umrahSAR:0,recYER:0,recSAR:0,expYER:0,expSAR:0,payYER:0,paySAR:0,commissionYER:0,commissionSAR:0,netYER:0,netSAR:0};

a.forEach(function(r){
var c=r.currency==="SAR"?"SAR":"YER",price=Number(r.price)||0;
t["sales"+c]+=price;
var hasPaid=r.carrierPaid!==""&&r.carrierPaid!==null&&r.carrierPaid!==undefined;
if(hasPaid){
var paid=Number(r.carrierPaid);
t["paid"+c]+=paid;
t["commission"+c]+=(price-paid);
}
});

var umrahList=getFinancialFilteredUmrah();
umrahList.forEach(function(u){
var c=u.currency==="SAR"?"SAR":"YER",price=Number(u.price)||0;
t["umrah"+c]+=price;
});

var vouchList=getFinancialFilteredVouchers();
vouchList.forEach(function(v){
var c=v.currency==="SAR"?"SAR":"YER",amt=Number(v.amount)||0;
if(v.type==="قبض"){
t["rec"+c]+=amt;
}else{
t["pay"+c]+=amt;
}
});

var expList=getFinancialFilteredExpenses();
expList.forEach(function(ex){
var c=ex.currency==="SAR"?"SAR":"YER";
t["exp"+c]+=Number(ex.amount)||0;
});

t.netYER = (t.salesYER - t.paidYER) + t.umrahYER + t.recYER - (t.expYER + t.payYER);
t.netSAR = (t.salesSAR - t.paidSAR) + t.umrahSAR + t.recSAR - (t.expSAR + t.paySAR);
return t;
}

function renderFinancial(){
var a=getFinancialFiltered();if(a===null)return;
var t=financeTotals(a);

document.getElementById("boxSalesYER").textContent=numberFormat(t.salesYER);
document.getElementById("boxSalesSAR").textContent=numberFormat(t.salesSAR);
document.getElementById("boxPaidYER").textContent=numberFormat(t.paidYER);
document.getElementById("boxPaidSAR").textContent=numberFormat(t.paidSAR);
document.getElementById("boxUmrahYER").textContent=numberFormat(t.umrahYER);
document.getElementById("boxUmrahSAR").textContent=numberFormat(t.umrahSAR);
document.getElementById("boxRecYER").textContent=numberFormat(t.recYER);
document.getElementById("boxRecSAR").textContent=numberFormat(t.recSAR);
document.getElementById("boxCommYER").textContent=numberFormat(t.commissionYER);
document.getElementById("boxCommSAR").textContent=numberFormat(t.commissionSAR);
document.getElementById("boxExpYER").textContent=numberFormat(t.expYER);
document.getElementById("boxExpSAR").textContent=numberFormat(t.expSAR);
document.getElementById("boxPayYER").textContent=numberFormat(t.payYER);
document.getElementById("boxPaySAR").textContent=numberFormat(t.paySAR);

document.getElementById("finNetYER").textContent=numberFormat(t.netYER)+" ريال يمني";
document.getElementById("finNetSAR").textContent=numberFormat(t.netSAR)+" ريال سعودي";

var companies={};
a.forEach(function(r){
var name=r.company||"شركة غير محددة",c=r.currency==="SAR"?"SAR":"YER";
if(!companies[name])companies[name]={YER:{sales:0,paid:0,unpaid:0,commission:0},SAR:{sales:0,paid:0,unpaid:0,commission:0},count:0};
var x=companies[name][c],price=Number(r.price)||0;
var hasPaid=r.carrierPaid!==""&&r.carrierPaid!==null&&r.carrierPaid!==undefined;
x.sales+=price;
if(hasPaid){
var paid=Number(r.carrierPaid);
x.paid+=paid;
x.commission+=(price-paid);
}else{
x.unpaid+=price;
}
companies[name].count++;
});
var cs=document.getElementById("financialCompanySummary");
var names=Object.keys(companies);
if(!names.length){cs.innerHTML="";}else{
var ch='<h3 style="color:#b00000;margin-top:22px">ملخص حساب كل شركة ناقلة</h3><div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>الشركة الناقلة</th><th>عدد التذاكر</th><th>مبيعات يمني</th><th>سداد الشركة يمني</th><th>مديونية غير مسددة يمني</th><th>العمولة يمني</th><th>مبيعات سعودي</th><th>سداد الشركة سعودي</th><th>مديونية غير مسددة سعودي</th><th>العمولة سعودي</th></tr></thead><tbody>';
names.forEach(function(n){var z=companies[n];ch+="<tr><td>"+escapeHTML(n)+"</td><td>"+z.count+"</td><td>"+numberFormat(z.YER.sales)+"</td><td>"+numberFormat(z.YER.paid)+"</td><td style='color:#b00000;font-weight:bold'>"+numberFormat(z.YER.unpaid)+"</td><td>"+numberFormat(z.YER.commission)+"</td><td>"+numberFormat(z.SAR.sales)+"</td><td>"+numberFormat(z.SAR.paid)+"</td><td style='color:#b00000;font-weight:bold'>"+numberFormat(z.SAR.unpaid)+"</td><td>"+numberFormat(z.SAR.commission)+"</td></tr>"});
cs.innerHTML=ch+"</tbody></table></div>"
}
var target=document.getElementById("financialReportResults");
if(!a.length){target.innerHTML='<div class="sales-report-empty">لا توجد تذاكر صادرة في الفترة المحددة.</div>';return}
var h='<div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>رقم التذكرة</th><th>تاريخ الإصدار</th><th>الموظف / المسافر</th><th>الشركة الناقلة</th><th>العملة</th><th>سعر التذكرة (المبيعات)</th><th>سداد الشركة</th><th>العمولة (المبيعات - السداد)</th><th>حالة السداد / المديونية</th><th>حالة الدفع</th><th>حفظ الحساب</th></tr></thead><tbody>';
a.forEach(function(r){
var price=Number(r.price)||0;
var hasPaid=r.carrierPaid!==""&&r.carrierPaid!==null&&r.carrierPaid!==undefined;
var paidVal=hasPaid?r.carrierPaid:"";
var paidNum=hasPaid?Number(r.carrierPaid):0;
var commission=hasPaid?(price-paidNum):0;
var curr=currencyName(r.currency);
var isLocked=r.isLocked?true:false;
var debtStatus=hasPaid?'<span style="color:green;font-weight:bold">تم السداد</span>':'<span style="color:#b00000;font-weight:bold">مديونية (بيد الموظف)</span>';
h+='<tr data-fin-ticket="'+escapeHTML(r.ticket)+'"><td>'+escapeHTML(r.ticket)+'</td><td>'+escapeHTML(r.issueDateDisplay||r.issueDate)+'</td><td>'+escapeHTML(r.passenger||"")+'</td><td>'+escapeHTML(r.company||"")+'</td><td>'+escapeHTML(curr)+'</td><td>'+numberFormat(price)+'</td><td><input class="financial-edit" type="number" min="0" step="any" data-fin-field="carrierPaid" value="'+paidVal+'"'+(isLocked?' disabled style="background:#e9e9e9"':'')+'></td><td style="color:#1769aa;font-weight:bold">'+(hasPaid?numberFormat(commission):"-")+'</td><td>'+debtStatus+'</td><td>'+escapeHTML(r.payment||"غير محدد")+'</td><td><button class="financial-save" type="button" data-fin-save="'+escapeHTML(r.ticket)+'"'+(isLocked?' disabled>🔒 محفوط':'')+'</button></td></tr>'
});
target.innerHTML=h+"</tbody></table></div>"
}
document.getElementById("showFinancialReport").addEventListener("click",renderFinancial);
document.getElementById("financialStartDate").addEventListener("change",renderFinancial);
document.getElementById("financialEndDate").addEventListener("change",renderFinancial);
document.getElementById("financialReportResults").addEventListener("click",function(e){
var b=e.target.closest("[data-fin-save]");if(!b||b.disabled)return;
var ticket=b.getAttribute("data-fin-save"),row=b.closest("tr");if(!row)return;
var paidInput=row.querySelector('[data-fin-field="carrierPaid"]');
var paidStr=paidInput.value.trim();
if(paidStr===""){alert("يرجى إدخال مبلغ سداد الشركة أولاً.");return}
var paid=Number(paidStr);
if(!Number.isFinite(paid)||paid<0){alert("أدخل مبلغاً صحيحاً لا يقل عن صفر.");return}
var a=getRecords(),i=a.findIndex(function(r){return String(r.ticket)===String(ticket)});if(i<0){alert("لم يتم العثور على التذكرة.");return}
var price=Number(a[i].price)||0;
if(paid>price&&!confirm("مبلغ سداد الشركة أكبر من سعر التذكرة الإجمالي. هل تريد الحفظ؟"))return;
a[i].carrierPaid=paid;
a[i].isLocked=true;
try{setRecords(a)}catch(err){alert("تعذر حفظ الحساب المالي في هذا المتصفح.");return}
renderFinancial();alert("تم حفظ سداد الشركة للتذكرة رقم "+ticket+" بنجاح وقفل التعديل.");
});

document.getElementById("expenseDate").value=getISODate();
document.getElementById("vDate").value=getISODate();
document.getElementById("umrahDate").value=getISODate();

function getFilteredExpenses(){
var start=document.getElementById("filterExpStart").value,end=document.getElementById("filterExpEnd").value;
return getExpenses().filter(function(ex){return (!start||ex.date>=start)&&(!end||ex.date<=end)}).sort(function(a,b){return b.date.localeCompare(a.date)});
}

function renderExpenses(){
var arr=getFilteredExpenses();
var sumYER=0,sumSAR=0;
arr.forEach(function(ex){var amt=Number(ex.amount)||0;if(ex.currency==="SAR")sumSAR+=amt;else sumYER+=amt});
document.getElementById("expTotalYER").textContent=numberFormat(sumYER);
document.getElementById("expTotalSAR").textContent=numberFormat(sumSAR);

var container=document.getElementById("expensesTableContainer");
if(!arr.length){container.innerHTML='<div class="sales-report-empty">لا توجد مصروفات مسجلة في الفترة المحددة.</div>';return}
var h='<div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>التاريخ</th><th>البند / البيان</th><th>المبلغ والعملة</th><th>الموظف المسجل</th><th>الملاحظات</th><th>إجراء</th></tr></thead><tbody>';
arr.forEach(function(ex,idx){
var canDel=currentUser.isAdmin||(currentUser.permissions&&currentUser.permissions.delete);
h+='<tr><td>'+escapeHTML(ex.date)+'</td><td>'+escapeHTML(ex.title)+'</td><td>'+escapeHTML(numberFormat(ex.amount)+" "+currencyName(ex.currency))+'</td><td>'+escapeHTML(ex.employee||"-")+'</td><td>'+escapeHTML(ex.notes||"-")+'</td><td>'+(canDel?'<button class="archive-action archive-delete" data-del-expense="'+ex.id+'">🗑 حذف</button>':'-')+'</td></tr>'
});
container.innerHTML=h+'</tbody></table></div>';
}

document.getElementById("saveExpenseBtn").addEventListener("click",function(){
var date=document.getElementById("expenseDate").value,title=document.getElementById("expenseTitle").value.trim(),amount=document.getElementById("expenseAmount").value.trim(),currency=document.getElementById("expenseCurrency").value,employee=document.getElementById("expenseEmployee").value.trim(),notes=document.getElementById("expenseNotes").value.trim();
if(!date||!title||!amount){alert("يرجى تعبئة الحقول الأساسية: تاريخ المصروف، البند، والمبلغ.");return}
var amtNum=Number(amount);if(!Number.isFinite(amtNum)||amtNum<0){alert("يرجى إدخال مبلغ صحيح.");return}
var arr=getExpenses();
arr.push({id:Date.now()+Math.random(),date:date,title:title,amount:amtNum,currency:currency,employee:employee,notes:notes});
try{
setExpenses(arr);
document.getElementById("expenseTitle").value="";
document.getElementById("expenseAmount").value="";
document.getElementById("expenseEmployee").value="";
document.getElementById("expenseNotes").value="";
renderExpenses();
renderFinancial();
alert("تم تسجيل المصروف بنجاح وعكسه على الصندوق.");
}catch(e){alert("تعذر حفظ المصروف.")}
});

document.getElementById("expensesTableContainer").addEventListener("click",function(e){
var btn=e.target.closest("[data-del-expense]");if(!btn)return;
if(!currentUser.isAdmin&&(!currentUser.permissions||!currentUser.permissions.delete)){alert("ليس لديك صلاحية حذف المصروفات.");return;}
var id=btn.getAttribute("data-del-expense");
if(!confirm("هل تريد حذف هذا المصروف؟"))return;
var arr=getExpenses().filter(function(ex){return String(ex.id)!==String(id)});
setExpenses(arr);renderExpenses();renderFinancial();
});

document.getElementById("filterExpStart").addEventListener("change",renderExpenses);
document.getElementById("filterExpEnd").addEventListener("change",renderExpenses);

function getFilteredUmrah(){
var start=document.getElementById("filterUStart").value,end=document.getElementById("filterUEnd").value;
return getUmrah().filter(function(u){return (!start||u.date>=start)&&(!end||u.date<=end)}).sort(function(a,b){return b.date.localeCompare(a.date)});
}

function renderUmrah(){
var arr=getFilteredUmrah();
var totYER=0,totSAR=0;
arr.forEach(function(u){var amt=Number(u.price)||0;if(u.currency==="SAR")totSAR+=amt;else totYER+=amt});
document.getElementById("umrahCount").textContent=arr.length;
document.getElementById("umrahTotalYER").textContent=numberFormat(totYER);
document.getElementById("umrahTotalSAR").textContent=numberFormat(totSAR);

var container=document.getElementById("umrahTableContainer");
if(!arr.length){container.innerHTML='<div class="sales-report-empty">لا توجد حجوزات عمرة أو زيارات في الفترة المحددة.</div>';return}
var h='<div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>التاريخ</th><th>المعتمر / الزائر</th><th>الجواز</th><th>الجوال</th><th>الحملة / البرنامج</th><th>السعر والعملة</th><th>حالة السداد</th><th>ملاحظات</th><th>إجراء</th></tr></thead><tbody>';
arr.forEach(function(u){
var canDel=currentUser.isAdmin||(currentUser.permissions&&currentUser.permissions.delete);
h+='<tr><td>'+escapeHTML(u.date)+'</td><td>'+escapeHTML(u.passenger)+'</td><td>'+escapeHTML(u.passport)+'</td><td>'+escapeHTML(u.phone)+'</td><td>'+escapeHTML(u.campaign)+'</td><td>'+escapeHTML(priceWithCurrency(u.price,u.currency))+'</td><td>'+escapeHTML(u.payment)+'</td><td>'+escapeHTML(u.notes||"-")+'</td><td>'+(canDel?'<button class="archive-action archive-delete" data-del-umrah="'+u.id+'">🗑 حذف</button>':'-')+'</td></tr>';
});
container.innerHTML=h+'</tbody></table></div>';
}

document.getElementById("saveUmrahBtn").addEventListener("click",function(){
var date=document.getElementById("umrahDate").value,passenger=document.getElementById("umrahPassenger").value.trim(),passport=document.getElementById("umrahPassport").value.trim(),phone=document.getElementById("umrahPhone").value.trim(),campaign=document.getElementById("umrahCampaign").value.trim(),price=document.getElementById("umrahPrice").value.trim(),currency=document.getElementById("umrahCurrency").value,payment=document.getElementById("umrahPayment").value,notes=document.getElementById("umrahNotes").value.trim();
if(!date||!passenger||!passport||!phone||!campaign||!price){alert("يرجى ملء جميع الحقول الإجبارية لحجز العمرة والزيارات.");return}
var pNum=Number(price);if(!Number.isFinite(pNum)||pNum<0){alert("يرجى إدخال سعر صحيح.");return}
var arr=getUmrah();
arr.push({id:Date.now()+Math.random(),date:date,passenger:passenger,passport:passport,phone:phone,campaign:campaign,price:pNum,currency:currency,payment:payment,notes:notes});
try{
setUmrah(arr);
document.getElementById("umrahPassenger").value="";
document.getElementById("umrahPassport").value="";
document.getElementById("umrahPhone").value="";
document.getElementById("umrahCampaign").value="";
document.getElementById("umrahPrice").value="";
document.getElementById("umrahNotes").value="";
renderUmrah();
renderFinancial();
alert("تم تسجيل حجز العمرة والزيارات بنجاح وإضافته لصندوق المكتب.");
}catch(e){alert("تعذر حفظ بيانات العمرة والزيارات.")}
});

document.getElementById("umrahTableContainer").addEventListener("click",function(e){
var btn=e.target.closest("[data-del-umrah]");if(!btn)return;
if(!currentUser.isAdmin&&(!currentUser.permissions||!currentUser.permissions.delete)){alert("ليس لديك صلاحية حذف سجلات العمرة.");return;}
var id=btn.getAttribute("data-del-umrah");
if(!confirm("هل تريد حذف هذا السجل؟"))return;
var arr=getUmrah().filter(function(u){return String(u.id)!==String(id)});
setUmrah(arr);renderUmrah();renderFinancial();
});

document.getElementById("filterUStart").addEventListener("change",renderUmrah);
document.getElementById("filterUEnd").addEventListener("change",renderUmrah);

document.getElementById("printUmrahReport").addEventListener("click",function(){
var start=document.getElementById("filterUStart").value,end=document.getElementById("filterUEnd").value;
var arr=getFilteredUmrah();
if(!arr.length){alert("لا توجد سجلات عمرة لطباعتها.");return}
var totYER=0,totSAR=0;
arr.forEach(function(u){var amt=Number(u.price)||0;if(u.currency==="SAR")totSAR+=amt;else totYER+=amt});
var rows=arr.map(function(u){return "<tr><td>"+escapeHTML(u.date)+"</td><td>"+escapeHTML(u.passenger)+"</td><td>"+escapeHTML(u.passport)+"</td><td>"+escapeHTML(u.phone)+"</td><td>"+escapeHTML(u.campaign)+"</td><td>"+escapeHTML(priceWithCurrency(u.price,u.currency))+"</td><td>"+escapeHTML(u.payment)+"</td></tr>"}).join("");
var w=window.open("","_blank");if(!w){alert("يرجى السماح بفتح نافذة الطباعة.");return}
w.document.open();
w.document.write('<!DOCTYPE html><html lang="ar" dir="rtl"><head><meta charset="UTF-8"><title>تقرير حجوزات العمرة والزيارات - الأمين</title><style>body{font-family:Arial,Tahoma,sans-serif;padding:18px;color:#111;direction:rtl}header{text-align:center;border-bottom:2px solid #b00000;padding-bottom:12px;margin-bottom:15px}header img{width:100px;height:80px;object-fit:contain}h1{color:#b00000;font-size:23px;margin:5px}p{text-align:center;line-height:1.8}.summary{display:flex;justify-content:space-around;margin:18px 0;font-weight:bold}.summary div{padding:10px;border:1px solid #ddd;background:#f9f9f9}table{width:100%;border-collapse:collapse;font-size:11px}th,td{border:1px solid #555;padding:7px;text-align:center}th{background:#eee}@media print{body{padding:0}}</style></head><body><header><img src="'+LOGO+'" alt="شعار الأمين"><h1>الأمين للسفريات والسياحة</h1><strong>تقرير حجوزات وبرامج العمرة والزيارات</strong></header><p>الفترة: '+escapeHTML(start||"البداية")+' — '+escapeHTML(end||"اليوم")+'</p><div class="summary"><div>إجمالي يمني: '+numberFormat(totYER)+'</div><div>إجمالي سعودي: '+numberFormat(totSAR)+'</div></div><table><thead><tr><th>التاريخ</th><th>المعتمر / الزائر</th><th>الجواز</th><th>الجوال</th><th>الحملة</th><th>السعر</th><th>حالة السداد</th></tr></thead><tbody>'+rows+'</tbody></table><p style="margin-top:20px;text-align:center">تم استخراج تقرير العمرة والزيارات من نظام الأمين للسفريات والسياحة.</p><script>window.onload=function(){var i=document.querySelector("header img");if(i.complete){window.print()}else{i.onload=function(){window.print()};i.onerror=function(){window.print()}}};<\/script></body></html>');
w.document.close();
});

function getFilteredVouchers(){
var start=document.getElementById("filterVStart").value,end=document.getElementById("filterVEnd").value;
return getVouchers().filter(function(v){return (!start||v.date>=start)&&(!end||v.date<=end)}).sort(function(a,b){return b.date.localeCompare(a.date)});
}

function renderVouchers(){
var arr=getFilteredVouchers();
var totRecYER=0,totRecSAR=0,totPayYER=0,totPaySAR=0;
arr.forEach(function(v){
var amt=Number(v.amount)||0;
if(v.type==="قبض"){
if(v.currency==="SAR")totRecSAR+=amt;else totRecYER+=amt;
}else{
if(v.currency==="SAR")totPaySAR+=amt;else totPayYER+=amt;
}
});
document.getElementById("vTotRecYER").textContent=numberFormat(totRecYER);
document.getElementById("vTotRecSAR").textContent=numberFormat(totRecSAR);
document.getElementById("vTotPayYER").textContent=numberFormat(totPayYER);
document.getElementById("vTotPaySAR").textContent=numberFormat(totPaySAR);

var container=document.getElementById("vouchersTableContainer");
if(!arr.length){container.innerHTML='<div class="sales-report-empty">لا توجد سندات مسجلة في الفترة المحددة.</div>';return}
var h='<div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>رقم السند</th><th>نوع السند</th><th>التاريخ</th><th>المستفيد / الدافع</th><th>المبلغ والعملة</th><th>السبب / البيان</th><th>إجراء</th></tr></thead><tbody>';
arr.forEach(function(v){
var badgeStyle=v.type==="قبض"?"color:#155b20;font-weight:bold":"color:#b00000;font-weight:bold";
var canDel=currentUser.isAdmin||(currentUser.permissions&&currentUser.permissions.delete);
h+='<tr><td>'+escapeHTML(v.id.toString().slice(-6))+'</td><td><span style="'+badgeStyle+'">'+escapeHTML(v.type)+'</span></td><td>'+escapeHTML(v.date)+'</td><td>'+escapeHTML(v.party)+'</td><td>'+escapeHTML(numberFormat(v.amount)+" "+currencyName(v.currency))+'</td><td>'+escapeHTML(v.reason)+'</td><td>'+(canDel?'<button class="archive-action archive-delete" data-del-voucher="'+v.id+'">🗑 حذف</button>':'-')+'</td></tr>';
});
container.innerHTML=h+'</tbody></table></div>';
}

document.getElementById("saveVoucherBtn").addEventListener("click",function(){
var type=document.getElementById("vType").value,date=document.getElementById("vDate").value,party=document.getElementById("vParty").value.trim(),amount=document.getElementById("vAmount").value.trim(),currency=document.getElementById("vCurrency").value,reason=document.getElementById("vReason").value.trim(),notes=document.getElementById("vNotes").value.trim();
if(!date||!party||!amount||!reason){alert("يرجى تعبئة الحقول الأساسية: التاريخ، الطرف، المبلغ، والسبب.");return}
var amtNum=Number(amount);if(!Number.isFinite(amtNum)||amtNum<0){alert("يرجى إدخال مبلغ صحيح.");return}
var arr=getVouchers();
arr.push({id:Date.now()+Math.random(),type:type,date:date,party:party,amount:amtNum,currency:currency,reason:reason,notes:notes});
try{
setVouchers(arr);
document.getElementById("vParty").value="";
document.getElementById("vAmount").value="";
document.getElementById("vReason").value="";
document.getElementById("vNotes").value="";
renderVouchers();
renderFinancial();
alert("تم حفظ وإصدار السند بنجاح وتحديث الصندوق العام.");
}catch(e){alert("تعذر حفظ السند.")}
});

document.getElementById("vouchersTableContainer").addEventListener("click",function(e){
var btn=e.target.closest("[data-del-voucher]");if(!btn)return;
if(!currentUser.isAdmin&&(!currentUser.permissions||!currentUser.permissions.delete)){alert("ليس لديك صلاحية حذف السندات.");return;}
var id=btn.getAttribute("data-del-voucher");
if(!confirm("هل تريد حذف هذا السند؟"))return;
var arr=getVouchers().filter(function(v){return String(v.id)!==String(id)});
setVouchers(arr);renderVouchers();renderFinancial();
});

document.getElementById("filterVStart").addEventListener("change",renderVouchers);
document.getElementById("filterVEnd").addEventListener("change",renderVouchers);

document.getElementById("printVouchersReport").addEventListener("click",function(){
var start=document.getElementById("filterVStart").value,end=document.getElementById("filterVEnd").value;
var arr=getFilteredVouchers();
if(!arr.length){alert("لا توجد سندات لطباعتها.");return}
var rows=arr.map(function(v){return "<tr><td>"+escapeHTML(v.id.toString().slice(-6))+"</td><td>"+escapeHTML(v.type)+"</td><td>"+escapeHTML(v.date)+"</td><td>"+escapeHTML(v.party)+"</td><td>"+escapeHTML(numberFormat(v.amount)+" "+currencyName(v.currency))+"</td><td>"+escapeHTML(v.reason)+"</td></tr>"}).join("");
var w=window.open("","_blank");if(!w){alert("يرجى السماح بفتح نافذة الطباعة.");return}
w.document.open();
w.document.write('<!DOCTYPE html><html lang="ar" dir="rtl"><head><meta charset="UTF-8"><title>تقرير سندات القبض والصرف - الأمين</title><style>body{font-family:Arial,Tahoma,sans-serif;padding:18px;color:#111;direction:rtl}header{text-align:center;border-bottom:2px solid #b00000;padding-bottom:12px;margin-bottom:15px}header img{width:100px;height:80px;object-fit:contain}h1{color:#b00000;font-size:23px;margin:5px}p{text-align:center;line-height:1.8}table{width:100%;border-collapse:collapse;font-size:11px}th,td{border:1px solid #555;padding:7px;text-align:center}th{background:#eee}@media print{body{padding:0}}</style></head><body><header><img src="'+LOGO+'" alt="شعار الأمين"><h1>الأمين للسفريات والسياحة</h1><strong>تقرير سندات القبض والصرف النقدية</strong></header><p>الفترة: '+escapeHTML(start||"البداية")+' — '+escapeHTML(end||"اليوم")+'</p><table><thead><tr><th>رقم السند</th><th>النوع</th><th>التاريخ</th><th>المستفيد / الدافع</th><th>المبلغ</th><th>السبب</th></tr></thead><tbody>'+rows+'</tbody></table><p style="margin-top:20px;text-align:center">تم استخراج التقرير من نظام الأمين للسفريات والسياحة.</p><script>window.onload=function(){var i=document.querySelector("header img");if(i.complete){window.print()}else{i.onload=function(){window.print()};i.onerror=function(){window.print()}}};<\/script></body></html>');
w.document.close();
});

function renderUsersList(){
var users=getUsers();
var owner=users.find(function(u){return u.isAdmin;});
if(owner){
var oUserEl=document.getElementById("ownerNewUsername");
if(oUserEl&&!oUserEl.value)oUserEl.value=owner.username;
}
var employees=users.filter(function(u){return !u.isAdmin;});
var container=document.getElementById("usersListContainer");
if(!employees.length){container.innerHTML='<div class="sales-report-empty">لا توجد حسابات موظفين إضافية.</div>';return;}
var h='<div class="sales-report-table-wrap"><table class="sales-report-table"><thead><tr><th>اسم المستخدم</th><th>الاسم الكامل</th><th>المبيعات</th><th>الصندوق</th><th>المصروفات</th><th>العمرة</th><th>السندات</th><th>الحذف</th><th>إجراء</th></tr></thead><tbody>';
employees.forEach(function(u){
var p=u.permissions||{};
h+='<tr><td>'+escapeHTML(u.username)+'</td><td>'+escapeHTML(u.fullName)+'</td><td>'+(p.sales?'✅':'❌')+'</td><td>'+(p.financial?'✅':'❌')+'</td><td>'+(p.expenses?'✅':'❌')+'</td><td>'+(p.umrah?'✅':'❌')+'</td><td>'+(p.vouchers?'✅':'❌')+'</td><td>'+(p.delete?'✅':'❌')+'</td><td><button class="archive-action archive-delete" data-del-user="'+escapeHTML(u.username)+'">🗑 حذف</button></td></tr>';
});
container.innerHTML=h+'</tbody></table></div>';
}

document.getElementById("saveOwnerSettingsBtn").addEventListener("click",function(){
var newU=val("ownerNewUsername"),newP=document.getElementById("ownerNewPassword").value;
if(!newU||!newP){alert("يرجى إدخال اسم المستخدم الجديد وكلمة المرور الجديدة للمالك.");return;}
var users=getUsers();
var owner=users.find(function(u){return u.isAdmin;});
if(owner){
owner.username=newU;
owner.password=newP;
}else{
users.push({username:newU,password:newP,fullName:"مدير النظام (المالك)",isAdmin:true,permissions:{sales:true,financial:true,expenses:true,umrah:true,vouchers:true,delete:true}});
}
setUsers(users);
document.getElementById("ownerNewPassword").value="";
alert("تم تحديث بيانات حساب المالك بنجاح! يمكنك الآن تسجيل الدخول بالاسم وكلمة المرور الجديدة.");
});

document.getElementById("saveNewUserBtn").addEventListener("click",function(){
var uname=val("newUsername").toLowerCase(),pass=val("newPassword"),fname=val("newFullName");
if(!uname||!pass||!fname){alert("يرجى ملء جميع حقول إنشاء الموظف.");return;}
var users=getUsers();
if(users.some(function(u){return u.username.toLowerCase()===uname;})){alert("اسم المستخدم موجود مسبقاً، اختر اسمًا آخر.");return;}
var newObj={
username:uname,
password:pass,
fullName:fname,
isAdmin:false,
permissions:{
sales:document.getElementById("permSales").checked,
financial:document.getElementById("permFinancial").checked,
expenses:document.getElementById("permExpenses").checked,
umrah:document.getElementById("permUmrah").checked,
vouchers:document.getElementById("permVouchers").checked,
delete:document.getElementById("permDelete").checked
}
};
users.push(newObj);
setUsers(users);
document.getElementById("newUsername").value="";
document.getElementById("newPassword").value="";
document.getElementById("newFullName").value="";
renderUsersList();
alert("تم إنشاء حساب الموظف بنجاح.");
});

document.getElementById("usersListContainer").addEventListener("click",function(e){
var btn=e.target.closest("[data-del-user]");if(!btn)return;
var uname=btn.getAttribute("data-del-user");
if(!confirm("هل تريد حذف حساب الموظف ("+uname+")؟"))return;
var users=getUsers().filter(function(u){return u.username.toLowerCase()!==uname.toLowerCase();});
setUsers(users);
renderUsersList();
alert("تم حذف الحساب بنجاح.");
});

function renderArchive(){
var q=(document.getElementById("archiveSearch").value||"").trim().toLowerCase(),a=getRecords().filter(function(r){return [r.ticket,r.passenger,r.passport,r.phone,r.company].some(function(v){return String(v||"").toLowerCase().includes(q)})}).sort(function(x,y){return Number(y.ticket)-Number(x.ticket)});
var target=document.getElementById("archiveResults");if(!a.length){target.innerHTML='<div class="archive-empty">لا توجد تذاكر مطابقة للبحث.</div>';return}
var canDel=currentUser.isAdmin||(currentUser.permissions&&currentUser.permissions.delete);
var h='<div class="archive-table-wrap"><table class="archive-table"><thead><tr><th>رقم التذكرة</th><th>المسافر</th><th>الجواز</th><th>تاريخ الإصدار</th><th>السعر</th><th>الإجراءات</th></tr></thead><tbody>';
a.forEach(function(r){
h+='<tr><td>'+escapeHTML(r.ticket)+'</td><td>'+escapeHTML(r.passenger)+'</td><td>'+escapeHTML(r.passport)+'</td><td>'+escapeHTML(priceWithCurrency(r.price,r.currency))+'</td><td><button class="archive-action archive-view" data-action="view" data-ticket="'+escapeHTML(r.ticket)+'">👁 عرض</button>'+(canDel?'<button class="archive-action archive-delete" data-action="delete" data-ticket="'+escapeHTML(r.ticket)+'">🗑 حذف</button>':"")+'</td></tr>';
});
target.innerHTML=h+"</tbody></table></div>"
}
document.getElementById("archiveSearch").addEventListener("input",renderArchive);
document.getElementById("archiveResults").addEventListener("click",function(e){
var b=e.target.closest("button[data-action]");if(!b)return;
var ticket=b.getAttribute("data-ticket"),a=getRecords(),r=a.find(function(x){return String(x.ticket)===String(ticket)});if(!r)return;
if(b.dataset.action==="view"){
loadTicket(r);fillFormFromRecord(r);archiveViewMode=true;closeDrawers();document.getElementById("alaminTicketWrapper").scrollIntoView({behavior:"smooth",block:"start"});return
}
if(b.dataset.action==="delete"){
if(!currentUser.isAdmin&&(!currentUser.permissions||!currentUser.permissions.delete)){alert("ليس لديك صلاحية حذف التذاكر.");return;}
if(!confirm("هل تريد حذف التذكرة رقم "+ticket+" نهائيًا؟"))return;
try{setRecords(a.filter(function(x){return String(x.ticket)!==String(ticket)}));if(String(currentBookingTicket)===String(ticket)){currentBookingTicket="";issuedTicketNumber="";document.getElementById("busTicketNumber").value=""}renderArchive();renderSales();renderFinancial();alert("تم حذف التذكرة.")}catch(err){alert("تعذر حذف التذكرة.")}
}
});
function closeDrawers(){document.querySelectorAll(".alamin-drawer").forEach(function(d){d.classList.remove("active")});document.getElementById("drawerOverlay").classList.remove("active")}
function openDrawer(id){
if(id==="salesDrawer"&&!currentUser.isAdmin&&currentUser.permissions&&!currentUser.permissions.sales){alert("عذراً، لا تملك صلاحية الوصول لقسم المبيعات.");return;}
if(id==="financialDrawer"&&!currentUser.isAdmin&&currentUser.permissions&&!currentUser.permissions.financial){alert("عذراً، لا تملك صلاحية الوصول للصندوق العام.");return;}
if(id==="expensesDrawer"&&!currentUser.isAdmin&&currentUser.permissions&&!currentUser.permissions.expenses){alert("عذراً، لا تملك صلاحية الوصول للمصروفات.");return;}
if(id==="umrahDrawer"&&!currentUser.isAdmin&&currentUser.permissions&&!currentUser.permissions.umrah){alert("عذراً، لا تملك صلاحية الوصول لقسم العمرة.");return;}
if(id==="vouchersDrawer"&&!currentUser.isAdmin&&currentUser.permissions&&!currentUser.permissions.vouchers){alert("عذراً، لا تملك صلاحية الوصول لقسم السندات.");return;}
if(id==="usersDrawer"&&!currentUser.isAdmin){alert("هذا القسم خاص بالمدير العام فقط.");return;}

closeDrawers();document.getElementById(id).classList.add("active");document.getElementById("drawerOverlay").classList.add("active");
if(id==="archiveDrawer")renderArchive();
if(id==="salesDrawer")renderSales();
if(id==="financialDrawer")renderFinancial();
if(id==="expensesDrawer")renderExpenses();
if(id==="umrahDrawer")renderUmrah();
if(id==="vouchersDrawer")renderVouchers();
if(id==="usersDrawer")renderUsersList();
}

document.getElementById("openArchive").addEventListener("click",function(){openDrawer("archiveDrawer")});
document.getElementById("openSalesDrawer").addEventListener("click",function(){openDrawer("salesDrawer")});
document.getElementById("openFinancialDrawer").addEventListener("click",function(){openDrawer("financialDrawer")});
document.getElementById("openExpensesDrawer").addEventListener("click",function(){openDrawer("expensesDrawer")});
document.getElementById("openUmrahDrawer").addEventListener("click",function(){openDrawer("umrahDrawer")});
document.getElementById("openVouchersDrawer").addEventListener("click",function(){openDrawer("vouchersDrawer")});
document.getElementById("openUsersDrawer").addEventListener("click",function(){openDrawer("usersDrawer")});

document.getElementById("drawerOverlay").addEventListener("click",closeDrawers);
document.querySelectorAll("[data-close-drawer]").forEach(function(b){b.addEventListener("click",closeDrawers)});
document.addEventListener("keydown",function(e){if(e.key==="Escape")closeDrawers()});

function printTicketReport(){
var a=getFiltered();if(a===null)return;if(!a.length){alert("لا توجد تذاكر صادرة في الفترة المحددة لطباعتها.");return}
var start=document.getElementById("salesStartDate").value||"كل الفترات",end=document.getElementById("salesEndDate").value||"حتى اليوم",t=totals(a);
var rows=a.map(function(r){return "<tr><td>"+escapeHTML(r.ticket)+"</td><td>"+escapeHTML(r.issueDateDisplay||r.issueDate)+"</td><td>"+escapeHTML(r.passenger)+"</td><td>"+escapeHTML(r.passport)+"</td><td>"+escapeHTML(r.phone)+"</td><td>"+escapeHTML("من "+(r.from||"")+" إلى "+(r.to||""))+"</td><td>"+escapeHTML(r.company)+"</td><td>"+escapeHTML(r.tripDate)+"</td><td>"+escapeHTML(priceWithCurrency(r.price,r.currency))+"</td><td>"+escapeHTML(r.payment)+"</td></tr>"}).join("");
var w=window.open("","_blank");if(!w){alert("يرجى السماح بفتح نافذة الطباعة في المتصفح.");return}
w.document.open();
w.document.write('<!DOCTYPE html><html lang="ar" dir="rtl"><head><meta charset="UTF-8"><title>تقرير مبيعات الأمين</title><style>body{font-family:Arial,Tahoma,sans-serif;padding:10px;color:#111;direction:rtl}header{text-align:center;border-bottom:2px solid #b00000;padding-bottom:8px;margin-bottom:10px}header img{width:80px;height:65px;object-fit:contain}h1{color:#b00000;font-size:18px;margin:3px}p{text-align:center;font-size:11px;line-height:1.5}.summary{display:flex;justify-content:space-around;flex-wrap:wrap;gap:5px;margin:10px 0;font-weight:bold;font-size:11px}.summary div{padding:5px;border:1px solid #ddd}table{width:100%;border-collapse:collapse;font-size:9.5px}th,td{border:1px solid #444;padding:4px 3px;text-align:center}th{background:#222;color:#fff}@media print{@page{size:A4 landscape;margin:5mm}body{padding:0}}</style></head><body><header><img src="'+LOGO+'" alt="شعار الأمين"><h1>الأمين للسفريات والسياحة</h1><strong>وخدمات الحج والعمرة</strong></header><p>تقرير مبيعات التذاكر الصادرة (كشف مضغوط)<br>الفترة: '+escapeHTML(start)+' — '+escapeHTML(end)+'</p><div class="summary"><div>عدد التذاكر: '+a.length+'</div><div>إجمالي اليمني: '+numberFormat(t.yer)+'</div><div>إجمالي السعودي: '+numberFormat(t.sar)+'</div></div><table><thead><tr><th>رقم التذكرة</th><th>تاريخ الإصدار</th><th>المسافر</th><th>الجواز</th><th>الجوال</th><th>خط الرحلة</th><th>الشركة</th><th>تاريخ الرحلة</th><th>السعر والعملة</th><th>الدفع</th></tr></thead><tbody>'+rows+'</tbody></table><p style="margin-top:10px;font-size:9px">تم استخراج التقرير من نظام حجز تذاكر الأمين للسفريات والسياحة.</p><script>window.onload=function(){var i=document.querySelector("header img");if(i.complete){window.print()}else{i.onload=function(){window.print()};i.onerror=function(){window.print()}}};<\/script></body></html>');
w.document.close()
}
document.getElementById("printSalesReport").addEventListener("click",printTicketReport);

function printFinancialReport(){
var a=getFinancialFiltered();if(a===null)return;
var t=financeTotals(a),start=document.getElementById("financialStartDate").value||"كل الفترات",end=document.getElementById("financialEndDate").value||"حتى اليوم";
var rows=a.map(function(r){var price=Number(r.price)||0;var hasPaid=r.carrierPaid!==""&&r.carrierPaid!==null&&r.carrierPaid!==undefined;var paid=hasPaid?Number(r.carrierPaid):0;var commission=hasPaid?(price-paid):0;return "<tr><td>"+escapeHTML(r.ticket)+"</td><td>"+escapeHTML(r.issueDateDisplay||r.issueDate)+"</td><td>"+escapeHTML(r.passenger)+"</td><td>"+escapeHTML(r.company)+"</td><td>"+escapeHTML(currencyName(r.currency))+"</td><td>"+numberFormat(price)+"</td><td>"+(hasPaid?numberFormat(paid):"-")+"</td><td>"+(hasPaid?numberFormat(commission):"-")+"</td><td>"+escapeHTML(r.payment)+"</td></tr>"}).join("");
var w=window.open("","_blank");if(!w){alert("يرجى السماح بفتح نافذة الطباعة في المتصفح.");return}
w.document.open();
w.document.write('<!DOCTYPE html><html lang="ar" dir="rtl"><head><meta charset="UTF-8"><title>الصندوق العام - الأمين</title><style>body{font-family:Arial,Tahoma,sans-serif;padding:10px;color:#111;direction:rtl}header{text-align:center;border-bottom:2px solid #b00000;padding-bottom:8px;margin-bottom:10px}header img{width:80px;height:65px;object-fit:contain}h1{color:#b00000;font-size:18px;margin:3px}p{text-align:center;font-size:11px;line-height:1.5}.summary{display:grid;grid-template-columns:repeat(2,1fr);gap:5px;margin:10px 0;font-size:10px}.summary div{padding:5px;border:1px solid #ddd;font-weight:bold}table{width:100%;border-collapse:collapse;font-size:9.5px}th,td{border:1px solid #444;padding:4px 3px;text-align:center}th{background:#222;color:#fff}h2{color:#b00000;font-size:14px;margin:10px 0 5px}@media print{@page{size:A4 landscape;margin:5mm}body{padding:0}}</style></head><body><header><img src="'+LOGO+'" alt="شعار الأمين"><h1>الأمين للسفريات والسياحة</h1><strong>تقرير الصندوق العام والخزنة (كشف مضغوط)</strong></header><p>الفترة: '+escapeHTML(start)+' — '+escapeHTML(end)+'</p><div class="summary"><div>إجمالي مبيعات يمني: '+numberFormat(t.salesYER)+'</div><div>إجمالي مبيعات سعودي: '+numberFormat(t.salesSAR)+'</div><div>إجمالي سداد يمني: '+numberFormat(t.paidYER)+'</div><div>إجمالي سداد سعودي: '+numberFormat(t.paidSAR)+'</div><div style="background:#eef6ff">إجمالي العمولات يمني: '+numberFormat(t.commissionYER)+'</div><div style="background:#eef6ff">إجمالي العمولات سعودي: '+numberFormat(t.commissionSAR)+'</div><div>صافي الصندوق يمني: '+numberFormat(t.netYER)+'</div><div>صافي الصندوق سعودي: '+numberFormat(t.netSAR)+'</div></div><h2>تفاصيل الحركة المالية للتذاكر</h2><table><thead><tr><th>رقم التذكرة</th><th>تاريخ الإصدار</th><th>المسافر</th><th>الشركة الناقلة</th><th>العملة</th><th>السعر</th><th>سداد الشركة</th><th>العمولة</th><th>حالة الدفع</th></tr></thead><tbody>'+rows+'</tbody></table><script>window.onload=function(){var i=document.querySelector("header img");if(i.complete){window.print()}else{i.onload=function(){window.print()};i.onerror=function(){window.print()}}};<\/script></body></html>');
w.document.close()
}
document.getElementById("printFinancialReport").addEventListener("click",printFinancialReport);

async function waitImages(el){await Promise.all(Array.from(el.querySelectorAll("img")).map(function(i){if(i.complete&&i.naturalWidth)return Promise.resolve();return new Promise(function(resolve){i.onload=resolve;i.onerror=resolve})}))}
async function downloadPDF(){
var ticket=document.getElementById("ticketMainContainer"),button=document.getElementById("downloadTicketPDF");if(typeof html2canvas==="undefined"||!window.jspdf){alert("تعذر تحميل أدوات PDF.");return}
var original=button.textContent,clone=null;button.disabled=true;button.textContent="⏳ جاري تجهيز PDF...";
try{
await waitImages(ticket);clone=ticket.cloneNode(true);clone.style.cssText="position:fixed;left:-100000px;top:0;width:793px;max-width:793px;min-width:793px;margin:0;background:white;direction:rtl;font-family:Arial,Tahoma,sans-serif";document.body.appendChild(clone);await waitImages(clone);
var canvas=await html2canvas(clone,{scale:3,useCORS:true,allowTaint:false,backgroundColor:"#fff",logging:false,imageTimeout:20000,width:793,windowWidth:793});
var pdf=new window.jspdf.jsPDF({orientation:"landscape",unit:"mm",format:[210,70],compress:true});pdf.addImage(canvas.toDataURL("image/png"),"PNG",0,0,210,70,undefined,"FAST");
pdf.save("تذكرة-الأمين-"+(document.getElementById("t-ticket-no").textContent||"ticket")+".pdf")
}catch(e){console.error(e);alert("تعذر إنشاء ملف PDF.")}
finally{if(clone&&clone.parentNode)clone.parentNode.removeChild(clone);button.disabled=false;button.textContent=original}
}
document.getElementById("downloadTicketPDF").addEventListener("click",downloadPDF);
document.getElementById("printTicket").addEventListener("click",async function(){await waitImages(document.getElementById("ticketMainContainer"));window.print()});

document.getElementById("busForm").addEventListener("submit",function(e){
e.preventDefault();if(!validateNumbers())return;
archiveViewMode=false;
var route="من "+val("busFrom")+" إلى "+val("busTo");
var lines=[["رقم التذكرة",currentBookingTicket||"سيتم إصداره عند إصدار التذكرة"],["المسافر",val("busPassenger")],["الجنس",val("busGender")],["رقم الجواز",val("busPassport")],["رقم الجوال",val("busPhone")],["تاريخ الميلاد",val("busBirthDate")],["مكان الميلاد",val("busBirthPlace")],["تاريخ إصدار الجواز",val("busPassportIssueDate")],["خط الرحلة",route],["الشركة",val("busCompany")],["التاريخ",val("busDate")],["وقت الرحلة",fmtTime(val("busTripTime"))||"غير محدد"],["وقت الحضور",fmtTime(val("busArrival"))||"غير محدد"],["المقعد",val("busSeat")||"غير محدد"],["السعر",priceWithCurrency(val("busPrice"),currency())],["الدفع",payment()],["ملاحظات",val("busNotes")||"لا توجد"]];
document.getElementById("busReviewContent").innerHTML=lines.map(function(x){return '<div class="review-line"><b>'+escapeHTML(x[0])+':</b> '+escapeHTML(x[1])+'</div>'}).join("");
document.getElementById("busReview").classList.add("active");
if(!currentBookingTicket)document.getElementById("alaminTicketWrapper").classList.remove("active");
});
document.getElementById("showBusTicket").addEventListener("click",async function(){
if(!validateNumbers())return;
var ticket=currentBookingTicket||nextTicket();
issuedTicketNumber=String(ticket);
document.getElementById("busTicketNumber").value=issuedTicketNumber;
var existing=getRecords().find(function(r){return String(r.ticket)===String(ticket)});
var record=makeRecord(ticket,existing);
if(!saveTicket(record))return;
currentBookingTicket=String(ticket);
archiveViewMode=false;
loadTicket(record);
await waitImages(document.getElementById("ticketMainContainer"));
document.getElementById("alaminTicketWrapper").scrollIntoView({behavior:"smooth",block:"start"});
});
document.querySelectorAll('input[name="busPayment"]').forEach(function(r){r.addEventListener("change",function(){updateSavedTicketPayment()})});

["busFrom","busTo","busCompany","busPassenger","busPassport","busPhone","busGender","busBirthPlace","busBirthDate","busPassportIssueDate","busDate","busArrival","busTripTime","busSeat","busPrice","busCurrency","busTicketType","busNotes"].forEach(function(id){
var el=document.getElementById(id);
if(!el)return;
el.addEventListener("input",function(){if(currentBookingTicket&&!archiveViewMode){currentBookingTicket="";issuedTicketNumber="";document.getElementById("busTicketNumber").value=""}});
el.addEventListener("change",function(){if(currentBookingTicket&&!archiveViewMode){currentBookingTicket="";issuedTicketNumber="";document.getElementById("busTicketNumber","").value=""}});
});

document.getElementById("sendBusWhatsApp").addEventListener("click",function(){
if(!validateNumbers())return;
var ticket=currentBookingTicket||issuedTicketNumber||"سيصدر عند تأكيد التذكرة",route="من "+val("busFrom")+" إلى "+val("busTo");
var msg="🎫 طلب حجز تذكرة باص\n\nالأمين للسفريات والسياحة وخدمات الحج والعمرة\nرقم التذكرة: "+ticket+"\nنوع التذكرة: "+val("busTicketType")+"\nالشركة الناقلة: "+val("busCompany")+"\n\nبيانات المسافر\nالاسم: "+val("busPassenger")+"\nرقم الجواز: "+val("busPassport")+"\nرقم الجوال: "+val("busPhone")+"\nالجنس: "+val("busGender")+"\nتاريخ الميلاد: "+val("busBirthDate")+"\nمكان الميلاد: "+val("busBirthPlace")+"\n\nبيانات الرحلة\nخط الرحلة: "+route+"\nتاريخ الرحلة: "+val("busDate")+"\nيوم الرحلة: "+(window.busDayValue||"")+"\nوقت الرحلة: "+(fmtTime(val("busTripTime"))||"غير محدد")+"\nوقت الحضور: "+fmtTime(val("busArrival"))+"\nالمقعد: "+(val("busSeat")||"غير محدد")+"\nالسعر: "+priceWithCurrency(val("busPrice"),currency())+"\nحالة الدفع: "+payment();
window.open("https://wa.me/"+whatsappNumber+"?text="+encodeURIComponent(msg),"_blank");
document.getElementById("successMessage").style.display="block"
});
renderSales();renderArchive();renderFinancial();renderExpenses();renderUmrah();renderVouchers();
})();
</script>
