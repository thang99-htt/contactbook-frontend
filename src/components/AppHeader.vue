<template>
    <nav class="navbar navbar-expand navbar-dark bg-dark justify-content-between">
        <div class="navbar-nav">
            <a href="/" class="navbar-brand">Ứng dụng Quản lý danh bạ</a>
            <li class="nav-item">
                <router-link :to="{ name: 'contactbook' }" class="nav-link">
                    Danh bạ
                    <i class="fas fa-address-book"></i>
                </router-link>
            </li>
        </div>
        <div class="navbar-nav">
            <li class="nav-item">
                <router-link :to="{ name: 'register' }" class="nav-link">
                    Đăng ký
                </router-link>
            </li>
            <li class="nav-item">
                <router-link :to="{ name: 'login' }" class="nav-link">
                    Đăng nhập
                </router-link>
            </li>
        </div>
    </nav>
</template>