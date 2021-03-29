<template>
  <div class="country">
    <div class="country_container">
      <div class="country_wrapper">
        <div class="country_block_left">
          <div class="country_inner_line">
            <div class="country_line"></div>
          </div>
          <div class="country_inner">
            <h1 class="country_title">
              грузоперевозки
              <br />
              по европе
            </h1>
          </div>
          <div class="country_inner">
            <h1 class="country_subtitle">
              Страны Евросоюза, а также Украина,
              <br />
              Белоруссия со всеми документами.
            </h1>
          </div>
          <div class="country_inner">
            <p class="country_btn">ПОДРОБНЕЕ</p>
          </div>
        </div>
        <div class="country_block_middle">
          <div class="country_img"></div>
        </div>
        <div class="country_block_right">
          <div class="country_sidebar_next">
            <p class="country_text">след</p>
            <div class="country_next"></div>
          </div>
          <div class="country_sidebar_back">
            <div class="country_back"></div>
            <p class="country_text_back">назад</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Country",
};
</script>
<style lang="scss" scoped>
.country {
  width: 100%;
  height: 561px;
  background: #393f47;
  position: relative;
  &_container {
    display: flex;
    width: 100%;
    justify-content: center;
  }
  &_wrapper {
    display: flex;
    width: 1110px;
    height: 561px;
  }
  &_block_left {
    display: flex;
    width: 30%;
    height: 561px;
    flex-direction: column;
    justify-content: center;
  }
  &_inner {
    display: flex;
    height: 8rem;
    justify-content: flex-start;
  }
  &_inner_line {
    display: flex;
    height: 2rem;
    margin-top: 4rem;
    justify-content: flex-start;
  }
  &_line {
    display: flex;
    width: 90px;
    height: 6px;
    background: #c8a35f;
  }
  &_title {
    display: flex;
    position: absolute;
    justify-content: flex-start;
    margin-top: 1rem;
    font-family: "Roboto_bold";
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 49px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
  &_subtitle {
    display: flex;
    justify-content: flex-start;
    margin-top: 1rem;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 28px;
    color: #ffffff;
  }
  &_btn {
    display: flex;
    width: 220px;
    height: 55px;
    justify-content: center;
    align-items: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 25px;
    text-align: center;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    background: #c8a35f;
    color: #ffffff;
  }

  //Midlle

  &_block_middle {
    display: flex;
    width: 40%;
    background: #2f343a;
  }
  &_img {
    width: 445px;
    height: 266px;
    position: absolute;
    margin-top: 12rem;
    margin-left: 10rem;
    background: url("../assets/img/block_country/Rectangle 4.png");
    background-size: cover;
  }

  //right
  &_block_right {
    display: flex;
    width: 30%;
    flex-direction: column;
  }
  &_sidebar_next {
    display: flex;
    height: 50%;
    margin-top: 10rem;
  }
  &_text,
  &_text_back {
    font-family: "Roboto";
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 25px;
    text-align: right;
    padding-right: 2rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #c8a35f;
  }
  &_next {
    width: 65px;
    height: 18px;
    cursor: pointer;
    background: url("../assets/img/block_country/Arrow.png");
    background-size: cover;
  }
  &_sidebar_back {
    display: flex;
    height: 50%;
    margin-top: 7rem;
    justify-content: flex-end;
  }
  &_back {
    width: 65px;
    height: 22px;
    cursor: pointer;
    background: url("../assets/img/block_country/Arrow (1).png");
    background-size: cover;
  }
  &_text_back {
    width: 4rem;
    margin-left: 2rem;
  }
}
</style>
