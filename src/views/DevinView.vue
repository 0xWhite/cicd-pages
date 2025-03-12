<script setup lang="ts">
</script>

<template>
  <div class="devin-container">
    <div class="hero-section">
      <h1>Devin</h1>
      <p class="tagline">世界上第一个AI软件工程师</p>
      <div class="hero-description">
        <p>Devin能够解决复杂的软件工程任务，从构建和部署全栈应用程序到调试和修复问题。</p>
      </div>
      <div class="cta-buttons">
        <button class="primary-button">加入等待列表</button>
        <button class="secondary-button">了解更多</button>
      </div>
    </div>

    <div class="features-section">
      <div class="feature-card">
        <div class="feature-icon">🚀</div>
        <h3>全栈开发</h3>
        <p>Devin可以构建和部署完整的应用程序，从前端到后端，包括数据库和API。</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">🔍</div>
        <h3>调试专家</h3>
        <p>Devin能够识别和修复复杂的软件问题，提供详细的错误分析和解决方案。</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">🤝</div>
        <h3>协作无间</h3>
        <p>与人类工程师无缝协作，理解需求，提供建议，并实现功能。</p>
      </div>
    </div>

    <div class="demo-section">
      <h2>观看Devin如何工作</h2>
      <div class="video-container">
        <div class="video-placeholder">
          <span>视频演示</span>
        </div>
      </div>
    </div>

    <div class="testimonials-section">
      <h2>用户评价</h2>
      <div class="testimonial-cards">
        <div class="testimonial-card">
          <p>"Devin彻底改变了我们的开发流程，将项目交付时间缩短了50%。"</p>
          <div class="testimonial-author">- 张三，技术总监</div>
        </div>
        <div class="testimonial-card">
          <p>"作为一名初级开发者，Devin帮助我快速提升技能，解决了许多我无法独自解决的问题。"</p>
          <div class="testimonial-author">- 李四，前端开发者</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.devin-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  color: #333;
}

.hero-section {
  text-align: center;
  padding: 4rem 0;
}

.hero-section h1 {
  font-size: 4rem;
  margin-bottom: 1rem;
  background: linear-gradient(90deg, #4776E6, #8E54E9);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.tagline {
  font-size: 1.8rem;
  margin-bottom: 2rem;
  color: #555;
}

.hero-description {
  max-width: 700px;
  margin: 0 auto 2rem;
  font-size: 1.2rem;
  line-height: 1.6;
}

.cta-buttons {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-top: 2rem;
}

.primary-button, .secondary-button {
  padding: 0.8rem 2rem;
  font-size: 1rem;
  border-radius: 30px;
  cursor: pointer;
  font-weight: bold;
  transition: all 0.3s ease;
}

.primary-button {
  background: linear-gradient(90deg, #4776E6, #8E54E9);
  color: white;
  border: none;
}

.secondary-button {
  background: transparent;
  color: #4776E6;
  border: 2px solid #4776E6;
}

.primary-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(71, 118, 230, 0.2);
}

.secondary-button:hover {
  background-color: rgba(71, 118, 230, 0.1);
}

.features-section {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 4rem 0;
}

.feature-card {
  background-color: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
  transition: transform 0.3s ease;
}

.feature-card:hover {
  transform: translateY(-10px);
}

.feature-icon {
  font-size: 2.5rem;
  margin-bottom: 1rem;
}

.feature-card h3 {
  margin-bottom: 1rem;
  color: #4776E6;
}

.demo-section {
  text-align: center;
  margin: 4rem 0;
}

.demo-section h2 {
  margin-bottom: 2rem;
  font-size: 2rem;
}

.video-container {
  max-width: 800px;
  margin: 0 auto;
}

.video-placeholder {
  background-color: #f0f0f0;
  aspect-ratio: 16/9;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
  color: #888;
  border-radius: 10px;
}

.testimonials-section {
  margin: 4rem 0;
  text-align: center;
}

.testimonials-section h2 {
  margin-bottom: 2rem;
  font-size: 2rem;
}

.testimonial-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.testimonial-card {
  background-color: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
}

.testimonial-card p {
  font-style: italic;
  margin-bottom: 1rem;
  line-height: 1.6;
}

.testimonial-author {
  font-weight: bold;
  color: #4776E6;
}

@media (max-width: 768px) {
  .hero-section h1 {
    font-size: 3rem;
  }

  .tagline {
    font-size: 1.4rem;
  }

  .cta-buttons {
    flex-direction: column;
    align-items: center;
  }

  .primary-button, .secondary-button {
    width: 100%;
    max-width: 300px;
  }
}
</style>
