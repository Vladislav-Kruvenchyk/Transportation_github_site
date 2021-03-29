<template>
  <div class="company">
    <div class="company_container">
      <div class="company_block_left">
        <div class="company_wrap">
          <div class="company_inner_line">
            <div class="company_line"></div>
          </div>
          <div class="company_inner">
            <h1 class="company_title">
              О компании
            </h1>
          </div>
          <div class="company_inner">
            <p class="company_text">
              Lorem Ipsum - это текст-"рыба", часто используемый в печати и
              вэб-дизайне. Lorem Ipsum является стандартной "рыбой" для текстов
              на латинице с начала XVI века. В то время некий безымянный
              печатник создал большую коллекцию размеров и форм шрифтов,
              используя Lorem Ipsum для распечатки образцов. Lorem Ipsum не
              только успешно пережил без заметных изменений пять веков, но и
              перешагнул в электронный дизайн.
            </p>
          </div>
        </div>
      </div>
      <div class="company_block_midlle">
        <div class="company_block"></div>
      </div>
      <div class="company_block_right">
        <div class="company_wrapper">
          <ul class="company_column">
            <li class="company_item_figure">48</li>
            <li class="company_item_subtitle">офисы</li>
            <li class="company_item_subtitle_lite">В Европе и СНГ</li>
          </ul>
          <ul class="company_column">
            <li class="company_item_figure">361</li>
            <li class="company_item_subtitle">грузовиков</li>
            <li class="company_item_subtitle_lite">Volvo, Scania</li>
          </ul>
          <div class="company_column">
            <div class="company_item_img"></div>
          </div>
          <div class="company_column">
            <div class="company_item_img"></div>
          </div>
          <ul class="company_column">
            <li class="company_item_figure">1500</li>
            <li class="company_item_subtitle">сотрудников</li>
            <li class="company_item_subtitle_lite">профессионалов</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Company",
};
</script>
<style lang="scss" scoped>
.company {
  width: 100%;
  height: 600px;
  background: #2f343a;
  &_container {
    display: flex;
    width: 100%;
    align-items: center;
  }
  &_block_left {
    display: flex;
    width: 42%;
    height: 500px;
    transform: translateX(395px);
  }
  &_wrap {
    display: flex;
    width: 100%;
    flex-direction: column;
    justify-content: center;
  }
  &_inner_line {
    display: flex;
  }
  &_line {
    display: flex;
    width: 90px;
    height: 6px;
    background: #c8a35f;
  }
  &_inner {
    display: flex;
    margin-top: 2rem;
  }
  &_title {
    display: flex;
    font-family: "Roboto";
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 49px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
  &_text {
    display: flex;
    width: 445px;
    height: 210px;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 23px;
    color: #ffffff;
  }

  &_block_midlle {
    display: flex;
    width: 26%;
  }
  &_block {
    display: flex;
    width: 410px;
    height: 482px;
    background: #393f47;
  }
  //Правый блок

  &_block_right {
    display: flex;
    width: 42%;
    transform: translateX(-271px);
  }
  &_wrapper {
    display: flex;
    width: 630px;
    height: 320px;
    flex-wrap: wrap;
  }
  &_column {
    display: flex;
    width: 200px;
    height: 160px;
    flex-direction: column;
    justify-content: center;
    background: #ffff;
    border: 0.25px solid #c8a35f;
  }
  &_item_figure {
    display: flex;
    height: 5rem;
    justify-content: center;
    align-items: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: bold;
    font-size: 64px;
    line-height: 75px;
    text-align: center;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #2f343a;
  }
  &_item_subtitle {
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 21px;
    text-align: center;
    letter-spacing: 0.05em;
    color: #000000;
  }
  &_item_subtitle_lite {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 1rem;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 14px;
    text-align: center;
    color: #000000;
  }
  &_item_img {
    width: 200px;
    height: 160px;
    background: url("../assets/img/block_compuny/Rectangle 2.2.png");
    background-size: cover;
  }
}
</style>
