<router-link class="" to="/"></router-link> 
<router-view/>
<template>
  <div class="">
    <div class=" bg-zinc-700 w-full h-16 mt-1 flex md:gap-[490px] gap-16 xl:gap-[790px]  items-center">
      <div class="text-white flex">
        <i class="fa-solid fa-venus-double text-green-500 text-2xl gap-4"></i>
      <h1 class="font-bold text-2xl">envato</h1>
      <h1 class="text-2xl" >market</h1>
    </div>
    <div class=".container bg-green-600 h-11 w-28 rounded-lg flex justify-center items-center">
    <a href="" class="text-white text-2xl">Buy now</a>
  </div>
    </div> 
    <div class="max-w-full h-[500px] bg-baddest  bg-no-repeat bg-cover bg-center
    text-white shadow-lg">
    <div class="relative">
    <!-- Navbar -->
    <nav class="flex justify-between items-center p-5 bg-black bg-opacity-50">
      <div class="text-white font-bold text-2xl flex items-center space-x-2">
        <!-- Logo -->
        <i class="fa-solid fa-utensils text-white text-3xl"></i>
        <span>TOMATO</span>
      </div>
      <div class="text-white md:hidden" @click="toggleMenu">
        <!-- Hamburger Icon -->
        <i v-if="!isMenuOpen" class="fas fa-bars text-3xl"></i>
        <!-- Cancel Icon -->
        <i v-else class="fas fa-times text-3xl"></i>
      </div>
      <!-- Menu Links for Larger Screens -->
      <ul class="hidden md:flex space-x-4 text-white font-semibold text-2xl">
        <li v-for="(item, index) in menuItems" :key="index" class="relative group">
          <a href="#" class="hover:underline">{{ item }}</a>
        </li>
      </ul>
    </nav>
    
    <!-- Menu for Mobile Screens -->
    <div v-if="isMenuOpen" class="md:hidden bg-black bg-opacity-75 top-0 left-0 w-full h-auto">
      <ul class="space-y-4 text-white text-xl p-5">
        <li v-for="(item, index) in menuItems" :key="index" class="relative group">
          <a href="#" class="block">{{ item }}</a>
        </li>
      </ul>
    </div>
  </div>
  <div class="mt-11 ml-7 md:pt-16 md:pl-60 xl:pt-20 xl:pl-96 ">
    <i class="fa-brands fa-pagelines text-orange-300 text-7xl md:pl-48"></i>
  <h1 class="text-white text-5xl font-bold md:text-7xl">Delicious Food</h1>
  <h1 class="md:text-3xl text-xl"> tomato is a delicious restaurant website template</h1>
</div>
</div> 
<div class=".container bg-gray-100 h-[900px] flex flex-col items-center">
<h1 class="text-black text-3xl md:text-5xl mt-16 font-bold">THE RESTAURANT</h1>
<h1 class="text-black md:text-xl px-2">A little about us and a brief history of how we started</h1>
<div class=" border-b-4 border-yellow-600 bg-gray-100 w-[200px] rounded-3xl focus:outline-none"></div> 
<div class="flex flex-row ml-[-200px] md:ml-[-250px] xl:ml-0 h-[400px] w-[150px] md:w-[300px] xl:w-[1200px] gap-7 mt-11">
<img src="https://i.pinimg.com/control/564x/e9/7f/4b/e97f4b9280e8e9ec718553aa27a6ac65.jpg" class="rounded-lg">
<img src="https://i.pinimg.com/control/564x/3d/1b/6e/3d1b6ec73a084d5514502251670d9677.jpg" class="rounded-lg">
</div>
<h1 class=" ml-[-30px] px-11 pt-10 text-xl md:text-2xl">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Beatae ex, ab, earum asperiores adipisci totam facilis veniam distinctio fuga eius dicta molestiae doloremque <br>
   porro officiis qui, debitis sit similique. Inventore, ad illo alias minima ab nam ipsum provident cum labore totam. Consequuntur distinctio, natus, quidem illum <br>
    impedit recusandae officiis dolore temporibus voluptatem 
  </h1>
</div>
<div class="max-w-full h-[850px] bg-baddest2  bg-no-repeat bg-cover 
    text-white shadow-lg">
    <div class="pt-16 ml-24 md:ml-[100px] xl:ml-[300px]">
    <h1 class="text-2xl md:text-4xl mt-7 font-bold text-white ml-[15px] md:ml-[125px]">TODAY'S SPECIALS</h1>
