<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة الهبوط | مصنع المحتوى</title>
    <!-- استخدام خط تجوال لدعم اللغة العربية بشكل احترافي -->
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0a0a0a;
            --surface-color: #111111;
            --accent-color: #d4af37; /* لون ذهبي يعكس الفخامة ويمكن تغييره لأي لون يطابق هويتك البصرية */
            --text-primary: #ffffff;
            --text-secondary: #888888;
        }
        
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Tajawal', sans-serif; }
        
        body { background-color: var(--bg-color); color: var(--text-primary); line-height: 1.6; }
        
        .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
        
        header { padding: 20px 0; display: flex; justify-content: center; border-bottom: 1px solid #222; }
        header h2 { letter-spacing: 1px; font-weight: 900; }
        
        .hero { text-align: center; padding: 80px 20px; }
        .hero .alert { display: inline-block; background: #222; color: var(--accent-color); padding: 5px 15px; border-radius: 20px; font-size: 0.9rem; margin-bottom: 20px; font-weight: bold; border: 1px solid var(--accent-color); }
        .hero h1 { font-size: 3.5rem; margin-bottom: 20px; line-height: 1.2; }
        .hero p { color: var(--text-secondary); font-size: 1.2rem; max-width: 700px; margin: 0 auto 30px; }
        
        .btn { display: inline-block; background: var(--accent-color); color: #000; text-decoration: none; padding: 18px 40px; font-size: 1.2rem; font-weight: bold; border-radius: 8px; transition: transform 0.2s; text-transform: uppercase; }
        .btn:hover { transform: scale(1.05); }
        
        .stats { display: flex; justify-content: center; gap: 40px; margin-top: 50px; flex-wrap: wrap; }
        .stat-item h3 { font-size: 2.5rem; color: var(--text-primary); }
        .stat-item p { color: var(--text-secondary); font-size: 1rem; }
        
        .section-title { text-align: center; margin-bottom: 40px; }
        .section-title h2 { font-size: 2.5rem; }
        .section-title p { color: var(--text-secondary); }
        
        .features { padding: 80px 0; background: var(--surface-color); }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; }
        .card { background: var(--bg-color); border: 1px solid #222; padding: 30px; border-radius: 10px; }
        .card h3 { margin-bottom: 15px; color: var(--text-primary); font-size: 1.5rem; }
        .card p { color: var(--text-secondary); }
        
        .pricing { padding: 80px 0; text-align: center; }
        .price-box { max-width: 500px; margin: 0 auto; background: var(--surface-color); border: 2px solid var(--accent-color); padding: 40px; border-radius: 15px; }
        .price-box h3 { font-size: 2rem; margin-bottom: 10px; }
        .price-box .price { font-size: 4rem; font-weight: 900; margin: 20px 0; }
        .price-box .old-price { text-decoration: line-through; color: var(--text-secondary); font-size: 1.5rem; margin-left: 10px; }
        .price-box ul { list-style: none; text-align: right; margin: 30px 0; }
        .price-box ul li { margin-bottom: 15px; color: var(--text-secondary); font-size: 1.1rem; }
        .price-box ul li::before { content: "✓ "; color: var(--accent-color); font-weight: bold; margin-left: 10px; }
        
        footer { text-align: center; padding: 30px; border-top: 1px solid #222; color: var(--text-secondary); }
        
        /* ضبط التجاوب مع شاشات الموبايل */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            .stat-item h3 { font-size: 1.8rem; }
            .stats { gap: 20px; }
        }
    </style>
</head>
<body>

    <header>
        <h2>مصنع المحتوى | CONTENT VAULT</h2>
    </header>

    <section class="hero container">
        <div class="alert">⚠ تنبيه: تبقى أماكن قليلة بسعر 9$</div>
        <h1>انشر. سيطر. حقق أرباح.</h1>
        <p>أضخم مكتبة محتوى مرئي فاخر (Dark Luxury). أكثر من 19,000 مقطع فيديو مصمم لاختراق خوارزميات التيك توك والريلز وبأقوى خطافات الانتباه (Hooks) بدون الحاجة للمونتاج.</p>
        <a href="#pricing" class="btn">افتح الخزنة الآن - 9$</a>
        
        <div class="stats">
            <div class="stat-item">
                <h3>+19K</h3>
                <p>فيديو جاهز</p>
            </div>
            <div class="stat-item">
                <h3>+400</h3>
                <p>إضافة أسبوعية</p>
            </div>
            <div class="stat-item">
                <h3>4.9★</h3>
                <p>تقييم صناع المحتوى</p>
            </div>
        </div>
    </section>

    <section class="features">
        <div class="container">
            <div class="section-title">
                <h2>مصمم للمحترفين، وليس للهواة</h2>
                <p>كل مقطع تم تصميمه بدقة للحفاظ على أعلى معدلات الاحتفاظ بالمشاهد (Retention Rate).</p>
            </div>
            <div class="grid">
                <div class="card">
                    <h3>وفر وقتك بالكامل</h3>
                    <p>تجاوز مرحلة التصوير وهندسة الإضاءة والمونتاج المعقد. حمل الفيديو وانشره فوراً لتوفر أكثر من 20 ساعة أسبوعياً.</p>
                </div>
                <div class="card">
                    <h3>استمرارية النشر</h3>
                    <p>مع وجود 19,000 فيديو وإضافات أسبوعية مستمرة، يمكنك النشر عدة مرات يومياً طوال العام لضمان التواجد المستمر.</p>
                </div>
                <div class="card">
                    <h3>نمو مضاعف 10X</h3>
                    <p>فيديوهات محسنة للخوارزميات ومصممة بأقوى زوايا التصوير الديناميكية لضمان الانتشار السريع وتوسيع قاعدتك الجماهيرية.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="pricing container">
        <div class="section-title">
            <h2>وصول مدى الحياة لخزنة المحتوى</h2>
            <p>دفعة واحدة. بدون اشتراكات شهرية. ابدأ النشر خلال دقائق.</p>
        </div>
        <div class="price-box">
            <h3>الوصول الكامل</h3>
            <div class="price">9$<span class="old-price">29$</span></div>
            <p style="color: var(--accent-color); font-weight: bold; font-size: 1.2rem;">وفر 20$ - خصم 69%</p>
            <ul>
                <li>أكثر من 19,000 فيديو تحفيزي جاهز للنشر</li>
                <li>تحديث أسبوعي بـ 400 فيديو جديد</li>
                <li>مقاسات متوافقة مع Reels, Shorts, TikTok</li>
                <li>تعديل سينمائي عالي الجودة لضمان المشاهدات</li>
                <li>رخصة استخدام مدى الحياة</li>
            </ul>
            <a href="#" class="btn" style="width: 100%; margin-top: 20px;">احصل على الوصول الفوري</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 مصنع المحتوى. جميع الحقوق محفوظة.</p>
    </footer>

</body>
</html>
