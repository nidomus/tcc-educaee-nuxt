<template>

    <v-card class="h-100 bg-purple-accent-3" rounded="xl" border="xl" density="comfortable" >
        <v-form class="h-100 pt-6 px-6" @submit.prevent>
            <v-container max-height="50%">
                <v-row>
                    <v-col lg="3" md="12">
                        <v-avatar size="10rem" border="xl" density="compact" color="black">
                            <v-img
                                alt="Foto de Perfil"
                                src="~/assets/images/aluna.png"
                                cover
                                color="white"
                            >
                            </v-img>
                        </v-avatar>
                    </v-col>
                    <v-col lg="9" md="10" sm="12">
                        <v-row>
                            <v-col lg="10" sm="12">
                                <v-text-field variant="solo" aria-required="true" label="Nome completo do aluno" bg-color="white">
                                </v-text-field>
                            </v-col>
                            <v-col lg="2" md="12">
                                <v-select bg-color="white" :items="['Masculino', 'Feminino']" label="Sexo"></v-select>
                            </v-col>
                            <v-col lg="4" md="12">
                                <v-date-input prepend-icon="" prepend-inner-icon="mdi-calendar" bg-color="white"  label="Data de Nascimento"></v-date-input>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col cols="8">
                        <v-text-field bg-color="white" variant="solo" label="Escola de Origem"></v-text-field>
                    </v-col>
                    <v-col cols="2">
                        <v-select bg-color="white" variant="solo" label="Ano/Série"></v-select>
                    </v-col>
                    <v-col cols="2">
                        <v-select bg-color="white" variant="solo" label="Turma"></v-select>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col cols="10">
                        <v-text-field bg-color="white" variant="solo" label="Nome completo do Responsável"></v-text-field>
                    </v-col>
                    <v-col cols="2">
                        <v-text-field bg-color="white" variant="solo" label="Parentesco"></v-text-field>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col cols="6">
                        <v-text-field bg-color="white" variant="solo" type="tel" label="Telefone do Responsável"></v-text-field>
                    </v-col>
                    <v-col cols="6">
                        <v-text-field bg-color="white" variant="solo" label="E-mail do Responsável" aria-label="E-mail do Responsável" type="email">
                            
                        </v-text-field>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col cols="12">
                        <v-textarea bg-color="white"   variant="solo" type="tel" label="Diagnóstico e apresentação de especificidades">
                        </v-textarea>
                    </v-col>
                </v-row>
                <v-row>
                    <v-col cols="12">
                        <v-select 
                            bg-color="white"
                            chips
                            multiple
                            variant="solo"
                            type="tel"
                            label="Habilidades, capacidades e interesses"
                            :items="['Habilidade 1', 'Habilidade 2', 'Habilidade 3', 'Habilidade 4', 'Habilidade 5', 'Habilidade 6', 'Habilidade 7', 'Habilidade 8', 'Habilidade 9', 'Habilidade 10']"
                         ></v-select>
                    </v-col>
                </v-row>
                <v-row>
                    <v-spacer></v-spacer>
                    <v-col cols="12" class="d-flex justify-end ga-4" >
                        <v-btn size="x-large" type="button">
                            Cancelar
                        </v-btn>
                        <v-btn color="success" size="x-large" type="submit">
                            Adicionar
                        </v-btn>
                    </v-col>
                </v-row>
            </v-container>
        </v-form>
            
    </v-card>


</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>