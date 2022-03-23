<template>
    <header>
        <div class="container">
            <div class="row justify-content-between align-items-center pt-4">
                <div class="col-auto">
                    <figure>
                        <img src="../assets/img/avadabarbers-logo-x1.png" alt="">
                    </figure>
                </div>
                <div class="col-auto">
                   <div class="collapse" id="navbarToggleExternalContent">
                    <ul class="p-4">
                        <li v-for="(el,i) in navLinks" :key="i"><a :href="el.href">{{el.text}}</a></li>
                    </ul>
                    </div>
                    <nav class="navbar navbar-dark">
                    <div class="container-fluid">
                        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                        </button>
                    </div>
                    </nav>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'MsHeader',
    data() {
        return {
            navLinks: [
                {
                    text: 'Barber Shop',
                    href: '#',
                },
                {
                    text: 'Pro Barbers',
                    href: '#',
                },
                {
                    text: 'Services',
                    href: '#',
                },
                {
                    text: 'Avada Grooming Products',
                    href: '#',
                },
                {
                    text: 'Reviews',
                    href: '#',
                },
                {
                    text: 'Blog',
                    href: '#',
                },
                {
                    text: 'Contacts',
                    href: '#',
                },
            ]
        }
    }
}
</script>

<style scoped lang="scss">

a {
    text-decoration: none;
    color: currentColor;
}
</style>