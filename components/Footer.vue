<template>
  <div :class="$style.footer">
    <logo :class="$style.logo" />
    <div :class="$style.center">
      <Navigation />
    </div>
    <div :class="$style.right">
    </div>
  </div>
</template>

<style lang="scss" module>

.footer {
  @include flex();
}

.center {
  @include flex();
}

</style>
