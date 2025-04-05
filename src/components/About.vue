<template>
  <div id="section1">
  <div class="about-wrapper">
   <img class="about-img" src="/Users/tojouyuki/Downloads/programming_practice/tojo-portfolio/src/my profile用写真.jpg" alt="my profile用写真" >
    <div class="about-container">
      <h2 class="about-title">My profile</h2>
      <p class="about-title.name">名前　東條裕樹(トウジョウ　ユウキ)</p>
      <p class="about-title.age">年齢　20</p>
      <p class="about-title.uni">大学　駒澤大学</p>
      <p class="about-title.overview">概要　大学では英米文学を学んでいます。<br />
         プログラミングには２年生の春休みから独学で学び始めました。
         今現在は長期インターンに参加し、フロントエンドエンジニアとして働いています。<br />
        </p>
        <p class="sbout-title.hobbies">趣味 映画鑑賞、洋楽を聴くこと、読書</p>
    </div>
  </div>
</div>
  </template>

  <style>
  .about-wrapper {
  display: flex;
  align-items: center; 
  gap: 20px; 
}
.about-title{
  text-decoration: underline;
}
.about-img {
  margin-top: 40px;
  padding-left: 40px;
  width: 450px;
  height: 600px;
  object-fit: cover; 
}
.about-container {
  font-size: 30px;
  max-width: 600px;
  padding-left: 60px;
}

  </style>