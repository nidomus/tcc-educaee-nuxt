<template>

    <v-card class="h-100 bg-cyan-accent-2" rounded="xl" border="xl" density="comfortable">
        <v-form class="h-100 py-5 px-5" @submit.prevent max-height="80%">
            <v-container max-height="50%">
                <v-row>
                    <v-col cols="5">
                        <v-text-field rounded label="Buscar aluno" color="cyan-darken-4" density="compact"
                            variant="solo" append-inner-icon="mdi-magnify" hide-details></v-text-field>
                    </v-col>
                </v-row>

                <v-row>
                    <v-col cols="12">

                        <v-table>
                            <thead>
                                <tr class="text-h5 font-weight-bold  ">
                                    <th>Nome</th>
                                    <th>Idade</th>
                                    <th>Ano</th>
                                    <th>Ações</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr v-for="a in alunos" :key="a.nome" class="text-subtitle-1">
                                    <td>
                                        <img :src="`/images/${a.foto}.jpg`" alt="Foto do aluno"></img>

                                        <span>
                                            {{ a.nome }}
                                        </span>
                                    </td>
                                    <td>{{ a.idade }}</td>
                                    <td>{{ a.ano }}</td>
                                </tr>
                            </tbody>
                        </v-table>
                    </v-col>
                </v-row>

            </v-container>

        </v-form>

    </v-card>

</template>

<script setup>

import json from './alunos.json';


const alunos = ref(json);



</script>

<style lang="scss" scoped></style>