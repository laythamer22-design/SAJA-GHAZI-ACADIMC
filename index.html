<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أكاديمية سجى غازي - المنصة المتكاملة</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <style>
        :root {
            --primary-color: #1a472a;
            --secondary-color: #d4af37;
            --bg-light: #f4f7f6;
            --text-dark: #333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-light);
            margin: 0;
            color: var(--text-dark);
        }

        header {
            background: var(--primary-color);
            color: var(--secondary-color);
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .container { max-width: 1200px; margin: auto; padding: 20px; }

        /* بوابات النظام */
        .portal-section { display: none; background: white; padding: 30px; border-radius: 15px; box-shadow: 0 5px 15px rgba(0,0,0,0.05); }
        .portal-active { display: block; animation: fadeIn 0.5s; }

        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }

        /* تصميم الأزرار */
        .btn {
            background: var(--secondary-color);
            color: var(--primary-color);
            border: none;
            padding: 12px 25px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            transition: 0.3s;
            margin: 5px;
        }

        .btn:hover { background: #c19b2e; transform: translateY(-2px); }

        /* منطقة الدروس التفاعلية */
        .word-box {
            font-size: 2.5rem;
            text-align: center;
            padding: 50px;
            border: 2px dashed var(--secondary-color);
            margin: 20px 0;
            border-radius: 15px;
            cursor: pointer;
        }

        .ai-tutor {
            background: #e8f5e9;
            border-right: 5px solid #4caf50;
            padding: 15px;
            margin-top: 20px;
        }

        /* لوحة التحكم للمدير */
        table { width: 100%; border-collapse: collapse; margin-top: 20px; }
        th, td { border: 1px solid #ddd; padding: 12px; text-align: center; }
        th { background-color: var(--primary-color); color: white; }

        .nav-tabs { display: flex; justify-content: center; gap: 10px; margin-bottom: 20px; }
    </style>
</head>
<body>

<header>
    <h1>أكاديمية سجى غازي للغة العربية 🎓</h1>
    <p>منصة التعليم الذكي - صوت، نص، وذكاء اصطناعي</p>
</header>

<div class="container">
    <div class="nav-tabs">
        <button class="btn" onclick="showPortal('studentPortal')">بوابة الطالب</button>
        <button class="btn" onclick="showPortal('adminPortal')">بوابة المدير (التقارير)</button>
    </div>

    <section id="studentPortal" class="portal-section portal-active">
        <h2>المستوى المبتدئ: الجملة الاسمية</h2>
        <div class="ai-tutor">
            🤖 <strong>المعلم الذكي:</strong> "أهلاً بك يا بطل! اضغط على الكلمات لتسمع النطق الصحيح وتتعلم الإعراب."
        </div>
        
        <div class="word-box" onclick="speak('الشجرةُ مثمرةٌ')">
            الشجرةُ مثمرةٌ 🔊
        </div>

        <div style="text-align: center;">
            <p>تحدي اليوم: اسحب المبتدأ وضعه في الميزان</p>
            <button class="btn" onclick="checkAnswer()">تقديم الإجابة</button>
        </div>
    </section>

    <section id="adminPortal" class="portal-section">
        <h2>لوحة إدارة الأكاديمية (المدير)</h2>
        <div class="ai-tutor">
            📊 <strong>ملخص الذكاء الاصطناعي اليومي:</strong> "تم تحقيق نسبة إتقان 92% في وحدة الجملة الاسمية اليوم."
        </div>

        <table>
            <thead>
                <tr>
                    <th>المتدرب</th>
                    <th>المستوى</th>
                    <th>التقدم</th>
                    <th>التقرير</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>أحمد علي</td>
                    <td>مبتدئ</td>
                    <td>85%</td>
                    <td><button class="btn" onclick="generatePDF('أحمد علي', 'مبتدئ')">تحميل الشهادة</button></td>
                </tr>
                <tr>
                    <td>سارة خالد</td>
                    <td>متوسط</td>
                    <td>40%</td>
                    <td><button class="btn">تقرير الأداء</button></td>
                </tr>
            </tbody>
        </table>

        <div style="margin-top: 30px;">
            <h3>إرسال تقارير دورية</h3>
            <button class="btn" onclick="alert('تم إرسال التقرير اليومي لبريدك الشخصي')">إرسال تقرير يومي الآن</button>
            <button class="btn" onclick="alert('جاري تجهيز التقرير الأسبوعي الشامل...')">تقرير أسبوعي</button>
        </div>
    </section>
</div>

<script>
    // 1. نظام النطق الصوتي لكل كلمة
    function speak(text) {
        const msg = new SpeechSynthesisUtterance(text);
        msg.lang = 'ar-SA';
        msg.rate = 0.8;
        msg.pitch = 1;
        window.speechSynthesis.speak(msg);
    }

    // 2. نظام التنقل بين البوابات
    function showPortal(portalId) {
        document.querySelectorAll('.portal-section').forEach(section => {
            section.classList.remove('portal-active');
        });
        document.getElementById(portalId).classList.add('portal-active');
    }

    // 3. محرك توليد الشهادات (PDF)
    function generatePDF(name, level) {
        const { jsPDF } = window.jspdf;
        const doc = new jsPDF();
        
        doc.setFontSize(22);
        doc.text("Saja Ghazi Academy", 105, 40, { align: "center" });
        doc.text("Certificate of Completion", 105, 60, { align: "center" });
        
        doc.setFontSize(16);
        doc.text(`This is to certify that: ${name}`, 105, 100, { align: "center" });
        doc.text(`Has mastered the level: ${level}`, 105, 120, { align: "center" });
        
        doc.text("Verified by AI Mentor", 105, 160, { align: "center" });
        
        doc.save(`Certificate_${name}.pdf`);
        speak("تهانينا! تم إصدار شهادتك بنجاح");
    }

    // 4. منطق بسيط للألعاب
    function checkAnswer() {
        speak("إجابة صحيحة! المبتدأ هو الشجرةُ وهي مرفوعة بالضمة");
        alert("أحسنت! الذكاء الاصطناعي سجل تقدمك بنسبة +5%");
    }
</script>

</body>
</html>
