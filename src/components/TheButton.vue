<template>
    <router-link :to="to" class="btn" :class="{
        'btn-primary':primary,
        'btn-danger':danger,
        'btn-info':info,
        'btn-large':large,
        'btn-sm':small,
        '':normal,
        'btn-block':block
    }">
    <slot/>
    </router-link>
</template>

<script>
    export default {
        props:{
            primary:{
                required:false,
                type:Boolean,
                default: true
            },
            danger:{
                required:false,
                type:Boolean,
                default: false
            },
             info:{
                required:false,
                type:Boolean,
                default: false
            },
            to:{
                required: true
            },
            large:{
                require:false,
                type:Boolean,
                default: false
            },
            small:{
                require:false,
                type:Boolean,
                default: false
            },
            normal:{
                require:false,
                type:Boolean,
                default: false
            },
            block:{
                require:false,
                type:Boolean,
                default: false
            }

           
            
        }
    }
</script>

<style lang="scss" scoped>

</style>