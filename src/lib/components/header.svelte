<script>
  const navItems = [
    {name: 'Home', href:'/'},
    {name: 'About', href: '/about'}
];
</script>

<header class="bg-blue-800 text-white flex justify-between p-4 text-2xl">
  <div>Card Components</div>
  <nav>
    <ul class="flex justify-around gap-4">
      {#each navItems as {name, href}}
      <li class="hover:text-gray-500"><a {href}>{name}</a></li>
      {/each}
    </ul>
  </nav>
</header>