<template>
  <div :class="$style.container">
    <div :class="$style.block">
      <ReportTree />

      <div :class="$style.wrapper">
        <div :class="$style.blockHeader">Продукт с подписками и скидками</div>
        <div :class="$style.blockHeader2">
          <div :class="$style.header2">Все атрибуты на стартовых позициях</div>
          <div :class="$style.app">
            <myButton>Captions</myButton>
            <myButton>Data Map</myButton>
            <myButton>Correspondance</myButton>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import myButton from "./myButton.vue";
import ReportTree from "./ReportTree.vue";

export default {
  name: "App",
  components: {
    myButton,
    ReportTree,
  },
};
</script>

<style lang="scss" module>
.container {
  background-color: #f4f4f4;
  height: 1500px;
}

.block {
  display: flex;
}

.blockHeader {
  height: 20px;
  padding: 20px 0 0 30px;
  text-align: left;
}

.wrapper {
  width: 100%;
  height: 1000px;
}

.blockHeader2 {
  display: flex;
}

.header2 {
  width: 50%;
  padding: 30px 0 0 30px;
  text-align: left;
}

.app {
  width: 480px;
  height: 100px;
  background-color: #f4f4f4;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>