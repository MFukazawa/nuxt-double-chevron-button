<template>
  <div class="to-top-container">
    <a class="to-top" href="#">
      <font-awesome-icon
        class="top-chevron"
        :icon="['fas', 'chevron-up']"
      ></font-awesome-icon>
      <font-awesome-icon
       class="bottom-chevron"
      :icon="['fas', 'chevron-up']"
      ></font-awesome-icon>
    </a>
  </div>
</template>

<style>
.to-top-container {
  position: absolute;
  z-index: 999;
  right: 40px;
  bottom: 41px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 52px;
  height: 52px;
  border: 3px solid black;
  border-radius: 90px;
  cursor: pointer;
  text-decoration: none;
}

.top-chevron {
  position: relative;
  top: 4px;
  color: #000;
}

.bottom-chevron {
  position: relative;
  top: -4px;
  color: #000;
}


</style>
