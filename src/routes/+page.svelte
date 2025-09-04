<!-- +page.svelte or any other page -->
<script>
  import Sidebar from "$lib/components/Sidebar.svelte";
</script>

<div class="flex h-screen">
  <!-- Sidebar -->
  <Sidebar />

  <!-- Main Content -->
  <main class="flex-1 p-8 overflow-y-auto bg-indigo-400">
    <h1 class="text-3xl font-bold mb-6">Welcome to My Portfolio</h1>
    <p class="text-gray-200">
      Content.
    </p>
  </main>
</div>