<h1 class="md:text-2xl text-white md:ml-9">A little about us and a brief history of how we started</h1>
<div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none ml-11 md:ml-[150px]"></div> 
<div class=".container md:w-[600px]  xl:w-[800px] w-[250px] bg-gray-100 h-[450px] flex flex-col mt-7 rounded-lg pl-4">
<h1 class="text-black text-lg font-bold md:text-3xl"> Pancake with caramel</h1>
<h1 class="text-gray-500 md:text-2xl mt-4">if you are a fan of caramel cake, then you'll love our Pancake
  with caramel icecream it's not thick, but very
</h1>
<div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none ml-5 md:ml-[20px] mt-4"></div> 
<h1 class="text-black text-lg px-2 mt-5 md:text-2xl "> Ultrices In massa est, dignissim in libero ac, fringilla ornare mi. Ultrices eget justo 
  Nam purus lacus
</h1>
<div class=" flex flex-row mt-14 gap-5">
<a href="/" class="home .container bg-amber-500 flex justify-center items-center w-48 md:w-44 h-11 text-black md:text-2xl font-bold rounded-lg">ORDER NOW</a>
<a href="/" class="home .container bg-gray-300 flex justify-center items-center w-48 md:w-44 h-11 text-gray-600 md:text-2xl font-bold rounded-lg">ADD TO CART</a>
</div>
</div>
  </div>
</div>
<div class=".container bg-gray-100 max-w-full h-[700px] ">
 <h1 class="text-black text-3xl md:text-6xl font-bold flex justify-center">RESERVATIONS</h1>
 <h1 class="text-black text-xl md:text-3xl flex justify-center px-4">Book a table online. Leads will reach in your email.</h1>
 <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none ml-32 md:ml-[500px] mt-4"></div>
 <div class="pl-11 grid grid-cols-2 mt-11">
  <div>
  <h1 class="text-black text-xl md:text-3xl">Date</h1>
 <input type="date" class=" bg-gray-300 text-gray-500 px-4 w-28 md:w-80 h-11 placeholder:pl-3 mt-3 rounded-lg text-sm md:text-xl" placeholder="Pick a date">
</div>
  <div>
    <h1 class="text-black text-xl md:text-3xl">Your name</h1>
    <input type="note" class="bg-gray-300 w-28 md:w-80 h-11 placeholder:text-gray-600 pl-3 mt-3 rounded-lg text-sm md:text-xl" placeholder="Full name">
  </div>
 <div>
   <h1 class="text-black text-xl md:text-3xl">Time</h1>
   <input type="Time" class="bg-gray-300 w-28 md:w-80 h-11 placeholder:text-gray-600 pl-3 mt-3 rounded-lg text-sm md:text-xl" placeholder="Pick a time">
 </div>
 <div>
   <h1 class="text-black text-xl md:text-3xl">Email Adress</h1>
   <input type="email" class="bg-gray-300 w-28 md:w-80 h-11 placeholder:text-gray-600 pl-3 mt-3 rounded-lg text-sm md:text-xl" placeholder="Your Email ID">
 </div>
 <div>
   <h1 class="text-black text-xl md:text-3xl">Guests</h1>
   <input type="number" class="bg-gray-300 w-28 md:w-80 h-11 placeholder:text-gray-600 pl-3 mt-3 rounded-lg text-sm md:text-xl" placeholder="How many of you?">
 </div>
  <div>
    <h1 class="text-black text-xl md:text-3xl">Phone number</h1>
    <input type="tel" class="bg-gray-300 w-28 md:w-80 h-11 placeholder:text-gray-600 pl-3 mt-3 rounded-lg text-sm md:text-xl" placeholder="Enter your Phone number">
  </div>
  <a href="/" class="home .container bg-amber-500 flex justify-center items-center w-32 md:w-72 h-16 text-black md:text-2xl font-bold rounded-lg mt-10 ml-20 md:ml-52 xl:ml-96 px-4">MAKE RESERVATIONS</a>
  <div class=".container bg-gray-200 w-36 md:w-[700px] h-16 text-gray-600 mt-36 ml-[-100px] md:ml-[-450px] text-sm md:text-xl xl:text-2xl font-bold flex items-center justify-center">You can also call +2348137628419 to make a reservation</div>
 </div> 
