<template>
     <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="img/logo_small.png" alt="Hefa Store">
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav text-uppercase mx-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Category</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Designer</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
        <a href="" class="nav-link text-white"><i class="fas fa-shopping-cart"></i> My Cart (<span>12</span>)</a>
      </div>
    </div>
  </nav>
  <!-- Akhir Navbar -->
</template>

<script>
export default {
    name: 'Header'
}
</script>