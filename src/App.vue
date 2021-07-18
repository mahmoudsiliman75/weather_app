<template>
  <div id="app">
    <main>
      <div class="search_box">
        <input type="text" placeholder="Search...." id="search_input">
      </div>

      <div class="weather_wraper">
        <div class="location_box">
          <div class="location"> Cairo, EGY </div>
          <div class="date"> Monday 20 January 2021 </div>
        </div>

        <div class="weather_box">
          <div class="temp"> 17°c </div>
          <div class="weather"> Rain </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: "App",
};
</script>