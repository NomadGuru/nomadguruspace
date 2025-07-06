<template>
  <footer class="footer sm:footer-horizontal text-base-content p-10">
    <aside>
      <NuxtImg
        alt="NOMAD GURU"
        style="display: none"
        src="/img/logo/black@2d.png"
      />
      <NuxtImg alt="NOMAD GURU" src="/img/logo/white@2d.png" />
    </aside>
    <nav>
      <h6 class="footer-title">Послуги</h6>
      <a class="link link-hover">Звукозапис</a>
      <a class="link link-hover">Тренінг голосу</a>
    </nav>
    <nav>
      <h6 class="footer-title">Інформація</h6>
      <a class="link link-hover">Про Нас</a>
      <a class="link link-hover">Зв'язатися З Нами</a>
      <a class="link link-hover">Співпраця</a>
    </nav>
  </footer>

  <footer
    class="footer sm:footer-horizontal text-neutral-content items-center p-4"
  >
    <aside class="grid-flow-col items-center">
      <p>Copyright © {{ new Date().getFullYear() }} - All right reserved</p>
    </aside>
    <nav class="grid-flow-col gap-4 md:place-self-center md:justify-self-end">
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://www.youtube.com/c/NoMaDGURU"
      >
        <Icon name="tabler:brand-youtube-filled" size="24" />
      </a>
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://t.me/nomadguru"
      >
        <Icon name="tabler:brand-telegram" size="24" />
      </a>
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://www.facebook.com/nmdguru"
      >
        <Icon name="tabler:brand-facebook-filled" size="24" />
      </a>
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://www.instagram.com/nmdguru/"
        class="flex items-center justify-center"
      >
        <Icon name="tabler:brand-instagram" size="24" />
        ART
      </a>
      <a
        rel="noopener noreferrer"
        target="_blank"
        href="https://www.instagram.com/nomadguruspace/"
        class="flex items-center justify-center"
      >
        <Icon name="tabler:brand-instagram" size="24" />
        SPACE
      </a>
    </nav>
  </footer>
</template>
