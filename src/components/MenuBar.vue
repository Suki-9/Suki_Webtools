<script setup>

</script>

<template>
  <div class="MenuBox">
    <a class="MenuButton">
      <img src="../components/icons/house-solid.svg" class="MenuIcon"/>
    </a>
    <a class="MenuButton">
      
    </a>
    <a class="MenuButton">

    </a>
    <a class="MenuButton">

    </a>
    <a class="MenuButton">

    </a>
  </div>
</template>

<style>
.MenuBox {
  width: 100vw;
  height: 10%;
  min-height: 15vw;

  position: absolute;
  bottom: 0px;

  border-top: solid 2px rgb(92, 92, 92);

  display: flex;
  align-items: center;
  justify-content: space-evenly;

  background-color: rgba(22, 22, 22, 0.877);
}
.MenuButton {
  width: 15vw;
  height: 15vw;

  border-radius: 50%;

  box-shadow: -4px -3px 1px rgb(201 28 109 / 24%);

  display: flex;
  align-items: center;
  justify-content: center;

  background-color: rgba(255, 255, 255, 0);
}
.MenuIcon {
  width: 40%;
}
</style>