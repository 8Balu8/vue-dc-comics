<template>
    <div class="header">
        <div class="container header-menu-contain">
            <div>
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div class="contain-menu">
                <ul class="menu">
                    <li v-for="link in links" :key="link">
                        <a href="#">{{link.name}}</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "HeaderMenu",
  data: function() {
      return {
          links: [
              {
                  name: 'CHARACTERS',
              },
              {
                  name: 'COMICS',
              },
              {
                  name: 'MOVIES',
              },
              {
                  name: 'TV',
              },
              {
                  name: 'GAMES',
              },
              {
                  name: 'COLLECTIBLES',
              },
              {
                  name: 'VIDEOS',
              },
              {
                  name: 'FANS',
              },
              {
                  name: 'NEWS',
              },
              {
                  name: 'SHOP',
              }
          ]
      }
  }
};
</script>

<style lang="scss">
@import '../styles/common.scss';
@import '../styles/variables.scss';
.header {
    height: 100px;
    background-color: #ffffff;
    height: 100px;
    .header-menu-contain {
        height: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
}
.menu {
    display: flex;
    li {
        list-style: none;
        margin-left: 20px;
        height: 100px;
    }
}
a {
    text-decoration: none;
    line-height: 100px;
    padding-bottom: 38px;
    color: black;
     &:hover {
         color: $brand_primary_color;
         border-bottom: 3px solid $brand_primary_color;
        }
}
img {
    width: 70px;
}
</style>