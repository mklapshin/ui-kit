<template>
  <div>
    <select :class="$style.selector">
      <slot>
        <option></option>
        <option></option>
        <option></option>
      </slot>
    </select>
  </div>
</template>

<script>
</script>

<style lang="scss" module>
.selector {
  width: 200px;
  height: 35px;
  display: block;
  margin-top: 5px;
  font-size: 14px;
  border: none;
  border-radius: 3px;
  outline: none;
  background-color: #f4f4f4;
}
</style>

<script>
</script>