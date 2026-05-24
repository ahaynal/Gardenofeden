# Gardenofeden<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Garden of Eden Yard Service LLC | Honolulu</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <style>
    body { font-family: 'Segoe UI', system-ui, sans-serif; }
    .hero-bg {
      background-image: linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.55)), url('https://picsum.photos/id/1015/2000/1200');
      background-size: cover;
      background-position: center;
    }
    .testimonial-card {
      transition: all 0.3s ease;
    }
    .testimonial-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
    }
  </style>
</head>
<body class="bg-emerald-50 text-emerald-950">

  <!-- Navbar -->
  <nav class="bg-emerald-900 text-white sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="flex items-center gap-4">
        <img src="logo.png" alt="Garden of Eden Yard Service LLC" class="h-16 w-auto">
        <div class="hidden sm:block">
          <h1 class="text-2xl font-bold">Garden of Eden</h1>
          <p class="text-xs text-emerald-300 -mt-1">Yard Service LLC</p>
        </div>
      </div>
      <div class="hidden md:flex gap-8 text-lg">
        <a href="#services" class="hover:text-emerald-400 transition">Services</a>
        <a href="#testimonials" class="hover:text-emerald-400 transition">Testimonials</a>
        <a href="#areas" class="hover:text-emerald-400 transition">Areas</a>
        <a href="#contact" class="hover:text-emerald-400 transition">Contact</a>
      </div>
      <a href="tel:8087079577" class="bg-emerald-500 hover:bg-emerald-600 px-6 py-3 rounded-full font-semibold transition">
        Call (808) 707-9577
      </a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero-bg h-screen flex items-center text-white">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <img src="logo.png" alt="Garden of Eden Yard Service" class="mx-auto mb-8 h-32 w-auto opacity-90">
      
      <h2 class="text-6xl md:text-7xl font-bold mb-4">Nature Perfected</h2>
      <p class="text-3xl md:text-4xl mb-6 text-emerald-100">Premium Landscaping & Yard Care in Honolulu</p>
      
      <div class="mb-8">
        <span class="inline-block bg-emerald-600 text-white text-xl font-semibold px-8 py-3 rounded-full">
          ✅ FREE QUOTE
        </span>
      </div>

      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <a href="#contact" class="bg-emerald-600 hover:bg-emerald-700 text-white text-xl px-10 py-5 rounded-full font-semibold transition">
          Get Your Free Quote Today
        </a>
        <a href="tel:8087079577" class="border-2 border-white hover:bg-white hover:text-emerald-900 text-xl px-10 py-5 rounded-full font-semibold transition">
          (808) 707-9577
        </a>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold text-center mb-4">Our Services</h2>
      <p class="text-center text-xl text-emerald-700 mb-12">Professional yard care with attention to every detail • Free quotes on all jobs</p>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="bg-emerald-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-cut text-4xl text-emerald-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-2">Lawn Maintenance</h3>
          <p class="text-emerald-700">Mowing, edging, fertilization & seasonal care</p>
        </div>
        <div class="bg-emerald-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-broom text-4xl text-emerald-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-2">Detail Work</h3>
          <p class="text-emerald-700">Weeding, trimming, and pristine finishing touches</p>
        </div>
        <div class="bg-emerald-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-tree text-4xl text-emerald-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-2">Tree Trimming</h3>
          <p class="text-emerald-700">Safe, clean pruning and removal services</p>
        </div>
        <div class="bg-emerald-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-leaf text-4xl text-emerald-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-2">Yard Cleanup</h3>
          <p class="text-emerald-700">Debris removal and property refresh</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="py-20 bg-emerald-50">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold text-center mb-4">What Our Customers Say</h2>
      <p class="text-center text-xl text-emerald-700 mb-12">Trusted by homeowners across Oahu</p>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="testimonial-card bg-white p-8 rounded-3xl shadow-md">
          <div class="flex text-yellow-400 mb-4">★★★★☆</div>
          <p class="text-emerald-800 italic mb-6">"Austin transformed our overgrown yard into a beautiful, low-maintenance paradise. Professional, reliable, and truly cares about the result. Best landscaping service on Oahu!"</p>
          <div class="flex items-center gap-3">
            <div class="w-12 h-12 bg-emerald-200 rounded-full flex items-center justify-center text-xl">🌺</div>
            <div>
              <p class="font-semibold">Sarah K.</p>
              <p class="text-sm text-emerald-600">Kahala</p>
            </div>
          </div>
        </div>

        <div class="testimonial-card bg-white p-8 rounded-3xl shadow-md">
          <div class="flex text-yellow-400 mb-4">★★★★★</div>
          <p class="text-emerald-800 italic mb-6">"Incredible attention to detail! Our lawn has never looked better. Austin is punctual, respectful, and does quality work every time. Highly recommend for anyone in East Honolulu."</p>
          <div class="flex items-center gap-3">
            <div class="w-12 h-12 bg-emerald-200 rounded-full flex items-center justify-center text-xl">🌴</div>
            <div>
              <p class="font-semibold">Michael Chen</p>
              <p class="text-sm text-emerald-600">Hawaii Kai</p>
            </div>
          </div>
        </div>

        <div class="testimonial-card bg-white p-8 rounded-3xl shadow-md">
          <div class="flex text-yellow-400 mb-4">★★★★★</div>
          <p class="text-emerald-800 italic mb-6">"Tree trimming and yard cleanup were done perfectly. Garden of Eden made our property look brand new. Fair pricing and excellent communication. We'll be using them for years!"</p>
          <div class="flex items-center gap-3">
            <div class="w-12 h-12 bg-emerald-200 rounded-full flex items-center justify-center text-xl">🌿</div>
            <div>
              <p class="font-semibold">Lisa Thompson</p>
              <p class="text-sm text-emerald-600">Manoa</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Areas Served -->
  <section id="areas" class="py-20 bg-emerald-800 text-white">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-5xl font-bold mb-8">Proudly Serving Oahu</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 max-w-4xl mx-auto">
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Honolulu</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Diamond Head</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Kahala</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Hawaii Kai</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Manoa</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Palolo</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Aina Haina</div>
        <div class="bg-emerald-700 py-6 px-8 rounded-2xl">Portlock</div>
      </div>
      <p class="mt-10 text-emerald-100 text-xl">Free quotes for all areas above</p>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold text-center mb-4">Get Your Free Quote</h2>
      <p class="text-center text-xl text-emerald-700 mb-12">Fast response • Honest pricing • No obligation</p>
      
      <div class="grid md:grid-cols-2 gap-12">
        <div>
          <div class="space-y-8">
            <div class="flex items-start gap-6">
              <i class="fas fa-phone text-4xl text-emerald-600 mt-1"></i>
              <div>
                <p class="font-semibold text-xl">(808) 707-9577</p>
                <p class="text-emerald-700">Call or Text</p>
              </div>
            </div>
            <div class="flex items-start gap-6">
              <i class="fas fa-envelope text-4xl text-emerald-600 mt-1"></i>
              <div>
                <p class="font-semibold text-xl">ahaynal@yahoo.com</p>
                <p class="text-emerald-700">Send us a message</p>
              </div>
            </div>
          </div>
        </div>

        <form action="https://formspree.io/f/your-email-here" method="POST" class="space-y-6">
          <input type="text" name="name" placeholder="Your Name" required class="w-full px-6 py-4 border border-emerald-200 rounded-2xl focus:outline-none focus:border-emerald-600">
          <input type="email" name="email" placeholder="Email Address" required class="w-full px-6 py-4 border border-emerald-200 rounded-2xl focus:outline-none focus:border-emerald-600">
          <input type="tel" name="phone" placeholder="Phone Number" class="w-full px-6 py-4 border border-emerald-200 rounded-2xl focus:outline-none focus:border-emerald-600">
          <textarea name="message" rows="5" placeholder="Tell us about your yard or service needs..." required class="w-full px-6 py-4 border border-emerald-200 rounded-2xl focus:outline-none focus:border-emerald-600"></textarea>
          <button type="submit" class="w-full bg-emerald-700 hover:bg-emerald-800 text-white py-5 rounded-2xl text-xl font-semibold transition">
            Request Free Quote
          </button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-emerald-950 text-emerald-300 py-12">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <img src="logo.png" alt="Garden of Eden Yard Service LLC" class="mx-auto mb-6 h-20 w-auto opacity-80">
      <p class="text-2xl font-semibold mb-2">"Nature Perfected"</p>
      <p>Honolulu, Hawaii • Licensed & Insured</p>
      <p class="mt-6 text-emerald-400 font-medium">Free Quotes • Reliable Service</p>
      <p class="mt-8 text-sm">&copy; 2026 Garden of Eden Yard Service LLC. All Rights Reserved.</p>
    </div>
  </footer>

</body>
</html>
