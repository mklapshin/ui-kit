<template>
  <div :class="$style.tree">
    <div :class="$style.logo">
      <div :class="$style.logoImageBlock">
        <img
          :class="$style.logoImage"
          src="../../assets/img/logoRadar.png"
          alt=""
        />
      </div>
      <div :class="$style.logoText">
        <p :class="$style.text1">RADAR Optimus</p>
        <p :class="$style.text2">by Radar Research</p>
      </div>
    </div>
    <div :class="$style.treeButton">
      <myButton>New Report</myButton>
    </div>
    <div :class="$style.treeButton">
      <myButton>New List</myButton>
    </div>
    <div :class="$style.treeForms">
      <div :class="$style.formHeader">Header 1</div>
      <myForm>
        <option>Weight 1</option>
        <option>Weight 2</option>
        <option>Weight 3</option>
      </myForm>
      <div :class="$style.formHeader">Header 2</div>
      <myForm>
        <option>Weight 4</option>
        <option>Weight 5</option>
        <option>Weight 6</option>
      </myForm>
    </div>
    <div :class="$style.treeForms">
      <div :class="$style.formHeader">Header 3</div>
      <myForm>
        <option>Weight 7</option>
        <option>Weight 8</option>
        <option>Weight 9</option>
      </myForm>
      <div :class="$style.formHeader">Header 4</div>
      <myForm>
        <option>Weight 10</option>
        <option>Weight 11</option>
        <option>Weight 12</option>
      </myForm>
    </div>
    <div :class="$style.treeForms">
      <div :class="$style.formHeader">Header 5</div>
      <myForm>
        <option>Weight 13</option>
        <option>Weight 14</option>
        <option>Weight 15</option>
      </myForm>
      <div :class="$style.formHeader">Header 6</div>
      <myForm>
        <option>Weight 16</option>
        <option>Weight 17</option>
        <option>Weight 18</option>
      </myForm>
    </div>
    <div :class="$style.treeButton">
      <myButton>Default Report</myButton>
    </div>
    <div :class="$style.treeButton">
      <myButton>Add Block</myButton>
    </div>
    <div :class="$style.treeButton">
      <myButton>Add</myButton>
    </div>
  </div>
</template>

<script>
</script>

<script>
import myButton from "./myButton.vue";
import myForm from "./myForm.vue";

export default {
  name: "App",
  components: {
    myButton,
    myForm,
  },
};
</script>

<style lang="scss" module>
.logo {
  width: 180px;
  height: 50px;
  margin: 12px 0 30px 20px;
  display: flex;
  border-bottom: 1px solid #000;
}

.logoImage {
  width: 45px;
  height: 40px;
}

.text1 {
  font-size: 16px;
  line-height: 16px;
  margin: 3px 0 0 0;
}

.text2 {
  font-size: 12px;
  line-height: 12px;
  margin: 1px 0 0 0;
}

.tree {
  width: 280px;
  height: 1500px;
  background-color: #ffffff;
  text-align: left;
}

.formHeader {
  margin: 0 0 2px 0;
  font-size: 12px;
  line-height: 12px;
  font-weight: 400;
  margin-top: 20px;
}

.treeForms {
  width: 190px;
  height: 160px;
  margin: 0 0 0 10px;
  border-bottom: 1px solid #b8b4b4;
}

.treeButton {
  margin: 0 0 20px 52px;
}
</style>