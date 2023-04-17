<script lang="ts" setup></script>

<template>
  <div>
    <h3 class="header">Companies</h3>
    <ul class="list">
      <li>
        <a class="list_item" href="">
          <div>
            <h5 class="company_name">Flutterwave</h5>
            <p class="review">30 reviews</p>
          </div>
          <span>></span>
        </a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
.header {
  font-weight: 700;
  font-size: 16px;
  line-height: 24px;
  color: #555555;
}

.list_item {
  display: flex;
  justify-content: space-between;
  align-items: center;
  text-decoration: none;
  border-bottom: 1px solid #f2f2f2;
  padding: 10px 16px;
}

.company_name {
  font-weight: 500;
  font-size: 16px;
  line-height: 22px;
  margin: 0;
}

.review {
  margin: 0;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 20px;
  color: #808080;
}
</style>
