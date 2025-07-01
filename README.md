<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Landing Page</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-800">

  <!-- Navbar -->
  <header class="flex justify-between items-center p-6 shadow-md">
    <h1 class="text-xl font-bold">MyBrand</h1>
    <nav class="space-x-4 hidden md:block">
      <a href="#" class="hover:text-blue-500">Home</a>
      <a href="#" class="hover:text-blue-500">Features</a>
      <a href="#" class="hover:text-blue-500">About</a>
      <a href="#" class="hover:text-blue-500">Contact</a>
    </nav>
    <button class="md:hidden text-blue-600">☰</button>
  </header>

  <!-- Hero Section -->
  <section class="flex flex-col-reverse md:flex-row items-center px-6 py-12 md:py-20">
    <div class="w-full md:w-1/2 space-y-6">
      <h2 class="text-4xl md:text-5xl font-bold leading-tight">Build a Stunning Website with Ease</h2>
      <p class="text-lg text-gray-600">Responsive, fast, and beautifully designed. Get started with our platform today.</p>
      <a href="#" class="inline-block px-6 py-3 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition">Get Started</a>
    </div>
    <div class="w-full md:w-1/2 mb-8 md:mb-0">
      <img src="https://source.unsplash.com/600x400/?technology,web" alt="Hero Image" class="rounded-lg shadow-lg w-full" />
    </div>
  </section>

  <!-- Features Section -->
  <section class="bg-gray-100 py-12 px-6">
    <h3 class="text-3xl font-semibold text-center mb-8">Features</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-white p-6 rounded-lg shadow">
        <h4 class="text-xl font-bold mb-2">Fast Performance</h4>
        <p>Lightning-fast load times to keep your visitors engaged.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow">
        <h4 class="text-xl font-bold mb-2">Mobile Responsive</h4>
        <p>Your website looks great on all screen sizes.</p>
      </div>
      <div class="bg-white p-6 rounded-lg shadow">
        <h4 class="text-xl font-bold mb-2">Easy Customization</h4>
        <p>No coding needed. Just drag, drop, and publish.</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white text-center py-6">
    <p>&copy; 2025 MyBrand. All rights reserved.</p>
  </footer>

</body>
</html>