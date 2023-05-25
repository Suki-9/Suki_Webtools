<script setup>

</script>

<template>
    <div class="HeadBar">
        <img class="AppIcon">
        <p class="HeadTitle">Suki WebTools</p>
        <a class="ThemeSwitch">
            <i></i>
        </a>
    </div>
</template>

<style scoped>
.HeadBar {
    width: 100vw;

    display: flex;
    align-items: center;

    border-bottom: solid 0.5px;

    box-shadow: 0 4px 1px rgb(201 28 109 / 24%);
}
.HeadTitle {
  margin: 0;

  min-height: 7vw;

  font-size: 400%;
}
.ThemeSwitch {
    border-radius: 50%;

    border: solid 3px;
}
</style>