<template>
  <div>
    <div class="page-header clear-filter" filter-color="secondary">
      <parallax
        class="page-header-image"
        style="background-image:url('img/header.jpg')"
      >
      </parallax>
      <div class="container">
        <div class="content-center brand">
          <img class="indie-logo" src="img/logo.svg" alt=""/>
          <h1>The IndieHD Project</h1>
          <h4>A simple, do-it-yourself platform for selling your music to fans, digitally.</h4>
        </div>
      </div>
    </div>

    <div class="section">
      <div class="container text-center">
        <div class="row justify-content-md-center">
          <div class="col-md-12 col-lg-8">
            <h2 class="title">Completed with examples</h2>
            <h5 class="description">
              The kit comes with three pre-built pages to help you get started
              faster. You can change the text and images and you're good to go.
              More importantly, looking at them will give you a picture of what
              you can built with this powerful Bootstrap 4 ui kit.
            </h5>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>
<script>
  export default {
    name: 'index',
    bodyClass: 'index-page',

  };
</script>
<style lang="scss" scoped>
  .brand .indie-logo {
    max-width: 180px;
    margin-bottom: 30px;
  }

  .section-components {
    padding-top: 300px;
  }
</style>
