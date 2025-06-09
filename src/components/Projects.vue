<template>
  <div id="section2">
    <h2 class="project-title">Skills</h2>
    <div class="project-language">
      <span>HTML/CSS</span>
      <span>Javascript</span>
      <span>TypeScript</span>
      <span>React.js</span>
      <span>Vue.js</span>
      <span>gas.js</span>
      <span>Next.js</span>
    </div>
  </div>
</template>

<style>
.project-title {
  padding-top: 20px;
  font-size: 45px;
  text-align: center;
  text-decoration: underline 7px;
}

.project-language {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
  padding: 50px;
  margin: 0 auto;
  max-width: 800px;
}

.project-language span {
  background-color: #f0f0f0;
  padding: 10px 20px;
  border-radius: 25px;
  font-size: 24px;
  color: #333;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}

.project-language span:hover {
  transform: translateY(-2px);
}

@media (max-width: 768px) {
  .project-language {
    padding: 30px;
    gap: 15px;
  }

  .project-language span {
    font-size: 18px;
    padding: 8px 16px;
  }
}
</style>