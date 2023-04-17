<script lang="ts" setup></script>

<template>
  <div class="blue-background">
    <h5>Add a review</h5>
    <form>
      <input type="text" name="alias" placeholder="Your name/alias" />
      <div class="flex">
        <input
          type="text"
          name="company"
          placeholder="Type or search company name"
        />
        <button>Add</button>
      </div>
      <textarea
        name="comment"
        id="comment"
        cols="30"
        rows="10"
        placeholder="Add your review"
      ></textarea>

      <button type="submit">Submit a review</button>
    </form>
  </div>

  <p>
    rvws.cafe aggregates user feedback and comments on Nigerian businesses, we
    don’t have spam or fake review detection, we source reviews from social
    media sites and from our review form
  </p>
</template>

<style scoped>
.blue-background {
  background: linear-gradient(
    180deg,
    #0094ff -13.99%,
    #3246fa 49.84%,
    #0047ff 117.16%
  );
  border-radius: 12px;
  padding: 20px 20px 40px;
  max-width: 320px;
}

h5 {
  color: #fff;
  margin: 0 0 20px;
}

.flex {
  display: flex;
  gap: 10px;
}

.flex > button {
  width: 68px;
}

input,
textarea {
  padding: 12px;
  background: #000000;
  opacity: 0.3;
  border-radius: 8px;
  border: 0;
  width: 100%;
  color: #fff;
  outline: none;
  margin-bottom: 20px;
}

button {
  background: rgba(255, 255, 255, 0.15);
  box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.13);
  border-radius: 10px;
  border: 0;
  height: 40px;
  width: 100%;
  color: #fff;
}
</style>
