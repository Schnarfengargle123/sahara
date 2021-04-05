<template>
  <div class="card">
    <div class="card__item">
      <img class="card__item__image" src="" alt="" />
      <h3 class="card__item__title">Colombian Coffee Beans</h3>
      <p class="card__item__bio">Single origin coffee beans from Colombia</p>
      <p class="card__item__price"><strong>£4.99</strong> <em>per</em> 100g</p>
      <div class="card__item__button">
        <button>Add to Cart</button>
        <button>Quantity</button>
      </div>
    </div>
    <div class="card__item">
      <img
        class="card__item__image"
        src="../assets/items/darjeeling.jpg"
        alt=""
      />
      <h3 class="card__item__title">Darjeeling Loose Leaf</h3>
      <p class="card__item__bio">Luxurious Indian loose leaf tea</p>
      <p class="card__item__price"><strong>£4.99</strong> per 100g</p>
      <div class="card__item__button">
        <button>Add to Cart</button>
        <button>Quantity</button>
      </div>
    </div>
    <div class="card__item">
      <img class="card__item__image" src="" alt="" />
      <h3 class="card__item__title">Belgian Hot Chocolate</h3>
      <p class="card__item__bio">Inuldgent Belgian hot chocolate</p>
      <p class="card__item__price"><strong>£4.99</strong> per 100g</p>
      <div class="card__item__button">
        <button>Add to Cart</button>
        <button>Quantity</button>
      </div>
    </div>
  </div>
</template>

<style scope>
.card {
  width: 100vw;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

.card__item {
  width: 20rem;
  height: 35rem;
  margin: 3rem;
  border-radius: 0.3rem;
  box-shadow: 0 0 0.2rem 0.1rem slategray;
  transition: 150ms;
  background-color: white;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
}

.card__item__image {
  width: 20rem;
  height: 20rem;
}

.card__item__button button {
    width: 5rem;
    height: 3rem;
}

.card__item:hover {
  box-shadow: 0 0 0.4rem 0.2rem slategray;
  transform: translateY(-0.7rem);
  cursor: pointer;
}
</style>
