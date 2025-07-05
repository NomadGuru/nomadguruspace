<template>
  <header class="root sticky-top d-print-none" id="sticky-from-here">
    <nav class="navbar navbar-expand-lg">
      <div class="container">
        <a class="navbar-brand" href="index.html">
          <img
            data-bs-theme="light"
            alt="NOMAD GURU"
            src="~/assets/img/logo/black-wide.png"
          /><img
            data-bs-theme="dark"
            alt="NOMAD GURU"
            style="display: none"
            src="~/assets/img/logo/white-wide.png"
          />
        </a>
        <button
          class="hamburger hamburger--slider d-lg-none"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#headerNavbar"
          aria-controls="headerNavbar"
          aria-expanded="false"
          aria-label=""
        >
          <span class="hamburger-box">
            <span class="hamburger-inner"></span>
          </span>
          <!-- <span class="navbar-toggler-icon"></span> -->
        </button>
        <div class="collapse navbar-collapse" id="headerNavbar">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="art.html">
                <span>ART</span>
              </a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="house.html">
                <span>HOUSE</span>
              </a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="school.html">
                <span>SCHOOl</span>
              </a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="about.html">
                <span>ПРО НАС</span>
              </a>
            </li>
          </ul>
          <div class="search">
            <button
              class="btn btn-warning"
              type="button"
              data-bs-toggle="modal"
              data-bs-target="#searchModal"
              nw-hotkey="cmd+k|s|и"
            >
              <span class="icon-search fs-3"></span>
              <span class="d-xl-none">Поїхали</span>
            </button>
          </div>

          <ul class="navbar-nav lang align-items-center">
            <li class="dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
                title="Change language"
                nw-lang="uk"
                ><img
                  src="~/assets/img/lang/uk.svg"
                  alt="Українська"
                  style="max-height: 3rem"
                /><span><span>Українська</span></span></a
              >
              <ul class="dropdown-menu dropdown-menu-end">
                <li>
                  <a
                    class="dropdown-item active"
                    href="ru/index.html"
                    nw-lang="uk"
                    ><img
                      src="~/assets/img/lang/uk.svg"
                      alt="Українська"
                      style="max-height: 3rem"
                    /><span><span>Українська</span></span></a
                  >
                </li>

                <li>
                  <a class="dropdown-item" href="/en/index.html" nw-lang="en"
                    ><img
                      src="~/assets/img/lang/en.svg"
                      alt="English"
                      style="max-height: 3rem"
                    /><span><span>English</span></span></a
                  >
                </li>

                <li>
                  <a class="dropdown-item" href="/ru/index.html" nw-lang="ru"
                    ><img
                      src="~/assets/img/lang/ru.svg"
                      alt="Русский"
                      style="max-height: 3rem"
                    /><span><span>Русский</span></span></a
                  >
                </li>
              </ul>
            </li>
          </ul>

          <div class="logo">
            <img
              data-bs-theme="light"
              alt="NOMAD GURU"
              src="~/assets/img/logo/black@2d.png"
            /><img
              data-bs-theme="dark"
              alt="NOMAD GURU"
              style="display: none"
              src="~/assets/img/logo/white@2d.png"
            />
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>
