<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <a class="navbar-brand" href="#">Vtasker</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <router-link class="nav-link active" to="/">Home</router-link>
            <router-link class="nav-link" to="/about">About</router-link>
          </div>
          <div class="navbar-nav ms-auto">
            <router-link class="nav-link" to="/add">Add User</router-link>
          </div>
        </div>
      </div>
    </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
</style>