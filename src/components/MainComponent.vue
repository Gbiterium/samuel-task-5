<template>
    <div class="main">
    <div class="profile">
    <img src="../assets/f.jpg" class="image" height="250px">
    <div class="profile-content">
      <p>About Me</p>
      <b><h1>Adegbite Samuel Adetona</h1></b>
          <p><i class="glyphicon glyphicon-tasks"></i> Web Developer, Tech geek</p>
          <p><i class="glyphicon glyphicon-envelope"></i> samueladetona56@gmail.com</p>
          <p><i class="glyphicon glyphicon-heart"></i> Knowing more about programming</p>
          <p>
          <a href="#"><i class="fa fa-twitter"></i></a>
          <a href="#"><i class="fa fa-instagram"></i></a>
          <a href="#"><i class="fa fa-facebook"></i></a>
          </p>
    </div>
    </div>
    <div class="profile-inner-content">
      <p>My name Adegbite Samuel Adetona, am a computer programmer, I love to code 
        and learn more about programmings. Aside that, I play online games. I'm cool, loving and friendly.
      </p>
      <table width="100%">
        <tr>
        <th>Skills</th>
        <th></th>
        </tr>
        <tr>
          <td>Front End</td>
          <td>Html, CSS, Javscript, Wordpress</td>
        </tr>
        <tr>
          <td>Back End</td>
          <td>PHP, Mysql</td>
        </tr>
        <tr>
          <td>Graphics Design</td>
          <td>CorelDraw</td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {
 
  }

</script>

<style scoped>
.main{
  background: #333;
  line-height: 2;
  padding: 3em;
  border-radius: 10px;
  color:white;
}
.profile{
  display: flex;
  align-items:center; 
  background: #222;
  border-radius: 10px; 
}
.image{
  border: 1px solid rgba(255,255,255,0.4);
  border-radius: 50%;
  margin: 10px 30px;
}
.profile-content p{
  margin: 0;
  color: rgb(210,210,210);
  cursor: pointer;
}
.profile-content h2{
  margin: 0;
}
.profile-inner-content{
  margin: 30px auto;
}
table{
  border-spacing: 0px;
  margin: 50px auto;
}
table tr th, tr td{
  border: 1px solid white;
  border-top: none;
  padding: 10px;
  text-align: center;
  border-left: none;
}
table tr th, tr td:last-child{
  border-right: none;
}
a{
  padding: 10px;
  color:white;
}
</style>
