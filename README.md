<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Capetal Labs Inc | US Soft-Landing & Startup Accelerator</title>
    <!-- Tailwind CSS CDN -->
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
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="font-sans text-gray-800 bg-white scroll-smooth">

    <!-- Header / Navigation -->
    <header class="sticky top-0 z-50 bg-white border-b border-gray-100 shadow-sm">
        <div class="container flex items-center justify-between px-6 py-4 mx-auto max-w-7xl">
            <a href="#" class="flex items-center space-x-3">
                <img src="https://github.com/arunvis-cpu/images/blob/main/Capetals%20icon.png?raw=true" alt="Capetal Labs Inc Logo" class="w-10 h-10 object-contain">
                <span class="text-xl font-bold tracking-tight text-brand-dark">Capetal <span class="text-brand-crimson">Labs</span></span>
            </a>
            <nav class="hidden space-x-8 md:flex font-medium text-gray-600 hover:text-gray-900">
                <a href="#about" class="hover:text-brand-crimson transition">About</a>
                <a href="#pillars" class="hover:text-brand-crimson transition">What We Do</a>
                <a href="#space" class="hover:text-brand-crimson transition">Workspace</a>
                <a href="#apply" class="hover:text-brand-crimson transition">Apply</a>
            </nav>
            <div class="hidden md:block">
                <a href="#apply" class="px-5 py-2.5 font-semibold text-white bg-brand-crimson rounded-lg hover:bg-red-800 transition shadow-sm">Join Accelerator</a>
            </div>
            <!-- Mobile Menu Button -->
            <button class="md:hidden text-gray-600 focus:outline-none" id="menu-btn">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>
    </header>

    <!-- Hero Section -->
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
                    Capetal Labs Inc is a premier accelerator built for global startups aiming to scale, fundraise, and plant strong roots in the United States. We turn cross-border ambitions into market realities.
                </p>
                <div class="flex flex-col sm:flex-row space-y-3 sm:space-y-0 sm:space-x-4">
                    <a href="#apply" class="px-8 py-4 font-semibold text-center text-white bg-brand-crimson rounded-lg hover:bg-red-800 transition shadow-md">
                        Apply to Accelerator
                    </a>
                    <a href="#pillars" class="px-8 py-4 font-semibold text-center text-gray-700 bg-white border border-gray-300 rounded-lg hover:bg-gray-50 transition">
                        Explore Our Pillars
                    </a>
                </div>
            </div>
            <div class="flex justify-center relative">
                <div class="absolute inset-0 bg-red-200 rounded-full filter blur-3xl opacity-20 transform -translate-x-10"></div>
                <img src="https://github.com/arunvis-cpu/images/blob/main/Capetals%20icon.png?raw=true" alt="Capetal Labs Motif" class="w-4/5 max-w-md md:w-full opacity-90 filter drop-shadow-xl transform hover:scale-105 transition duration-500">
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container px-6 mx-auto max-w-4xl text-center">
            <h2 class="text-3xl font-bold text-gray-900 sm:text-4xl">Bridging Innovation and Market Scale</h2>
            <div class="w-16 h-1 mx-auto mt-4 bg-brand-crimson rounded"></div>
            <p class="mt-6 text-xl leading-relaxed text-gray-600">
                Establishing a business in the United States presents boundless opportunities, but navigating the regulatory landscape, fundraising ecosystem, and local Go-To-Market (GTM) strategies requires an experienced partner. 
            </p>
            <p class="mt-4 text-lg text-gray-500">
                At Capetal Labs, we don’t just provide capital advice—we offer a holistic ecosystem designed to transform high-potential startups into robust, sustainable US corporate entities.
            </p>
        </div>
    </section>

    <!-- The 6 Pillars of Acceleration Section -->
    <section id="pillars" class="py-20 bg-brand-light">
        <div class="container px-6 mx-auto max-w-7xl">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl font-bold text-gray-900 sm:text-4xl">Our Acceleration Framework</h2>
                <p class="mt-4 text-gray-600">Everything a cross-border founder needs to launch, scale, and thrive in the competitive US landscape.</p>
            </div>

            <div class="grid gap-8 sm:grid-cols-2 lg:grid-cols-3">
                <!-- Pillar 1: GTM -->
                <div class="p-8 bg-white border border-gray-100 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="flex items-center justify-center w-12 h-12 text-white bg-brand-crimson rounded-xl mb-6">
                        <i class="fa-solid fa-chart-line text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Go-To-Market (GTM) Strategy</h3>
                    <p class="text-gray-600">Localized marketing positioning, enterprise customer discovery pipelines, and strategic sales localization engineered for US buyer behavior.</p>
                </div>

                <!-- Pillar 2: Talent Acquisition -->
                <div class="p-8 bg-white border border-gray-100 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="flex items-center justify-center w-12 h-12 text-white bg-brand-crimson rounded-xl mb-6">
                        <i class="fa-solid fa-users text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Talent Acquisition</h3>
                    <p class="text-gray-600">Access to premier US tech and executive talent networks, recruitment pipelines, and compliant employment frameworks for cross-border teams.</p>
                </div>

                <!-- Pillar 3: Fundraising & Capital -->
                <div class="p-8 bg-white border border-gray-100 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="flex items-center justify-center w-12 h-12 text-white bg-brand-crimson rounded-xl mb-6">
                        <i class="fa-solid fa-hand-holding-dollar text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Fundraising & Investor Access</h3>
                    <p class="text-gray-600">Pitch polishing, financial modeling, and targeted warm introductions to leading Silicon Valley VCs, micro-funds, and institutional angel networks.</p>
                </div>

                <!-- Pillar 4: Mentorship -->
                <div class="p-8 bg-white border border-gray-100 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="flex items-center justify-center w-12 h-12 text-white bg-brand-crimson rounded-xl mb-6">
                        <i class="fa-solid fa-chalkboard-user text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Elite Mentorship</h3>
                    <p class="text-gray-600">Regular 1-on-1 operational reviews with battle-tested entrepreneurs, corporate executives, and regulatory compliance specialists.</p>
                </div>

                <!-- Pillar 5: Workspace -->
                <div class="p-8 bg-white border border-gray-100 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="flex items-center justify-center w-12 h-12 text-white bg-brand-crimson rounded-xl mb-6">
                        <i class="fa-solid fa-laptop-code text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">US Physical Footprint</h3>
                    <p class="text-gray-600">Dedicated desk space, collaborative meeting rooms, and professional mailing addresses to anchor your corporate presence locally.</p>
                </div>

                <!-- Pillar 6: Foundational Education -->
                <div class="p-8 bg-white border border-gray-100 rounded-2xl shadow-sm hover:shadow-md transition">
                    <div class="flex items-center justify-center w-12 h-12 text-white bg-brand-crimson rounded-xl mb-6">
                        <i class="fa-solid fa-graduation-cap text-xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-2">Foundational Education</h3>
                    <p class="text-gray-600">Structured masterclasses covering US corporate governance, corporate tax alignment, intellectual property, and compliance structures.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Working Space Spotlight Section -->
    <section id="space" class="py-20 bg-white">
        <div class="container grid items-center gap-12 px-6 mx-auto max-w-7xl lg:grid-cols-2">
            <div class="space-y-6">
                <h2 class="text-3xl font-bold text-gray-900 sm:text-4xl">A Launchpad with a Physical Address</h2>
                <p class="text-gray-600 text-lg">
                    Collaboration happens best in environments built for productivity. Capetal Labs provides dynamic, turn-key working spaces designed for international founders to scale up teams, host customer syncs, or iterate alongside other visionary founders.
                </p>
                <ul class="space-y-3 font-medium text-gray-700">
                    <li class="flex items-center"><i class="fa-solid fa-check text-brand-crimson mr-3"></i> Premium Coworking Desks & High-Speed Utilities</li>
                    <li class="flex items-center"><i class="fa-solid fa-check text-brand-crimson mr-3"></i> Private Meeting Rooms for Board Reviews & Pitch Calls</li>
                    <li class="flex items-center"><i class="fa-solid fa-check text-brand-crimson mr-3"></i> Vibrant Ecosystem of Local Peer Entrepreneurs</li>
                </ul>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <div class="h-48 bg-gray-200 rounded-2xl overflow-hidden relative">
                    <div class="absolute inset-0 bg-brand-dark opacity-40"></div>
                    <div class="absolute bottom-4 left-4 text-white font-bold text-sm">Meeting Suites</div>
                </div>
                <div class="h-48 bg-gray-300 rounded-2xl overflow-hidden relative mt-6">
                    <div class="absolute inset-0 bg-brand-crimson opacity-20"></div>
                    <div class="absolute bottom-4 left-4 text-white font-bold text-sm">Hot Desks</div>
                </div>
                <div class="h-48 bg-gray-300 rounded-2xl overflow-hidden relative -mt-6">
                    <div class="absolute inset-0 bg-brand-dark opacity-30"></div>
                    <div class="absolute bottom-4 left-4 text-white font-bold text-sm">Collab Lounges</div>
                </div>
                <div class="h-48 bg-gray-200 rounded-2xl overflow-hidden relative">
                    <div class="absolute inset-0 bg-brand-crimson opacity-40"></div>
                    <div class="absolute bottom-4 left-4 text-white font-bold text-sm">Pitch Theaters</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Application Form Section -->
    <section id="apply" class="py-20 bg-brand-dark text-white relative">
        <div class="container px-6 mx-auto max-w-3xl relative z-10">
            <div class="text-center mb-12">
                <img src="https://github.com/arunvis-cpu/images/blob/main/Capetals%20icon.png?raw=true" alt="Capetal Icon" class="w-12 h-12 mx-auto mb-4 filter brightness-0 invert opacity-90">
                <h2 class="text-3xl font-bold sm:text-4xl">Begin Your US Expansion</h2>
                <p class="mt-3 text-gray-400">Tell us briefly about your startup. Our cross-border evaluation panel responds to chosen applicants within 7 business days.</p>
            </div>

            <form class="p-8 bg-white text-gray-900 rounded-2xl shadow-xl space-y-6">
                <div class="grid gap-6 sm:grid-cols-2">
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Company Name *</label>
                        <input type="text" placeholder="Capetal Labs Inc" required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-crimson">
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Founder / Contact Name *</label>
                        <input type="text" placeholder="John Doe" required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-crimson">
                    </div>
                </div>

                <div class="grid gap-6 sm:grid-cols-2">
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Contact Email *</label>
                        <input type="email" placeholder="founder@company.com" required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-crimson">
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-gray-700 mb-1">Current Corporate Location *</label>
                        <input type="text" placeholder="e.g., Chennai, London, Toronto" required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-crimson">
                    </div>
                </div>

                <div>
                    <label class="block text-sm font-semibold text-gray-700 mb-1">What is your primary acceleration requirement?</label>
                    <select class="w-full px-4 py-2.5 border border-gray-300 rounded-lg bg-white focus:outline-none focus:ring-2 focus:ring-brand-crimson">
                        <option>Go-To-Market (GTM) Strategy & Customer Acquisition</option>
                        <option>Fundraising & Pitch Preparation</option>
                        <option>Talent Acquisition & Executive Hiring</option>
                        <option>US Office Working Space & Compliance</option>
                        <option>Comprehensive Cross-Border Soft Landing</option>
                    </select>
                </div>

                <div>
                    <label class="block text-sm font-semibold text-gray-700 mb-1">Brief Description of Product & Traction *</label>
                    <textarea rows="4" placeholder="Tell us about what you build, your current market metrics, and your roadmap for entering the US market..." required class="w-full px-4 py-2.5 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-brand-crimson"></textarea>
                </div>

                <div>
                    <button type="submit" class="w-full py-4 text-lg font-bold text-white bg-brand-crimson rounded-lg hover:bg-red-800 transition shadow-md">
                        Submit Application to Accelerator
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-12 border-t border-gray-800">
        <div class="container flex flex-col items-center justify-between px-6 mx-auto max-w-7xl sm:flex-row space-y-4 sm:space-y-0">
            <div class="flex items-center space-x-3">
                <img src="https://github.com/arunvis-cpu/images/blob/main/Capetals%20icon.png?raw=true" alt="Capetal Labs Footer Icon" class="w-8 h-8 filter brightness-0 invert opacity-60">
                <span class="text-lg font-bold text-white tracking-tight">Capetal <span class="text-brand-crimson">Labs</span></span>
            </div>
            <p class="text-sm text-center">&copy; 2026 Capetal Labs Inc. All rights reserved. Empowering global ventures to scale responsibly.</p>
            <div class="flex space-x-4 text-lg">
                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-linkedin"></i></a>
                <a href="#" class="hover:text-white transition"><i class="fa-brands fa-x-twitter"></i></a>
            </div>
        </div>
    </footer>

    <!-- Mobile Menu Toggle -->
    <script>
        const menuBtn = document.getElementById('menu-btn');
        const nav = document.querySelector('nav');
        menuBtn.addEventListener('click', () => {
            nav.classList.toggle('hidden');
            nav.classList.toggle('flex');
            nav.classList.toggle('flex-col');
            nav.classList.toggle('absolute');
            nav.classList.toggle('top-16');
            nav.classList.toggle('left-0');
            nav.classList.toggle('w-full');
            nav.classList.toggle('bg-white');
            nav.classList.toggle('p-6');
            nav.classList.toggle('shadow-lg');
            nav.classList.toggle('space-y-4');
        });
    </script>
</body>
</html>

