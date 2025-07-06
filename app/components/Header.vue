<template>
  <header>
    <nav class="navbar shadow-sm px-4">
      <div class="navbar-start">
        <NuxtLink to="/" class="btn btn-link">
          <NuxtImg
            data-bs-theme="light"
            alt="NOMAD GURU"
            style="display: none"
            src="/img/logo/black-wide.png"
          />
          <NuxtImg
            data-bs-theme="dark"
            alt="NOMAD GURU"
            src="/img/logo/white-wide.png"
          />
        </NuxtLink>
      </div>

      <div class="navbar-center hidden lg:flex">
        <ul class="menu menu-horizontal px-1 font-medium text-xl opacity-65">
          <li><NuxtLink>ART</NuxtLink></li>
          <li><NuxtLink>HOUSE</NuxtLink></li>
          <li><NuxtLink>SCHOOL</NuxtLink></li>
          <li><NuxtLink>Про Нас</NuxtLink></li>
        </ul>
      </div>
      <div class="navbar-end text-xl font-medium">
        <a class="btn">Українська</a>
      </div>
    </nav>
  </header>
</template>
