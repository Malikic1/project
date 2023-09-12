<template>
  <header>
    <aside class="flex jus-between">
      <div class="self-center">
        <p class="logo fs-xxl bold">Logo</p>
      </div>
      <div class>
        <input type="text" name="" value="" />
        <select class="s-cat col-1">
          <option value="">All Category</option>
        </select>
        <button>Search</button>
      </div>
      <div class="flex gap-2">
        <section class="flex flex-col text-center">
          <span><i>cc</i></span>
          <span class="fs-xs col-1">Favourite</span>
        </section>
        <section class="flex flex-col text-center">
          <span><i>cc</i></span>
          <span class="fs-xs col-1">My Cart</span>
        </section>
        <section class="flex flex-col text-center">
          <span><i>cc</i></span>
          <span class="fs-xs col-1">Profile</span>
        </section>
      </div>
    </aside>
    <nav class="flex jus-between">
      <section>
        <a href="" class="fs-sm col-1 mr">All Category</a>
        <a href="" class="fs-sm col-1 mr">Super Deal</a>
        <a href="" class="fs-sm col-1 mr">Gift Boxes</a>
        <a href="" class="fs-sm col-1 mr">Blog</a>
        <a href="" class="fs-sm col-1 mr">Connect Us</a>
        <a href="" class="fs-sm col-1 mr">About Us</a>
        <a href="" class="fs-sm col-1">Help</a>
      </section>
      <section>
        <a href="" class="fs-sm col-1 mr">
          <select class="s-lang col-1">
            <option>English, USD</option>
          </select>
        </a>
        <a href="" class="fs-sm col-1">Get the app</a>
      </section>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Navigation",
};
</script>

<style>
.flex {
  display: flex;
}
.flex-col {
  flex-direction: column;
}
.jus-between {
  justify-content: space-between;
}
.jus-around {
  justify-content: space-around;
}
.jus-center {
  justify-content: center;
}
.self-center {
  align-self: center;
}
.text-center {
  text-align: center;
}

body {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
.fs-xs {
  font-size: 0.8rem;
}
.fs-sm {
  font-size: 0.85rem;
}
.fs-xxl {
  font-size: 1.5rem;
}
.gap-2 {
  gap: 10px;
}
.bold {
  font-weight: 600;
}
.bolder {
  font-weight: 700;
}
.col-1 {
  color: grey;
}
a {
  text-decoration: none;
}
</style>

<style scoped>
.s-cat,
input {
  border: solid grey 2px;
}
input {
  padding: 6px 2px 6px 2px;
  border-radius: 5px 0 0 5px;
}
.s-cat {
  padding: 5px 2px 5px 2px;
  border-right: none;
  border-left: none;
}
.s-lang {
  border: none;
}
button {
  background-color: royalblue;
  padding: 6px 15px 5.5px 15px;
  border: solid royalblue 2px;
  border-radius: 0 5px 5px 0;
}
nav {
  margin-top: 7px;
  padding: 5px 2px 5px 2px;
  border: solid grey 2px;
  border-right: none;
  border-left: none;
  padding: 10px 5% 10px 5%;
}
header {
}
.logo {
  margin: 0;
}
.mr {
  margin-right: 15px;
}
aside {
  padding: 12px 5% 4px 5%;
}
</style>
