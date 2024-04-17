<script>
import AiInput from "@/components/sft.vue";
import AiDescribeFilter from "@/components/tft.vue";
</script>

<template>
  <div class="container is-fluid is-3 mt-5">
    <div class="columns">
      <div class="column">
        <div class="box m-5 pt-3">
          <AiInput/>
        </div>
        <div class="column">
          <div class="box m-5 pt-3">
            <AiDescribeFilter/>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
