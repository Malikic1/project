<template>
  <section class="flex-col flex">
    <button class="cat-btn">Fashion</button>
    <button class="cat-btn">Beauty Wellness & Spa</button>
    <button class="cat-btn">System and Tech</button>
    <button class="cat-btn">Spory & Hobbies</button>
    <button class="cat-btn">Animal & pets</button>
    <button class="cat-btn">Home & Gaejn</button>
    <button class="cat-btn">Antiques & Art</button>
    <button class="cat-btn">More Category</button>
  </section>
</template>
<script>
export default {
  name: "CategoryPanel",
};
</script>
<style scoped>
.cat-btn {
  background: transparent;
  border: none;
  padding: 9px 5px 9px 7px;
  text-align: left;
}
.cat-btn:hover {
  background-color: royalblue;
  border-radius: 5px;
}
section {
  width: 180px;
}
</style>
