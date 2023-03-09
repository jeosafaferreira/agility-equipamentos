<template>
  <div style="display: flex;
    align-items: center;
    justify-content: center;transform: translateY(50%);">
    <div style="width:500px">
      <v-card class="elevation-12">
        <v-toolbar color="primary">
          <v-toolbar-title>Efetuar Login</v-toolbar-title>
        </v-toolbar>
        <v-card-text>
          <v-form>
            <v-text-field prepend-icon="person" name="login" label="E-mail" type="text"></v-text-field>
            <v-text-field id="password" name="password" prepend-icon="lock"  label="Senha" type="password"></v-text-field>
          </v-form>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn active to="/home">Login</v-btn>
        </v-card-actions>
      </v-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  props: {
    source: String,
  },
};
</script>

<style></style>