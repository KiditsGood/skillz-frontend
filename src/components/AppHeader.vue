<template>
  <header class="header">
    <a class="header__logo">
      <img src="../assets/static/img/logo.svg" alt="" class="header__logo-image">
    </a>
    <nav class="header__nav">
      <a href="" class="header__nav-item">Courses</a>
      <a href="" class="header__nav-item">Free Workshops</a>
      <a href="" class="header__nav-item">Blog</a>
      <a href="" class="header__nav-item">About</a>
      <a href="" class="header__nav-item">Contact</a>
    </nav>
    <a class="header__cart">
      <img src="../assets/static/img/cart.svg" alt="" class="header__cart-image">
    </a>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 10px;
    padding: 25px 100px;
    background: #1C1C33;

    &__logo{
      width: 135px;
      height: 44px;

      &-image{
        width: inherit;
      }
    }

    &__nav{
      display: flex;
      align-items: center;
      gap: 40px;

      &-item{
        font-size: 17px;
        line-height: 27px;
        color: #F6F6F8;

        &:hover{
          color: #57D9A6;
          cursor: pointer;
        }
      }
    }

    &__cart{
      width: 32px;
      height: 32px;

      &-image{
        width: inherit;
      }
    }
  }
</style>
