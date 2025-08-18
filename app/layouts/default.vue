<template>
    
    <v-app>
        <v-container class="fill-height align-center align-content-center ga-4" max-width="90dvw" width="70dvw" >
            
            <header class="d-flex justify-center align-center w-100 bg-yellow-accent-2 rounded-xl px-5">
                <v-spacer></v-spacer>
                <h1 class="text-h2 font-weight-bold">ADICIONAR ALUNO</h1>
                <v-spacer></v-spacer>
                <v-btn icon="mdi-close" text="Fechar" aria-label="Fechar" class="bg-red-accent-2 mr-5" />
            </header>

            <v-main class="h-75">
                <slot />
            </v-main>

        </v-container>
    </v-app>
</template>

<script setup>

</script>

<style lang="scss" scoped>


header {
    height: 10dvh;
}

.v-application {
    height: 100dvh;
    background-image: url("~/assets/images/background.svg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: bottom;

}

</style>