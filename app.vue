<template>
  <div>
    <h2>Font Awesome Icons</h2>
    <hr />

    <div>
      <!-- Array Syntax -->
      <font-awesome-icon
        :icon="['fas', 'dog']"
        size="3x"
        shake
      />

      <!-- String Syntax -->
      <font-awesome-icon
        icon="fa-solid fa-cat"
        size="2x"
        bounce
      />
    </div>
  </div>
</template>
