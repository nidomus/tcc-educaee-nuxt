<template>
    <v-container class="h-100 " rounded="xl" border="xl" density="comfortable"  >
        <v-row class="h-50">
            <v-col cols="4"  height="100%" class="d-flex justify-center">
                <v-btn stacked="" height="100%" width="85%" color="light-green-accent-3" class="d-flex justify-center ga-4">
                    <span class="py-6 text-h4">
                        INICIAR SESSÃO
                    </span>
                
                    <v-img   width="10em"  src="~/assets/images/play.png"></v-img>
               
                </v-btn>
            </v-col>
            <v-col cols="4"  height="100%" class="d-flex justify-center">
                <v-btn stacked height="100%" width="85%" color="cyan-accent-2" density="compact" >
                    <span class="py-6 text-h4">
                        MEUS ALUNOS
                    </span>
                    
                    <v-img  width="20em"   src="~/assets/images/alunos.png"></v-img>
               
                </v-btn>
            </v-col>
            <v-col cols="4"  height="100%" class="d-flex justify-center">
                <v-btn stacked="" height="100%" width="85%" color="purple-accent-2">
                    <span class="py-6 text-h4">
                        ADICIONAR ALUNO
                    </span>
                
                    <v-img  width="10em"  src="~/assets/images/add_aluno.png"></v-img>
               
                </v-btn>
            </v-col>
        </v-row>
                <v-row class="h-50">
            <v-col cols="4"  height="100%" class="d-flex justify-center">
                <v-btn stacked="" height="100%" width="85%" color="orange-accent-3">
                    <span class="py-6 text-h4">
                        ATIVIDADES
                    </span>
                
                    <v-img  width="10em"  src="~/assets/images/atividades.png"></v-img>
               
                </v-btn>
            </v-col>
            <v-col cols="4"  height="100%" class="d-flex justify-center">
                <v-btn stacked="" height="100%" width="85%" color="light-green-accent-3" >
                    <span class="py-6 pb-6 text-h4">
                        MINHAS SESSÕES
                    </span>
                
                    <v-img   width="10em"  src="~/assets/images/minhas_sessoes.png"></v-img>
               
                </v-btn>
            </v-col>
            <v-col cols="4"  height="100%" class="d-flex justify-center">
                <v-btn stacked=""  height="100%" width="85%" color="blue-grey-lighten-4">
                    <span class="py-6 text-h4 ">
                        RELATÓRIOS
                    </span>
                
                    <v-img   width="10em"  src="~/assets/images/relatorio.png"></v-img>
               
                </v-btn>
            </v-col>
        </v-row>

    </v-container>
</template>

<script setup>

</script>

<style lang="scss" scoped>

.v-btn{
    border-radius: 15%;
    // box-shadow: -9px 9px 4px 3px rgba(0,0,0,0.59);
    // -webkit-box-shadow: -9px 9px 4px 3px rgba(0,0,0,0.59);
    // -moz-box-shadow: -9px 9px 4px 3px rgba(0,0,0,0.59);
}

.v-btn:focus{
    outline: 4px solid rgb(24, 103, 192);
}


</style>
