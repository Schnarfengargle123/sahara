<template>
  <div class="navigation-bar">
    <h2 class="navigation-bar__brand"><a href="../App.vue">Sahara</a></h2>
    <ul class="navigation-bar__navigation">
      <div>
        <li class="navigation-bar__navigation__link"><a href="">Account</a></li>
        <li class="navigation-bar__navigation__link">
          <a href="">Trending</a>
        </li>
        <li class="navigation-bar__navigation__link"><a href="">Shop</a></li>
        <li class="navigation-bar__navigation__link"><a href="">Plus+</a></li>
      </div>
      <div>
        <li class="navigation-bar__navigation__link">
          <a href="">Shipping</a>
        </li>
        <li class="navigation-bar__navigation__link"><a href="">Returns</a></li>
        <li class="navigation-bar__navigation__link"><a href="">Sign In</a></li>
        <li class="navigation-bar__navigation__link">
          <a href="">Sign Out</a>
        </li>
      </div>
    </ul>
  </div>
</template>

<style scoped>
.navigation-bar {
  width: 100vw;
  height: 5rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  background-color: rgb(141, 168, 196);
  box-shadow: 0 0 2rem 0.3rem slategray;
  border-radius: 0.2rem;
}

.navigation-bar__brand a {
  text-decoration: none;
  color: snow;
}

.navigation-bar__brand,
.navigation-bar__navigation {
  margin: 0 5rem;
}

.navigation-bar__navigation {
  width: 200rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.navigation-bar__navigation div {
  width: 25rem;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}

.navigation-bar__navigation__link {
  list-style: none;
}

.navigation-bar__navigation__link a {
  text-decoration: none;
  color: cornsilk;
  font-size: larger;
  transition: 75ms;
  margin: 1rem 0rem;
}


.navigation-bar__navigation__link a:hover {
  color: snow;
  box-shadow: inset 0 0 0 1px seashell;
  padding: 0.3rem;
}
</style>
