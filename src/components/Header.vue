<template>
  <nav class="navbar navbar-default">
    <div class="container-fluid">

      <div class="navbar-header">
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
          <span class="sr-only">Ouvrir la navigation</span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
          <span class="icon-bar"></span>
        </button>
        <a class="navbar-brand" href="/">Générateur de signature</a>
      </div>

      <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
        <ul class="nav navbar-nav">
          <li><a href="http://capefrei.fr/" target="_blank">Cap Efrei</a></li>
          <li><a href="http://groupe-efrei.fr/" target="_blank">Groupe Efrei</a></li>
          <li><a href="https://github.com/GarysDev/signatures" target="_blank">GitHub du projet</a></li>
        </ul>

        <ul class="nav navbar-nav navbar-right">
          <li><a href="https://www.facebook.com/capefrei1/" target="_blank"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
          <li><a href="https://github.com/GarysDev" target="_blank"><i class="fa fa-github" aria-hidden="true"></i></a></li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
  export default {
    name: 'Header'
  }
</script>

<style>
  .fa {
    font-size: 150%;
  }
</style>
