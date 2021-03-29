<template>
  <div class="service">
    <div class="service_wrap">
      <div class="service_block_header">
        <div class="service_block_line">
          <div class="service_line"></div>
        </div>
        <div class="service_block_title">
          <div class="service_title">Услуги</div>
        </div>
      </div>
    </div>
    <div class="service_container">
      <div class="service_wrapper">
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
        <div class="service_inner">
          <div class="service_inner_icon">
            <div class="service_radius_icon">
              <div class="service_icon"></div>
              <div class="service_icon_hover"></div>
            </div>
          </div>
          <p class="service_text">авиаперевозки</p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Service",
};
</script>

<style lang="scss" scoped>
.service {
  width: 100%;
  height: 900px;
  background: #2f343a;
  position: relative;
  &_wrap {
    display: flex;
    width: 100%;
    height: 12rem;
    justify-content: center;
    align-items: flex-end;
  }
  &_block_header {
    display: flex;
    width: 1110px;
    flex-direction: column;
  }
  &_block_line {
    display: flex;
    width: 1110px;
    height: 1rem;
  }
  &_line {
    display: flex;
    width: 90px;
    height: 6px;
    background: #c8a35f;
  }
  &_block_title {
    display: flex;
    width: 1110px;
    height: 5rem;
    align-items: center;
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
  /// второй блок

  &_container {
    display: flex;
    width: 100%;
    justify-content: center;
    margin-top: 2rem;
  }
  &_wrapper {
    display: flex;
    width: 1200px;
    height: 364px;
    flex-wrap: wrap;
    justify-content: center;
  }
  &_inner {
    display: flex;
    width: 276px;
    height: 180px;
    margin: 1px;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    // background: #393f47;
    // background-color: #c8a35f;
  }
  &_radius_icon {
    display: flex;
    width: 4rem;
    justify-content: center;
  }
  ///Анимация
  &_inner,
  :hover {
    background-color: #c8a35f;
    transition: 0.9s;
  }
  &_wrap,
  &_block_header,
  :hover {
    background: #2f343a;
  }
  &_radius_icon:hover,
  ::before {
    width: 70px;
    height: 70px;
    position: absolute;
    transform: translateY(-1rem);
    background: #fff;
    border-radius: 50%;
  }
  &_icon_hover:hover,
  :focus {
    content: "";
    display: flex;
    position: absolute;
    margin-top: 1.1rem;
    width: 30px;
    height: 30px;
    background: url("../assets/img/block_service/Vector (1).png");
    background-size: cover;
  }
  &_icon_hover {
    width: 30px;
    height: 30px;
    position: absolute;
  }
  &_inner_icon {
    display: flex;
    width: 5rem;
    height: 4rem;
    align-content: center;
    justify-content: center;
  }
  &_icon {
    display: flex;
    width: 30px;
    height: 30px;
    background: url("../assets/img/block_service/Vector.png");
    background-size: cover;
  }
  &_text {
    font-family: "Roboto";
    font-style: normal;
    font-weight: bold;
    font-size: 18px;
    line-height: 22px;
    text-align: center;
    letter-spacing: 0.05em;
    text-transform: uppercase;
    color: #ffffff;
  }
}
.service_inner,
:hover {
  background-color: #c8a35f;
  transition: 0.9s;
}
.service_wrap,
.service_block_header,
:hover {
  background: #2f343a;
}
</style>
