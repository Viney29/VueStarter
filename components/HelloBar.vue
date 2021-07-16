<template>
  <div :class="$style.bar">This is boilerplate</div>
</template>

<style lang="scss" module>
.bar {
  @include text('center');
  @include use-text-style('copy');

  background-color: #fbc34f;
  color: black;
}
</style>
