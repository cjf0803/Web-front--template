<template lang="html">
  <div class="index">
    <ul>
      <li>
         <router-link to="/home">
           <img src="../assets/logo1.png" alt="">
         </router-link>
      </li>
      <li>
        <router-link to="/artists">
          歌手
        </router-link>
      </li>
      <li>
        <router-link to="/listcate">
          MV榜
        </router-link>
      </li>
      <li>
        <router-link to="/ucenter">
          我的
        </router-link>
      </li>
      <li>
        <router-link to="/search">
          搜索
        </router-link>
      </li>
    </ul>
    <router-view />
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>

.index img{
  width: 26px;
  height: 26px;
}

.index ul{
  display: flex;
  height: 50px;
  line-height: 50px;
  background: #f9f9f9;
}

.index ul li {
  flex: 1;
  text-align: center;
}

.index ul li a{
  font-size: 16px;
  color: #999;
}
.router-link-active{color:rgb(240, 51, 51) !important;}
</style>
