<template>
  <nav class="navbar1 navbar navbar-expand navbar-dark bg-dark">
      <a href="/" class="navbar-brand">Quản Lý Danh Bạ</a>
      <div class="mr-auto navbar-nav">
          <li class="nav-item">
              <router-link :to="{ name: 'contactbook' }" class="nav-link">
                  Danh bạ
                  <i class="fas fa-address-book"></i>
              </router-link>
          </li>
      </div>
  </nav>
</template>
