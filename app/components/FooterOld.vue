<template>
  <footer class="root" id="footer">
    <div class="logo">
      <img
        data-bs-theme="light"
        alt="NOMAD GURU"
        src="/img/logo/black@2d.png"
      /><img
        data-bs-theme="dark"
        alt="NOMAD GURU"
        style="display: none"
        src="/img/logo/white@2d.png"
      />
    </div>

    <cite>
      <div class="copy">
        <p>&copy; NOMAD GURU.</p>
        <p>2008 - 2025.</p>
        <p>Всі права захищені.</p>
      </div>
      <form class="settings">
        <div class="form-check form-switch">
          <input
            class="form-check-input"
            type="checkbox"
            role="switch"
            id="settingsDarkMode"
            nw-hotkey="cmd+shift+d"
            nw="DarkMode"
          />
          <label class="form-check-label" for="settingsDarkMode"
            >Нічний режим</label
          >
        </div>
      </form>
    </cite>
  </footer>
</template>
