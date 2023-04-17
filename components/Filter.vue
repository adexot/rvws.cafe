<script lang="ts" setup></script>

<template>
  <ul class="filters">
    <li>
      <button>Everyting</button>
    </li>
    <li>
      <button>Local</button>
    </li>
    <li>
      <button>Facebook</button>
    </li>
    <li>
      <button>Twitter</button>
    </li>
  </ul>
</template>

<style scoped>
.filters {
  display: flex;
  padding: 20px 0;
}

button {
  border: none;
  background: none;
  outline: none;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
  padding: 6px 12px;
  cursor: pointer;
}

button:hover {
  background: #000;
  color: #fff;
  border-radius: 20px;
}
</style>
