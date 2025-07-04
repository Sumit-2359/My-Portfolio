<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Creative Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Custom scrollbar for smooth experience */
    ::-webkit-scrollbar {
      width: 8px;
    }
    ::-webkit-scrollbar-thumb {
      background-color: #4F46E5;
      border-radius: 10px;
    }
  </style>
  <link rel="manifest" href="manifest.json" />
</head>
<body class="bg-gray-900 text-gray-100 font-sans">

  <!-- Navbar -->
  <nav class="fixed w-full bg-gray-800 bg-opacity-80 backdrop-blur-md z-50">
    <div class="max-w-7xl mx-auto flex justify-between items-center p-4">
      <a href="#" class="text-2xl font-bold text-indigo-500">MyPortfolio</a>
      <ul class="hidden md:flex space-x-8 text-lg">
        <li><a href="#about" class="hover:text-indigo-400 transition">About</a></li>
        <li><a href="#projects" class="hover:text-indigo-400 transition">Projects</a></li>
        <li><a href="#contact" class="hover:text-indigo-400 transition">Contact</a></li>
      </ul>
      <button id="menuBtn" class="md:hidden text-indigo-400 focus:outline-none">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8h16M4 16h16"/>
        </svg>
      </button>
    </div>
    <div id="mobileMenu" class="hidden md:hidden bg-gray-700">
      <ul class="flex flex-col space-y-4 p-4 text-lg">
        <li><a href="#about" class="block hover:text-indigo-400 transition">About</a></li>
        <li><a href="#projects" class="block hover:text-indigo-400 transition">Projects</a></li>
        <li><a href="#contact" class="block hover:text-indigo-400 transition">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="min-h-screen flex flex-col justify-center items-center text-center px-6 bg-gradient-to-r from-indigo-900 via-purple-900 to-pink-900">
    <h1 class="text-5xl md:text-6xl font-extrabold mb-4">Hi, I'm <span class="text-indigo-400">Sumit Liman</span></h1>
    <p class="text-xl md:text-2xl max-w-xl mb-8">A passionate creative developer crafting beautiful and functional web experiences.</p>
    <a href="#projects" class="inline-block bg-indigo-500 hover:bg-indigo-600 px-8 py-4 rounded-lg text-lg font-semibold transition">View My Work</a>
  </header>

  <!-- About Section -->
  <section id="about" class="max-w-4xl mx-auto px-6 py-16">
    <h2 class="text-4xl font-bold mb-6 text-indigo-400 text-center">About Me</h2>
    <p class="text-lg leading-relaxed text-gray-300 max-w-3xl mx-auto">
      I’m a creative developer specializing in building engaging websites and interactive digital experiences. With a background in design and coding, I merge aesthetics with functionality to deliver seamless solutions. When I'm not coding, you'll find me exploring new art techniques or playing guitar.
    </p>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="bg-gray-800 py-16 px-6">
    <h2 class="text-4xl font-bold mb-12 text-indigo-400 text-center">Projects</h2>
    <div class="grid gap-10 max-w-6xl mx-auto sm:grid-cols-2 lg:grid-cols-3">
      
      <!-- Project Card 1 -->
      <div class="bg-gray-900 rounded-lg shadow-lg overflow-hidden hover:scale-105 transform transition duration-300">
        <img style="object-fit: cover; height: 300px; width: 360px;" src="https://upload.wikimedia.org/wikipedia/en/thumb/0/04/Facebook_f_logo_%282021%29.svg/512px-Facebook_f_logo_%282021%29.svg.png?20210818083032" alt="Project 1" class="w-full h-48 object-cover" />
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">FaceLook</h3>
          <p class="text-gray-400 mb-4">Facebook clone </p>
          <a href="projects/Facebook clone .html" class="text-indigo-400 hover:text-indigo-600 font-semibold">View project →</a>
        </div>
      </div>

      <!-- Project Card 2 -->
      <div class="bg-gray-900 rounded-lg shadow-lg overflow-hidden hover:scale-105 transform transition duration-300">
        <img style="object-fit: cover; height: 300px; width: 360px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Spotify_App_Logo.svg/400px-Spotify_App_Logo.svg.png?20210620075506" alt="Project 2" class="w-full h-48 object-cover" />
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">NetfliXpress</h3>
          <p class="text-gray-400 mb-4">Netflix clone</p>
          <a href="projects/netflix clone .html" class="text-indigo-400 hover:text-indigo-600 font-semibold">View project →</a>
        </div>
      </div>

      <!-- Project Card 3 -->
      <div class="bg-gray-900 rounded-lg shadow-lg overflow-hidden hover:scale-105 transform transition duration-300">
        <img style="object-fit: cover; height: 300px; width: 360px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0c/Netflix_2015_N_logo.svg/330px-Netflix_2015_N_logo.svg.png?20221130064001" alt="Project 3" class="w-full h-48 object-cover" />
        <div class="p-6">
          <h3 class="text-xl font-semibold mb-2">SpotPlay</h3>
          <p class="text-gray-400 mb-4">Spotify clone </p>
          <a href="projects/spotify clone.html" class="text-indigo-400 hover:text-indigo-600 font-semibold">View project →</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="max-w-4xl mx-auto px-6 py-16 text-center">
    <h2 class="text-4xl font-bold mb-6 text-indigo-400">Get In Touch</h2>
    <p class="text-lg mb-8 text-gray-300 max-w-2xl mx-auto">Interested in working together? Feel free to reach out via email or connect on social media.</p>
    <form id="contactForm" class="max-w-md mx-auto bg-gray-800 p-8 rounded-lg shadow-lg" novalidate>
      <input
        type="text"
        id="name"
        placeholder="Your Name"
        required
        class="w-full mb-4 px-4 py-3 rounded bg-gray-700 text-gray-100 focus:outline-none focus:ring-2 focus:ring-indigo-400"
      />
      <input
        type="email"
        id="email"
        placeholder="Your Email"
        required
        class="w-full mb-4 px-4 py-3 rounded bg-gray-700 text-gray-100 focus:outline-none focus:ring-2 focus:ring-indigo-400"
      />
      <textarea
        id="message"
        placeholder="Your Message"
        required
        rows="5"
        class="w-full mb-6 px-4 py-3 rounded bg-gray-700 text-gray-100 focus:outline-none focus:ring-2 focus:ring-indigo-400"
      ></textarea>
      <button
        type="submit"
        class="w-full bg-indigo-500 hover:bg-indigo-600 py-3 rounded text-lg font-semibold transition"
      >
        Send Message
      </button>
    </form>
    <p id="formMsg" class="mt-4 text-green-400 font-semibold"></p>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-center py-6 text-gray-500 text-sm">
    &copy; 2025 Your Name. All rights reserved.
  </footer>
