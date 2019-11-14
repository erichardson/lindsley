<template>
  <div class="root">
    <div class="main">
      <div class="page-container">
        <h2 class="tagline">
          Learn your times tables
          <strong>through Precision Teaching.</strong>
        </h2>
        <div class="sums"></div>
        <div class="get-started">
            <h3>Try Precision Teaching free with</h3>
        </div>
      </div>
    </div>
    <div id="features" class="features">
      <div class="feature effortless">
        <h3 class="feature-title">Track your progress</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.main {
  width: 100%;
  height: 800px;
  background-image: linear-gradient(to right, #00001a, #003333);
  overflow: hidden;
}

.page-container {
  max-width: 960px;
  overflow: hidden;
  margin: 0 auto;
  position: relative;
}

.main .tagline {
  color: #fff;
  font-size: 40px;
  line-height: 66px;
  margin: 100px 0 0;
  font-weight: 300;
  position: relative;
}

.main .tagline strong {
  display: block;
  font-size: 36px;
  line-height: 66px;
  color: #9ea0a6;
  margin: 0;
  font-weight: 300;
}

.main .sums {
    width: 320px;
    height: 240px;
    position: absolute;
    right: 0;
    top: 100px;
    background-image: url("../assets/SumsSmall.png");
}

.main .get-started {
    margin-top: 180px;
    overflow: hidden;
}

.features .feature {
  min-height: 800px;
}

.features,
.features .feature {
  width: 100%;
  overflow: hidden;
}

.features .feature .feature-title {
  font-size: 40px;
  color: #003333;
  text-align: center;
  margin: 0;
  line-height: 50px;
}

.features .feature.effortless {
  background: #fff;
}
</style>
