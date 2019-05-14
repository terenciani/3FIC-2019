<template>
  <v-app>
    <v-content>
      <v-toolbar color="red" dark>
        <v-toolbar-side-icon color="white--text"></v-toolbar-side-icon>
        <v-toolbar-title>Barberia</v-toolbar-title>
        <v-spacer></v-spacer>
        <v-text-field label="Pesquisar" append-icon="search"></v-text-field>
        <v-spacer></v-spacer>
        <v-toolbar-items class="hidden-sm-and-down">
          <v-btn flat>Início</v-btn>
          <v-btn flat>Produtos</v-btn>
          <v-btn flat>Contato</v-btn>
        </v-toolbar-items>
      </v-toolbar>
    </v-content>
  </v-app>
</template>