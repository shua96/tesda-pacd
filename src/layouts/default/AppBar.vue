<!-- <template>
  <v-navigation-drawer v-model="drawer" :rail="rail" permanent @click="rail = false" app fixed clipped color="#4D68AF"
    light>
    <v-app-bar>
      <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
    </v-app-bar>
    <v-list-item prepend-avatar="src/assets/logo.png" title="TESDA-PACD" style="color: white;" @click.stop="rail = !rail"
      nav>
      <template v-slot:append>
        <v-btn variant="text" icon="mdi-chevron-left" @click.stop="rail = !rail"></v-btn>
      </template>
    </v-list-item>

    <v-divider></v-divider>

    <v-list density="compact" nav style="color: white;">
      <v-list-item prepend-icon="mdi-view-dashboard" title="DASHBOARD" to="/dashboard"
        style="color: white;"></v-list-item>
      <v-list-item prepend-icon="mdi-frequently-asked-questions" title="FAQ LIST" to="/faqlist"
        style="color: white;"></v-list-item>
      <v-list-item prepend-icon="mdi-database" title="CLIENT DATA" to="/database" style="color: white;"></v-list-item>
      <v-list-item prepend-icon="mdi-poll" title="SUMMARY REPORT" to="/report" style="color: white;"></v-list-item>
    </v-list>
  </v-navigation-drawer>

  <v-app-bar>

    <v-app-bar-title>{{ $route.meta.title || "Default title" }}</v-app-bar-title>
  </v-app-bar>

  <v-main
    style="--v-layout-left:56px; --v-layout-right:0px; --v-layout-top:0px; --v-layout-bottom:0px; background-color: #F7F7FB;"></v-main>
</template>
<script setup>
  //
</script>
<script>
export default {
  data() {
    return {
      drawer: true,
      items: [
        { title: 'Home', icon: 'mdi-view-dashboard' },
        { title: 'FAQ LIST', icon: 'mdi-frequently-asked-questions' },
        { title: 'CLIENT DATA', icon: 'mdi-database' },
        { title: 'SUMMARY REPORT', icon: 'mdi-poll' },
      ],
      rail: true,
    }
  },
}
</script>


<style>
.v-list-item.v-list-item--link.v-list-item--nav.v-theme--light {
  padding-top: 6px;
  padding-bottom: 10px;
}

/* .v-avatar.v-avatar--size-default {
  --v-avatar-height: 70px;
} */
</style> -->


<template>
  <v-navigation-drawer v-model="drawer" :rail="rail" permanent @click="rail = false" app fixed clipped color="#4D68AF">
    <v-list-item prepend-avatar="https://randomuser.me/api/portraits/men/85.jpg" title="John Leider" nav>
      <template v-slot:append>
        <v-btn variant="text" icon="mdi-chevron-left" @click.stop="rail = !rail"></v-btn>
      </template>
    </v-list-item>

    <v-divider></v-divider>

    <v-list density="compact" nav>
      <v-list-item prepend-icon="mdi-home-city" title="Home" value="home"></v-list-item>
      <v-list-item prepend-icon="mdi-account" title="My Account" value="account"></v-list-item>
      <v-list-item prepend-icon="mdi-account-group-outline" title="Users" value="users"></v-list-item>
    </v-list>
  </v-navigation-drawer>

  <v-app-bar title="Application bar"></v-app-bar>

  <v-main style="min-height: 100vh;"></v-main>
</template>

<script>
export default {
  data() {
    return {
      drawer: true,
      items: [
        { title: 'Home', icon: 'mdi-home-city' },
        { title: 'My Account', icon: 'mdi-account' },
        { title: 'Users', icon: 'mdi-account-group-outline' },
      ],
      rail: true,
    }
  },
}
</script>
