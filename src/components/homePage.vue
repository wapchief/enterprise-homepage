<template>
  <div class="hello">
    <!-- <img src="../../../../../assets/footer.png"> -->
    <Header />
    <div class="banner-box">
      <div class="w">
        <h3>为你创造完美的留学文书</h3>
        <p>
          每篇文书均由目标学校直系学长姐、专业大牛打磨，高学历Native
          Speakers精修
        </p>
        <a class="button">挑选专业</a>
      </div>
    </div>
    <div class="school-box">
      <div class="school">
        <div
          class="
            swiper-container
            swiper-container-initialized
            swiper-container-horizontal
          "
        >
          <div
            class="swiper-wrapper"
            style="transform: translate3d(0px, 0px, 0px)"
          >
            <div class="swiper-slide swiper-slide-active" style="width: 1200px">
              <a href="#/college/majorlist?id=19" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7d7ntkpaj2una5r1rbi11vd9.png" /></a
              ><a href="#/college/majorlist?id=12" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7jrvft18f51avv19o41n6hljee.png" /></a
              ><a href="#/college/majorlist?id=17" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7jr6e0117peqs114qqqcr239.png" /></a
              ><a href="#/college/majorlist?id=8" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7dtjmem341olcf2ahc33fij.png" /></a
              ><a href="#/college/majorlist?id=13" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7dq0e35upstrr7g1h9ajc5o.png" /></a
              ><a href="#/college/majorlist?id=5" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7jut92eg5tbi1r9j19kptn3o.png" /></a
              ><a href="#/college/majorlist?id=22" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7jscp1bqn1g0j41a1ogoa3nj.png" /></a
              ><a href="#/college/majorlist?id=10" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7k0d2v66t137arkpmer1png12.png" /></a
              ><a href="#/college/majorlist?id=1" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7jvu5p1n97nfct4718po1prpt.png" /></a
              ><a href="#/college/majorlist?id=2" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1de7k1ct11si59q41s4j1cm9p1v17.png"
              /></a>
            </div>
            <div class="swiper-slide swiper-slide-next" style="width: 1200px">
              <a href="#/college/majorlist?id=25" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq6c075r14l7h2iddr14qms6t12.jpg" /></a
              ><a href="#/college/majorlist?id=27" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq6c268upr11tkv4nslv83bk17.jpg" /></a
              ><a href="#/college/majorlist?id=26" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq6cfev81j4k1cnbvb4ptu1khp1m.png" /></a
              ><a href="#/college/majorlist?id=28" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq6ce3qb3dp12hmugc16pk4f71h.png" /></a
              ><a href="#/college/majorlist?id=3" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq6cm1klt181hteuv61ipemi31r.png" /></a
              ><a href="#/college/majorlist?id=11" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq8ci6akiq8e7uq5tuvd1mpp12.jpg" /></a
              ><a href="#/college/majorlist?id=20" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq8cm68l1nfvkng14cps8bk0917.png" /></a
              ><a href="#/college/majorlist?id=21" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq8cdaqu1vol1qkj1she77v1eq5j.jpg" /></a
              ><a href="#/college/majorlist?id=6" class="item"
                ><img
                  src="https://qnimg.personalstatement.cn/o_1dq8cpfc6ue632jn5sak71nt71c.png" /></a
              ><a href="#/college/majorlist?id=16" class="item"
                ><img
                  Î
                  src="https://qnimg.personalstatement.cn/o_1dq8ceirsr74lkl1189tgs1l2tt.png"
              /></a>
            </div>
          </div>
          <div
            class="swiper-button-prev swiper-button-disabled"
            tabindex="0"
            role="button"
            aria-label="Previous slide"
            aria-disabled="true"
          >
            <i class="left"></i>
          </div>
          <div
            class="swiper-button-next"
            tabindex="0"
            role="button"
            aria-label="Next slide"
            aria-disabled="false"
          >
            <i class="right"></i>
          </div>
          <span
            class="swiper-notification"
            aria-live="assertive"
            aria-atomic="true"
          ></span>
        </div>
      </div>
    </div>
    <div class="img-box">
      <img src="../assets/part01.png" />
      <img src="../assets/part02.png" />
      <img src="../assets/part03.png" />
      <img src="../assets/part04.png" />
      <img src="../assets/part05.png" />
    </div>
  </div>
</template>

<script>
import Header from './header'
export default {
  name: 'HomePage',
  components: {
    Header
  },
  data () {
    return {
      msg: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.hello {
  display: block;
  //   justify-content: flex-start;
  .banner-box {
    background-image: url("../assets/banner.png");

    height: 372px;
    min-width: 1200px;
    background-position: 50%;
    background-repeat: repeat-x;
    color: #fff;
    .w {
      padding-left: 130px;
      padding-top: 100px;
      color: #fff;
    }
    h3 {
      font-size: 34px;
      line-height: 50px;
    }
    p {
      font-size: 16px;
      padding-bottom: 20px;
    }
    .button {
      height: 36px;
      line-height: 36px;
      background-color: #4a90e2;
      border-radius: 4px;
      font-size: 12px;
      letter-spacing: 0;
      text-align: center;
      display: inline-block;
      color: #fff;
      padding: 0 30px;
    }
  }
  .school-box {
    background: #fff;
    position: relative;
    .school {
      text-align: left;
      padding: 30px 0;
      position: relative;
      font-size: 0;
      letter-spacing: -3px;
      min-height: 200px;
      .swiper-container {
        margin: 0 auto;
        position: relative;
        overflow: hidden;
        list-style: none;
        padding: 0;
        z-index: 1;
        .swiper-wrapper {
          position: relative;
          width: 100%;
          height: 100%;
          z-index: 1;
          display: -webkit-box;
          display: -webkit-flex;
          display: -ms-flexbox;
          display: flex;
          -webkit-transition-property: -webkit-transform;
          transition-property: -webkit-transform;
          -o-transition-property: transform;
          transition-property: transform;
          transition-property: transform, -webkit-transform;
          -webkit-box-sizing: content-box;
          box-sizing: content-box;
          .swiper-slide {
            padding-left: 40px;
          }
          .swiper-button-prev {
            position: absolute;
            top: 50%;
            width: 27px;
            height: 44px;
            margin-top: -22px;
            z-index: 10;
            cursor: pointer;
            background-size: 27px 44px;
            background-position: 50%;
            background-repeat: no-repeat;
          }
          a {
            color: #333;
            text-decoration: none;
            cursor: pointer;
          }
          .item {
            display: inline-block;
            margin: 20px 30px;
          }
        }
      }
    }
  }
  .img-box {
    text-align: center;
    padding-top: 70px;
    width: 1200px;
  }
}
</style>
