<template>
  <main class="main">
            <div class="center">
                <div class="main__top">
                    <div class="main__top_text"><h1 class="main__top_h1">Let
                            Your
                            Home
                            Be Unique</h1>
                        <p class="main__top_txt">
                            There are many variations of the passages of
                            lorem Ipsum fromavailable, majority.
                        </p>
                        <button class="main__top_button">Get Started</button>
                    </div>
                </div>

                <div class="main__text1">
                    <h2 class="main__h2">Follow Our Projects</h2>
                    <p class="main__p">It is a long established fact that a
                        reader
                        will be distracted by the of readable content of page
                        lookings at its layouts points.</p>
                </div>

                <div class="main__catalog">
                    <div class="main__cat main__cat1">
                        <img src="../assets/img/cat1.png" alt="image1">
                        <div class="main__cat_down">
                            <div class="main__down">
                                <h3 class="main__h3">Modern Kitchan</h3>
                                <p class="main__link">Decor / Artchitecture</p>
                            </div>
                            <div class="main__btn">
                                <svg width="70" height="70" viewBox="0 0 70 70"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <circle cx="35" cy="35" r="35"
                                        fill="#F4F0EC" />
                                    <path d="M32 44L40 35L32 26"
                                        stroke="#292F36"
                                        stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg>
                            </div>
                        </div>

                    </div>

                    <div class="main__cat main__cat2">
                        <img src="../assets/img/cat2.png" alt="image2">
                        <div class="main__cat_down">
                            <div class="main__down">
                                <h3 class="main__h3">Modern Kitchan</h3>
                                <p class="main__link">Decor / Artchitecture</p>
                            </div>
                            <div class="main__btn">
                                <svg width="70" height="70" viewBox="0 0 70 70"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <circle cx="35" cy="35" r="35"
                                        fill="#F4F0EC" />
                                    <path d="M32 44L40 35L32 26"
                                        stroke="#292F36"
                                        stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg>
                            </div>
                        </div>

                    </div>

                    <div class="main__cat main__cat3">
                        <img src="../assets/img/cat3.png" alt="image3">
                        <div class="main__cat_down">
                            <div class="main__down">
                                <h3 class="main__h3">Modern Kitchan</h3>
                                <p class="main__link">Decor / Artchitecture</p>
                            </div>
                            <div class="main__btn">
                                <svg width="70" height="70" viewBox="0 0 70 70"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <circle cx="35" cy="35" r="35"
                                        fill="#F4F0EC" />
                                    <path d="M32 44L40 35L32 26"
                                        stroke="#292F36"
                                        stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg>
                            </div>
                        </div>

                    </div>

                    <div class="main__cat main__cat4">
                        <img src="../assets/img/cat4.png" alt="image4">
                        <div class="main__cat_down">
                            <div class="main__down">
                                <h3 class="main__h3">Modern Kitchan</h3>
                                <p class="main__link">Decor / Artchitecture</p>
                            </div>
                            <div class="main__btn">
                                <svg width="70" height="70" viewBox="0 0 70 70"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <circle cx="35" cy="35" r="35"
                                        fill="#F4F0EC" />
                                    <path d="M32 44L40 35L32 26"
                                        stroke="#292F36"
                                        stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg>
                            </div>
                        </div>

                    </div>

                </div>

            </div>

            <div class="main__numbers">
                <div class="main__flex center">
                    <div class="main__number main__number1">
                        <span class="main__span">12</span>
                        <p class="main__link">Years Of Experiance</p>
                    </div>

                    <div class="main__number main__number2">
                        <span class="main__span">85</span>
                        <p class="main__link">Success Project</p>
                    </div>

                    <div class="main__number main__number3">
                        <span class="main__span">15</span>
                        <p class="main__link">Active Project</p>
                    </div>

                    <div class="main__number main__number4">
                        <span class="main__span">95</span>
                        <p class="main__link">Happy CUstomers</p>
                    </div>
                </div>

            </div>

            <div class="center">
                <div class="main__text1 center">
                    <h2 class="main__h2">Articles & News</h2>
                    <p class="main__p">It is a long established fact that a
                        reader
                        will be distracted by the of readable content of a page
                        when
                        lookings at its layouts the points of using.</p>
                </div>

                <div class="main__bottom app">
                  <div class="main__news" v-for="item in items" :key="item.id" >                                                          
                    <img v-bind:src="require(`@/assets/img/${item.src}`)" alt="news">                        
                    <h3 class="main__h3">{{ item.name }}</h3>
                    <div class="main__news_bottom">
                            <span>{{ item.dat }}</span>
                            <svg width="52" height="53" viewBox="0 0 52 53"
                                fill="none" xmlns="http://www.w3.org/2000/svg">
                                <circle cx="26" cy="26.267" r="26"
                                    fill="#F4F0EC" />
                                <path
                                    d="M23.7714 32.9527L29.7143 26.267L23.7714 19.5813"
                                    stroke="#292F36" stroke-width="2"
                                    stroke-linecap="round"
                                    stroke-linejoin="round" />
                            </svg>
                        </div>

                      </div>
                  
                </div>
            </div>

        </main>
</template>

