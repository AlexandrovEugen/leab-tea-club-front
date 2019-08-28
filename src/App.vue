<template>
    <v-app>
        <v-card>
            <AppHeader/>
        </v-card>
        <v-content>
            <HomePage/>
        </v-content>
        <v-footer>
            <AppFooter/>
        </v-footer>
    </v-app>
</template>

<script>
    import HomePage from "./components/HomePage";
    import AppHeader from "./components/AppHeader";
    import AppFooter from "./components/AppFooter";

    export default {
        name: 'App',
        components: {
            AppFooter,
            AppHeader,
            HomePage
        },
        data: () => ({
            //
        }),
    };
</script>
