# shivudha.github.io

<section id="collection">
  <h2>Our Collection</h2>
  <div class="products">
    <div class="product">
      <h3>Suit</h3>
      <img src="images/suit.jpg" alt="Suit" width="180">
    </div>
    <div class="product">
      <h3>Kurti</h3>
      <img src="images/kurti.jpg" alt="Kurti" width="180">
    </div>
    <div class="product">
      <h3>Cordset</h3>
      <img src="images/cordset.jpg" alt="Cordset" width="180">
    </div>
  </div>
</section>
.products {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.product {
  background-color: #fff;
  padding: 20px;
  width: 200px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  border-radius: 5px;
  text-align: center;
}

.product img {
  border-radius: 5px;
  margin-bottom: 10px;
}
