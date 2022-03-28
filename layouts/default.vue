<template>
  <div>
      <div class="header"></div>
    <div class="container__main">
      <slot />
    </div>
    <div class="container__menu">
      <ul class="menu">
        <li><nuxt-link to="/">HOME</nuxt-link></li>
        <li><nuxt-link to="info">INFO</nuxt-link></li>
        <li><nuxt-link to="contact">CONTACT</nuxt-link></li>
      </ul>
    </div>
  </div>
</template>

<style>
/* .header {
    width: 100%;
    height: 30px;
    background-color: red;
    position: sticky;
} */
.container__main {
  /* padding-top: 30px; */
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  overflow-y: scroll;
  scroll-snap-type: y mandatory;
}
.container__menu {
  max-width: 100px;
  position: absolute;
  top: 50%;
  transform: translate(0, -50%);
}
.menu {
  list-style-type: none;
  font-family: Arial, Helvetica, sans-serif;
}
li {
  margin: 10px 0;
}
li:hover {
  color: #BBBBBB;
}
a {
    text-decoration: none;
    color: inherit;
}
</style>

