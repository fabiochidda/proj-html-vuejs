<template>
    <div class="container-fluid msFooterContainer">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-4 py-5 text-center">
                    <div class="msFooterShopLink">
                        <img src="../assets/img/avadabarbers_footer_shop_image-300x234.png" alt="">
                    </div>
                    <button class="bg-transparent px-4 py-2" type="button">SHOP OUR RANGE NOW</button>
                </div>
                <div class="col-4 py-5">
                    <div class="msFooterInfo text-center">
                        <figure>
                            <img src="../assets/img/avadabarbers-stickylogo-x2.png" alt="">
                        </figure>
                        <div class="msFooterText py-4">
                            <p>Avada Barbers</p>
                            <p>123 New York Street</p>
                            <p>New York City</p>
                            <p>info@yourwebsite.com</p>
                            <p>+1 (555) 555-1212</p>
                        </div>
                        <div class="msFooterLinks">
                            <p>FOLLOW US</p>
                            <ul class="d-flex justify-content-center gap-3">
                                <li v-for="(el, i) in footerLinks" :key="i" ><a :href="el.href"><i class="fa-brands " :class="el.icon"></i></a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-4 py-5 text-center">
                    <div class="msFooterShopLink">
                        <img src="../assets/img/avadabarbers_footer_appointment_image-300x234.png" alt="">
                    </div>
                    <button class="bg-transparent px-4 py-2" type="button">BOOK YOUR APPOINTMENT</button>
                </div>
            </div>
        </div>
        <div class="col-12 msCopyright d-flex justify-content-center align-items-center py-4">
            <p>&copy; Copyright 2012-2020 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by VueJS</p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'msFooter',
    data() {
        return {
            footerLinks: [
                {
                    icon: 'fa-facebook',
                    href: '#'
                },
                {
                    icon: 'fa-twitter',
                    href: '#'
                },
                {
                    icon: 'fa-youtube',
                    href: '#'
                },
                {
                    icon: 'fa-instagram',
                    href: '#'
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import '../assets/scss/colors.scss';

ul {
    padding: 0;
}

a {
    color: currentColor;
}

.msFooterContainer {
    background: $cod-gray;
    padding: 0;
}

.msFooterText {
    p {
        margin: 0;
        color: $emperor;
    }
}

button {
    font-size: 20px;
    color: $driftwood;
    border: 2px solid $driftwood;
}

.msFooterLinks {
    p {
        color: $emperor;
    }
}

.msCopyright {
    background-color: $cod-gray-light;

    p {
        margin: 0;
        color: $emperor;
    }
}
</style>