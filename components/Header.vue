<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container container-fluid">
    <a class=" brand navbar-brand" href="#">
        <img src="assets/img/logosmk.png" alt="logo" width="48" height="55" > SMKN 4 TSM
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Profil
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Visi dan Misi</a></li>
            <!-- <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li> -->
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Jurusan
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Pengembangan Perangkat Lunak Dan Game</a></li>
            <li><a class="dropdown-item" href="#">Teknik Komputer dan Jaringan</a></li>
            <li><a class="dropdown-item" href="#">Teknik Bisnis dan Sepeda Motor</a></li>
            <li><a class="dropdown-item" href="#">Teknik otomasi Industri</a></li>
            <li><a class="dropdown-item" href="#">Desain Komunikasi Visual</a></li>
          </ul>
        </li>
        <!-- <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Disabled</a>
        </li> -->
      </ul>
    </div>
  </div>
</nav>
</template>

<style scoped>
.navbar {
    padding-left: 35%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position:fixed;
    top: 0; 
    width: 100%; 
    z-index: 1;
    height: auto;
}


</style>
