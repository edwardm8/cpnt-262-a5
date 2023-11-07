<script>  
  import {cardInfo} from '../data.js'
</script>

<section class="flex flex-col mx-auto gap-4 p-4">
{#each cardInfo as {web,img,title,description,alt}}
  <a href= {web} class="flex flex-col justify-center mx-auto text-center max-w-xl p-4 bg-blue-400 hover:bg-blue-200">
    <img src= {img} alt= {alt}>
    <h2 class="text-xl p-4">{title}</h2>
    <p class="text-l">{description}</p>
  </a>
{/each}
</section>