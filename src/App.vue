<template functional>
  <div id="app">
    <div class="parent">
      <h1 class="parent_title">
        just a title
      </h1>

      <div class="parent_child">
        <ParentCmp />
      </div>
    </div>
  </div>
</template>

<style scoped>
* {
  margin: 0;
}

li {
  list-style: none;
}

body {
  padding: 100px;
  background: lightcoral;
}

.parent {
  padding: 20px;
  background: greenyellow;
}

.parent_title {
  font-size: 48px;
  text-decoration: underline;
}
</style>
