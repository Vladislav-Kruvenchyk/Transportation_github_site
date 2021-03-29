<template>
  <div class="imgHeader">
    <div class="imgHeader_container">
      <div class="imgHeader_wrapper">
        <div class="imgHeader_inner">
          <h1 class="imgHeader_title">Грузовые перевозки</h1>
        </div>
        <div class="imgHeader_inner">
          <p class="imgHeader_subtitle">
            Перевозка крупногабаритных грузов по России и Европе. Полное
            экспедирование,
            <br />
            страхование, упаковка и хранение грузов
          </p>
        </div>
      </div>
      <div class="imgHeader_footer_mouse">
        <div class="imgHeader_mouse_icon"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ImgHeader",
};
</script>
<style lang="scss" scoped>
.imgHeader {
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 620px;
  background: url("../assets/img/block_header/Rectangle 2.png") center center;
  background-size: cover;
  &_container {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 620px;
  }
  &_wrapper {
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin-top: 6rem;
    width: 920px;
    height: 245px;
    border: 1px solid #c8a35f;
  }
  &_inner {
    display: flex;
    width: 100%;
    // border: 1px solid #c8a35f;
  }
  &_title {
    display: flex;
    height: 5rem;
    justify-content: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: bold;
    font-size: 64px;
    line-height: 75px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
  &_subtitle {
    display: flex;
    margin-top: 1rem;
    text-align: center;
    justify-content: center;
    align-items: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 28px;
    color: #ffffff;
  }
  &_footer_mouse {
    display: flex;
    width: 100%;
    height: 10rem;
    justify-content: center;
  }
  &_mouse_icon {
    display: flex;
    width: 30px;
    height: 30px;
    margin-top: 8rem;
    background: url("../assets/img/block_header/mouse.png");
    background-size: cover;
  }
}
</style>
