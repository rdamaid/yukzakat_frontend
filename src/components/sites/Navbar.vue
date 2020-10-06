<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <router-link to="/">
        <img
          :src="require(`@/assets/sites/img/logo.png`)"
          alt="logo"
          class="logo"
        />
      </router-link>
      <a class="navbar-brand pl-3" href="#">YUKZAKAT</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ml-auto">
          <router-link class="nav-link" to="/" exact>Beranda</router-link>
          <li class="nav-item dropdown">
            <router-link
              class="nav-link"
              to="/zakat"
              id="navbarDropdownMenuLink"
              role="button"
            >
              Zakat
              <i class="fa fa-chevron-down"></i>
            </router-link>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <router-link class="dropdown-item" to="/kalkulasi-zakat">
                Kalkulasi Zakat
              </router-link>
              <router-link class="dropdown-item" to="/pembayaran-zakat">
                Pembayaran Zakat
              </router-link>
            </div>
          </li>
          <router-link class="nav-link" to="/rekening">Rekening</router-link>
          <router-link class="nav-link" to="/login">Masuk</router-link>
          <router-link class="btn btn-primary tombol-nav" to="/register">
            Daftar
          </router-link>
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
