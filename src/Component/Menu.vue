<template>
  <header>
    <div class="logo-container">
      <h1>Logo</h1>
    </div>

    <nav :class="{ open: mobileMenuOpen }">
      <ul>
        <li><a href="#" @click="mobileMenuOpen = false">Home</a></li>
        <li><a href="#" @click="mobileMenuOpen = false">About</a></li>
        <li><a href="#" @click="mobileMenuOpen = false">Get Involved</a></li>
        <li><a href="#" @click="mobileMenuOpen = false">Contact</a></li>
      </ul>
      <button class="btn">Donate</button>
    </nav>
    <button class="hamburger" @click="toggleMenu" :class="{ active: mobileMenuOpen }">
      <span></span>
      <span></span>
      <span></span>
    </button>
  </header>
</template>

<script>
export default {
  data() {
    return {
      mobileMenuOpen: false,
    };
  },
  methods: {
    toggleMenu() {
      this.mobileMenuOpen = !this.mobileMenuOpen;
    },
  },
};
</script>

<style scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  margin-right: 100px;
  background-color: var(--color-white);
  z-index: 1000;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
}

.logo-container {
  flex-shrink: 0;
}

.logo-container h1 {
  margin: 0;
  font-size: 24px;
}

nav {
  display: flex;
  /* justify-content: center; */
  align-items: center;
  gap: 30px;
}

nav ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
  gap: 30px;
}

nav a {
  color: var(--color-accent);
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

nav a:hover {
  color: var(--secondary-color);
}
.btn {
  padding: 10px 20px;
  background-color: var(--secondary-color);
  color: var(--color-white);
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-weight: 600;
  transition: background-color 0.3s ease;
}

.btn:hover {
  background-color: #1f6b52;
}

.hamburger {
  display: none;
  flex-direction: column;
  cursor: pointer;
  background: none;
  border: none;
  gap: 6px;
  z-index: 1001;
}

.hamburger span {
  width: 25px;
  height: 3px;
  background-color: var(--color-accent);
  border-radius: 3px;
  transition: all 0.3s ease;
}

.hamburger.active span:nth-child(1) {
  transform: rotate(45deg) translate(10px, 10px);
}

.hamburger.active span:nth-child(2) {
  opacity: 0;
}

.hamburger.active span:nth-child(3) {
  transform: rotate(-45deg) translate(8px, -8px);
}

/* Add padding to body to account for fixed header */
/* :deep(body) {
  padding-top: 64px;
} */

/* Mobile (< 768px) */
@media (max-width: 767px) {
  header {
    padding: 15px;
  }

  .logo-container h1 {
    font-size: 20px;
  }

  .hamburger {
    display: flex;
  }

  nav {
    position: absolute;
    top: 100%;
    left: 0;
    right: 0;
    background-color: var(--primary-color);
    flex-direction: column;
    gap: 0;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.3s ease;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
  }

  nav.open {
    max-height: 500px;
  }

  nav ul {
    flex-direction: column;
    gap: 0;
    width: 100%;
  }

  nav li {
    border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  }

  nav li:last-child {
    border-bottom: none;
  }

  nav a {
    display: block;
    padding: 15px 20px;
  }

  .btn {
    width: 100%;
    margin: 15px;
    margin-top: 10px;
  }
}

/* iPad (768px - 1024px) */
@media (min-width: 768px) and (max-width: 1024px) {
  header {
    padding: 15px 20px;
  }

  .logo-container h1 {
    font-size: 22px;
  }

  nav {
    gap: 20px;
  }

  nav ul {
    gap: 20px;
  }

  nav a {
    font-size: 15px;
  }

  .btn {
    padding: 8px 16px;
    font-size: 14px;
  }
}

/* Large screens (> 1024px) */
@media (min-width: 1025px) {
  header {
    padding: 20px 40px;
  }

  .logo-container h1 {
    font-size: 28px;
  }
}
</style>
