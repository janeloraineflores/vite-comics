<script>
  export default {
    name: "App",
    components: {
    },
    data() {
      return {};
    },
    methods: {},
};
</script>

<template>
    
  <header>
    <div class="container">
      <div class="header-container">
        <div class="logo-container">
        <img src="./assets/img/dc-logo.png" alt="">
        </div>

        <ul>
          <li>
            <a href="#">CHARACTERS</a>
          </li>
          <li>
            <a href="#">COMICS</a>
          </li>
          <li>
            <a href="#">MOVIES</a>
          </li>
          <li>
            <a href="#">TV</a>
          </li>
          <li>
            <a href="#">GAMES</a>
          </li>
          <li>
            <a href="#">COLLECTIBLES</a>
          </li>
          <li>
            <a href="#">VIDEOS</a>
          </li>
          <li>
            <a href="#">FANS</a>
          </li>
          <li>
            <a href="#">NEWS</a>
          </li>
          <li>
            <a href="#">SHOP</a>
          </li>
        </ul>
      </div>
    </div>
  </header>

  <main>
    MAIN
  </main>

  <footer>
    FOOTER
  </footer>

  

</template>

<style lang="scss">
  *{
    margin: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;   

    &:not(ul) {
      padding: 0;
    }
  }

  .container {
    margin: 0 auto;
    width: 1200px;
  }
  
  header {
    padding: 20px 0;

    .header-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo-container {
      width: 80px;
      height: 80px;

      img{
        width: 100%;
        height: 100%;
      }
    }

    ul {
      display: flex;
      list-style: none;

      li {
        a{
          display: inline-block;
          padding: 15px;
          color: black;
          text-decoration: none;
          font-size: .9375rem;
          transition: .2s all ease-in-out;

          &:hover {
            background-color: #0282F9
          }
        }
      }
    }
  }
</style>
