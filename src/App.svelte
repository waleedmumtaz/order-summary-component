<script>
  import Footer from './lib/footer.svelte'
  import MainContent from './lib/main-content.svelte'
</script>

<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link
    rel="preconnect"
    href="https://fonts.gstatic.com"
    crossorigin="anonymous"
  />
  <link
    href="https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@500;700;900&display=swap"
    rel="stylesheet"
  />
</svelte:head>

<div
  class="min-h-screen flex flex-col bg-[url(/assets/pattern-background-mobile.svg)] md:bg-[url(/assets/pattern-background-desktop.svg)] bg-no-repeat bg-cstm-primary-pale-blue px-5 font-red-hat-display"
>
  <MainContent />
  <Footer />
</div>
