<script>
</script>

<main>
  <nav class="bg-blue-900 shadow-lg">
    <div class="container mx-auto">
      <div class="sm:flex">
        <a href="#/" class="p-3 text-3xl font-bold text-white"> APP LOGO</a>

        <!-- Menus  -->
        <div class="mt-4 ml-55">
          <ul class="text-xl text-white sm:self-center">
            <li class="sm:inline-block">
              <a href="#/" class="p-3 hover:text-red-900">About</a>
            </li>
            <li class="sm:inline-block">
              <a href="#/" class="p-3 hover:text-red-900">Services</a>
            </li>
            <li class="sm:inline-block">
              <a href="#/" class="p-3 hover:text-red-900">Blog</a>
            </li>
            <li class="sm:inline-block">
              <a href="#/" class="p-3 hover:text-red-900">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  /* purgecss end ignore */
  @tailwind utilities;

  @layer utilities {
    .ml-55 {
      margin-left: 55%;
    }
  }
</style>
