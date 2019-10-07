<template>
    <div class="container mx-auto my-5 p-10">
        <div class="bg-white border rounded-lg m-5 p-5 w-56">
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
                product:
                {
                    id: 1,
                    href: '/en-gb/playstation-plus-membership',
                    alt: 'PlayStation Plus',
                    src: 'https://static.rapido.com/cms/sites/19/2019/07/16091920/1EPClSqCSzjVtsytQbeJNV/Playstation_Plus_Logo_Popular_Products.jpg'
                }
            }
        }
    }
</script>

<style lang="postcss" scoped>

</style>