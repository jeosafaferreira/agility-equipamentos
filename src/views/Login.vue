<template>
  <v-sheet class="d-flex">
    <v-card class="elevation-12">
      <v-toolbar color="primary">
        <v-toolbar-title>Efetuar Login</v-toolbar-title>
      </v-toolbar>
      <v-card-text>
        <v-form>
          <v-text-field prepend-icon="person" name="login" label="Login" type="text"></v-text-field>
          <v-text-field id="password" prepend-icon="lock" name="password" label="Password" type="password"></v-text-field>
        </v-form>
      </v-card-text>
      <v-card-actions>
        <v-spacer></v-spacer>
        <v-btn color="primary" to="/">Login</v-btn>
      </v-card-actions>
    </v-card>
  </v-sheet>
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