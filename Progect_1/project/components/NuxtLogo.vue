<template>
   <main>

        <section class="product" id="one">
            <div class="svg_1"><img class="svg1" src="./page_and_font/Vector 98.svg" alt="#"></div>
            <div class="product__content">
    
                <h1 class="product__title">We do campaigns that works well for your idea</h1>
                <p class="product__description">Our documentary campaigns feature leading figures, organisations and
                    leaders, in open and candid discussions about transformative strategies and mindsets. Addressing
                    complex trends.</p>
                <div class="product__button-wrapper">
                    <button class="product__button">All campaigns <svg xmlns="http://www.w3.org/2000/svg" width="24"
                            height="24" viewBox="0 0 24 24" fill="none">
                            <g clip-path="url(#clip0_256_3)">
                                <path d="M13.6887 6.5L18.5 12L13.6887 17.5M18.1232 12H5.5" stroke="#AC55F2" stroke-width="2"
                                    stroke-linecap="round" stroke-linejoin="round" />
                            </g>
                            <defs>
                                <clipPath id="clip0_256_3">
                                    <rect width="24" height="24" fill="white" transform="translate(24) rotate(90)" />
                                </clipPath>
                            </defs>
                        </svg></button>
                </div>
            </div>
            <img class="svg_2" src="./page_and_font/Vector 99.svg" alt="#" width="46.5px" height="47px">
            <img class="product__picture" src="./page_and_font/Rectangle 1cfhnj.png" alt="Card" />
    
        </section>
    
        <section class="product_2" id="one">
            <div class="svg_11"><img class="svg1" src="./page_and_font/Vector 97.svg" alt="#"></div>
            <div class="product__content">
    
                <h1 class="product__title">We make films that stick in your heart</h1>
                <p class="product__description">This exclusive service provided by our team of professional content creators
                    is available for global use. Our clients will have access and total creative control throughout the
                    process of production, with resources and talent supplied by us.</p>
                <div class="product__button-wrapper">
                    <button class="product__button">I have an idea for film <svg xmlns="http://www.w3.org/2000/svg" width="24"
                            height="24" viewBox="0 0 24 24" fill="none">
                            <g clip-path="url(#clip0_256_3)">
                                <path d="M13.6887 6.5L18.5 12L13.6887 17.5M18.1232 12H5.5" stroke="#AC55F2" stroke-width="2"
                                    stroke-linecap="round" stroke-linejoin="round" />
                            </g>
                            <defs>
                                <clipPath id="clip0_256_3">
                                    <rect width="24" height="24" fill="white" transform="translate(24) rotate(90)" />
                                </clipPath>
                            </defs>
                        </svg></button>
                </div>
            </div>
            <img class="svg_22" src="./page_and_font/Vector 96.svg" alt="#" width="46.5px" height="47px">
            <img class="product__picture_2" src="./page_and_font/Rectangle 14.png" width="800" height="560" alt="Card" />
    
        </section>
    </main>
</template>

<style>
@import url("https://fonts.googleapis.com/css2? Family= Raleway & display=swap");

*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}

main {
  font-family: 'Raleway', sans-serif;
  display: flex;
  width: 1600px;
  padding: 144px 60px 144px 60px;
  flex-direction: column;
  align-items: flex-start;
  gap: 128px;
  background-color: #1F293E;
  margin: 0;
}

.product {
  display: flex;
  width: 1480px;

}

.product__picture {
  margin-left: 64px;
  border-radius: 15px;
  width: 100%;
  height: auto;
  justify-content: flex-end;

}

.product__content {
  display: flex;
  /* padding-left: 48px; */
  flex-direction: column;
  align-items: flex-start;
  gap: 48px;
  flex: 1 0 0;
  align-content: center;
  margin-top: 104px;
}


.product__title {
  color: #F9FAFB;
  width: 520px;
  height: 112px;
  font-size: 40px;
}

p {
  color: #E5E7EB;
  height: 120px;
  width: 520px;
  font-size: 20px;
  line-height: 30px;
  gap: 10px;
  letter-spacing: -0.2px;
}

button {
  display: flex;
  height: 48px;
  padding: 14px 0px;
  justify-content: center;
  align-items: center;
  gap: 12px;
  background-color: none;
  border: none;
  text-align: center;
  font-size: 18px;
  background: linear-gradient(90deg, #6366F1 0%, #AC54F1 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.svg_1 {
  display: inline-block;
  padding-top: 74px;
}

.svg_2 {
  margin-top: 431px;
}

.product_2 {
  display: flex;
  flex-direction: row-reverse;

}

.product__picture_2 {
  margin-right: 64px;
  border-radius: 15px;
}

.svg_11 {
  display: inline-block;
  padding-top: 74px;
}

.svg_22 {
  margin-top: 470px;
}


</style>