<script src="app.js"></script>
<script src="service-worker.js"></script>
  <script>
    // Mobile menu toggle
    const menuBtn = document.getElementById('menuBtn');
    const mobileMenu = document.getElementById('mobileMenu');

    menuBtn.addEventListener('click', () => {
      mobileMenu.classList.toggle('hidden');
    });

    // Simple form validation and submission simulation
    const form = document.getElementById('contactForm');
    const formMsg = document.getElementById('formMsg');

    form.addEventListener('submit', (e) => {
      e.preventDefault();

      // Simple validation
      const name = form.name.value.trim();
      const email = form.email.value.trim();
      const message = form.message.value.trim();

      if (!name || !email || !message) {
        formMsg.textContent = 'Please fill out all fields.';
        formMsg.style.color = 'red';
        return;
      }

      // Basic email regex validation
      const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
      if (!emailPattern.test(email)) {
        formMsg.textContent = 'Please enter a valid email address.';
        formMsg.style.color = 'red';
        return;
      }

      // Simulate form submission
      formMsg.textContent = 'Sending...';
      formMsg.style.color = 'white';

      setTimeout(() => {
        formMsg.textContent = 'Thanks for your message! I will get back to you soon.';
        formMsg.style.color = 'lightgreen';
        form.reset();
      }, 1500);
    });
  </script>
</body>
</html>
