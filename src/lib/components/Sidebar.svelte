<!-- Sidebar.svelte -->
<aside class="relative z-10 flex flex-col w-72 h-screen bg-white/20 backdrop-blur-xl border-r border-white/20 shadow-lg rounded-r-3xl overflow-hidden">
  <!-- Optional decorative curve on the left -->
  <div class="absolute -left-16 top-0 w-32 h-full bg-white/10 rounded-full"></div>

  <!-- Sidebar Content -->
  <div class="relative z-10 flex flex-col flex-1 px-4">
    <!-- Header -->
    <div class="flex items-center justify-between p-4">
      <h1 class="text-lg font-semibold text-white">Menu</h1>
    </div>

    <!-- Nav Links -->
    <nav class="flex flex-col space-y-3">
      <a href="/" class="flex items-center space-x-2 hover:text-blue-300">
        <svg
          class="w-6 h-6"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
          />
        </svg>
        <span>Home</span>
      </a>
      <a href="/projects" class="hover:text-blue-300">Projects</a>
      <a href="/about" class="hover:text-blue-300">About</a>
      <a href="/contact" class="hover:text-blue-300">Contact</a>
    </nav>

    <!-- Footer -->
    <div class="mt-auto p-4">
      <button class="flex items-center space-x-2 hover:text-red-300">
        <svg
          class="w-6 h-6"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 16l4-4m0 0l-4-4m4 4H7" />
        </svg>
        <span>Logout</span>
      </button>
    </div>
  </div>
</aside>
