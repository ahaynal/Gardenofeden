<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Garden of Eden Yard Service | Nature Perfected</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <style>
    .hero-bg {
      background-image: linear-gradient(rgba(0,0,0,0.55), rgba(0,0,0,0.55)), url('https://source.unsplash.com/random/1920x1080/?hawaii,landscape,garden');
      background-size: cover;
      background-position: center;
    }
    .flag {
      filter: drop-shadow(0 4px 6px rgba(0,0,0,0.3));
    }
  </style>
</head>
<body class="font-sans bg-gray-50 text-gray-800">

  <!-- Navbar -->
  <nav class="bg-green-900 text-white sticky top-0 z-50 shadow-lg">
    <div class="max-w-7xl mx-auto px-6 py-5 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <span class="text-3xl">🌴</span>
        <div>
          <h1 class="text-2xl font-bold">Garden of Eden</h1>
          <p class="text-green-300 text-sm -mt-1">Yard Service</p>
        </div>
      </div>
      <div class="space-x-8 text-lg">
        <a href="#services" class="hover:text-green-300 transition">Services</a>
        <a href="#areas" class="hover:text-green-300 transition">Areas</a>
        <a href="#testimonials" class="hover:text-green-300 transition">Reviews</a>
        <a href="#contact" class="hover:text-green-300 transition">Contact</a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero-bg h-screen flex items-center text-white">
    <div class="max-w-5xl mx-auto text-center px-6">
      <img src="hawaii-flag.png" alt="Hawaii Flag" class="flag mx-auto mb-6 w-48">
      <h2 class="text-6xl md:text-7xl font-bold mb-4">Nature Perfected</h2>
      <p class="text-2xl mb-8">Professional Landscaping & Yard Care in Honolulu & East Oahu</p>
      <a href="#contact" class="bg-green-600 hover:bg-green-700 text-white px-10 py-5 rounded-full text-xl font-semibold inline-flex items-center gap-3">
        <i class="fas fa-phone"></i> Get a Free Quote Today
      </a>
      <p class="mt-6 text-lg">(808) 707-9577</p>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold text-center mb-4 text-green-900">Our Services</h2>
      <p class="text-center text-xl text-gray-600 mb-12">Expert care for your Hawaiian paradise</p>
      
      <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="bg-gray-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-cut text-4xl text-green-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-3">Lawn Maintenance</h3>
          <p class="text-gray-600">Mowing, edging, fertilizing, and weed control for lush, healthy lawns.</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-tools text-4xl text-green-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-3">Detail Work</h3>
          <p class="text-gray-600">Trimming, pruning, and meticulous yard cleanup for a polished look.</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-tree text-4xl text-green-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-3">Tree Trimming</h3>
          <p class="text-gray-600">Safe, professional tree trimming and removal to keep your property beautiful and safe.</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl hover:shadow-xl transition">
          <i class="fas fa-broom text-4xl text-green-600 mb-4"></i>
          <h3 class="text-2xl font-semibold mb-3">Yard Cleanup</h3>
          <p class="text-gray-600">Complete property cleanup, debris removal, and seasonal maintenance.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Service Areas -->
  <section id="areas" class="py-20 bg-green-50">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-10">Proudly Serving East Oahu</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 text-center">
        <div class="bg-white p-6 rounded-xl shadow">Honolulu</div>
        <div class="bg-white p-6 rounded-xl shadow">Diamond Head</div>
        <div class="bg-white p-6 rounded-xl shadow">Kahala</div>
        <div class="bg-white p-6 rounded-xl shadow">Manoa</div>
        <div class="bg-white p-6 rounded-xl shadow">Palolo</div>
        <div class="bg-white p-6 rounded-xl shadow">Aina Haina</div>
        <div class="bg-white p-6 rounded-xl shadow">Portlock</div>
        <div class="bg-white p-6 rounded-xl shadow">Kailua</div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-5xl font-bold text-center mb-12 text-green-900">What Our Clients Say</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-gray-50 p-8 rounded-3xl">
          <p class="italic mb-6">"Garden of Eden transformed our overgrown yard into a beautiful, low-maintenance oasis. Professional, reliable, and truly care about their work!"</p>
          <p class="font-semibold">— Michael K., Kahala</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-3xl">
          <p class="italic mb-6">"Best yard service on Oahu! They do such detail-oriented work. Our lawn has never looked better. Highly recommend!"</p>
          <p class="font-semibold">— Sarah L., Aina Haina</p>
        </div>
        <div class="bg-gray-50 p-8 rounded-3xl">
          <p class="italic mb-6">"Fast response, fair pricing, and excellent results every time. They even helped with tree trimming after the last storm. True professionals."</p>
          <p class="font-semibold">— David P., Kailua</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-20 bg-green-900 text-white">
    <div class="max-w-4xl mx-auto text-center px-6">
      <h2 class="text-5xl font-bold mb-8">Ready for a Beautiful Yard?</h2>
      <p class="text-2xl mb-10">Call or email us for a free quote</p>
      
      <div class="flex flex-col md:flex-row gap-8 justify-center items-center text-xl">
        <a href="tel:8087079577" class="flex items-center gap-4 hover:text-green-300 transition">
          <i class="fas fa-phone text-3xl"></i>
          <div>
            <div class="font-semibold">(808) 707-9577</div>
          </div>
        </a>
        <a href="mailto:ahaynal@yahoo.com" class="flex items-center gap-4 hover:text-green-300 transition">
          <i class="fas fa-envelope text-3xl"></i>
          <div>ahaynal@yahoo.com</div>
        </a>
      </div>

      <div class="mt-16">
        <p class="text-sm opacity-75">Garden of Eden Yard Service • Honolulu, Hawaii</p>
      </div>
    </div>
  </section>

  <footer class="bg-green-950 text-white py-8 text-center text-sm">
    © 2026 Garden of Eden Yard Service. All Rights Reserved. Proudly serving East Oahu.
  </footer>
</body>
</html>
