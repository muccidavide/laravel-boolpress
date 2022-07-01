<template>
  <div class="page">
    <div class="jumbotron">
      <div class="container">
        <div class="jumbo_title">
          <h1 class="display-3">404 Page Not Found</h1>
          <p class="lead">Sorry but this page doesn't exist</p>
        </div>

        <div class="more_info">
          <p>More info</p>
          <p class="lead">
            <ul>
              <li>

              </li>
                      <li>
                
              </li>
                      <li>
                
              </li>
            </ul>
            <router-link :to="{ name: 'home' }">Home</router-link>
            <router-link :to="{ name: 'about' }">About</router-link>
            <router-link :to="{ name: 'posts' }">Posts</router-link>
          </p>
        </div>
      </div>

      <div class="container">
        <div class="content">
         
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "About",
};
</script>
