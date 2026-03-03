<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>लूडो अड्डा - खेलो और जीतो</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; background: #1a1a2e; color: white; text-align: center; margin: 0; padding: 15px; }
        header { background: #e94560; padding: 20px; border-radius: 0 0 20px 20px; box-shadow: 0 4px 15px rgba(0,0,0,0.5); }
        .card { background: #16213e; border: 2px solid #e94560; border-radius: 15px; padding: 20px; margin: 25px auto; max-width: 400px; box-shadow: 0 8px 20px rgba(0,0,0,0.3); }
        .prize { font-size: 24px; color: #44ff62; font-weight: bold; }
        .btn { background: #e94560; color: white; padding: 12px 25px; border: none; border-radius: 30px; cursor: pointer; font-size: 16px; font-weight: bold; text-decoration: none; display: inline-block; margin-top: 15px; width: 85%; }
        .whatsapp { background: #25d366; margin-top: 10px; }
        input { width: 85%; padding: 12px; margin: 10px 0; border-radius: 8px; border: none; background: #0f3460; color: white; border: 1px solid #1a1a2e; }
        .rules { font-size: 14px; opacity: 0.8; margin-top: 15px; text-align: left; padding: 10px; }
    </style>
</head>
<body>

<header>
    <h1>🏆 लूडो अड्डा 🏆</h1>
    <p>डेली टूर्नामेंट्स - इंस्टेंट पेमेंट</p>
</header>

<div class="card">
    <h3>महारानी बैटल #001</h3>
    <p>एंट्री फीस: <b>₹20</b></p>
    <p>विजेता को मिलेगा: <span class="prize">₹39</span></p>
    <p>मैच का समय: <b>09:30 PM (आज)</b></p>
    <hr style="border: 0.5px solid #0f3460;">
    
    upi :- 9636901446@fam
    
    <form id="regForm">
        <input type="text" name="name" placeholder="आपका शुभ नाम" required>
        <input type="number" name="phone" placeholder="व्हाट्सएप नंबर" required>
        <input type="text" name="utr" placeholder="पेमेंट ट्रांजैक्शन ID" required>
        <button type="submit" class="btn">रजिस्टर करें</button>
    </form>
    
    <a href="https://wa.me" class="btn whatsapp">व्हाट्सएप पर सहायता लें</a>
    
    <div class="rules">
        <b>नियम:</b><br>
        1. मैच शुरू होने से 5 मिनट पहले रूम कोड मिलेगा।<br>
        2. गलत स्क्रीनशॉट डालने पर आईडी ब्लॉक होगी।
    </div>
</div>

<script>
    document.getElementById('regForm').onsubmit = function(e) {
        e.preventDefault();
        alert('बधाई हो! आपकी डिटेल्स भेज दी गई हैं। हम आपसे व्हाट्सएप पर संपर्क करेंगे।');
        this.reset();
    };
</script>

</body>
</html>
