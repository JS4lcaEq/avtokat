<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'

</script>

<template>
<header>
      <h1>AvtoKat<span>UZ</span></h1>
      <div class="switch long">
        <label>
          <span>Страна:</span>
          <select>
            <option>Узбекистан</option>
            <option>Россия</option>
          </select>
        </label>

      </div>
      <div class="switch">
        <label>
          <span>Язык:</span>
          <select>
            <option>Узбекский</option>
            <option>Русский</option>
          </select>
        </label>
      </div>
      <div>
        <a href="#">Регистрация/вход</a>
      </div>
    </header>
    <main>
      <section id="buy">
        <div class="black-box">
          <h3>Найдите нужное авто</h3>
          <h2>КУПИТЬ</h2>

          <div class="content-line">
            <p>Если вы знаете код <br />нужного автомобиля, <br />введите его в поле</p>
            <h4>AKHD</h4>
            <input type="text" class="long" placeholder="Введите код формата ABCD1234" />
            <button>Найти</button>
          </div>

        </div>
      </section>
      <section id="sell">
        <div class="black-box">
          <h3>Оцифруйте свое авто</h3>
          <h2>ПРОДАТЬ</h2>
          <div class="content-line">
            <p>Оцифруйте свой автомобиль, <br />загрузи его в наш каталог <br />распечатай удобный стикер <br />с
              QR-кодом на авто</p>
            <ul class="long">
              <li>Цена контакты и QR-код</li>
              <li>Ссылка и фото для покупателей</li>
              <li>Описание по 400+ параметрам</li>
              <li>Возможность сравнения</li>
            </ul>
            <button class="button-border">Будет вот так</button>
            <button class="long-button">Заявка в телеграмм </button>
          </div>
        </div>
      </section>
      <section id="dill">
        <div class="black-box">
          <h3>Улучшите процесс продаж</h3>
          <h2>ДИЛЕРАМ</h2>
          <div class="content-line">
            <p>Оцифруйте свой автомобиль, <br />загрузи его в наш каталог <br />распечатай удобный стикер <br />с
              QR-кодом на авто</p>
            <ul class="long">
              <li>15+ лет на рынке</li>
              <li>20+ брендов <br />являются нашими партнерами</li>
            </ul>
            <button class="button-border">О нас</button>
            <button class="long-button">Заявка в телеграмм </button>
          </div>
        </div>
      </section>
      <!-- <section id="debug">
        <div class="black-box">
          <h3>Шрифтовое решение</h3>
          <h2>Техническая секция</h2>
          <p class="mr">Продать/Купить MartianMono-Regular</p>
          <p class="mb">Продать/Купить MartianMono-Bold</p>
          <p class="mcr">Продать/Купить MartianMono_Condensed-Regular</p>
          <p class="mcl">Продать/Купить MartianMono_Condensed-Light</p>
          <p class="mcb">Продать/Купить MartianMono_Condensed-Bold</p>
        </div>
      </section> -->
    </main>
    <footer>
      <div class="long">
        <a href="#">О нас</a>
        <p>&nbsp;</p>
        <p>2023, AvtoCat</p>
        <p>All Rigths reserved</p>
      </div>
      <div>
        <!-- <a href="#" style="margin-bottom: 10px;" class="ae"></a> -->
        <!-- <a href="#"><img src="./assets/AvtoKatKZ_logo_white_x200.png" width="150"/></a> -->
      </div>
  
        <!-- <a href="#" style="margin-left: 50px;"><img src="./assets/AvtoKatUZ_logo_white_x200.png" style="width: 200px;"/></a> -->
  
      
    </footer>
</template>

<style scoped>

</style>
