<script>
	import Header from '$lib/components/navbars/header.svelte';
</script>
  
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Austin Ridge Bible Church</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      href="https://fonts.googleapis.com/css?family=Open+Sans:400,600,700&display=swap"
      rel="stylesheet"
    />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
    />
  </head>
  <body>
    <!-- Header -->
    <Header />

    <!-- Main Hero Section -->
    <section class="relative">
      <img
        src="https://placehold.co/1920x1080"
        alt="Community gathering at Austin Ridge Bible Church"
        class="w-full h-auto"
      />
      <div
        class="absolute top-0 left-0 right-0 bottom-0 flex items-center justify-center"
      >
        <div class="text-center">
          <h1 class="text-white text-5xl font-bold mb-4">
            FIND YOUR COMMUNITY AT AUSTIN RIDGE BIBLE CHURCH
          </h1>
          <p class="text-yellow-300 mb-8">Sunday services at 9am & 11am</p>
          <a href="#" class="bg-teal-500 text-white px-8 py-3">I'M NEW</a>
          <a href="#" class="bg-teal-700 text-white px-8 py-3 ml-4"
            >GET CONNECTED</a
          >
        </div>
      </div>
    </section>

    <!-- Who We Are Section -->
    <section class="container mx-auto my-12">
      <div class="flex flex-wrap -mx-4">
        <div class="w-full md:w-1/2 px-4 mb-8 md:mb-0">
          <h2 class="text-4xl font-bold text-gray-800 mb-4">WHO WE ARE</h2>
          <p class="text-gray-600">
            Austin Ridge Bible Church exists to pursue people at all costs, so
            they can know Jesus, grow in Him, and serve Him daily.
          </p>
          <a href="#" class="text-blue-600 mt-4 inline-block">LEARN MORE</a>
        </div>
        <div class="w-full md:w-1/2 px-4">
          <img
            src="https://placehold.co/600x400"
            alt="Church congregation"
            class="w-full h-auto"
          />
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-8">
      <div class="container mx-auto">
        <div class="flex flex-wrap -mx-4">
          <!-- Footer content -->
        </div>
        <div class="text-center mt-4">
          <p>&copy; 2024 Austin Ridge Bible Church. All Rights Reserved.</p>
        </div>
      </div>
    </footer>

    <script>
  window.watsonAssistantChatOptions = {
    integrationID: "dc8fd20b-9582-411c-9670-e0e956029a75", // The ID of this integration.
    region: "us-south", // The region your integration is hosted in.
    serviceInstanceID: "00c8ffe4-5665-4be9-85db-a7dd6537c021", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>
  </body>