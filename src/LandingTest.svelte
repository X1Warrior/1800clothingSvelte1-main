 <script>

    // import { Router, Link, Route } from "svelte-routing";

    // import About from "./About.svelte";
    // import Book from "./Book.svelte";
    // import Nav from "./Nav.svelte";
    // let mobileOpen = false
    // const toggleMobileNav = () => {
    //     mobileOpen = !mobileOpen
    // }  
//         import { link } from "svelte-routing";
// import Landing from "./Landing.svelte";
// import { Router, Route, Link } from "svelte-routing";
</script>

<div class="page">
  <section class="left">
  <!-- <div class=logo><img src="assets/logo/logoVer5.png" alt="Logo" class="logo"></div> -->
  <div class="container">

    <div class="description">
      <p>This will be your accurate reference for all clothing that was worn in the 1800s. Whether you are an artist, author, historian, or just here out of curiousity — we hope you find what you are looking for.
      </p>
    </div>

    <div class="card">
      <button><a href="./Landing"></a>View Collection</button>
    </div>
  </div>

  </section>
 <section class="right">
  <div class="images">    
            <img src="assets/images/fancy_women.png" alt="fancy" class="fancy"/>
        </div>
      </section>
    </div>


  <style>
    .container {
      display: flex;
      justify-content: center;
      flex-direction: column;
    }
    
    .card {
      background-color: #f0f0f0;
      margin: 0 10px;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
   
    .page{
      display: flex;
      height: 100vh;
      width: 100vw;
      overflow: hidden;
    }

    button{
      padding: 10px 20px;
      margin: 20px;
      background-color: #f0f0f0;
      border: none;
      border-radius: 8px;
      font-size: 18px;
      cursor: pointer;
    }

    .logo{
      width: 300px;
      height: 50px;
      position: absolute;
      top: 0;
    }

    .description{
      color: #f0f0f0;
      font-size: 18px;
    }

    .left{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 50%;
      height: 100vh;
      background-color: #4b0d0d;
    }

    .right{
      display: flex;
      justify-content: center;
      align-items: center;
      width: 50%;
      height: 100vh;
      background-color: black;
    }

    .fancy{
      width: auto;
      height: auto;
      overflow: hidden;

      
    }
    .images{
      display: flex;
      justify-content: center;
      align-items: center;
      width: 90%;
      height: 90%;
    }
  </style>