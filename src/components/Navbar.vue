<template>
  <nav class="navbar navbar-expand-xl navbar-light bg-white">
  <a class="navbar-brand" href="/">
    <img :src="require('../assets/brand.png')">
  </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span style="font-size: 1.5em; color: black;">
      <i class="fas fa-bars"></i>
      <i class="fas fa-chevron-up"></i>
    </span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          About Us
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="/contact">Contact</a>
          <a class="dropdown-item" href="/history">History</a>
          <a class="dropdown-item" href="/staff">Administrative Staff</a>
          <a class="dropdown-item" href="/board">Board of Directors</a>
          <a class="dropdown-item" href="/careers">Careers</a>
          <a class="dropdown-item" href="/directions">Directions</a>
        </div>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Early Childhood Program
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="/ecp">About</a>
          <a class="dropdown-item" href="/ecp/rooms">Classrooms</a>
          <a class="dropdown-item" href="/ecp/enroll">Enrollment</a>
          <a class="dropdown-item" href="/ecp/tuition">Tuition</a>
          <a class="dropdown-item" href="/ecp/forms">Forms</a>
          <a class="dropdown-item" href="/ecp/policies">Policies</a>
        </div>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          After School Program
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="/asp">About</a>
          <a class="dropdown-item" href="/asp/sites">Sites</a>
          <a class="dropdown-item" href="/asp/enroll">Enrollment</a>
          <a class="dropdown-item" href="/asp/tuition">Tuition</a>
          <a class="dropdown-item" href="/asp/forms">Forms</a>
          <a class="dropdown-item" href="/asp/policies">Policies</a>
          <a class="dropdown-item" href="/asp/fullday">Full Day Programs</a>
        </div>
      </li>
      <a class="btn btn-success btn-lg active" role="button" href="/pay" aria-pressed="true">Pay Bill</a>
      <a class="btn btn-primary btn-lg active" role="button" href="/donate" aria-pressed="true">Donate</a>
    </ul>
  </div>
</nav>
</template>
