<template>
  <div class="col-sm-6 col-md-4 col-lg-3">
    <div class="panel panel-default">
      <div class="panel-body quote">
        <slot></slot>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style>
.panel-body {
  font-family: "Tangerine", cursive;
  font-size: 24px;
  color: blue;
  border: 1px solid black;
}
.quote {
  cursor: pointer;
}
.quote:hover {
  background-color: lightsalmon;
}
</style>