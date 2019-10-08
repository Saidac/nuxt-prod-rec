<template>
    <div class="container mx-auto my-5 p-5">
        <div v-for="product in products" v-bind:key="product.id" class="w-1/4 bg-white border rounded-lg m-5 p-5">
            <a :href='product.href'>
                <img :alt='product.alt' :src='product.src'>            
            </a>
        </div>
    </div>
</template>

<script>
    export default {
        data: function() {
            return {
                products: [
                {
                    id: 1,
                    href: '/en-gb/playstation-plus-membership',
                    alt: 'PlayStation Plus',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/16091920/1EPClSqCSzjVtsytQbeJNV/Playstation_Plus_Logo_Popular_Products.jpg'
                },
                {
                    id: 2,
                    href: '/en-gb/nintendo-eshop-card',
                    alt: 'Nintendo eShop Card',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/08131249/1EPClSqCSzjVtsytQbeJNV/nintendo-eshop-recommendation.png'
                },
                {
                    id: 3,
                    href: '/en-gb/o2-top-up',
                    alt: 'o2 top up',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/22150711/1EPClSqCSzjVtsytQbeJNV/o2-recommendation.png'
                },
                {
                    id: 4,
                    href: '/en-gb/xbox-gift-card',
                    alt: 'Xbox Gift Card',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/04085123/1EPClSqCSzjVtsytQbeJNV/XBOX_logo.png'
                },
                {
                    id: 5,
                    href: '/en-gb/itunes-gift-card',
                    alt: 'iTunes Voucher',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/13080146/1EPClSqCSzjVtsytQbeJNV/app-store-and-itunes-recommendations.png'
                },
                {
                    id: 6,
                    href: '/en-gb/psn-card',
                    alt: 'PSN Card',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/16091804/1EPClSqCSzjVtsytQbeJNV/psn-card.png'
                },
                ]
            }
        }
    }
</script>

<style lang="postcss" scoped>

</style>