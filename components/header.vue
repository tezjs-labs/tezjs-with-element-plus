<template>
<div class="container">
  <el-menu
    :default-active="activeIndex"
    class="el-menu-demo"
    mode="horizontal"
    :ellipsis="false"
    @select="handleSelect"
  >
    <el-menu-item index="0"
      >
      <el-image
        style="width: 45px; height: 55px"
        src="https://tailwindui.com/img/logos/workflow-mark-indigo-600.svg"
      />
    </el-menu-item>
    <div class="flex-grow" />
    <el-menu-item index="1">
    <tez-link to="/" class="nav-link"> Home 
    </tez-link>
    </el-menu-item>
      <el-menu-item index="2">
      <el-link href="https://github.com/tezjs/tezjs">Tezjs</el-link>
      </el-menu-item>
  </el-menu>
</div>
   
</template>

<style>
.flex-grow {
  flex-grow: 1;
}
.nav-link{
  text-decoration:none
}
</style>
