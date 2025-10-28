<template>
  <main class="page">
    <!-- 메인 인사 영역 -->
    <section class="hero">
      <div class="moon">🌕</div>
      <h1 class="title">풍성한 한가위 보내세요</h1>
      <p class="subtitle">
        가족, 친구, 그리고 맛있는 음식과 함께
        따뜻하고 편안한 추석 보내세요 🌾
      </p>
    </section>

    <!-- 간단 소개 영역 -->
    <section class="message-box">
      <h2 class="section-heading">한가위(추석)란?</h2>
      <p class="message-text">
        한 해 수확에 감사하고 서로의 안부를 전하는 우리나라의 큰 명절입니다.
        잘 먹고, 잘 쉬고, 좋은 마음 나누는 날이에요.
      </p>
    </section>

    <!-- 인사 문구 -->
    <section class="wish-box">
      <p class="wish-line">보름달처럼 마음도 꽉 찬 연휴 되세요 😊</p>
      <p class="wish-line small">행복 가득, 걱정 비우기, 휴식 필수!</p>
    </section>

    <footer class="footer">
      <small>© 2025 한가위 인사 페이지</small>
    </footer>
  </main>
</template>

<style scoped>
/* 페이지 전체 박스 */
.page {
  min-height: 100vh;
  background: radial-gradient(circle at 50% 30%, #fffbe0 0%, #ffefb3 40%, #f9d17a 70%, #b9802b 100%);
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem 1rem 4rem;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
  "Noto Sans KR", sans-serif;
  color: #2a1a00;
}

/* 상단 인사 영역 */
.hero {
  text-align: center;
  background: rgba(255, 253, 245, 0.7);
  backdrop-filter: blur(4px);
  border-radius: 1rem;
  padding: 2rem 1.5rem;
  width: 100%;
  max-width: 480px;
  box-shadow: 0 24px 40px rgba(0, 0, 0, 0.15);
  border: 1px solid rgba(255, 255, 255, 0.7);
}

/* 달 아이콘 */
.moon {
  font-size: 3rem;
  line-height: 1;
  margin-bottom: 0.5rem;
  text-shadow: 0 0 20px rgba(255, 255, 200, 0.8),
  0 0 40px rgba(255, 255, 180, 0.4);
}

/* 큰 타이틀 */
.title {
  font-size: 1.6rem;
  font-weight: 600;
  margin: 0 0 0.5rem;
  color: #3a2a00;
}

/* 부제 */
.subtitle {
  font-size: 0.95rem;
  line-height: 1.5;
  color: #4a3a08;
  margin: 0;
}

/* 추석이 뭔지 설명 박스 */
.message-box {
  margin-top: 2rem;
  background: rgba(255, 255, 255, 0.6);
  border: 1px solid rgba(255, 255, 255, 0.8);
  border-radius: 1rem;
  padding: 1.25rem 1rem 1rem;
  width: 100%;
  max-width: 480px;
  box-shadow: 0 16px 28px rgba(0, 0, 0, 0.12);
}

.section-heading {
  font-size: 1rem;
  font-weight: 600;
  color: #3a2a00;
  margin: 0 0 0.5rem;
}

.message-text {
  margin: 0;
  font-size: 0.9rem;
  color: #4a4022;
  line-height: 1.5;
}

/* 인사 문구 강조 박스 */
.wish-box {
  margin-top: 2rem;
  background: rgba(58, 42, 0, 0.8);
  color: #fffbe9;
  border-radius: 0.75rem;
  padding: 1rem 1rem 1.2rem;
  width: 100%;
  max-width: 480px;
  text-align: center;
  box-shadow: 0 20px 32px rgba(0, 0, 0, 0.4);
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.wish-line {
  font-size: 1rem;
  font-weight: 500;
  margin: 0 0 0.4rem;
  line-height: 1.4;
}

.wish-line.small {
  font-size: 0.8rem;
  font-weight: 400;
  opacity: 0.9;
  margin: 0;
}

/* 푸터 */
.footer {
  margin-top: auto;
  font-size: 0.75rem;
  color: rgba(42, 26, 0, 0.7);
  text-align: center;
  padding-top: 3rem;
}
</style>