<template>
  <div class="footer">
    <div class="footer_container">
      <div class="footer_content">
        <div class="footer_item">
          <div class="footer_logo"></div>
        </div>
        <div class="footer_item_contact">
          <p class="footer_adress">
            123456, Санкт-Петербург, Невский пр-кт 127
          </p>
          <p class="footer_email">sales@log.ru</p>
        </div>
        <div class="footer_item_figure">
          <p class="footer_number_phone">+7 (812) 344-56-65</p>
          <p class="footer_number_phone">+7 (812) 344-56-65</p>
        </div>
        <div class="footer_item_copyright">
          <p class="footer_copy">Разработано - D-E-N.ru</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style lang="scss" scoped>
.footer {
  width: 100%;
  height: 161px;
  background: #c8a35f;
  &_container {
    display: flex;
    width: 100%;
    justify-content: center;
    align-items: center;
  }
  &_content {
    display: flex;
    width: 1110px;
    height: 161px;
  }
  &_item {
    display: flex;
    width: 10rem;
    height: 161px;
    align-items: center;
  }
  &_logo {
    width: 160px;
    height: 46px;
    background: url("../assets/img/block_footer/logo.png");
    background-size: cover;
  }
  &_item_contact {
    display: flex;
    width: 24rem;
    height: 161px;
    justify-content: center;
    flex-direction: column;
    padding-left: 3rem;
  }
  &_adress {
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #f2f2f2;
    opacity: 0.8;
  }
  &_email {
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #2f343a;
  }
  &_item_figure {
    display: flex;
    width: 13rem;
    height: 161px;
    justify-content: center;
    flex-direction: column;
  }
  &_number_phone {
    display: flex;
    justify-content: center;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    color: #f2f2f2;
  }
  &_item_copyright {
    display: flex;
    width: 22rem;
    height: 161px;
    align-items: center;
  }
  &_copy {
    display: flex;
    justify-content: flex-end;
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 16px;
    text-align: right;
    text-decoration-line: underline;
    color: #2f343a;
  }
}
</style>
