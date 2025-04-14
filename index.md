<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>云游书景文创集</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f9f9f9;
      color: #333;
    }

  header {
      background-color: #4b8b88;
      color: white;
      padding: 10px 20px;
      text-align: center;
      position: relative;
    }

   header img {
      height: 40px;
      vertical-align: middle;
      margin-right: 10px;
    }

   h1 {
      display: inline;
      font-size: 22px;
    }

  section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

   h2 {
      color: #4b8b88;
      margin-bottom: 20px;
      border-left: 4px solid #4b8b88;
      padding-left: 10px;
    }

   .team-grid, .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

   .team-member, .product {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      text-align: center;
    }

   .team-member img, .product img {
      width: 100%;
      max-height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }

   .product p {
      margin-top: 10px;
      font-size: 15px;
    }

  .contact {
      text-align: center;
    }

   .contact img {
      max-width: 200px;
      margin-top: 10px;
    }

  footer {
      background-color: #4b8b88;
      color: white;
      text-align: center;
      padding: 15px;
    }

  @media screen and (max-width: 600px) {
      header img {
        height: 30px;
      }

   h1 {
        font-size: 18px;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="your-logo.png" alt="云游书景Logo" />
    <h1>云游书景文创集</h1>
  </header>

  <section id="about">
    <h2>公司介绍</h2>
    <p>云游书景文创集是一个融合了教育、文创与旅游的新媒体项目。我们致力于将中小学教材中的名著、名画与中国各地的著名景点巧妙结合，通过拍摄短视频、制作微课和文创产品的方式，让知识“走进现实”，让学习充满趣味。我们的产品不仅适用于课堂教学，也能成为学生课后的文化补充和家长亲子共学的好助手。</p>
  </section>

  <section id="team">
    <h2>团队介绍</h2>
    <div class="team-grid">
      <div class="team-member">
        <img src="team1.jpg" alt="团队成员1">
        <h3>张晓文</h3>
        <p>项目策划与运营，擅长内容创意与脚本撰写。</p>
      </div>
      <div class="team-member">
        <img src="team2.jpg" alt="团队成员2">
        <h3>李晨宇</h3>
        <p>摄影剪辑与视觉包装，负责视频拍摄与后期制作。</p>
      </div>
      <div class="team-member">
        <img src="team3.jpg" alt="团队成员3">
        <h3>王丽娜</h3>
        <p>产品设计师，专注于文创商品的开发与视觉设计。</p>
      </div>
    </div>
  </section>

  <section id="products">
    <h2>文创产品展示</h2>
    <div class="products-grid">
      <div class="product">
        <img src="product1.jpg" alt="明信片套装">
        <p>《云游诗画》明信片套装：将《登鹳雀楼》《早发白帝城》等古诗与对应景点摄影融合，寓教于游。</p>
      </div>
      <div class="product">
        <img src="product2.jpg" alt="书签组合">
        <p>《书景之间》书签组合：精选古典文学与风景相结合，制作高质感镂空书签，适合赠送与收藏。</p>
      </div>
      <div class="product">
        <img src="product3.jpg" alt="手账贴纸">
        <p>《古画游记》手账贴纸：将教材中的名画设计为趣味贴纸，提升学习趣味性，适合学生与手帐爱好者。</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>联系我们</h2>
    <div class="contact">
      <p>关注我们的微信公众号，获取最新内容与产品信息：</p>
      <img src="your-wechat.png" alt="微信公众号二维码" />
    </div>
  </section>

  <footer>
    &copy; 2025 云游书景文创集 | 版权所有
  </footer>
</body>
</html>
