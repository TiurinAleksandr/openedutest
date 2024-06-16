<script >

</script>

<template>
  <div class="wrapper">
    <div class="sidebar">
      <div class="logo">
        <a href="#">
          <img src="../src/assets/logo.png" alt="OpenEdu Logo">
        </a>
      </div>
      <ul class="menu">
        <li class="active">
          <img src="../src/assets/icons/home.svg" alt="Sleep">
          <span>Главная</span>
        </li>
        <li>
          <img src="../src/assets/icons/courses.svg" alt="Learn">
          <span>Курсы</span>
        </li>
        <li>
          <img src="../src/assets/icons/tasks.svg" alt="Train">
          <span>Задания</span>
        </li>
      </ul>
      <div class="buttons">
        <a href="#">
          <img src="../src/assets/icons/gotosite.svg" alt="Go To General Site">
          <span>Перейти на основной сайт</span>
        </a>
        <a href="#" class="tech-support">
          <img src="../src/assets/icons/phone.svg" alt="Help Me">
          <span>Связаться с техподдержкой</span>
        </a>
      </div>
    </div>


    <div class="content">
      <div class="face">
        <div class="title">
          <h1>Добро пожаловать<br><span class="color-violet">в OpenEdu</span></h1>
          <p class="subtitle">Достигайте своих целей с современной и доступной образовательной платформой</p>
        </div>
        <div class="lc-img">
          <img src="../src/assets/smart-boy.png" alt="Smart Boy">
        </div>
      </div>
      <div class="infoblock tariff">
        <div class="infoblock-header">
          <h2>Ваш тариф</h2>
          <p class="tariff-name color-violet">Начальный</p>
        </div>
      </div>
      <div class="infoblock courses-current">
        <div class="infoblock-header">
          <h2>Прохожу сейчас</h2>
          <a class="infoblock-button color-violet">Все курсы</a>
        </div>
        <div class="courses-list">
          <div class="course">Course</div>
          <div class="course">Course</div>
          <div class="course">Course</div>
        </div>
      </div>
      <div class="infoblock courses-ready">
        <div class="infoblock-header">
          <h2>Пройденные курсы</h2>
          <a class="infoblock-button color-violet">Все курсы</a>
        </div>
        <div class="courses-list">
          <div class="course">Course</div>
          <div class="course">Course</div>
          <div class="course">Course</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
/*родительский компонент*/
.wrapper {
  width: 100%;
  height: 100%;
  display: flex;
  background: linear-gradient(135deg, #F0E4ED 0%, #F1F7FB 100%);
}
/*компонент сайдбар*/
.sidebar {
  width: 300px;
  height: 100vh;
  background-color: #FFFFFF;
  display: flex;
  flex-direction: column;
  padding: 40px 30px;
  position: fixed;
}
.logo a {
  cursor: pointer;
}
.buttons {
  display: flex;
  flex-direction: column;
}
.buttons a {
  display: flex;
  align-items: center;
  padding: 15px;
  color: #78258D;
}
.menu {
  padding: 0;
  margin: 50px 0 450px;
}
.menu li {
  list-style: none;
  padding: 12px;
  margin: 8px 0;
  display: flex;
  flex-direction: row;
  align-items: center;
  cursor: pointer;
}
.menu li.active, .menu li:hover, .menu li:active {
  background-color: #EFEFFF;
  border-radius: 10px;
  color: #78258D;
}
.menu li.active img path {
  fill: #78258D;
}
.menu li img, .buttons a img {
  margin-right: 10px;
}
.tech-support {
  border: 1px solid #78258D;
  border-radius: 10px;
}




/*компонент контент*/
.content {
  width: 100%;
  padding: 0 90px;
  margin-left: 360px;
}
.color-violet {
  color: #78258D;
}
.infoblock {
  background-color: #F9F9F9;
  border-radius: 20px;
  /*box-shadow: 0 4px 10px 0 #F9F9F9;*/
  display: flex;
  flex-direction: column;
  margin: 40px 0;
  padding: 20px 40px;
}
.infoblock-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.infoblock h2 {
  color: #232323;
  font-size: 32px;
  font-weight: 900;
  margin: 0;
}
.infoblock-button {
  border-radius: 8px;
  border: 1px solid #78258D;
  padding: 12px 16px;
  font-weight: 600;
  cursor: pointer;
}
.courses-list {
  display: flex;
  padding: 30px 0 0;
}


/*лицевой блок*/
.face{
  display: flex;
  padding: 125px 110px;
  align-items: center;
}
.title {
  width: 60%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-right: 100px;
}
.title h1, .title span {
  font-size: 60px;
  font-weight: 900;
}
.subtitle {
  font-size: 20px;
  line-height: 35px;
  color: #828282;
  margin: 0;
}
.lc-img {
  width: 40%;
  display: flex;
  justify-content: center;
}
.lc-img img {
  width: 100%;
}


/*тариф*/
.tariff-name {
  font-size: 18px;
}

/*прохожу сейчас*/



/*пройденные курсы*/



</style>
