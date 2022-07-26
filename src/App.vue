<template>
  <router-view />
</template>

<style lang="less">
body{
  margin: 0;
}

.flex-flaot{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.flex{
  display: flex;
  align-items: center;
}
.page_content{
  box-sizing: border-box;
  display: block;
  width: 100%;
  padding:20px;
  background: #fff;
  margin-top: 20px;
}
.cell {
  text-align: center !important;
}
</style>
