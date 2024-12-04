<template>
  <nav>
    <RouterLink :to="{name: 'Home' }">Home</RouterLink>
    <RouterLink :to="{name: 'MealsByName' }">Meals by Name</RouterLink>
    <RouterLink :to="{name: 'MealsByLetter' }">Meals by Letter</RouterLink>
    <RouterLink :to="{name: 'Ingredients' }">Meals by Ingredients</RouterLink>
  </nav>
</template>

<style lang="postcss" scoped>
nav {
  @apply flex justify-center space-x-4;

  & .router-link-active {
    @apply underline underline-offset-4;
  }
}
</style>
