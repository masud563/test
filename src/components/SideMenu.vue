<template>
  <div class="menu">
    <div class="menu__upper">
      <MenuButton class="menu__button"> Inbox </MenuButton>
      <MenuButton class="menu__button"> Archive </MenuButton>
    </div>
    <div class="menu__lower">
      <MenuButton class="menu__button"> Logout </MenuButton>
    </div>
  </div>
</template>

<script>
import MenuButton from "./common/MenuButton.vue";
</script>

<style scoped>
.menu {
  background-color: #413f3f;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content:space-between ;
  min-height: calc(100vh - 40px);
  width: 25vw;
  padding: 20px;
}
.menu__upper {
  display: flex;
  flex-direction: column;
}
.menu__lower {
  display: flex;
  flex-direction: column;
}
.menu__button{
  background-color: white;
  color: black;
  border-radius: 4px;
  padding: 10px;
  margin: 0 0 10px 0;
}

</style>
