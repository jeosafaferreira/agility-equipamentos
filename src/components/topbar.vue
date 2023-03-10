<template>
    <v-app-bar flat style="background: #2C3333; color:white">
      <v-container class="fill-height d-flex align-center">
        <v-avatar class="me-10 ms-4" color="grey-darken-1" size="32"></v-avatar>

        <v-btn variant="text">Equipamentos</v-btn>
        <v-btn variant="text">Chamados</v-btn>
        <v-btn variant="text">Financeiro</v-btn>
        <v-btn variant="text">Solicitações</v-btn>
        <v-btn variant="text">Relatórios</v-btn>

        <v-spacer></v-spacer>
      </v-container>
    </v-app-bar>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>