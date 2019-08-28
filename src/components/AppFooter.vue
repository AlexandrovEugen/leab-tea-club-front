<template>
    <v-toolbar
            color="yellow accent-2"
            dark
            flat
            tabs
    >
        <v-toolbar-title class="black--text font-weight-bold">Мы в социальных сетях</v-toolbar-title>
        <div class="flex-grow-1"></div>
        <div class="flex-md-nowrap">
            <v-btn class="ma-1 v-color-picker__hue">войти</v-btn>
            <v-btn class="v-color-picker__hue">подать заявку</v-btn>
        </div>
    </v-toolbar>
</template>

<script>
    export default {
        name: "AppFooter",
        icons: [
            {
                icon: '',
                link: ''
            }
        ]
    }
</script>

<style scoped>

</style>