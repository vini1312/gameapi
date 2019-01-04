<template>

    <v-content>
        <v-toolbar dark>
            <v-btn flat color="cyan" value="Home">
                <font-awesome-icon icon="igloo"/>
            </v-btn>
            <v-btn flat color="red">
                <font-awesome-icon icon="eye"/>
            </v-btn>
            <v-spacer></v-spacer>
            <v-btn flat color="green" value="Lançamento">
                <font-awesome-icon icon="calendar-week"/>
            </v-btn>
            <v-btn flat color="pink" value="popular">
                <font-awesome-icon icon="heart"/>
            </v-btn>
            <v-btn flat color="yellow" value="best">
                <font-awesome-icon icon="glass-cheers"/>
            </v-btn>
        </v-toolbar>
    </v-content>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style>

</style>