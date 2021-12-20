<template>
    <div class="header">
        <div class="container header-menu-contain">
            <div>
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div class="contain-menu">
                <ul class="menu">
                    <li v-for="link in links" :key="link">
                        <a href="#">{{link.nameLink}}</a>
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
                  nameLink: 'CHARACTERS',
              },
              {
                  nameLink: 'COMICS',
              },
              {
                  nameLink: 'MOVIES',
              },
              {
                  nameLink: 'TV',
              },
              {
                  nameLink: 'GAMES',
              },
              {
                  nameLink: 'COLLECTIBLES',
              },
              {
                  nameLink: 'VIDEOS',
              },
              {
                  nameLink: 'FANS',
              },
              {
                  nameLink: 'NEWS',
              },
              {
                  nameLink: 'SHOP',
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