<template>
    <div class="header">
        <div class="container header-menu-contain">
            <div>
                <img src="../assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div class="contain-menu">
                <ul class="menu">
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                    <li>
                        <a href="#">link</a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: "HeaderMenu",
};
</script>

<style lang="scss" scoped>
@import url('../styles/common.scss');
@import url('../styles/variables.scss');
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
        height: 70px;
        color: $primary_color;
        &:hover {
            border-bottom: 3px solid $primary_color;
        }
    }
}
a {
    text-decoration: none;
    line-height: 70px;
}
img {
    width: 70px;
}
</style>