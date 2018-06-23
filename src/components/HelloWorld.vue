<template>
  <div class="hello">
    <nav class="navbar navbar-expand-lg navbar-dark bg-realdark">
      <div class="container">
        <div class="d-flex justify-content-around">
          <a class="navbar-brand" href="#">鬍子科技學院</a>
        </div>
        <div class="d-flex justify-content-around">
          <img class="logo" src="http://mtache.com/wp-content/themes/enfold/assets/images/white_mus.png" alt="">
        </div>
        <div class="d-flex justify-content-around">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">ENG <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">我要報名</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
