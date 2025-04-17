# Moving
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>QuickMove - Moving & Delivery Services</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 font-sans">
  <header class="bg-blue-600 text-white p-6">
    <div class="max-w-6xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">QuickMove</h1>
      <nav class="space-x-6">
        <a href="#services" class="hover:underline">Services</a>
        <a href="#about" class="hover:underline">About</a>
        <a href="#contact" class="hover:underline">Contact</a>
      </nav>
    </div>
  </header>

  <section class="bg-white py-20 text-center">
    <h2 class="text-4xl font-bold mb-4">Fast, Reliable Moving & Delivery Services</h2>
    <p class="text-gray-700 mb-6">We make your moving experience hassle-free and efficient. Serving local and long-distance clients with care.</p>
    <a href="#contact" class="bg-blue-600 text-white px-6 py-3 rounded hover:bg-blue-700">Get a Free Quote</a>
  </section>

  <section id="services" class="py-20 bg-gray-100">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-10">Our Services</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-semibold mb-2">Home Moving</h4>
          <p>Professional packing and moving for homes and apartments.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-semibold mb-2">Office Relocation</h4>
          <p>Efficient and secure office transitions tailored to your schedule.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-semibold mb-2">Last-Mile Delivery</h4>
          <p>Fast and reliable delivery of packages and small freight.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="about" class="py-20">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-4">About Us</h3>
      <p class="text-gray-700">QuickMove is your trusted moving and delivery partner. With a team of experienced professionals and a commitment to customer satisfaction, we ensure your belongings are moved safely and on time.</p>
    </div>
  </section>

  <section id="contact" class="bg-blue-600 text-white py-20">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Contact Us</h3>
      <p class="mb-4">Ready to move? Reach out for a free consultation and quote.</p>
      <form class="grid gap-4 max-w-md mx-auto">
        <input type="text" placeholder="Your Name" class="p-3 rounded text-black" required>
        <input type="email" placeholder="Your Email" class="p-3 rounded text-black" required>
        <textarea placeholder="Your Message" class="p-3 rounded text-black" rows="4" required></textarea>
        <button type="submit" class="bg-white text-blue-600 font-semibold px-6 py-3 rounded hover:bg-gray-200">Send Message</button>
      </form>
    </div>
  </section>

  <footer class="bg-gray-800 text-white text-center py-6">
    <p>&copy; 2025 QuickMove. All rights reserved.</p>
  </footer>
</body>
</html>
