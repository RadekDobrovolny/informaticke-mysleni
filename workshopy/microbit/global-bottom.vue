<template>
  <a
    href="../../../index.html"
    class="home-link"
    title="Zpět na rozcestník"
    aria-label="Zpět na rozcestník"
  >
    <svg viewBox="0 0 24 24" aria-hidden="true">
      <path
        d="M12 3.2L3.5 10v10.3c0 .5.4.9.9.9h5.2c.5 0 .9-.4.9-.9v-4.9c0-.5.4-.9.9-.9h1.3c.5 0 .9.4.9.9v4.9c0 .5.4.9.9.9h5.2c.5 0 .9-.4.9-.9V10L12 3.2z"
      />
    </svg>
  </a>
</template>

<style scoped>
.home-link {
  position: fixed;
  right: 1rem;
  bottom: 1rem;
  z-index: 40;
  width: 2.5rem;
  height: 2.5rem;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  border-radius: 9999px;
  background: rgba(255, 255, 255, 0.92);
  color: #9a3412;
  border: 1px solid rgba(194, 65, 12, 0.25);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.14);
  transition: transform 120ms ease, background-color 120ms ease, color 120ms ease;
}

.home-link:hover {
  background: #ffedd5;
  color: #7c2d12;
  transform: translateY(-1px);
}

.home-link svg {
  width: 1.1rem;
  height: 1.1rem;
  fill: currentColor;
}
</style>
