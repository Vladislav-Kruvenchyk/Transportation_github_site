<template>
  <div class="header">
    <div class="header_container">
      <div class="header_wrapper">
        <div class="header_items">
          <ul class="header_inner">
            <li class="header_language_ru">РУС</li>
            <li class="header_language_eng">ENG</li>
            <li class="header_language_fr">FR</li>
          </ul>
          <p class="header_list_figure">8 (800) 123-45-67</p>
          <p class="header_list_email">sales@log.ru</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>
<style lang="scss" scoped>
.header {
  width: 100%;
  height: 45px;
  background: #c8a35f;
  &_container {
    display: flex;
    width: 100%;
    height: 45px;
    justify-content: center;
    align-items: center;
  }
  &_wrapper {
    display: flex;
    width: 1110px;
  }
  &_items {
    display: flex;
    width: 100%;
    justify-content: center;
  }
  &_inner {
    display: flex;
  }
  &_language_ru {
    width: 35px;
  }
  &_language_eng {
    width: 35px;
  }
  &_language_fr {
    width: 35px;
  }
  &_language_ru:hover,
  &_language_fr:hover,
  &_language_eng:hover {
    color: rgb(255, 255, 255);
    opacity: 0.5;
    transition: 0.5s;
  }

  &_list_figure {
    display: flex;
    justify-content: center;
  }
  &_list_email {
    display: flex;
    justify-content: flex-end;
  }
  &_inner,
  &_list_figure,
  &_list_email {
    font-family: "Roboto";
    font-style: normal;
    font-weight: normal;
    font-size: 12px;
    line-height: 14px;
    color: #ffffff;
  }
}
</style>
