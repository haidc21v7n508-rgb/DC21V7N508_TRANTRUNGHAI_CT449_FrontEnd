<template>
  <nav class="navbar navbar-expand navbar-dark bg-dark">
    <router-link to="/" class="navbar-brand">
      Ứng dụng Quản lý danh bạ
    </router-link>
    <div class="navbar-nav mr-auto">
      <li class="nav-item">
        <router-link :to="{ name: 'contactbook' }" class="nav-link">
          <i class="fas fa-address-book"></i> Danh bạ
        </router-link>
      </li>
    </div>
  </nav>
</template>
