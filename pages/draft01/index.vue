<template>
  <main class="mt-5">
    <div id="app" class="container-fluid py-5">
      <h3 class="text-center">Draft 01</h3>
      <a href="/drafts/draft01/house-in-the-trees-draft-01.pdf"
        ><div class="text-center">House in the Trees - Draft 01</div></a
      >
      <a
        href="/drafts/draft01/house-in-the-trees-draft-01(spread).pdf"
        class="text-center"
        ><div class="text-center">
          House in the Trees - Draft 01 (spread)
        </div></a
      >
      <br />

      <h3 class="text-center">Audio</h3>
      <p class="text-center">Coming soon!</p>
    </div>
  </main>
</template>

<script setup lang="ts">
//
</script>

<style lang="scss">
h1,
h2,
h3 {
  font-family: gelica, sans-serif;
  font-weight: 400;
  font-style: normal;
}

p {
  font-family: gelica, sans-serif;
  font-weight: 300;
  font-style: normal;
}

a {
  color: #3b8fd6;

  &:hover {
    color: #2c6a9e;
  }
}

body {
  background: -webkit-radial-gradient(
    center,
    ellipse cover,
    #4b4242 0%,
    #413d3d 100%
  );
  background: -moz-radial-gradient(
    center,
    ellipse cover,
    #4b4242 0%,
    #413d3d 100%
  );
  background: -o-radial-gradient(
    center,
    ellipse cover,
    #4b4242 0%,
    #413d3d 100%
  );
}
.book {
  background: linear-gradient(
    -30deg,
    #52a5ea -20%,
    #3b8fd6 46%,
    #2a7dc2 90%,
    #3e97e4 130%
  );

  margin: 0px auto;
  margin-top: 40px;
  width: 250px;
  height: 300px;
  border-radius: 10px 25px 25px 10px;
  box-shadow: 0px 2px 2px rgba(255, 255, 255, 0.24) inset, 2px 2px 0px #326792,
    0px 3px 0px #27567e, 0px 10px 40px #585858;
  border-left: 1px solid #326792;

  h1,
  p {
    color: #e1e1e1;
    text-align: center;
    padding-top: 100px;
    text-shadow: 0px 1px 2px #69afec;
    font-size: 24px;
    margin: 0px;
    line-height: 1.1;
  }

  p {
    padding-top: 5px;
    font-size: 13px;
    box-shadow: 0px -1px #1362a5;
    border-top: 1px solid #69afec;
    margin: 0px 60px;
  }
}

.book:after {
  content: "";
  position: absolute;
  height: 40px;
  width: 1px;
  margin-left: -1px;
  background: #b8cbdb;
  border-right: 1px solid #315c83;
  margin-top: 50px;
}
.book:before {
  content: "";
  position: absolute;
  height: 40px;
  width: 1px;
  margin-left: -1px;
  background: #b8cbdb;
  border-right: 1px solid #315c83;
  margin-top: 40px;
}
</style>
