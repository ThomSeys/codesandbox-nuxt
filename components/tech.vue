<template>
  <div class="tech">
    <h3>Hi,</h3>
    <h4>
      I'm Thomas, Gentian, Creative mind, Developer since <span>1991</span>.
    </h4>
    <p>
      Since i was young, i'm facinated by design and user friendly layouts.
      <br />
      At first i was looking for it in magazines and small artwork on stickers,
      after a while, since the internet wasn't that populated when i was 10, on
      the web. <br />
      When i was 16, i chose the direction of the web & media. Learned how to
      make websites with simple <i>html-code</i> and a little bit of <i>css.</i>

      <br />
      <br />
      <strong
        >How i fill my days now, you can find out scrolling further!</strong
      >
    </p>
  </div>
</template>

<script>
export default {
  name: "Tech",
  components: {}
};
</script>

<style scoped>
.tech {
  text-align: left;
  padding: 2rem;
}

.tech h3,
.tech h4 {
  font-weight: normal;
}

.tech h4 span {
  font-weight: bold;
  font-style: italic;
}

.tech h3 {
  font-weight: bold;
  font-style: italic;
  margin-bottom: 1rem;
}
</style>
