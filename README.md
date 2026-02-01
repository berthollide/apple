<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>이웃집 사과</title>
  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, 'Apple SD Gothic Neo', 'Noto Sans KR', sans-serif;
      background: #faf9f7;
      color: #222;
      line-height: 1.6;
    }
    section {
      min-height: 100vh;
      padding: 64px 24px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .hero {
      background: #eee;
      text-align: center;
    }
    .hero h1 {
      font-size: 28px;
      font-weight: 600;
      margin-bottom: 12px;
    }
    .hero p {
      font-size: 16px;
      color: #555;
    }
    .text {
      max-width: 520px;
      margin: 0 auto;
      font-size: 16px;
    }
    .brand {
      margin-top: 40px;
      font-size: 14px;
      color: #777;
    }
    .button {
      margin-top: 32px;
      display: inline-block;
      padding: 10px 18px;
      border: 1px solid #ccc;
      border-radius: 999px;
      text-decoration: none;
      color: #222;
      font-size: 14px;
    }
    .footer {
      text-align: center;
      font-size: 14px;
      color: #666;
    }
  </style>
</head>
<body>

  <!-- 1. Hero -->
  <section class="hero">
    <h1>이웃집 사과</h1>
    <p>이 사과는 멀리서 오지 않았습니다.</p>
  </section>

  <!-- 2. 사과의 정체 -->
  <section>
    <div class="text">
      <p>
        이 사과는<br />
        우리 동네에서 20년 넘게<br />
        같은 자리에 있던 사과나무에서 자랐습니다.
      </p>
      <p>
        빠르게 크지 않았고<br />
        특별하게 꾸미지도 않았습니다.
      </p>
    </div>
  </section>

  <!-- 3. 듀퍼의 태도 -->
  <section>
    <div class="text">
      <p>
        듀퍼는<br />
        이런 재료를 좋아합니다.
      </p>
      <p>
        크게 말하지 않아도<br />
        맛으로 남는 것들.
      </p>
      <div class="brand">Duper Coffee Roastery</div>
    </div>
  </section>

  <!-- 4. 복권 안내 -->
  <section>
    <div class="text">
      <p>
        지금 이 사과로 만든 메뉴를<br />
        드시고 계신다면
      </p>
      <p>
        작은 복권 한 장을<br />
        받아보셨을 거예요.
      </p>
      <a href="#lottery" class="button">사과 복권 이야기 보기</a>
    </div>
  </section>

  <!-- 5. 복권의 의미 -->
  <section id="lottery">
    <div class="text">
      <p>
        이 복권은<br />
        많이 주기 위한 이벤트가 아니라
      </p>
      <p>
        이 사과를<br />
        한 번 더 기억하게 하기 위한 장치입니다.
      </p>
      <ul>
        <li>사과</li>
        <li>듀퍼</li>
        <li>이 동네</li>
        <li>그리고 오늘</li>
      </ul>
    </div>
  </section>

  <!-- 6. 엔딩 -->
  <section class="footer">
    <p>좋은 재료는 보통 가까이에 있습니다.</p>
  </section>

</body>
</html>
