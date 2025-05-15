<script>

</script>

<nav class="nav">
    <div class="container">
      <div class="main_list" id="mainListDiv">
        <ul>
          <li><a href="/">Home</a></li>
          <li><a href="/about">About</a></li>
          <li><a href="/blog/one">Blog one</a></li>
          <li><a href="/blog/two">Blog two</a></li>
          <li><a href="/blog/three">Blog three</a></li>
          <li><a href="/blog/four">Blog four</a></li>

        </ul>
      </div>
    </div>
  </nav>

<style>
   .nav {
    width: 100%;
    height: 65px;
    line-height: 65px;
    text-align: center;
    background-color: black;
    margin: 0 auto;
  }

  .nav div.main_list {
    height: 65px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .nav div.main_list ul {
    display: flex;
    gap: 30px;
    list-style: none;
    padding: 0;
    margin: 0;
    align-items: center;
  }

  .nav div.main_list ul li {
    height: 65px;
  }

  .nav div.main_list ul li a {
    display: block;
    text-decoration: none;
    color: #fff;
    line-height: 65px;
    font-size: 1.2em;
    text-transform: uppercase;
  }

  .nav div.main_list ul li a:hover {
    color: #c0c0c0;
  }
</style>