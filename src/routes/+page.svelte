<script>
  import background from '$lib/assets/device.jpg';
</script>


<svelte:head>
    <title>Paul s WebShop - Electronics for all !</title>
    <meta name = "description" content="We sell used electronics for a super cheap price!">
</svelte:head>
<div 
  class="relative h-screen bg-center bg-cover"
  style={`background-image: url(${background})`}
>
  <div class="absolute inset-0 bg-black/70"></div>
  
  <div class="absolute inset-0 flex items-center justify-center text-white px-4">
    <h1 class="text-6xl md:text-8xl font-bold">
      Electronic Devices
    </h1>
  </div>
</div>