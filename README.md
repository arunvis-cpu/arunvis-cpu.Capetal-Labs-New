<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capetal Labs Inc | US Soft-Landing & Cross-Border Venture Studio</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            crimson: '#A61111',
                            dark: '#1F2937',
                            light: '#F9FAFB'
                        }
                    }
                }
            }
        }
    </script>
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        /* Hides specific header titles if needed */
        header h1, .site-header h1, #header h1 {
            display: none !important;
        }
        .mobile-nav-active {
            display: flex !important;
            flex-direction: column;
            position: absolute;
            top: 100%;
            left: 0;
            width: 100%;
            background: white;
            padding: 1.5rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
            gap: 1rem;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-white scroll-smooth">

    <header class="sticky top-0 z-50 bg-white border-b border-gray-100 shadow-sm">
        <div class="container relative flex items-center justify-between px-6 py-4 mx-auto max-w-7xl">
            <a href="#" class="flex items-center space-x-3">
                <img src="https://raw.githubusercontent.com/arunvis-cpu/images/main/Capetals%20icon.png" alt="Capetal Labs Inc Logo" class="w-10 h-10 object-contain">
                <span class="text-xl font-bold tracking-tight text-brand-dark">Capetal <span class="text-brand-crimson">Labs</span></span>
            </a>
            
            <nav id="nav-menu" class="hidden space-x-8 md:flex font-medium text-gray-600">
                <a href="#about" class="hover:text-brand-crimson transition">About</a>
                <a href="#pillars" class="hover:text-brand-crimson transition">What We Do</a>
                <a href="#space" class="hover:text-brand-crimson transition">Workspace</a>
                <a href="#apply" class="hover:text-brand-crimson transition">Apply</a>
            </nav>

            <div class="hidden md:block">
                <a href="#apply" class="px-5 py-2.5 font-semibold text-white bg-brand-crimson rounded-lg hover:bg-red-800 transition shadow-sm">Join Studio</a>
            </div>

            <button class="md:hidden text-gray-600 focus:outline-none" id="menu-btn">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>
    </header>

    <section class="relative bg-brand-light py-20 lg:py-32 overflow-hidden">
        <div class="container grid items-center gap-12 px-6 mx-auto max-w-7xl lg:grid-cols-2 relative z-10">
            <div class="space-y-6">
                <div class="inline-flex items-center px-3 py-1 text-sm font-semibold text-brand-crimson bg-red-50 rounded-full">
                    <span class="flex h-2 w-2 rounded-full bg-brand-crimson mr-2 animate-pulse"></span>
                    Now Accepting Applications for 2026 Cohorts
                </div>
                <h1 class="text-4xl font-extrabold tracking-tight text-gray-900 sm:text-5xl lg:text-6xl">
                    Your Gateway to the <span class="text-brand-crimson">US Market</span>.
                </h1>
                <p class="text-lg text-gray-600 max-w-xl">
                    Capetal Labs Inc is a premier Cross-Border Venture Studio built for global startups aiming to scale, fundraise, and plant strong roots in the United States.
                </p>
                <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                    <a href="#apply" class="px-8 py-4 font-semibold text-center text-white bg-brand-crimson rounded-lg hover:bg-red-800 transition shadow-md">
                        Apply Now
                    </a>
                    <a href="#pillars" class="px-8 py-4 font-semibold text-center text-gray-700 bg-white border border-gray-300 rounded-lg hover:bg-gray-50 transition">
                        Our Pillars
                    </a>
                </div>
            </div>
            <div class="flex justify-center relative">
                <div class="absolute inset-0 bg-red-200 rounded-full filter blur-3xl opacity-20 transform -translate-x-10"></div>
                <img src="https://raw.githubusercontent.com/arunvis-cpu/images/main/Capetals%20icon.png" alt="Capetal Labs Motif" class="w-4/5 max-w-md md:w-full opacity-90 filter drop-shadow-xl transform hover:scale-105 transition duration-500">
            </div>
        </div>
    </section>

    <section id="apply" class="py-20 bg-brand-dark text-white">
        <div class="container px-6 mx-auto max-w-3xl">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold sm:text-4xl">Begin Your US Expansion</h2>
                <p class="mt-3 text-gray-400">Our evaluation panel responds within 7 business days.</p>
            </div>

            <form class="p-8 bg-white text-gray-900 rounded-2xl shadow-xl space-y-6">
                <div class="grid gap-6 sm:grid-cols-2">
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Company Name *</label>
                        <input type="text" placeholder="Capetal Labs Inc" required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-brand-crimson outline-none">
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Contact Email *</label>
                        <input type="email" placeholder="founder@company.com" required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-brand-crimson outline-none">
                    </div>
                </div>
                <button type="submit" class="w-full py-4 text-lg font-bold text-white bg-brand-crimson rounded-lg hover:bg-red-800 transition">
                    Submit Application
                </button>
            </form>
        </div>
    </section>

    <footer class="bg-gray-900 text-gray-400 py-12 border-t border-gray-800 text-center">
        <p>&copy; 2026 Capetal Labs Inc. All rights reserved.</p>
    </footer>

    <script>
        const menuBtn = document.getElementById('menu-btn');
        const navMenu = document.getElementById('nav-menu');

        menuBtn.addEventListener('click', () => {
            navMenu.classList.toggle('mobile-nav-active');
            navMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>
