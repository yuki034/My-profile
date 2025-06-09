<script setup>
import myProfileImage from '@/assets/my-profile.jpg'
</script>
<template>
  <div id="section1">
    <div class="about-wrapper">
      <div class="profile-image">
        <img :src="myProfileImage" alt="プロフィール画像" />
      </div>
      <div class="about-container">
        <h2 class="about-title">My profile</h2>
        <p class="about-title-name">名前 東條裕樹(トウジョウ ユウキ)</p>
        <p class="about-title-age">年齢 21</p>
        <p class="about-title-uni">大学 駒澤大学</p>
        <p class="about-title-overview">概要 大学では英米文学を学んでいます。<br />
          プログラミングには２年生の春休みから独学で学び始めました。
          今現在は長期インターンに参加し、フロントエンドエンジニアとして働いています。<br />
        </p>
        <p class="about-title-hobbies">趣味 映画鑑賞、洋楽を聴くこと</p>
      </div>
    </div>
  </div>
</template>

<style>
.about-wrapper {
  display: flex;
  align-items: center;
  gap: 20px;
  padding: 20px;
}

.profile-image img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
}

.about-title {
  text-decoration: underline;
}

.about-container {
  font-size: 30px;
  max-width: 600px;
  padding-left: 60px;
}

/* レスポンシブ対応 */
@media (max-width: 768px) {
  .about-wrapper {
    flex-direction: column;
    text-align: center;
  }

  .profile-image img {
    width: 150px;
    height: 150px;
    margin-bottom: 20px;
  }
}
</style>