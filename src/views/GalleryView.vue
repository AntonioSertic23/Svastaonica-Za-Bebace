<script setup>
import PageTitle from "../components/ui/PageTitle.vue";
</script>

<template>
  <section class="gallery-section py-4">
    <div class="container">
      <div class="row justify-content-center text-center">
        <p class="mb-5 menu-title">Gallery</p>
        <div class="col-8">
          <p class="gallery-description">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cum
            facilis tempora porro, suscipit ducimus delectus quaerat alias
            corporis a obcaecati, molestiae expedita dolorem nisi commodi maxime
            nulla exercitationem illo dolores.
          </p>
        </div>
      </div>

      <!-- gallery cards -->
      <div class="row my-5 py-5">
        <div class="d-flex justify-content-center">
          <a class="mx-2 category-link" href="">U trendu</a>
          <a class="mx-2 category-link" href="">Novo u ponudi</a>
          <a class="mx-2 category-link" href="">Akcija</a>
          <a class="mx-2 category-link" href="">Paketi</a>
        </div>
      </div>
      <div class="section-cards row justify-content-evenly mb-5">
        <div class="container text-center">
          <div class="row row-cols-3 g-5">
            <div class="col">
              <div class="image-div">
                <div class="image-div-background"></div>
                <img src="../assets/img/new.png" alt="" />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/1.jpg" alt="" />
              </div>
              <h1>Lorem, ipsum dolor</h1>
            </div>

            <div class="col">
              <div class="border product-image-div">
                <img src="../assets/img/products/5.jpg" alt="" />
              </div>
              <h1>Lorem dolor</h1>
            </div>

            <div class="col">
              <div class="border product-image-div">
                <img src="../assets/img/products/6.jpg" alt="" />
              </div>
              <h1>Lorem ipsum</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background"></div>
                <img src="../assets/img/trending.png" alt="" />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/2.jpg" alt="" />
              </div>
              <h1>Ipsum dolor</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background"></div>
                <img src="../assets/img/gift-box.png" alt="" />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/3.jpg" alt="" />
              </div>
              <h1>Dolor</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background"></div>
                <img src="../assets/img/trending.png" alt="" />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/4.jpg" alt="" />
              </div>
              <h1>Dolor</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background"></div>
                <img src="../assets/img/discount.png" alt="" />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/5.jpg" alt="" />
              </div>
              <h1>Lorem dolor</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background"></div>
                <img src="../assets/img/positive-vote.png" alt="" />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/6.jpg" alt="" />
              </div>
              <h1>Lorem ipsum</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div
                  class="image-div-background"
                  style="width: 55%; border-radius: 40%; height: 110px"
                ></div>
                <img
                  style="margin-left: 28%"
                  src="../assets/img/new.png"
                  alt=""
                />
                <img
                  style="margin-right: 28%"
                  src="../assets/img/gift-box.png"
                  alt=""
                />
              </div>
              <div class="border product-image-div">
                <img src="../assets/img/products/1.jpg" alt="" />
              </div>
              <h1>Lorem, ipsum</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background" style="z-index: 1"></div>
                <img
                  src="../assets/img/gift-box.png"
                  style="z-index: 1; filter: brightness(60%)"
                  alt=""
                />
              </div>
              <div class="border">
                <div class="soldout-div showhim">
                  <img
                    src="../assets/img/products/2.jpg"
                    class="product-image"
                    alt=""
                    style="filter: brightness(60%)"
                  />
                  <img src="../assets/img/sold-out.png" class="showme" alt="" />
                </div>
              </div>
              <h1 style="opacity: 0.5">Lorem.</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background" style="z-index: 1"></div>
                <img
                  src="../assets/img/positive-vote.png"
                  style="z-index: 1; filter: brightness(60%)"
                  alt=""
                />
              </div>
              <div class="border">
                <div class="soldout-div showhim">
                  <img
                    src="../assets/img/products/3.jpg"
                    class="product-image"
                    alt=""
                    style="filter: brightness(60%)"
                  />
                  <img src="../assets/img/sold-out.png" class="showme" alt="" />
                </div>
              </div>
              <h1 style="opacity: 0.5">Lorem dolor</h1>
            </div>

            <div class="col">
              <div class="border">
                <div class="soldout-div showhim">
                  <img
                    src="../assets/img/products/4.jpg"
                    class="product-image"
                    alt=""
                    style="filter: brightness(60%)"
                  />
                  <img src="../assets/img/sold-out.png" class="showme" alt="" />
                </div>
              </div>
              <h1 style="opacity: 0.5">Lorem dolor</h1>
            </div>

            <div class="col">
              <div class="image-div">
                <div class="image-div-background" style="z-index: 1"></div>
                <img
                  src="../assets/img/trending.png"
                  style="z-index: 1; filter: brightness(60%)"
                  alt=""
                />
              </div>
              <div class="border">
                <div class="soldout-div showhim">
                  <img
                    src="../assets/img/products/5.jpg"
                    class="product-image"
                    alt=""
                    style="filter: brightness(60%)"
                  />
                  <img src="../assets/img/sold-out.png" class="showme" alt="" />
                </div>
              </div>
              <h1 style="opacity: 0.5">Lorem dolor</h1>
            </div>

            <div class="col">
              <div class="border">
                <div class="soldout-div showhim">
                  <img
                    src="../assets/img/products/6.jpg"
                    class="product-image"
                    alt=""
                    style="filter: brightness(60%)"
                  />
                  <img src="../assets/img/sold-out.png" class="showme" alt="" />
                </div>
              </div>
              <h1 style="opacity: 0.5">Lorem dolor</h1>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
