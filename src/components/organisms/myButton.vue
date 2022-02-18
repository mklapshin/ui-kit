<template>
  <div>
    <button :class="$style.button">
      <slot> </slot>
    </button>
  </div>
</template>

<script>
</script>

<style lang="scss" module>
.button {
  width: 120px;
  height: 35px;
  font-size: 12px;
  line-height: 12px;
  font-weight: 600;
  padding: 7px 11px;
  color: #fff;
  background-color: #2f2f2f;
  border-radius: 35px;
  cursor: pointer;
  font-family: Roboto, Arial, Helvetica, sans-serif;
  letter-spacing: 0.02em;
  border: none;
}

.button:hover {
  background-color: #8a8181;
}

.button:active {
  background-color: #2f2f2f;
}
</style>

<script>
</script>