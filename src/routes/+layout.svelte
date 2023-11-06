<script>
  import "../app.css"
  import Navbar from '../lib/components/header.svelte'
  import Footer from '../lib/components/footer.svelte'
</script>

<Navbar/>
<slot></slot>
<Footer/>
