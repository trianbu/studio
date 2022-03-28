<template>
    <div class="container__column">
        <img class="image" src="/images/SH1.jpeg" alt="" />
        <img class="image" src="/images/SH2.jpeg" alt="" />
        <img class="image" src="/images/SH3.jpg" alt="" />
        <img class="image" src="/images/SH4.jpg" alt="" />
        <img class="image" src="/images/SH5.jpg" alt="" />
        <img class="image" src="/images/NY1.jpeg" alt="" />
        <img class="image" src="/images/NY2.jpeg" alt="" />
        <img class="image" src="/images/NY3.jpeg" alt="" />
    </div>
</template>

<style>
.container__column {
  max-width: 50%;
}
/* @media only screen
  and (min-width : 1000px) {
      .container__column {
          max-width: 1000px;
      }
} */
.image {
  max-width: 100%;
  scroll-snap-align: center;
  padding-top: 50px;
}
</style>