<script>
export default {
    name: 'MainComponent',    

    data() {
        return {
                items: [{
                  id:0,
            src: 'news1.png',
            name: 'Let’s Get Solution For Building Construction Work',
            dat: '26 December,2022',
        }, {
          id:1,
            src: 'news2.png',
            name: 'Low Cost Latest Invented Interior Designing Ideas.',
            dat: '22 December,2022',
        },
        {
          id:2,
            src: 'news3.png',
            name: 'Best For Any Office & Business Interior Solution',
            dat: '25 December,2022',
        },
        {
          id:3,
            src: 'news4.png',
            name: 'Let’s Get Solution For Building Construction Work',
            dat: '26 December,2022',
        }, {
          id:4,
            src: 'news5.png',
            name: 'Low Cost Latest Invented Interior Designing Ideas.',
            dat: '22 December,2022',
        },
        {
          id:5,
            src: 'news6.png',
            name: 'Best For Any Office & Business Interior Solution',
            dat: '25 December,2022',
        }
        ]
            
        };
    },
    methods: {
        
    },
};
</script>

<style lang="scss" scoped>
.main {
  &__top_text {
    width: 444px;
  }

  &__top {
    position: relative;
    // border: 1px solid;
    border-radius: 50px;
    background-image: url("../assets/img/Images.png");
    min-height: 758px;
    // height: 758px;
    background-repeat: no-repeat;
    // background-size: contain;

    padding-left: 50px;
    display: flex;
    align-items: center;

    &_h1 {
      color: #292f36;

      font-size: 65px;
      font-style: normal;
      font-weight: 400;
      line-height: 125%;
    }

    &_txt {
      color: #4d5053;
      font-family: "Jost", sans-serif;
      font-size: 22px;
      font-style: normal;
      font-weight: 400;
      line-height: 150%;
      letter-spacing: 0.22px;
      padding-top: 18px;
    }

    &_button {
      padding-top: 26px;
      padding-bottom: 26px;
      padding-right: 48px;
      padding-left: 48px;
      border-radius: 18px;
      background-color: #292f36;
      color: #fff;
      border: 0px;
      font-size: 18px;
      // position: absolute;
      bottom: -150px;
    }
  }

  &__text1 {
    text-align: center;
    padding-top: 100px;
    padding-left: 20%;
    padding-right: 20%;
  }

  &__h2 {
    color: #292f36;
    font-size: 50px;
    font-style: normal;
    font-weight: 400;
    line-height: 125%;
    letter-spacing: 1px;
  }

  &__p {
    color: #4d5053;
    text-align: center;
    font-family: "Jost";
    font-size: 22px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    /* 33px */
    letter-spacing: 0.22px;
  }

  &__h3 {
    color: #292f36;

    font-size: 25px;
    font-style: normal;
    font-weight: 400;
    line-height: 125%;
    /* 31.25px */
    letter-spacing: 0.5px;
  }

  &__link {
    color: #4d5053;
    font-family: "Jost";
    font-size: 22px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    /* 33px */
    letter-spacing: 0.22px;
  }

  &__cat {
    // min-width: 547px;
    width: 547px;
  }

  &__cat_down {
    justify-content: space-between;
    padding-top: 24px;
    display: flex;
  }

  &__catalog {
    display: flex;
    flex-wrap: wrap;
    gap: 100px;
    padding-top: 93px;
    padding-bottom: 93px;
  }

  &__cat1 img {
    border-radius: 0px 50px 0px 0px;
  }

  &__cat2 img {
    border-radius: 50px 0px 0px 0px;
  }

  &__cat3 img {
    border-radius: 0px 0px 50px 0px;
  }

  &__cat4 img {
    border-radius: 0px 0px 0px 50px;
  }

  &__number {
    text-align: center;
  }

  &__numbers {
    background-color: #f4f0ec;
  }

  &__span {
    color: #cda274;

    font-size: 85px;
    font-style: normal;
    font-weight: 400;
    line-height: 125%;
    /* 106.25px */
    letter-spacing: 1.7px;
  }

  &__flex {
    display: flex;
    justify-content: center;
    padding-top: 150px;
    padding-bottom: 150px;
  }

  &__number {
    width: 300px;
  }

  &__number1 {
    border-right: 1px solid #cda274;
  }

  &__number2 {
    border-right: 1px solid #cda274;
  }

  &__number3 {
    border-right: 1px solid #cda274;
  }

  &__news_bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 40px;
  }

  &__news {
    width: 382px;
    padding: 20px;
    border: 1px solid #e7e7e7;
    border-radius: 50px;
  }

  &__news img {
    border-radius: 30px 30px 0 0;
  }

  &__news:hover {
    background-color: #e7e7e7;
  }

  &__h3 {
    color: #292f36;

    font-size: 25px;
    font-style: normal;
    font-weight: 400;
    line-height: 125%;
    /* 31.25px */
    letter-spacing: 0.5px;
  }

  &__news_bottom span {
    color: #4d5053;
    font-family: "Jost";
    font-size: 16px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    /* 24px */
    letter-spacing: 0.16px;
    text-transform: capitalize;
  }

  &__bottom {
    padding-top: 52px;
    display: flex;
    gap: 27px;
    padding-bottom: 93px;
  }

}
</style>