</div>
<div>
  <div class="max-w-full h-[1100px] md:h-[1500px] bg-baddest3  bg-no-repeat bg-cover 
  text-white shadow-lg md:px-28">
  <div class="">
    <h1 class=" text-2xl md:text-4xl flex justify-center font-bold pt-7">OUR FEATURES</h1>
    <h1 class="text-xl md:text-3xl flex justify-center font-bold">Little things make us best in town</h1>
    <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none ml-32 md:ml-[200px] xl:ml-[500px] mt-4"></div>
    <div class="px-6 md:px-6 gap-4  grid grid-cols-2 rounded-lg mt-5 md:mt-11">
      <div>
    <img src="https://i.pinimg.com/control/564x/9c/61/6e/9c616e7db412f5df726078d18dc52d94.jpg" class="h-[200px] w-[150px] md:w-[300px] md:h-[400px]">
    <div class=".container bg-white h-[250px] w-[150px] px-4 md:px-6 md:w-[240px] xl:w-[300px] md:h-[250px] ">
      <h1 class="font-bold text-black md:text-2xl ">SERVING WITH LOVE</h1>
      <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none  md:ml-[10px] mt-2"></div>
      <h1 class="mt-3 text-black md:text-xl font-bold ">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Pariatur adipisci.</h1>
    </div>
  </div>
  <div>
    <img src="https://i.pinimg.com/564x/b5/60/3e/b5603ee13f283a4ed950209260d83f9e.jpg" class="h-[200px] w-[150px] md:w-[300px] md:h-[400px]">
    <div class=".container bg-white h-[250px] w-[150px] px-4 md:px-6 md:w-[240px] xl:w-[300px] md:h-[250px]">
      <h1 class="font-bold text-black md:text-2xl">SERVING WITH LOVE</h1>
      <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none  md:ml-[10px] mt-2"></div>
      <h1 class="mt-3 text-black font-bold md:text-xl">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Pariatur adipisci.</h1>
    </div>
  </div>
  <div>
    <img src="https://i.pinimg.com/736x/fc/ad/0e/fcad0e5915eb1116c70ac16462bbc6b3.jpg" class="h-[200px] w-[150px] md:w-[300px] md:h-[400px]">
    <div class=".container bg-white h-[250px] w-[150px] px-4 md:px-6 md:w-[240px] xl:w-[300px] md:h-[250px] ">
      <h1 class="font-bold text-black md:text-2xl ">SERVING WITH LOVE</h1>
      <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none  md:ml-[10px] mt-2 "></div>
      <h1 class="mt-3 text-black md:text-xl font-bold ">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Pariatur adipisci.</h1>
    </div>
  </div>
  <div>
    <img src="https://i.pinimg.com/control/564x/b3/c9/6d/b3c96dd6c41fb146ab34cdaada021385.jpg" class="h-[200px] w-[150px] md:w-[300px] md:h-[400px]">
    <div class=".container bg-white h-[250px] w-[150px] px-4 md:px-6 md:w-[240px] xl:w-[300px] md:h-[250px] ">
      <h1 class="font-bold text-black md:text-2xl ">SERVING WITH LOVE</h1>
      <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none  md:ml-[10px] mt-2"></div>
      <h1 class="mt-3 text-black md:text-xl font-bold ">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Pariatur adipisci.</h1>
    </div>
  </div>
</div>
  </div>
</div>
</div>
<div class=".container max-w-full h-[600px] bg-gray-100">
  <h1 class=" text-black text-xl md:text-4xl font-bold flex justify-center ">OUR MENU</h1>
  <p class="text-gray-500 font-bold flex justify-center text-sm md:text-2xl">These fine folks trusted the award winning restaurant</p>
  <div class=" border-b-4 border-yellow-600 bg-gray-100 md:w-[200px] w-[100px] rounded-3xl focus:outline-none ml-[100px] md:ml-[250px]  xl:ml-[550px] mt-2"></div>
  <div class="mt-5 mr-3 flex flex-col md:grid md:grid-cols-2 md:text-2xl ">
    <div>
  <h1 class="text-black font-bold flex flex-row mt-3 ml-7">ENGLISH ASPARAGUS    <p class="text-gray-500">.......................</p> $12.5 </h1>
   <p class="text-gray-500 ml-7" >pellente enim. Aliuam rempor</p>
  </div>
   <div>
  <h1 class="text-black font-bold flex flex-row mt-3 ml-7">ENGLISH ASPARAGUS    <p class="text-gray-500">.......................</p> $16.6 </h1>
  <p class="text-gray-500 ml-7" >pellente enim. Aliuam rempor</p>
</div>
  <div>
  <h1 class="text-black font-bold flex flex-row mt-3 ml-7">ENGLISH ASPARAGUS    <p class="text-gray-500">.......................</p> $65.4 </h1>
  <p class="text-gray-500 ml-7" >pellente enim. Aliuam rempor</p>
