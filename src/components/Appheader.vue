<script>
export default {
    data() {
        return {
            links: [
                {
                    label: 'characters',
                    href: '#',
                    active: false
                },
                {
                    label: 'comics',
                    href: '#',
                    active: false
                },
                {
                    label: 'movies',
                    href: '#',
                    active: false
                },
                {
                    label: 'tv',
                    href: '#',
                    active: false
                },
                {
                    label: 'games',
                    href: '#',
                    active: false
                },
                {
                    label: 'collectibles',
                    href: '#',
                    active: false
                },
                {
                    label: 'video',
                    href: '#',
                    active: false
                },
                {
                    label: 'fand',
                    href: '#',
                    active: false
                },
                {
                    label: 'tv',
                    href: '#',
                    active: false
                },
                {
                    label: 'news',
                    href: '#',
                    active: false
                },
                {
                    label: 'shop ',
                    href: '#',
                    active: false
                }
            ]

        }
    }
}
</script>
<template lang="">
    <!--  logo e link  -->
    <header class="container">
        <div class="j-between flex">
            <a href="/">
                <img src="../img/dc-logo.png " alt="">
            </a>
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :href="link.href">
                    {{ link.label }}
                    </a>
                </li>
            </ul>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/mixis_header.scss' as*;

header {
    padding: 20px 0px;
}

ul li {
    display: inline-block;

    &:hover {
        border-bottom: 5px solid blue;
    }
}

li {
    padding: 0px 10px;
    margin-top: 40px;
}

a {
    @include linkHeader;
}
</style>