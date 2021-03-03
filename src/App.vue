<template>
    <div>
      <!--Header-->
      <header class="bg-black bg-opacity-75 py-5">
          <div class="container mx-auto flex justify-between items-center">
              <div class="flex-1 header-logo">
                <a href="/"><img src="./img/homepage/bdx-logo-white.png" alt="BDX"></a>
              </div>
              <ul class="flex space-x-2 items-center">
                  <li class="flex-1 text-white"><a href="">SIGNIN</a></li>
                  <li class="flex-1 text-white"><a href="">SIGNUP</a></li>
                  <li><a class="text-white border-3 border-white r" href="">CONTACT US</a></li>
              </ul>
          </div>
      </header>

      <!--Main Section-->
      
      <main>
        <h1>GET A QUOTE</h1>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorum quidem minima laborum cupiditate fuga consequatur dicta eaque maxime eum incidunt officia explicabo nostrum minus fugiat odit, quaerat fugit, obcaecati aperiam.</p>
        <form action="">
          <input type="text" placeholder="Email*"><br>
          <input type="text" placeholder="Password*"><br>
          <input type="submit" placeholder="SUBMIT">
        </form>
      </main>
    
    </div>
</template>

<script>
  export default {
    name: `App`,
  };
</script>

<style lang="scss" scoped>
</style>

