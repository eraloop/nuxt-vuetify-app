<template>
  <v-main>
    <v-container fluid class="hero-section">
      <Navbar />
      <v-row>
        <v-col>
          <h1>This is the hero section</h1>
        </v-col>
      </v-row>
    </v-container>
  </v-main>
</template>
<script>

</script>

<style scoped>
.hero-section {
    height: 300px;
    width: 100%;
    background: url("@/static/images/image-hero-desktop.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}
</style>
