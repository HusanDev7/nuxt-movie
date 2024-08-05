<script setup lang="ts">
useHead({title: "The Best Streaming Experience"})
const menu = [{name: "Home"}, {name: "Movies & Shows"}, {name: "Support"}, {name: "Subscriptions"}]
</script>

<template>

<div class="container">
    <nav class="nav">
        <NuxtLink to="/"><img class="nav-logo" src="@/assets/img/logo.svg" alt="logo"></NuxtLink>
        <ul class="nav__list">
            <li v-for="item in menu" :key="item.name" class="nav__list-item"><NuxtLink to="/#">{{item.name}}</NuxtLink></li>
        </ul>
        <div class="nav-icons">
        <button class="nav-icons-icon"><img class="nav-icons-icon-img" src="@/assets/img/search-btn.svg" alt="search"></button>
        <button class="nav-icons-icon"><img class="nav-icons-icon-img" src="@/assets/img/ball.svg" alt="ball"></button>
        </div>
    </nav>
</div>
</template>