<script lang="ts" setup></script>

<template>
  <div>
    <div class="review">
      <span class="avatar">
        <!-- img here -->
      </span>
      <div>
        <h5 class="user">Djunehor</h5>
        <ul class="tags">
          <li class="tag">unveried review</li>
          <li class="tag">unrated</li>
          <li class="tag">8/10/22 • 9:09am</li>
        </ul>
        <p>
          Finding a cottage to suit our requirements - location, bungalow - was
          relatively straightforward.Being able to reserve so far in advance
          (but 2022 for Jun 2024) was very welcome and gave us some comfort.When
          asked yesterday for our deposit being told 'we need to check some
          things' was a bit disconcerting, but it's turned out we're okay. Phew.
        </p>
      </div>
    </div>
    <div class="review">
      <span class="avatar">
        <!-- img here -->
      </span>
      <div>
        <h5 class="user">Djunehor</h5>
        <ul class="tags">
          <li class="tag">unveried review</li>
          <li class="tag">unrated</li>
          <li class="tag">8/10/22 • 9:09am</li>
        </ul>
        <p>
          Finding a cottage to suit our requirements - location, bungalow - was
          relatively straightforward.Being able to reserve so far in advance
          (but 2022 for Jun 2024) was very welcome and gave us some comfort.When
          asked yesterday for our deposit being told 'we need to check some
          things' was a bit disconcerting, but it's turned out we're okay. Phew.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.review {
  border: 1px solid #f2f2f2;
  border-radius: 12px;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  gap: 16px;
  margin-bottom: 16px;
}

.avatar {
  display: inline-block;
  height: 40px;
  min-width: 40px;
  border-radius: 50%;
  background-color: #d6d6d6;
}

.user {
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 20px;
  color: #000000;
  margin: 0;
}

.tags {
  display: flex;
  gap: 10px;
  padding: 6px 0;
}

.tag {
  border-radius: 10px;
  border: 1px solid #ccc;
  padding: 0 10px;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 16px;
}

p {
  margin: 0;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 20px;
}
</style>