</div>
  <div>
  <h1 class="text-black font-bold flex flex-row mt-3 ml-7">ENGLISH ASPARAGUS    <p class="text-gray-500">.......................</p> $35.9 </h1>
  <p class="text-gray-500 ml-7" >pellente enim. Aliuam rempor</p>
</div>
  <div>
  <h1 class="text-black font-bold flex flex-row mt-3 ml-7">ENGLISH ASPARAGUS    <p class="text-gray-500">.......................</p> $45.52 </h1>
  <p class="text-gray-500 ml-7" >pellente enim. Aliuam rempor</p>
</div>
  <div>
  <h1 class="text-black font-bold flex flex-row mt-3 ml-7">ENGLISH ASPARAGUS    <p class="text-gray-500">.......................</p> $25.5 </h1>
  <p class="text-gray-500 ml-7" >pellente enim. Aliuam rempor</p>
</div>
</div>
<a href="/" class="home .container bg-amber-500 flex justify-center items-center w-32 md:w-72 h-16 text-black md:text-2xl font-bold rounded-lg mt-16 ml-20 md:ml-[250px] xl:ml-[500px] px-4">EXPLORE OUR MENU</a>
</div>
<div class="max-w-full h-[1100px] md:h-[1000px] xl:h-[800px] bg-baddest4  bg-no-repeat bg-cover 
text-white shadow-lg md:px-28">
<div class="pt-8">
  <h1 class="text-amber-500 font-bold text-2xl flex justify-center  md:text-4xl">ABOUT US</h1>
  <p class="pt-8 font-bold md:text-2xl flex justify-center px-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequuntur nisi libero quo numquam facilis, iste aut fugiat voluptas doloremque eum deserunt soluta est qui ut incidunt, maiores sed exercitationem. Nisi.</p>
    <p class="text-amber-500 font-bold md:text-2xl pt-4 pl-7">Read more <i class="fa-solid fa-arrow-right"></i></p>
    <h1 class="text-amber-500 font-bold text-2xl  md:text-4xl pt-11 ml-7">REACH US</h1>
    <div class="mt-7 bg-gray-800 text-white text-xl md:text-3xl space-x-4 ml-5  md:space-x-10 rounded-lg h-10 md:h-16 w-[250px] md:w-[400px] flex justify-center items-center">
      <i class="fa-brands fa-square-facebook"></i>
      <i class="fa-brands fa-twitter"></i>
      <i class="fa-brands fa-google"></i>
      <i class="fa-brands fa-youtube"></i>
      <i class="fa-brands fa-linkedin"></i>
      <i class="fa-brands fa-pinterest"></i>
    </div>
    <div class="flex flex-col justify-center px-4 mt-11 text-xl md:text-3xl">
      <p class="flex flex-row gap-8"><i class="fa-solid fa-location-dot text-amber-500"></i>28, seventh avenue. New york, 10014</p>
      <p class="flex flex-row gap-8"> <i class="fa-solid fa-phone text-amber-500"></i> Phone: (415) 124-5678</p>
      <p class="flex flex-row gap-8"> <i class="fa-solid fa-envelope text-amber-500"></i> support@restaurant.com</p>
  </div>
  <div class="flex flex-row text-xl md:text-3xl font-bold gap-7 mt-32 ml-10">
  <i class="fa-regular fa-copyright"></i>
   <p class="text-amber-500">2015,Tomato.All rights reserved. Designed by Taofeeq</p>
</div>
  </div>
  </div>
  </div>

</template>


<style>
.bg-baddest {
  background-image: url(https://i.pinimg.com/control/564x/c0/05/f1/c005f12867549656070006bf650579a2.jpg);
}
.bg-baddest2{
  background-image: url(https://i.pinimg.com/control/564x/c8/11/e1/c811e16e296b7830943b90943a3d5c51.jpg);
}
.bg-baddest3{
  background-image: url(https://i.pinimg.com/control/564x/70/68/d1/7068d104f7bcc633e4ea59a464a441da.jpg);
}
.bg-baddest4{
  background-image: url(https://i.pinimg.com/control/564x/bd/57/c2/bd57c2c9ac1c072e1adb5af267f66f7a.jpg);
}

</style>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView',
  components: {
  },
  data() {
    return {
      isMenuOpen: false,
      menuItems: ['Home', 'Menu', 'Reservation', 'Pages', 'Recipe', 'Blog', 'Shop', 'Contact'],
    };
  },
  methods: {
    toggleMenu() {
      this.isMenuOpen = !this.isMenuOpen;
    }
  }
}
</script>
