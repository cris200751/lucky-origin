<template>
  <section>
    <div class="section-container">
      <h1 class="title">Introducing Lucky Meta</h1>
      <div class="video-wrapper">
        <img width="110" height="110" src="@/assets/images/Play-button.png" />
      </div>
      <p class="description">
        LUCKY METAS ARE FIERCE CREATURES THAT LOVE TO BATTLE, BUILD, AND HUNT
        FOR TREASURE! BUILD UP A COLLECTION AND USE THEM ACROSS AN EVER
        EXPANDING UNIVERSE OF GAMES!
      </p>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
.section-container {
  max-width: 1080px;
  margin: auto
}

.title {
  margin-top: 110px;
  margin-bottom: 60px;
  line-height: 63px;
  letter-spacing: 0.035em;
  text-align: center;
  font-size: 42px;
}

.description {
  font-weight: 600;
  font-size: 24px;
  line-height: 34px;
  letter-spacing: 0.05em;
  text-align: center;
  margin-bottom: 100px;
}

.video-wrapper {
  background: #515151 url("../../assets/images/man.png");
  background-repeat: no-repeat;
  border-radius: 20px;
  width: 950px;
  height: 433px;
  padding: 10px;
  display: flex;
  margin: auto;
  position: relative;
  z-index: 0;
  align-items: center;
  justify-content: center;
}
.video-wrapper:before {
  content: "";
  position: absolute;
  z-index: -1;
  inset: 0;
  padding: 5px;
  border-radius: 15px;
  background: linear-gradient(
    140.24deg,
    #fe53bb 15.06%,
    rgba(158, 149, 196, 0) 45.93%,
    rgba(106, 185, 202, 0) 60.84%,
    #09fbd3 86.66%
  );
  -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
  -webkit-mask-composite: xor;
  mask-composite: exclude;
}

.description {
  font-weight: 600;
  font-size: 24px;
  line-height: 20px;
  text-align: center;
  letter-spacing: 0.05em;
  margin-top: 70px;
}
</style>