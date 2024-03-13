<template lang="">
  <div>
<!--     <h1>根組件</h1>
    <nuxt-link to="/">首頁</nuxt-link>
    <nuxt-link to="/users">用戶默認頁</nuxt-link>
    <nuxt-link to="/users/create-or-edit">用戶添加或修改</nuxt-link>
    <nuxt-link to="/roles/admin">角色-管理員</nuxt-link>
    <nuxt-link to="/roles/normal">角色-普通用戶</nuxt-link>
    <nuxt-link to="/about">關於</nuxt-link>
    <a href="/about">關於-原始超連結</a>
    <nuxt-page /> -->
    <AppHeader />
    <AppAside />
      <NuxtPage />
    <AppFooter />

  </div>
</template>

<style lang="scss">
  a{
    margin-right: 10px;
  }
</style>
