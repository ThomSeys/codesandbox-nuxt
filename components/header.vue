<template>
  <div class="header">
    <div class="header-image"></div>
    <div class="header-text">
      <h1 class="title">
        <span class="big-title">HI</span><span class="greeting">I'm</span>Thomas
      </h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  components: {}
};
</script>

<style scoped>
.header {
  overflow: hidden;
  width: 100vw;
  height: 100vh;
  display: block;
}

.header:before {
  display: block;
  content: "";
  width: 150%;
  position: absolute;
  bottom: -2.75vh;
  left: 0;
  right: 0;
  z-index: 5;
  border-bottom: 20vh solid #4fb99f;
  border-left: 100vw solid transparent;
}

.header-image {
  position: relative;
  overflow: hidden;
  width: 100%;
  height: 100vh;
  text-align: center;
  background-image: url("~static/IMG_20190206_135359.jpg");
}

.header-image:before {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 0.5;
  background-color: #000;
  z-index: 2;
  display: block;
  content: "";
}

.header-image img {
  z-index: 1;
}

.header-text {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  text-shadow: 0 2px 2px #000;
  font-weight: bold;
  z-index: 3;
}

.header img {
  height: 100%;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 4rem;
  color: #fff;
  letter-spacing: 1px;
  font-size: 10vh;
  vertical-align: top;
  font-style: italic;
  position: relative;
}

.title span.greeting {
  font-weight: bold;
  font-size: 10vh;
  color: #fff;
  font-style: italic;
  text-transform: none;
  display: block;
}

.title span.big-title {
  font-size: 50vh;
  line-height: 50vh;
  display: block;
  color: #fff;
  font-style: normal;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
</style>
