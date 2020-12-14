<template>
  <div id="app">

    <div class="section1">
      <div class="content">
      <h1>Закись азота Санкт-Петербург</h1>
      <a href="tel:+79202636863" class="button b1">Заказать</a>
      </div>
    </div>

    <div class="section2">
      <div class="content">
        <el-row :gutter="40">
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                  <img :src="require('~/assets/images/ballon.jpg')" alt="Ballon" width="200px" style="padding-top: 35px">
                </div>
                <h2>Баллон 1.5 л</h2>
                <p class="price">1500 руб</p>
                <a href="tel:+79202636863" class="button b1">Заказать</a>
              </div>
            </div>

          </el-col>
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                  <img :src="require('~/assets/images/ballon.jpg')" alt="Ballon" width="230px">
                </div>
                <h2>Баллон 1.5 л</h2>
                <p class="price">1500 руб</p>
                <a href="tel:+79202636863" class="button b1">Заказать</a>
              </div>
            </div>

          </el-col>
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                <img :src="require('~/assets/images/ballon.jpg')" alt="Ballon" width="260px" style="position:relative;top:-40px">
                </div>
                <h2>Баллон 1.5 л</h2>
                <p class="price">1500 руб</p>
                <a href="tel:+79202636863" class="button b1">Заказать</a>
              </div>
            </div>

          </el-col>
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                  <img :src="require('~/assets/images/ballon10.jpg')" alt="Ballon" width="140px" style="padding-top:40px">
                </div>
                <h2>Баллон 1.5 л</h2>
                <p class="price">1500 руб</p>
                <a href="tel:+79202636863" class="button b1">Заказать</a>
              </div>
            </div>

          </el-col>
        </el-row>
      </div>
    </div>

    <div class="section4">
      <div class="content">
        <h2>Сертификаты</h2>
        <el-row :gutter="50">
          <el-col :md="8" :sm="12">
            <div class="s">
              <el-image 
                style="width:100%"
                :src="require('~/assets/images/s1.jpg')"
                :preview-src-list="srcList">
              </el-image>
            </div>
          </el-col>
          <el-col :md="8" :sm="12">
            <div class="s">
              <el-image 
                style="width:100%"
                :src="require('~/assets/images/s2.jpg')"
                :preview-src-list="srcList">
              </el-image>
            </div>
          </el-col>
          <el-col :md="8" :sm="12">
            <div class="s">
              <el-image 
                style="width:100%"
                :src="require('~/assets/images/s2.jpg')"
                :preview-src-list="srcList">
              </el-image>
            </div>
          </el-col>
        </el-row>
      </div>
    </div>

    <div class="section3">
      <div class="content">
        <el-row :gutter="140">
          <el-col :md="12">
            <div class="grid-content bg-purple">
              <h2>Доставка</h2>
              <p>
                Доставка пищевой закиси азота  от компании «Формула Газа» производится по всей 
                Москве в пределах МКАД в течение 30 минут ежедневно и круглосуточно, стоимость 
                доставки составляет 500 рублей, также возможен самовывоз у ближайшего курьера. 
                Данный вид доставки относится к экспресс-варианту, котрый предлагают далеко не 
                многие компании. В случае, если Вы оказались недовольны обслуживанием, качеством 
                товара, временем доставки или еще какими-либо нюансами работы с нашей компанией - 
                Вы можете написать об этом напрямую руководству с помощью данной формы или заполнить 
                ее внизу страницы. На забудьте указать дату и время заказа, описать суть проблемы 
                и оставить контактную информацию. Внимание! Доставка баллонов осуществляется до 
                подъезда, поднятие на этаж оговаривается отдельно с курьером на месте или оператором 
                при заказе!
              </p>   
            </div>
          </el-col>
          <el-col :md="12">
            <div class="grid-content bg-purple-light">
              <h2>Контакты</h2>
              <p>Телефон:</p>
              <h3>+792323232323</h3>
              <br>
              <p>Telegram:</p>
              <h3>@zakis.ru</h3>
              <br>
              <p>E-mail:</p>
              <h3>zakisazota@spb.ru</h3>
            </div>
          </el-col>
        </el-row>
      </div>
    </div>








  </div>
</template>

<script>
  export default {
    name: 'App',
    components: {
  
    },
    data: () => ({
      srcList:[
        require('assets/images/s1.jpg'),
        require('assets/images/s2.jpg'),
        require('assets/images/s2.jpg'),
      ]
    }),
    computed: {
      
    },
    async updated() {
      
    },
    methods: {
    
    }
  }
</script>

<style lang='scss'>
  @font-face {
    font-family: 'Montserrat-Bold';
    src: url(assets/fonts/Montserrat-Bold.ttf);
  }
   @font-face {
    font-family: 'Montserrat-ExtraBold';
    src: url(assets/fonts/Montserrat-ExtraBold.ttf);
  }
   @font-face {
    font-family: 'Montserrat-Light';
    src: url(assets/fonts/Montserrat-Light.ttf);
  }
  @font-face {
    font-family: 'Montserrat-Regular';
    src: url(assets/fonts/Montserrat-Regular.ttf);
  }
  body {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Montserrat-Regular';
  }
  body * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }


  h1 {
    font-family: 'Montserrat-ExtraBold';
    font-size: 54px;
  }
  h2 {
    font-family: 'Montserrat-Bold';
    font-size: 32px;
  }
  a {
    text-decoration: none;
    font-family: 'Montserrat-Light';
  }
  .button {
    color: white;
    padding: 15px 40px;
    background: linear-gradient(to right,#3957ff,#0020d4);
    border-radius: 7px;
    display: inline-block;
    margin-bottom: 10px;
  }
  .content {
    max-width: 1200px;
    margin: 0 auto;
  }


  .section1 {
    max-width: 100%;
    background: url('assets/images/bg2.jpg');
    padding: 300px 0px;
    color: white;
    text-align: center;
    background-size:cover;
    box-shadow:inset 0 0 0 2000px rgba(3, 1, 8, 0.37);
  }
  .section1 h1 {
    padding: 0 0 50px 0;
  }

  .section2 {
    overflow: hidden;
    background: #f3f3f3;
    padding: 80px 10px;

    .card{
      padding: 20px 0;
    }

    .grid-content {
      text-align: center;
      background: #ffffff;
      border-radius: 10px;
      overflow: hidden;
      padding-bottom: 20px;
    }

    h2 {
      font-size: 24px;
    }
    
    .price {
      padding-bottom: 20px;
      font-family: 'Montserrat-Light';
      font-size: 20px;
    }

    .img {
      height:   451px;
    }
  }

  


  .section3 {
    max-width: 100%;
    background: url('assets/images/bg2.jpg');
    padding: 150px 10px;
    color: white;

    overflow: hidden;
  
    background-size:cover;
    box-shadow:inset 0 0 0 2000px rgba(3, 1, 8, 0.747);

    .grid-content{
      padding: 20px;
    }
  }
  .section3 h2 {
    padding-bottom: 20px;
  }


  @media screen and  (max-width: 564px) {
    h1 {
      font-size: 32px;
    }

  }

  .section4 {
    padding: 80px 0;

    h2{
      text-align: center;
    }

    .s{
      padding: 30px 0;
    }
  }
</style>