<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SurfSpot Cafe | Internet & Printing Services</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#1e3a8a',
                        }
                    }
                }
            }
        }
    </script>
    <!-- Inter Font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-500 selection:text-white">

    <!-- Navigation Header -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <div class="flex items-center space-x-3">
                    <div class="bg-brand-600 text-white p-2.5 rounded-xl font-black text-xl tracking-wider shadow-md shadow-brand-600/20">
                        SS
                    </div>
                    <div>
                        <span class="text-xl font-extrabold tracking-tight text-slate-900 block">SurfSpot Cafe</span>
                        <span class="text-xs font-medium text-brand-600 block">Basdiot, Moalboal, Cebu</span>
                    </div>
                </div>
                <nav class="hidden md:flex items-center space-x-8 font-medium text-sm text-slate-600">
                    <a href="#services" class="hover:text-brand-600 transition">Services</a>
                    <a href="#location" class="hover:text-brand-600 transition">Location</a>
                    <a href="#contact" class="hover:text-brand-600 transition">Contact</a>
                </nav>
                <div>
                    <a href="tel:09166572365" class="bg-brand-600 hover:bg-brand-700 text-white font-semibold px-5 py-2.5 rounded-xl text-sm shadow-md shadow-brand-600/20 transition transform active:scale-95 inline-block">
                        Call Us
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative overflow-hidden bg-gradient-to-b from-brand-50/50 to-slate-50 py-20 lg:py-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative">
            <div class="max-w-3xl mx-auto text-center">
                <span class="inline-block bg-brand-100 text-brand-700 font-semibold px-4 py-1.5 rounded-full text-xs uppercase tracking-wider mb-6">
                    Your Go-To Hub in Basdiot
                </span>
                <h1 class="text-4xl sm:text-6xl font-black text-slate-900 tracking-tight mb-6 leading-tight">
                    Fast Internet & Reliable Digital Services
                </h1>
                <p class="text-lg sm:text-xl text-slate-600 mb-10 leading-relaxed">
                    Welcome to SurfSpot Cafe! Experience high-speed internet surfing, gaming, clear document printing, scanning, and professional ID photo services right here in Moalboal, Cebu.
                </p>
                <div class="flex flex-col sm:flex-row justify-center gap-4">
                    <a href="#services" class="bg-brand-600 hover:bg-brand-700 text-white font-bold px-8 py-4 rounded-xl shadow-lg shadow-brand-600/25 transition">
                        Explore Services
                    </a>
                    <a href="#contact" class="bg-white hover:bg-slate-100 text-slate-700 font-bold px-8 py-4 rounded-xl border border-slate-300 transition">
                        Get in Touch
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-extrabold text-slate-900 tracking-tight mb-4">What We Offer</h2>
                <p class="text-slate-600 text-base">Equipped to handle your online, gaming, and documentation needs with quality equipment.</p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 hover:border-brand-300 transition shadow-sm">
                    <div class="w-12 h-12 bg-brand-100 text-brand-600 rounded-xl flex items-center justify-center font-bold text-xl mb-6">
                        🌐
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Internet & Gaming</h3>
                    <p class="text-slate-600 leading-relaxed text-sm">
                        High-speed wired and wireless internet connections optimized for web browsing, research, remote work, and online gaming sessions.
                    </p>
                </div>

                <!-- Service 2 -->
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 hover:border-brand-300 transition shadow-sm">
                    <div class="w-12 h-12 bg-brand-100 text-brand-600 rounded-xl flex items-center justify-center font-bold text-xl mb-6">
                        🖨️
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">Printing & Scanning</h3>
                    <p class="text-slate-600 leading-relaxed text-sm">
                        Full-color and monochrome document printing, document scanning, and photocopying services to support your study or business requirements.
                    </p>
                </div>

                <!-- Service 3 -->
                <div class="bg-slate-50 p-8 rounded-2xl border border-slate-200 hover:border-brand-300 transition shadow-sm">
                    <div class="w-12 h-12 bg-brand-100 text-brand-600 rounded-xl flex items-center justify-center font-bold text-xl mb-6">
                        📸
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-3">ID Photo Services</h3>
                    <p class="text-slate-600 leading-relaxed text-sm">
                        Quick and clean passport and identification photo formatting, including standard 1x1 and 2x2 sizes for official applications and documents.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Location & Contact Section -->
    <section id="location" class="py-20 bg-slate-50 border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <div>
                    <span class="text-brand-600 font-semibold text-xs uppercase tracking-wider block mb-2">Visit Our Shop</span>
                    <h2 class="text-3xl font-extrabold text-slate-900 tracking-tight mb-6">Conveniently Located in Basdiot</h2>
                    <p class="text-slate-600 mb-6 leading-relaxed">
                        Drop by our hub for all your quick digital, computer, and paperwork needs. We are ready to assist you!
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start space-x-4">
                            <div class="bg-brand-100 text-brand-600 p-3 rounded-lg font-bold">📍</div>
                            <div>
                                <h4 class="font-bold text-slate-900">Address</h4>
                                <p class="text-slate-600 text-sm">Basdiot, Moalboal, Cebu</p>
                            </div>
                        </div>
                        <div class="flex items-start space-x-4" id="contact">
                            <div class="bg-brand-100 text-brand-600 p-3 rounded-lg font-bold">📞</div>
                            <div>
                                <h4 class="font-bold text-slate-900">Contact Number</h4>
                                <p class="text-slate-600 text-sm font-semibold text-brand-600">0916-657-2365</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="bg-brand-900 text-white p-8 sm:p-12 rounded-3xl shadow-xl relative overflow-hidden">
                    <div class="relative z-10">
                        <h3 class="text-2xl font-bold mb-4">Need Assistance?</h3>
                        <p class="text-brand-100 text-sm mb-6 leading-relaxed">
                            Have specific files to print or inquiries about our computer setups? Reach out via call, WhatsApp, or Facebook Messenger below!
                        </p>
                        <div class="flex flex-col sm:flex-row gap-3">
                            <a href="tel:09166572365" class="bg-white text-brand-900 hover:bg-brand-50 font-bold px-5 py-3 rounded-xl text-center transition text-sm">
                                Call Now
                            </a>
                            <a href="https://wa.me/639166572365" target="_blank" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-5 py-3 rounded-xl text-center transition text-sm">
                                WhatsApp Chat
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Floating Chat Buttons for Mobile -->
    <div class="fixed bottom-6 right-6 z-50 flex flex-col gap-3">
        <!-- Messenger Bubble (Replace YOUR_FB_PAGE with your Facebook Page username) -->
        <a href="https://m.me/YOUR_FB_PAGE" target="_blank" aria-label="Messenger" class="bg-blue-600 hover:bg-blue-700 text-white w-14 h-14 rounded-full shadow-2xl flex items-center justify-center text-2xl transition transform hover:scale-110">
            💬
        </a>
        <!-- WhatsApp Bubble -->
        <a href="https://wa.me/639166572365" target="_blank" aria-label="WhatsApp" class="bg-emerald-500 hover:bg-emerald-600 text-white w-14 h-14 rounded-full shadow-2xl flex items-center justify-center text-2xl transition transform hover:scale-110">
            📱
        </a>
    </div>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col sm:flex-row justify-between items-center gap-4">
            <div class="flex items-center space-x-2">
                <span class="font-bold text-white text-lg">SurfSpot Cafe</span>
                <span class="text-xs text-slate-500">| Basdiot, Moalboal, Cebu</span>
            </div>
            <p class="text-xs text-slate-500">
                &copy; 2026 SurfSpot Cafe. All rights reserved.
            </p>
        </div>
    </footer>

</body>
</html>
