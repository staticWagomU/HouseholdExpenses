<template>
  <div>
    <nuxt />
    <nav class="bottomMenu">
      <div class="l-flex">
      <nuxt-link to="registry" class="bottomMenu__item">登録</nuxt-link>
      <nuxt-link to="input" class="bottomMenu__item">入力</nuxt-link>
      <nuxt-link to="view" class="bottomMenu__item">データ表示</nuxt-link>
      </div>
    </nav>
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.bottomMenu {
  width: 100vw;
  height: 4rem;
  position: fixed;
  bottom: 0;
}

.l-flex {
  width: 100%;
  height: 100%;
  display: flex;
}

.bottomMenu__item {
  width: 100%;
  height: 100%;
  line-height: 4rem;
  text-align: center;
  font-size: 1.5rem;
  background: #00f;
  color: white;
}
</style>
