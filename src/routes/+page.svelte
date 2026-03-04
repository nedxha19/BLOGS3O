<script>
  import background from '$lib/assets/device.jpg';
</script>

<header
  class="relative h-[500px] bg-center bg-cover flex items-center justify-center"
  style={`background-image: url(${background})`}
>
  <!-- Dark Overlay -->
  <div class="absolute inset-0 bg-black/50"></div>

  <!-- Hero Content -->
  <div class="relative text-center text-white px-4">
    <h1 class="text-5xl md:text-6xl font-bold mb-4">
      Electronic Devices
    </h1>
    <p class="text-lg md:text-xl max-w-2xl mx-auto">
      Explore the world of modern electronic technology and innovation.
    </p>
  </div>
</header>

<main class="max-w-5xl mx-auto px-6 py-12">
  <h2 class="text-3xl font-semibold mb-6">Latest Articles</h2>

  <p class="text-gray-600 leading-relaxed">
    This blog covers the newest trends in consumer electronics,
    embedded systems, IoT devices, and hardware innovations.
  </p>
</main>

<footer class="bg-gray-900 text-white text-center py-6 mt-12">
  <p>© 2026 Electronic Devices Blog. All rights reserved.</p>
</footer>