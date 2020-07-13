<template>
<div class="pagebody">
  <button @click="gotoLogin" class="btn1">登录</button>
<!--  <img src="../assets/1556286926629.jpeg">-->
</div>
</template>
<script>
export default {
  name: 'index',
  methods: {
    gotoLogin () {
      this.$router.push('/login')
    }
  }
}
</script>

<style scoped>
.pagebody {
  height: 100%;
  width: 100%;
  overflow: hidden;
}
img {
  height: 100%;
  width: 100%;
}
.btn1 {
  line-height: 1;
  margin-right: 30px;
  position: absolute;
  right: 70px;
  top: 0;
  white-space: nowrap;
  cursor: pointer;
  background-color: #409eff;
  border-color: #409eff;
  color: #fff;
  -webkit-appearance: none;
  text-align: center;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  outline: 0;
  margin: 0;
  -webkit-transition: 0.1s;
  transition: 0.1s;
  font-weight: 500;
  padding: 12px 20px;
  font-size: 14px;
  border-radius: 4px;
}
</style>
