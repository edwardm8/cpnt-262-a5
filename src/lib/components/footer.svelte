<script>
  const navItems = [
    {name: 'Home', href:'/'},
    {name: 'About', href: '/about'}
];
</script>

<footer class="bg-blue-800 text-white flex justify-between p-4 flex-col text-center gap-4">
  <div>Card Components</div>
  <nav>
    <ul class="flex justify-center gap-4">
      {#each navItems as {name, href}}
      <li class="hover:text-gray-500"><a {href}>{name}</a></li>
      {/each}
    </ul>
  </nav>
  <div>Edward Mah</div>
  <p>Copyright</p>
</footer>