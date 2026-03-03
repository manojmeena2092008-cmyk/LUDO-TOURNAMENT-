<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NK Adda Clone</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <style>
        body { background-color: #ffffff; font-family: 'Segoe UI', sans-serif; }
        /* Professional Banner Style */
        .hero-banner { width: 100%; border-radius: 0 0 30px 30px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        /* Sticky Bottom Button */
        .sticky-footer { position: fixed; bottom: 20px; width: 100%; display: flex; justify-content: center; gap: 10px; padding: 0 20px; z-index: 100; }
        .play-now-btn { background: linear-gradient(90deg, #ff1e56, #e94560); color: white; width: 80%; padding: 15px; border-radius: 12px; font-weight: bold; font-size: 18px; display: flex; align-items: center; justify-content: center; gap: 10px; box-shadow: 0 5px 20px rgba(233, 69, 96, 0.4); }
        .support-btn { background: #e94560; color: white; padding: 15px; border-radius: 12px; width: 60px; display: flex; align-items: center; justify-content: center; font-size: 20px; }
        /* Features Section */
        .feature-tag { display: flex; align-items: center; gap: 8px; font-size: 11px; font-weight: bold; color: #444; background: #f0f0f0; padding: 5px 12px; border-radius: 20px; }
    </style>
</head>
<body>

    <!-- Header with Logo -->
    <div class="flex justify-between items-center p-4 border-b">
        <i class="fas fa-bars text-xl text-gray-600"></i>
        <img src="https://via.placeholder.com" class="h-10" alt="Logo">
        <div class="flex items-center gap-1 text-blue-600 font-bold border-2 border-blue-600 px-2 py-1 rounded">
            <i class="fas fa-info-circle"></i> निर्देश
        </div>
    </div>

    <!-- Features Row -->
    <div class="flex justify-around p-3 bg-gray-50">
        <div class="feature-tag"><i class="fas fa-headset text-blue-500"></i> 24x7 SUPPORT</div>
        <div class="feature-tag"><i class="fas fa-percentage text-green-500"></i> 3% COMMISSION</div>
        <div class="feature-tag"><i class="fas fa-bolt text-yellow-500"></i> INSTANT WITHDRAWAL</div>
    </div>

    <!-- Main Hero Banner -->
    <div class="p-4">
        <img src="https://img.freepik.com" class="hero-banner" alt="Ludo Game">
    </div>

    <!-- Statistics Section (Optional) -->
    <div class="text-center mt-4">
        <p class="text-gray-500 text-sm font-semibold">India's Fastest Ludo Platform</p>
        <h2 class="text-2xl font-black text-gray-800">चलो खेलें और जीतें!</h2>
    </div>

    <!-- Sticky Bottom Navigation -->
    <div class="sticky-footer">
        <button class="play-now-btn" onclick="location.href='#games'">
            <i class="fas fa-gamepad"></i> अब खेलते हैं
        </button>
        <button class="support-btn">
            <i class="fas fa-headset"></i>
        </button>
    </div>

</body>
</html>
