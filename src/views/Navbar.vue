<template>
  <!-- Navbar -->
  <nav class="main-header navbar navbar-expand navbar-dark farobot-dark-mode">
    <!-- Left navbar links -->
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" data-widget="pushmenu" href="#" role="button">
          <i class="fas fa-bars"></i>
        </a>
      </li>
      <!-- <li class="nav-item d-none d-sm-inline-block">
        <a href="index3.html" class="nav-link">Home</a>
      </li>
      <li class="nav-item d-none d-sm-inline-block">
        <a href="#" class="nav-link">Contact</a>
      </li> -->
    </ul>

    <!-- Right navbar links -->
    <ul class="navbar-nav ml-auto">
      <!-- Navbar Search -->
      <!-- <li class="nav-item">
        <a class="nav-link" data-widget="navbar-search" href="#" role="button">
          <i class="fas fa-search"></i>
        </a>
        <div class="navbar-search-block">
          <form class="form-inline">
            <div class="input-group input-group-sm">
              <input class="form-control form-control-navbar" type="search" placeholder="Search" aria-label="Search">
              <div class="input-group-append">
                <button class="btn btn-navbar" type="submit">
                  <i class="fas fa-search"></i>
                </button>
                <button class="btn btn-navbar" type="button" data-widget="navbar-search">
                  <i class="fas fa-times"></i>
                </button>
              </div>
            </div>
          </form>
        </div>
      </li> -->

      <li
        class="nav-item align-self-center font-weight-bold"
        id="user-login-status"
        style="font-size: 100%"
      >
        Hi, farobot_admin!
      </li>
      <li class="nav-item align-self-center font-weight-bold" style="font-size: 100%"> |</li>
      <li class="nav-item align-self-center">
        <button
          type="button"
          data-i18n="nav.sign_out"
          class="btn btn-link"
          id="user-logout-btn"
          onclick="restLogout()"
          style="font-size: 100%"
        >
          Sign out
        </button>
      </li>
      <li class="nav-item">
        <a class="nav-link" data-slide="true" href="#" role="button">
          <i class="country_flags" country="US"></i>
        </a>
      </li>
      <!-- <li class="nav-item">
        <a class="nav-link" data-widget="fullscreen" href="#" role="button">
          <i class="fas fa-expand-arrows-alt"></i>
        </a>
      </li>
      <li class="nav-item">
        <a class="nav-link" data-widget="control-sidebar" data-slide="true" href="#" role="button">
          <i class="fas fa-th-large"></i>
        </a>
      </li> -->
    </ul>
  </nav>
  <!-- /.navbar -->
</template>

<script>
export default {}
</script>

<style></style>
