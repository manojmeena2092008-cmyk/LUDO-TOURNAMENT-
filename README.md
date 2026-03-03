<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>लूडो टूर्नामेंट</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com">
    <style>
        body { font-family: 'Segoe UI', sans-serif; background-color: #ffffff; margin: 0; padding-bottom: 100px; }
        .sticky-btn { position: fixed; bottom: 20px; left: 50%; transform: translateX(-50%); width: 90%; background: linear-gradient(90deg, #ff1e56, #e94560); color: white; padding: 15px; border-radius: 12px; font-weight: bold; font-size: 18px; text-align: center; box-shadow: 0 5px 20px rgba(233, 69, 96, 0.4); z-index: 100; }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="flex justify-between items-center p-4 border-b">
        <h1 class="text-xl font-bold text-gray-800">लूडो टूर्नामेंट</h1>
        <button class="border-2 border-blue-600 text-blue-600 px-4 py-1 rounded font-bold">निर्देश</button>
    </div>

    <!-- Features Section -->
    <div class="flex justify-around bg-gray-50 p-4 mt-2">
        <div class="text-center text-[10px] font-bold text-gray-600 bg-white p-2 rounded-lg shadow-sm border">
            <i class="fas fa-headset text-blue-500 mb-1 block"></i> 24x7 सहायता
        </div>
        <div class="text-center text-[10px] font-bold text-gray-600 bg-white p-2 rounded-lg shadow-sm border">
            <i class="fas fa-percentage text-green-500 mb-1 block"></i> 3% कमीशन
        </div>
        <div class="text-center text-[10px] font-bold text-gray-600 bg-white p-2 rounded-lg shadow-sm border">
            <i class="fas fa-bolt text-yellow-500 mb-1 block"></i> तत्काल निकासी
        </div>
    </div>

    <!-- Banner Placeholder -->
    <div class="p-6 text-center">
        <div class="bg-gray-100 rounded-3xl h-48 flex items-center justify-center border-2 border-dashed border-gray-300">
            <i class="fas fa-gamepad text-5xl text-gray-300"></i>
        </div>
        <p class="text-gray-400 mt-4 font-semibold italic">भारत का सबसे तेज़ लूडो प्लेटफॉर्म</p>
        <h2 class="text-3xl font-black text-gray-800 mt-2">चलो खेलें और जीतें!</h2>
    </div>

    <!-- Sticky Bottom Button -->
    <a href="#" class="sticky-btn">
        <i class="fas fa-play mr-2"></i> अब खेलते हैं
    </a>

</body>
</html>

