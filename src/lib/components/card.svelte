<script>  
  import {cardInfo} from '../data.js'
</script>


<a href= {cardInfo.web} class="flex flex-col justify-center mx-auto text-center max-w-xl p-4 bg-blue-400
border-2">
  <img src= {cardInfo.img} alt="hand holding vanilla ice cream cone">
  <h2 class="text-xl p-4">{cardInfo.title}</h2>
  <p class="text-l">{cardInfo.description}</p>
</a>