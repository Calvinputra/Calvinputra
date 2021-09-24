<template>
  <section style="min-height: 2000px">
    <nav
      id="navbar"
      class="navbar sticky-top navbar-expand-lg navbar-light bg-light"
    >
      <!-- Logo -->
      <div class="container-fluid space-between">
        <div id="logo" class="navbar-brand col-sm-1">
          <a href="#"><img class="img-fluid" src="img/metro.png" alt="" /></a>
        </div>
        <!-- coloum Kosong -->
        <div id="kosong" class="col-sm-1"></div>
        <!-- search -->
        <div id="search" class="nav-item col-sm-7 align-self-start mt-4">
          <form class="d-flex">
            <input
              class="form-control"
              type="search"
              placeholder="Cari Barang Di sini"
              aria-label="Search"
            />
            <button
              class="btn btn-outline-success mx-auto"
              style="background-color: #e5e5e5"
              type="submit"
            >
              <img src="img/search.png" alt="" />
            </button>
          </form>
          <!-- kategory -->
          <div id="kategory" class="nav-item col-sm-12 align-self-end">
            <ul
              class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll"
              style="--bs-scroll-height: 100px"
            >
              <li class="nav-item col-2">
                <a
                  class="nav-link active text-danger"
                  aria-current="page"
                  href="#"
                  >kategory 1</a
                >
              </li>
              <li class="nav-item col-2">
                <a
                  class="nav-link active text-danger"
                  aria-current="page"
                  href="#"
                  >kategory 2</a
                >
              </li>
              <li class="nav-item col-2">
                <a
                  class="nav-link active text-danger"
                  aria-current="page"
                  href="#"
                  >kategory 3</a
                >
              </li>
              <li class="nav-item col-2">
                <a
                  class="nav-link active text-danger"
                  aria-current="page"
                  href="#"
                  >kategory 4</a
                >
              </li>
              <li class="nav-item col-2">
                <a
                  class="nav-link active text-danger"
                  aria-current="page"
                  href="#"
                  >kategory 5</a
                >
              </li>
              <li class="nav-item col-2">
                <a
                  class="nav-link active text-danger"
                  aria-current="page"
                  href="#"
                  >lainnya</a
                >
              </li>
            </ul>
          </div>
        </div>
        <!-- hamburger button -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarScroll"
          aria-controls="navbarScroll"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <!-- icon -->
        <div class="collapse navbar-collapse" id="navbarScroll">
          <div id="icon navbar" class="container">
            <div class="col-sm-4">
              <a class="nav-link active" aria-current="page" href="#"
                ><img src="img/profile.png" alt=""
              /></a>
            </div>
            <div class="col-sm-4">
              <a class="nav-link" href="https://facebook.com"
                ><img src="img/wishlist.png" alt=""
              /></a>
            </div>
            <div class="col-sm-4">
              <a class="nav-link" href="#"><img src="img/cart.png" alt="" /></a>
            </div>
            <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
            </ul>
          </div>
        </div>
        <!-- kolom kosong -->
        <div id="kosong" class="col-sm-1 width:50%"></div>
      </div>
    </nav>
    <!-- <nav id="subnav">
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
    </nav> -->
  </section>
</template>