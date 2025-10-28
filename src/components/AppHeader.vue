<template>
  <nav class="navbar navbar-expand navbar-dark bg-dark">
    <a href="/" class="navbar-brand ms-3">Ứng dụng Quản lý danh bạ</a>
    <div class="navbar-nav ms-auto me-3">
      <li class="nav-item">
        <router-link :to="{ name: 'contactbook' }" class="nav-link">
          Danh bạ <i class="fas fa-address-book"></i>
        </router-link>
      </li>
    </div>
  </nav>
</template>

<style>
.navbar {
  width: 100%;
}
</style>
