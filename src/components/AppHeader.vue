<template xmlns:v-slot="http://www.w3.org/1999/XSL/Transform">
    <v-toolbar
            color="yellow accent-2"
            dark
            flat
            tabs
    >
        <v-app-bar-nav-icon class="black--text"></v-app-bar-nav-icon>
        <v-toolbar-title class="black--text font-weight-bold">Дефолтное название</v-toolbar-title>
        <div class="flex-grow-1"></div>
        <div class="flex-md-nowrap">
            <v-btn class="ma-1 v-color-picker__hue">войти</v-btn>
            <v-btn class="v-color-picker__hue">подать заявку</v-btn>
        </div>
        <template v-slot:extension="">
            <v-tabs
                    align-with-title
                    background-color="transparent"
                    v-model="tabs"
            >
                <v-tab class="black--text" href="#one">Устав</v-tab>
                <v-tab class="black--text" href="#two">Принципы</v-tab>
                <v-tabs-slider color="black"></v-tabs-slider>
            </v-tabs>
        </template>
    </v-toolbar>
</template>
<script>
    export default {
        data: () => ({
            fab: false,
            hidden: false,
            tabs: null,
        })
    }
</script>
