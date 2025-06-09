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
  gap: 40px;
  padding: 20px 0; /* 左右の余白を削除 */
}

.profile-image img {
  width: 300px; /* サイズを大きく */
  height: 300px; /* サイズを大きく */
  border-radius: 50%;
  object-fit: cover;
}

.about-title {
  text-decoration: underline;
}

.about-container {
  font-size: 30px;
  max-width: 600px;
  padding-left: 0; /* 左の余白を削除 */
}

/* スマホ対応 */
@media (max-width: 768px) {
  .profile-image img {
    width: 250px;
    height: 250px;
  }
  
  .about-wrapper {
    padding: 10px;
  }
}
</style>