
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>云游书景文创集</title>
  <style>
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Helvetica Neue', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 20px;
      background-color: #4b8b88;
      color: white;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    header img {
      height: 40px;
      margin-right: 10px;
    }

    .site-name {
      display: flex;
      align-items: center;
      font-size: 20px;
      font-weight: bold;
    }

    nav {
      display: flex;
      align-items: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 15px;
      font-size: 15px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .menu-toggle {
      display: none;
      font-size: 26px;
      cursor: pointer;
    }

    @media screen and (max-width: 768px) {
      nav {
        display: none;
        flex-direction: column;
        width: 100%;
        background-color: #4b8b88;
      }

      nav.active {
        display: flex;
      }

      nav a {
        padding: 10px 0;
        border-top: 1px solid #ffffff33;
        margin-left: 0;
        text-align: center;
      }

      .menu-toggle {
        display: block;
      }
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

    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .product {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
      text-align: center;
    }

    .product img {
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
  </style>
</head>
<body>

  <header>
    <div class="site-name">
      <img src="your-logo.png" alt="Logo">
      云游书景文创集
    </div>
    <div class="menu-toggle" onclick="toggleMenu()">☰</div>
    <nav id="navbar">
      <a href="#about">公司介绍</a>
      <a href="#team">团队介绍</a>
      <a href="#products">产品展示</a>
      <a href="#contact">联系我们</a>
    </nav>
  </header>

  <section id="about">
    <h2>公司介绍</h2>
    <p>云游书景文创集是一个融合了教育、文创与旅游的新媒体项目。我们致力于将中小学教材中的名著、名画与中国各地的著名景点巧妙结合，通过拍摄短视频、制作微课和文创产品的方式，让知识“走进现实”，让学习充满趣味。我们的产品不仅适用于课堂教学，也能成为学生课后的文化补充和家长亲子共学的好助手。</p>
  </section>

  <section id="team">
    <h2>团队介绍</h2>
    <p>我们是一支由教育技术、设计、影视制作等多学科背景成员组成的年轻团队，怀着对知识传播的热情与对传统文化的敬意，启动了“云游书景文创集”项目。我们的初心是让教材不再“死板”，而是“活”在风景与生活中；我们的目标是借助文创产品与数字内容的结合，打造属于新时代青少年的文化教育新体验。</p>
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

  <h3 style="margin-top: 50px; color: #4b8b88;">《千里江山图》系列</h3>
  <div class="product">
    <img src="product4.jpg" alt="千里江山图系列">
    <p>灵感来源于中国十大传世名画之一《千里江山图》，融合国风与实用性，打造兼具收藏与日用的文创产品：</p>
    <ul>
      <li>钥匙扣</li>
      <li>冰箱贴</li>
      <li>透卡</li>
      <li>帆布袋</li>
      <li>书签</li>
    </ul>
  </div>

  <h3 style="margin-top: 50px; color: #4b8b88;">《红楼梦》系列</h3>
  <div class="product">
    <img src="product5.jpg" alt="红楼梦系列">
    <p>以《红楼梦》经典人物与场景为设计灵感，打造具有文学韵味的文创衍生品：</p>
    <ul>
      <li>钥匙扣</li>
      <li>冰箱贴</li>
      <li>透卡</li>
      <li>徽章</li>
      <li>便利贴</li>
    </ul>
  </div>

  <h3 style="margin-top: 50px; color: #4b8b88;">《我与地坛》系列</h3>
  <div class="product">
    <img src="product6.jpg" alt="我与地坛系列">
    <p>结合史铁生散文《我与地坛》的人文情怀与视觉意境，推出文艺而富有哲思的主题周边：</p>
    <ul>
      <li>明信片</li>
      <li>邮票</li>
      <li>贴纸</li>
      <li>胶片拍立得</li>
      <li>木质挂件</li>
      <li>帆布包</li>
    </ul>
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

  <script>
    function toggleMenu() {
      document.getElementById('navbar').classList.toggle('active');
    }
  </script>

</body>
</html>