.menu-title {
  font-size: 48.83px;
}

.gallery-description {
  font-size: 25px;
}

.category-link {
  color: #222;
  text-decoration: none;
  text-transform: uppercase;
  background-color: rgb(205, 180, 219);
  border-radius: 15px;
  padding: 1rem;
  font-weight: 500;
  letter-spacing: 2px;
}
.category-link:hover {
  background-color: #a375bd;
}

.border {
  height: 400px;
  border-radius: 15px;
  cursor: pointer;
  overflow: hidden;
}

.section-cards .image-div img {
  width: 70px;
  position: absolute;

  margin-top: -35px;
  margin-right: auto;
  margin-left: auto;
  left: 0;
  right: 0;
  z-index: 2;
}
.image-div {
  position: relative;
}

/* new - soldout item */
.soldout-div {
  position: relative;
  width: 100%;
  height: 100%;
}

.soldout-div .showme {
  position: absolute;
  left: 0;
  right: 0;
  margin-left: auto;
  margin-right: auto;
  top: 0;
  bottom: 0;
  margin-top: auto;
  margin-bottom: auto;
  width: 128px;
}

.showme {
  visibility: hidden;
  opacity: 0;
  transition: visibility 0.5s, opacity 0.5s linear;
}

.showhim:hover .showme {
  visibility: visible;
  opacity: 1;
}

.col h1 {
  text-align: center;
  margin-top: 1rem;
  font-size: 32px;
  font-weight: 300;
  margin-bottom: 1rem;
}
/* new */

.section-cards2 .image-div img {
  width: 64px;
  position: absolute;
  right: 0;
}
.section-cards2 .border img {
  width: 100%;
  border-radius: 15px;
}
.section-cards2 .border {
  height: auto;
  border-radius: 15px;
}
.section-cards2 .border .btn {
  font-size: 20px;
}

.section-cards3 .border img {
  width: 100%;
  height: 100%;
}
.section-cards3 .border {
  height: 400px;
  border-radius: 0;
}

.badge {
  position: absolute;
  background-color: gray;
  left: 20px;
  top: 20px;
  border-radius: 0;
}

.section-cards3 .border {
  position: relative;
  border: 1px solid #999 !important;
  cursor: pointer;
}
.section-cards3 .border p {
  font-size: 16px;
  letter-spacing: 2px;
}

.coupon-div {
  border-radius: 30px !important;
}
.coupon-div img {
  border-radius: 30px;
}
.coupon-card {
  height: calc(100% - 40px);
  width: calc(100% - 40px);
  position: absolute;
  border: 5px dashed white;
  top: 0;
  margin-top: 20px;
  margin-bottom: 20px;
  margin-left: 20px;
  margin-right: 20px;
  border-radius: 30px;
}

.product-image-div img,
.soldout-div .product-image {
  height: 100%;
  width: 100%;
  border-radius: 15px;
  object-fit: cover;
}

.image-div-background {
  height: 100px;
  position: absolute;
  width: 100px;
  background-color: #ede4f2;
  margin-left: auto;
  margin-right: auto;
  left: 0;
  right: 0;
  border-radius: 50%;
  margin-top: -50px;
  z-index: 1;
}

img {
  transition: transform 0.5s;
}
img:hover {
  transform: scale(1.2);
}
</style>
