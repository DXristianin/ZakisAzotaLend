<template>
  <div id="app">


    <div class="section1">
      <div class="header">
        <div class="content">
          <p>
            Zakis-spb
          </p>
          <p>
            <b><a href="tel:+7(965)-011-51-11">+7(965)-011-51-11</a></b>
          </p>
        </div>
      </div>
      <div class="content">
      <h1>Закись азота Санкт-Петербург</h1>
      <a href="tel:+7(965)-011-51-11" class="button b1">Заказать</a>
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
                <p>
                  Пищевая закись азота
                  
                </p>
                
                <h2>1.5 л</h2>
                <br>
                <p class="price">
                  1300 руб     
                </p>
                
                <a href="tel:+7(965)-011-51-11" class="button b1">Заказать</a>
                <span class="zalog">Залог 500 руб</span>
              </div>
            </div>

          </el-col>
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                  <img :src="require('~/assets/images/ballon.jpg')" alt="Ballon" width="230px">
                </div>
                <p>
                  Пищевая закись азота
                  
                </p>
                
                <h2>2.5 л</h2>
                <br>
                <p class="price">
                  2200 руб     
                </p>
                
                <a href="tel:+7(965)-011-51-11" class="button b1">Заказать</a>
                <span class="zalog">Залог 1000 руб</span>
              </div>
            </div>

          </el-col>
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                <img :src="require('~/assets/images/ballon.jpg')" alt="Ballon" width="260px" style="position:relative;top:-40px">
                </div>
                <p>
                  Пищевая закись азота
                  
                </p>
                
                <h2>5 л</h2>
                <br>
                <p class="price">
                  3300 руб     
                </p>
                
                <a href="tel:+7(965)-011-51-11" class="button b1">Заказать</a>
                <span class="zalog">Залог 2000 руб</span>
              </div>
            </div>

          </el-col>
          <el-col :md="6" :sm="12">

            <div class="card">
              <div class="grid-content bg-purple">
                <div class="img">
                  <img :src="require('~/assets/images/ballon10.jpg')" alt="Ballon" width="140px" style="padding-top:40px">
                </div>
                <p>
                  Пищевая закись азота
                  
                </p>
                
                <h2>10 л</h2>
                <br>
                <p class="price">
                  5000 руб     
                </p>
                
                <a href="tel:+7(965)-011-51-11" class="button b1">Заказать</a>
                <span class="zalog">Залог 2500 руб</span>
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
          <el-col :md="6" :sm="6" :xs="6">
            <div class="s">
              <el-image 
                style="width:100%"
                :src="require('~/assets/images/s11.jpg')"
                :preview-src-list="srcList">
              </el-image>
            </div>
          </el-col>
          <el-col :md="6" :sm="6" :xs="6">
            <div class="s">
              <el-image 
                style="width:100%"
                :src="require('~/assets/images/s22.jpg')"
                :preview-src-list="srcList">
              </el-image>
            </div>
          </el-col>
          <el-col :md="6" :sm="6" :xs="6">
            <div class="s">
              <el-image 
                style="width:100%"
                :src="require('~/assets/images/s33.jpg')"
                :preview-src-list="srcList">
              </el-image>
            </div>
          </el-col>
          <el-col :md="6" :sm="6" :xs="6">
          <div class="s">
            <el-image 
              style="width:100%"
              :src="require('~/assets/images/s44.jpg')"
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
                Наша компания доставляет пищевую закись азота по Санкт-Петербургу и Ленинградской области. 
                <br>
                
                У нас имеются все сертификаты качества и необходимые документы. 
                <br>
                <br>
                Доставка по СПб происходит в течении 1 часа.
                <br>
                Доставка за КАД и в Ленинградскую область оговаривается отдельно с оператором.
                <br>
                <br>
                Обьёмы баллонов с закисью азота : 
                <br>
                - 1.5л
                <br>
                - 2.5л
                <br>
                - 5л
                <br>
                - 10л
                <br>
                <br>
                <br>

                Мы продаём только пищевую закись азота!
                <br>
                <br>
                Звоните, и мы ответим на все ваши вопросы!
                <br>
                Тел. : <a href="tel:+7(965)-011-51-11">+7(965)-011-51-11</a>
              </p>   
            </div>
          </el-col>
          <el-col :md="12">
            <div class="grid-content bg-purple-light">
              <h2>Контакты</h2>
              <p>Телефон:</p>
              <h3><a href="tel:+7(965)-011-51-11">+7(965)-011-51-11</a></h3>
              <br>
              <p>E-mail:</p>
              <h3><a href="mailto:zakis-spb@yandex.ru">zakis-spb@yandex.ru</a></h3>
              <br>
              <p>Режим работы : круглосуточно 24/7</p>
            </div>
          </el-col>
        </el-row>
      </div>
      
    </div>
<div class="copyright">
  <p>
    © Zakis-azota 2020
  </p>
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
        require('assets/images/s3.jpg'),
        require('assets/images/s4.jpg'),
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


  .header {
    background: rgba(0, 0, 0, 0.541);
    padding: 30px 10px;
    overflow: hidden;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;

    p {
      display: inline-block;
      color: white;

    }

    p:first-child {
      float: left;
      font-family: 'Montserrat-Light';
      font-size: 20px;
      text-transform: uppercase;
    }

    p:last-child {
      float: right;
      
    }

    a {
      color: white;
      line-height: 24px;
      position: relative;
      top: 1px;
    }
  }

  .section1 {
    max-width: 100%;
    background: url('assets/images/bg2.jpg');
    padding: 0 0 0px 0px;
    color: white;
    text-align: center;
    background-size:cover;
    box-shadow:inset 0 0 0 2000px rgba(3, 1, 8, 0.37);
    height: 100vh;
    display: flex;
 justify-content: center;
    position: relative;
 
    .content {
       align-self: center;
    }
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
      font-size: 22px;
    }

    .zalog {
      font-size: 16px;
      display: block;
      color: rgb(155, 155, 155);
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

    a {
      color: white;
    }
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
    overflow: hidden;

    h2{
      text-align: center;
    }

    .s{
      padding: 30px 0;
    }
  }

  .copyright {
    text-align: center;
    background: black;
    color: white;
    padding: 12px 0px;
  }
</style>