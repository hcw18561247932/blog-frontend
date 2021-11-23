<template>
  <div class="layout">
    <!-- Navigation-->
    <nav class="navbar" style="position: absolute; z-index: 100;width: 100%;">
      <div class="container px-4 px-lg-5">
        <g-link class="navbar-brand" to="/" style="color:#fff;font-weight: 800;font-size:30px">Start Bootstrap</g-link>

        <div>
          <ul class="navbar-nav ms-auto py-4 py-lg-0" style="display: flex;flex-direction: row;color: #fff;">
            <li class="nav-item">
              <g-link  style="color:#fff;font-weight: 800;font-size:30px" class="nav-link px-lg-3 py-3 py-lg-4" to="/"
                >Home</g-link
              >
            </li>
            <li class="nav-item">
              <g-link  style="color:#fff;font-weight: 800;font-size:30px" class="nav-link px-lg-3 py-3 py-lg-4" 
                >About</g-link
              >
            </li>
            <li class="nav-item">
              <g-link  style="color:#fff;font-weight: 800;font-size:30px" class="nav-link px-lg-3 py-3 py-lg-4"
                >Sample Post</g-link
              >
            </li>
            <li class="nav-item">
              <g-link  style="color:#fff;font-weight: 800;font-size:30px" class="nav-link px-lg-3 py-3 py-lg-4" 
                >Contact</g-link
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- 默认插槽 -->
    <slot />

    <!-- Footer-->
    <footer class="border-top">
      <div class="container px-4 px-lg-5">
        <div class="row gx-4 gx-lg-5 justify-content-center">
          <div class="col-md-10 col-lg-8 col-xl-7">
            <ul class="list-inline text-center">
              <li class="list-inline-item">
                <a href="#!">
                  <span class="fa-stack fa-lg">
                    <i class="fas fa-circle fa-stack-2x"></i>
                    <i class="fab fa-twitter fa-stack-1x fa-inverse"></i>
                  </span>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#!">
                  <span class="fa-stack fa-lg">
                    <i class="fas fa-circle fa-stack-2x"></i>
                    <i class="fab fa-facebook-f fa-stack-1x fa-inverse"></i>
                  </span>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#!">
                  <span class="fa-stack fa-lg">
                    <i class="fas fa-circle fa-stack-2x"></i>
                    <i class="fab fa-github fa-stack-1x fa-inverse"></i>
                  </span>
                </a>
              </li>
            </ul>
            <div class="small text-center text-muted fst-italic">
              Copyright &copy; Your Website 2021
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>



<style>
</style>
