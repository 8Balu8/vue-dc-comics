<template>
    <footer>
        <div class="container">
            <div class="footer-menu">
                <div class="col-left">
                    <h4>DC COMICS</h4>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </ul>
                    <h4>SHOP</h4>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
                <div class="col-center">
                    <h4>DC</h4>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy Policy(New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div class="col-right">
                    <h4>SITES</h4>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>
            <div class="footer-logo">
                <img src="../assets/img/dc-logo-bg.png" alt="DC Logo">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name:'Footer'
}
</script>

<style lang="scss" scoped>
@import '../styles/common.scss';
footer {
    background-image: url('../assets/img/footer-bg.jpg');
    .container {
        position: relative;
        overflow: hidden;
        .footer-menu {
            display: flex;
        }
        .footer-logo img {
        width: 400px;
        position: absolute;
        top: -100px;
        right: 0;
        }
    }
}
h4 {
    color: white;
    padding: 10px 0;
}
ul {
    list-style: none;
    padding-right: 30px;
    line-height: 18px;
    padding-bottom: 5px;
}
li {
    color: gray;
    font-size: 11px;
    cursor: pointer;
    &:hover {
        color: white;
    }
}

</style>