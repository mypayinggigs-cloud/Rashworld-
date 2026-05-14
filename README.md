<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rashworld Premium Shoemaker | Awoyé Culture</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    
    <style>
        :root {
            --coffee-dark: #3E2723;
            --coffee-medium: #5D4037;
            --milky-cream: #F5F5DC;
            --milky-white: #FAF9F6;
            --gold-accent: #C5A059;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--milky-white);
            color: var(--coffee-dark);
            scroll-behavior: smooth;
        }

        h1, h2, h3, .serif {
            font-family: 'Playfair Display', serif;
        }

        .bg-coffee { background-color: var(--coffee-dark); }
        .text-coffee { color: var(--coffee-dark); }
        .bg-milky { background-color: var(--milky-cream); }
        .border-gold { border-color: var(--gold-accent); }
        
        .hero-gradient {
            background: linear-gradient(rgba(62, 39, 35, 0.8), rgba(62, 39, 35, 0.8)), 
                        url('https://images.unsplash.com/photo-1595950653106-6c9ebd614d3a?q=80&w=1974&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
        }

        .card-hover:hover {
            transform: translateY(-10px);
            transition: all 0.3s ease;
            box-shadow: 0 20px 25px -5px rgba(62, 39, 35, 0.1);
        }

        .btn-whatsapp {
            background-color: #25D366;
            transition: transform 0.2s;
        }
        .btn-whatsapp:hover { transform: scale(1.05); }

        .image-overlay {
            position: relative;
            overflow: hidden;
            border-radius: 1rem;
        }
        .image-overlay img { transition: transform 0.5s ease; }
        .image-overlay:hover img { transform: scale(1.1); }
    </style>
</head>
<body class="overflow-x-hidden">

    <nav class="fixed w-full z-50 bg-white/80 backdrop-blur-md border-b border-stone-200">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex flex-col">
                <span class="text-2xl font-bold tracking-tighter text-coffee uppercase">Rashworld</span>
                <span class="text-[10px] tracking-[0.2em] uppercase text-stone-500 font-semibold">Premium Shoemaker</span>
            </div>
            <div class="hidden md:flex space-x-8 font-medium uppercase text-xs tracking-widest">
                <a href="#about" class="hover:text-amber-700 transition">The Artisan</a>
                <a href="#music" class="hover:text-amber-700 transition">The Band</a>
                <a href="#gallery" class="hover:text-amber-700 transition">Gallery</a>
                <a href="#contact" class="hover:text-amber-700 transition">Bookings</a>
            </div>
            <a href="https://wa.me/2347054505514" class="bg-coffee text-white px-6 py-2 rounded-full text-sm font-semibold hover:bg-stone-800 transition">
                WhatsApp
            </a>
        </div>
    </nav>

    <section class="relative h-screen flex items-center justify-center text-white hero-gradient">
        <div class="text-center px-6 max-w-4xl animate-fade-in">
            <h4 class="uppercase tracking-[0.4em] text-gold-accent mb-4 font-semibold text-sm">The Art of Walking. The Soul of Sound.</h4>
            <h1 class="text-5xl md:text-8xl mb-6 leading-tight">Craftsmanship <span class="italic font-normal">Meets</span> Rhythm</h1>
            <p class="text-lg md:text-xl text-stone-200 mb-10 max-w-2xl mx-auto leading-relaxed">
                By day, OKUNLOLA Abdulrasheed stitches excellence into every hide. By night, he breathes life into Awoyé Culture. Premium footwear and soulful melodies, hand-crafted for you.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="#gallery" class="bg-white text-coffee px-8 py-4 rounded-full font-bold uppercase tracking-wider hover:bg-stone-100 transition">View Bespoke Collection</a>
                <a href="#contact" class="border-2 border-white px-8 py-4 rounded-full font-bold uppercase tracking-wider hover:bg-white hover:text-coffee transition">Book a Consultation</a>
            </div>
        </div>
    </section>

    <section id="about" class="py-24 px-6 bg-milky">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 items-center">
            <div class="image-overlay h-[600px]">
                <img src="https://images.unsplash.com/photo-1533174072545-7a4b6ad7a6c3?q=80&w=2070&auto=format&fit=crop" 
                     alt="Abdulrasheed at work" class="w-full h-full object-cover">
                <div class="absolute bottom-6 left-6 bg-white p-6 rounded-lg shadow-xl">
                    <p class="text-coffee font-bold text-xl">OKUNLOLA Abdulrasheed</p>
                    <p class="text-stone-500 text-sm italic">Master Shoemaker & Band Leader</p>
                </div>
            </div>
            <div>
                <h2 class="text-4xl md:text-5xl mb-8 text-coffee">Two Worlds, <br><span class="italic">One Visionary Spirit.</span></h2>
                <div class="space-y-6 text-stone-700 leading-relaxed text-lg">
                    <p>
                        Rashworld is more than a brand; it is a testament to the precision of the human hand. Abdulrasheed approaches shoemaking with the same rhythmic intensity he brings to the stage with **Awoyé Culture**.
                    </p>
                    <p>
                        Every stitch is a note, and every pair of shoes is a performance. We specialize in premium, custom-fit footwear that carries the heritage of Nigerian craftsmanship into the modern global stage.
                    </p>
                    <div class="grid grid-cols-2 gap-4 pt-4">
                        <div class="border-l-4 border-gold p-4 bg-white rounded-r-lg">
                            <h4 class="font-bold text-coffee uppercase text-xs tracking-widest mb-1">Leather Work</h4>
                            <p class="text-sm">Bespoke Italian & Local Leather Mastery</p>
                        </div>
                        <div class="border-l-4 border-gold p-4 bg-white rounded-r-lg">
                            <h4 class="font-bold text-coffee uppercase text-xs tracking-widest mb-1">Awoyé Culture</h4>
                            <p class="text-sm">Afro-Fusion & Cultural Band Performances</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="py-24 px-6 bg-white">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl text-coffee mb-4">Our Services</h2>
                <div class="w-24 h-1 bg-gold-accent mx-auto"></div>
            </div>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Shoemaking -->
                <div class="p-8 border border-stone-100 rounded-3xl bg-milky card-hover">
                    <div class="w-16 h-16 bg-coffee text-white flex items-center justify-center rounded-2xl mb-6 text-2xl">
                        <i class="fas fa-shoe-prints"></i>
                    </div>
                    <h3 class="text-2xl mb-4">Bespoke Shoemaking</h3>
                    <p class="text-stone-600 mb-6">Hand-measured and hand-lasted shoes built specifically for your feet using the finest textures.</p>
                    <a href="https://wa.me/2347054505514" class="text-coffee font-bold underline underline-offset-8">Start Your Order</a>
                </div>

                <!-- Music -->
                <div class="p-8 border border-stone-100 rounded-3xl bg-milky card-hover">
                    <div class="w-16 h-16 bg-amber-800 text-white flex items-center justify-center rounded-2xl mb-6 text-2xl">
                        <i class="fas fa-music"></i>
                    </div>
                    <h3 class="text-2xl mb-4">Band Bookings</h3>
                    <p class="text-stone-600 mb-6">Bring the vibrant energy of Awoyé Culture to your weddings, festivals, and corporate events.</p>
                    <a href="https://wa.me/2347054505514" class="text-coffee font-bold underline underline-offset-8">Book the Band</a>
                </div>

                <!-- Consulting -->
                <div class="p-8 border border-stone-100 rounded-3xl bg-milky card-hover">
                    <div class="w-16 h-16 bg-stone-400 text-white flex items-center justify-center rounded-2xl mb-6 text-2xl">
                        <i class="fas fa-handshake"></i>
                    </div>
                    <h3 class="text-2xl mb-4">Consultation</h3>
                    <p class="text-stone-600 mb-6">Get professional advice on leather care, fashion styling, or musical arrangement for your project.</p>
                    <a href="https://wa.me/2347054505514" class="text-coffee font-bold underline underline-offset-8">Get Expert Advice</a>
                </div>
            </div>
        </div>
    </section>

    <section id="gallery" class="py-24 px-6 bg-coffee text-white">
        <div class="max-w-7xl mx-auto text-center mb-16">
            <h2 class="text-4xl md:text-5xl mb-4 text-milky-cream">The Masterpieces</h2>
            <p class="text-stone-400 italic">Capturing the soul of craft and sound</p>
        </div>
        
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
            <!-- Shoe Item -->
            <div class="image-overlay h-64 md:h-80">
                <img src="https://images.unsplash.com/photo-1549298916-b41d501d3772?q=80&w=2012&auto=format&fit=crop" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-700">
            </div>
            <!-- Music Item -->
            <div class="image-overlay h-64 md:h-80 col-span-2">
                <img src="https://images.unsplash.com/photo-1514525253361-bee8d400c07c?q=80&w=1964&auto=format&fit=crop" class="w-full h-full object-cover">
                <div class="absolute inset-0 bg-black/40 flex items-end p-6">
                    <span class="text-xs tracking-[0.3em] font-bold uppercase">Awoyé Live</span>
                </div>
            </div>
            <!-- Shoe Item -->
            <div class="image-overlay h-64 md:h-80">
                <img src="https://images.unsplash.com/photo-1614252235316-8c857d38b5f4?q=80&w=1930&auto=format&fit=crop" class="w-full h-full object-cover grayscale hover:grayscale-0 transition duration-700">
            </div>
            <!-- Shoe Item -->
            <div class="image-overlay h-64 md:h-80 col-span-2">
                <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=2070&auto=format&fit=crop" class="w-full h-full object-cover">
            </div>
            <!-- Music Item -->
            <div class="image-overlay h-64 md:h-80">
                <img src="https://images.unsplash.com/photo-1508700115892-45ecd05ae2ad?q=80&w=2069&auto=format&fit=crop" class="w-full h-full object-cover">
            </div>
            <!-- Shoe Item -->
            <div class="image-overlay h-64 md:h-80">
                <img src="https://images.unsplash.com/photo-1449247709967-d4461a6a6103?q=80&w=2071&auto=format&fit=crop" class="w-full h-full object-cover">
            </div>
        </div>
    </section>

    <section id="contact" class="py-24 px-6 bg-milky-white">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-20">
            <div>
                <h2 class="text-4xl md:text-5xl text-coffee mb-6">Ready to Step <br>Into Excellence?</h2>
                <p class="text-stone-600 mb-10 text-lg">For bespoke shoes, music bookings, or consultation, please fill out the form or reach out directly on social media.</p>
                
                <div class="space-y-6">
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-coffee/10 flex items-center justify-center text-coffee">
                            <i class="fas fa-location-dot"></i>
                        </div>
                        <p class="font-semibold">Lagos, Nigeria | Global Delivery</p>
                    </div>
                    <div class="flex items-center gap-4">
                        <div class="w-12 h-12 rounded-full bg-coffee/10 flex items-center justify-center text-coffee">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <p class="font-semibold">contact@rashworld.com</p>
                    </div>
                </div>

                <div class="mt-12">
                    <h4 class="uppercase tracking-widest text-xs font-bold text-stone-400 mb-4">Follow the Culture</h4>
                    <div class="flex gap-4">
                        <a href="https://www.facebook.com/share/1AzuV17Y98/" class="w-12 h-12 rounded-full bg-white shadow-md flex items-center justify-center text-coffee hover:bg-coffee hover:text-white transition">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="https://www.tiktok.com/@rashworld007?_r=1&_t=ZS-96LvjM4aAuw" class="w-12 h-12 rounded-full bg-white shadow-md flex items-center justify-center text-coffee hover:bg-coffee hover:text-white transition">
                            <i class="fab fa-tiktok"></i>
                        </a>
                        <a href="https://wa.me/2347054505514" class="w-12 h-12 rounded-full bg-green-500 shadow-md flex items-center justify-center text-white hover:scale-110 transition">
                            <i class="fab fa-whatsapp"></i>
                        </a>
                    </div>
                </div>
            </div>

            <div class="bg-white p-10 rounded-3xl shadow-2xl border border-stone-100">
                <form id="contactForm" class="space-y-6">
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-widest mb-2 text-stone-500">Full Name</label>
                        <input type="text" placeholder="Your Name" class="w-full px-6 py-4 rounded-xl bg-stone-50 border-none focus:ring-2 focus:ring-amber-800 outline-none transition">
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-widest mb-2 text-stone-500">Service Interest</label>
                        <select class="w-full px-6 py-4 rounded-xl bg-stone-50 border-none focus:ring-2 focus:ring-amber-800 outline-none transition">
                            <option>Bespoke Shoemaking</option>
                            <option>Awoyé Band Booking</option>
                            <option>Creative Consultation</option>
                            <option>General Enquiry</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-widest mb-2 text-stone-500">Message</label>
                        <textarea rows="4" placeholder="Tell us about your needs..." class="w-full px-6 py-4 rounded-xl bg-stone-50 border-none focus:ring-2 focus:ring-amber-800 outline-none transition"></textarea>
                    </div>
                    <button type="button" onclick="handleForm()" class="w-full bg-coffee text-white font-bold py-5 rounded-xl uppercase tracking-widest hover:bg-stone-800 transition">
                        Send Inquiry
                    </button>
                    <p class="text-center text-xs text-stone-400 mt-4">Or click the floating WhatsApp button for instant chat.</p>
                </form>
            </div>
        </div>
    </section>

    <footer class="py-12 px-6 border-t border-stone-100 text-center">
        <p class="text-coffee font-bold text-lg mb-2">RASHWORLD & AWOYÉ CULTURE</p>
        <p class="text-stone-500 text-sm">© 2024. Hand-stitched and rhythm-infused. All rights reserved.</p>
    </footer>

    <!-- Floating WA -->
    <a href="https://wa.me/2347054505514" class="fixed bottom-8 right-8 btn-whatsapp text-white w-16 h-16 rounded-full flex items-center justify-center shadow-2xl z-[60] text-3xl">
        <i class="fab fa-whatsapp"></i>
    </a>

    <script>
        function handleForm() {
            // Simple logic to redirect to WA with a pre-filled message
            const name = document.querySelector('input[type="text"]').value || "Guest";
            const service = document.querySelector('select').value;
            const message = `Hello Rashworld! My name is ${name}. I am interested in ${service}.`;
            const waUrl = `https://wa.me/2347054505514?text=${encodeURIComponent(message)}`;
            
            window.open(waUrl, '_blank');
        }

        // Smooth scroll reveal animation
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 50) {
                nav.classList.add('py-2', 'shadow-md');
                nav.classList.remove('py-4');
            } else {
                nav.classList.remove('py-2', 'shadow-md');
                nav.classList.add('py-4');
            }
        });
    </script>

</body>
</html>
