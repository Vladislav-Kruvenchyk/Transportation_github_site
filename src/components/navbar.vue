<template>
  <div class="navbar">
    <div class="navbar_container">
      <div class="navbar_wrapper">
        <div class="navbar_block_left">
          <div class="navbar_inner_start">
            <div class="navbar_logo"></div>
          </div>
          <div class="navbar_inner_line">
            <div class="navbar_line"></div>
          </div>
          <div class="navbar_inner_start">
            <div class="navbar_row">
              <div class="navbar_map"></div>
              <p class="navbar_title">Наши офисы</p>
            </div>
          </div>
        </div>
        <div class="navbar_block_right">
          <div class="navbar_inner">
            <div class="navbar_content">
              <p class="navbar_item_one">услуги</p>
            </div>
          </div>
          <div class="navbar_inner">
            <div class="navbar_content">
              <p class="navbar_item_two">о компании</p>
            </div>
          </div>
          <div class="navbar_inner">
            <div class="navbar_content">
              <p class="navbar_item_tree">вакансии</p>
            </div>
          </div>
          <div class="navbar_inner">
            <div class="navbar_content">
              <p class="navbar_item_foure">контакты</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "navbar",
};
</script>
<style lang="scss" scoped>
.navbar {
  width: 100%;
  height: 5rem;
  &_container {
    display: flex;
    width: 100%;
    height: 5rem;
    justify-content: center;
    align-items: center;
    background: #2f343a;
  }
  &_wrapper {
    display: flex;
    width: 1110px;
    height: 46px;
    align-items: center;
  }
  &_block_left {
    display: flex;
    width: 100%;
    height: 46px;
  }
  &_inner_start {
    display: flex;
    width: 170px;
    justify-content: flex-start;
  }
  &_inner_line {
    display: flex;
    width: 2px;
    margin-left: 1.5rem;
  }
  &_line {
    width: 2px;
    height: 46px;
    background: #fff;
  }

  &_row {
    display: flex;
    align-items: center;
  }
  &_title {
    display: flex;
    justify-content: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.05em;
    color: #ffffff;
  }
  &_map {
    width: 29px;
    height: 25px;
    margin-left: 1rem;
    background: url("../assets/img/block_header/placeholder.png");
    background-size: cover;
  }
  &_logo {
    display: flex;
    width: 160px;
    height: 100%;
    background: url("../assets/img/block_header/logo.png");
    background-size: cover;
  }
  &_inner {
    display: flex;
    width: 130px;
    justify-content: flex-end;
  }

  //Правый блок
  &_block_right {
    display: flex;
    justify-content: flex-end;
  }
  &_items {
    display: flex;
  }
  &_content {
    display: flex;
    width: 100px;
    text-align: center;
    justify-content: flex-end;
  }
  &_item_foure {
    width: 82px;
    height: 16px;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
  & &_item_tree {
    width: 82px;
    height: 16px;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
  &_item_two {
    width: 115px;
    height: 16px;
    overflow: hidden;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
  &_item_one {
    width: 83px;
    padding-right: 1rem;
    height: 16px;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
}
</style>
