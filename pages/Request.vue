<template>
  <div id="RequestServices">
    <section id="hero" class="p-2 py-lg-3 bg-white overflow-hidden h-100">
      <header class="container sticky">
        <header class="wrap">
         <Navbar />
       </header>
      </header>
    </section>
    <RequestFormhtml />
  </div>
</template>

<script>
export default {
    head() {
      return {
          title: 'Request a Service',
          meta: [
              {
                  hid: 'description',
                  name: 'description',
                  content:'Request a service from Promotion Efficiency'
              }

          ]
      }
  },
}
</script>