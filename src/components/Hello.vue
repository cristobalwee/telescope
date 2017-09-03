<template>
  <div>
    <nav>
      <img src="../assets/logo.png">
      <h3 class="right"><a href="https://github.com/cristobalwee/telescope">Github</a></h3>
      <h3 class="right"><a href="http://cristobalgrana.me">Developer</a></h3>
    </nav>
    <div class="content">
      <h1>A <span class="underline">next-gen</span> component library for the Web</h1>
      <h2>Currently under development, but check out the sneak peek below.</h2>
      <img src="../assets/pageview.png">
    </div>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Arvo:400,700|Open+Sans:300,400,600,700,800');

  * {
    padding: 0;
    margin: 0;
  }

  body {
    padding: 2rem;
    overflow: hidden;
  }

  nav img {
    height: 2.5rem;
  }

  h1 {
    font-family: "Arvo", serif;
    color: #404e5c;
    margin-bottom: 0.5rem;
    font-size: 1.6rem;
  }

  h2 {
    font-family: "Open Sans", sans-serif;
    font-weight: 100;
    color: #404e5c;
    font-size: 1.2rem;
    margin-bottom: 4rem;
  }

  h3 {
    font-family: "Open Sans", sans-serif;
    font-weight: 100;
    color: #404e5c;
    font-size: 1rem;
    margin-bottom: 4rem;
  }

  a {
    color: #404e5c;
    text-decoration: none;
    margin-left: 1rem;
  }

  a:hover {
    border-bottom: solid 3px #404e5c;
  }

  .content {
    text-align: center;
    padding-top: 3rem;
  }

  .content img {
    height: 30rem;
    box-shadow: 0 3px 6px rgba(0, 0, 0, 0.5);
  }

  .right {
    float: right;
  }

  .underline {
    border-bottom: solid 4px #b7d0e2;
    border-radius: 4px;
  }

  @media only screen and (max-width: 950px) {
    .content img {
      height: 25rem;
    }
  }
</style>
