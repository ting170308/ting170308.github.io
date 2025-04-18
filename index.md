<html lang="zh">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>云游书景文创集</title>
  <style>
    body {
      font-family: "Arial", sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f8f8f8;
      color: #333;
    }
    header {
      background-color: #006d77;
      color: white;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 40px;
      width: auto;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      border-left: 5px solid #006d77;
      padding-left: 10px;
      margin-bottom: 20px;
    }
    .product-gallery {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .product-list {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .product-item {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      overflow: hidden;
      width: 250px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      text-align: center;
      padding-bottom: 10px;
    }
    .product-item:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .product-item img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product-item.two-images img {
      height: 100px;
    }
    .contact img {
      width: 150px;
      margin-right: 20px;
    }
    .contact {
      display: flex;
      align-items: center;
      flex-wrap: wrap;
    }
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      .contact {
        flex-direction: column;
        align-items: flex-start;
      }
      .contact img {
        margin-bottom: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="云游书景文创集 Logo" />
    <nav>
      <a href="#about">关于我们</a>
      <a href="#team">团队介绍</a>
      <a href="#products">文创产品</a>
      <a href="#contact">联系我们</a>
    </nav>
  </header>

  <section class="section" id="about">
    <h2>公司介绍</h2>
    <p>
      云游书景传媒有限公司是一家专注于“文化+旅游+数字内容”创新融合的现代传媒企业。公司以经典教材、文学名著、艺术名画为内容载体，通过“跟着名作去旅行”的核心产品理念，打造线上线下相结合的文旅新业态。
    </p>
    <h3>核心业务模式：</h3>
    <ul>
      <li>数字内容生产</li>
      <li>新媒体矩阵运营</li>
      <li>文创产品开发</li>
    </ul>
  </section>

  <section class="section" id="team">
    <h2>核心团队介绍</h2>
    <p>云游书景汇聚了一支多学科融合的专业团队，成员来自多个领域，共同构建“文化+旅游+数字媒体”的创新生态。</p>
    <ul>
      <li><strong>内容创作中心：</strong>文学、美术、教育等专业协作</li>
      <li><strong>数字媒体中心：</strong>新媒体、技术、数据支持</li>
      <li><strong>商业运营中心：</strong>市场营销、财务管控</li>
    </ul>
  </section>

<section class="product-gallery" id="products">
  <h2>产品展示</h2>

  <!-- 产品一：《千里江山图》 -->
  <div class="product-gallery" id="jiangshan">
    <h3>《千里江山图》系列</h3>
    <div class="product-list">
      <div class="product-item">
        <img src="images/jiangshan_notebook.jpg" alt="千里江山图笔记本">
        <h4>千里江山图笔记本</h4>
        <p><strong>定价：</strong>35元</p>
        <p><strong>规格：</strong>A5，80页</p>
        <p><strong>材质：</strong>米黄道林纸</p>
      </div>
      <div class="product-item">
        <img src="images/jiangshan_pouch.jpg" alt="千里江山图帆布袋">
        <h4>千里江山图帆布袋</h4>
        <p><strong>定价：</strong>39元</p>
        <p><strong>规格：</strong>35cm × 40cm</p>
        <p><strong>材质：</strong>棉麻帆布</p>
      </div>
    </div>
  </div>

  <!-- 产品二：《红楼梦》 -->
  <div class="product-gallery" id="honglou">
    <h3>《红楼梦》系列</h3>
    <div class="product-list">
      <div class="product-item">
        <img src="images/honglou_fan1.jpg" alt="红楼梦团扇1">
        <img src="images/honglou_fan2.jpg" alt="红楼梦团扇2">
        <h4>红楼梦团扇</h4>
        <p><strong>定价：</strong>29.9元</p>
        <p><strong>规格：</strong>直径18cm</p>
        <p><strong>材质：</strong>仿绢布、竹骨</p>
      </div>
      <div class="product-item">
        <img src="images/honglou_notebook1.jpg" alt="红楼梦手账本1">
        <img src="images/honglou_notebook2.jpg" alt="红楼梦手账本2">
        <h4>红楼梦手账本</h4>
        <p><strong>定价：</strong>42元</p>
        <p><strong>规格：</strong>B6，128页</p>
        <p><strong>材质：</strong>特种封面纸+米黄内页</p>
      </div>
    </div>
  </div>

  <!-- 产品三：《我与地坛》 -->
  <div class="product-gallery" id="ditan">
    <h3>《我与地坛》系列</h3>
    <div class="product-list">
      <div class="product-item">
        <img src="images/ditan_set.jpg" alt="我与地坛明信片套组">
        <h4>明信片套组</h4>
        <p><strong>定价：</strong>5元/张，19.9元/组</p>
        <p><strong>规格：</strong>148mm × 100mm</p>
        <p><strong>材质：</strong>卡纸、哑粉纸、珠光纸</p>
        <p><strong>产品描述：</strong></p>
        <p style="text-align: left; padding: 0 10px;">
          这组以《我与地坛》为灵感的明信片，将文学哲思与艺术设计深度融合，采用蓝白主调与冷色视觉语言，呈现四种风格各异的场景：
        </p>
        <ul style="text-align: left; padding: 0 20px;">
          <li><strong>清新文艺：</strong>线条色块勾勒地坛树木与长椅，配以诗意短句，展现自然与人文的灵动交融。</li>
          <li><strong>冷峻深沉：</strong>雪地与轮椅解构融合，“我已不在地坛，地坛在我”承载生命哲思。</li>
          <li><strong>静谧深邃：</strong>蓝色调勾勒树木夹道，英文“I AND THE TEMPLE OF EARTH”赋予文艺国际气质。</li>
          <li><strong>内省冷寂：</strong>雪景中树影与轮椅并置，中文与英文“我与地坛”诗意共鸣，引导心灵的沉思。</li>
        </ul>
        <p style="text-align: left; padding: 0 10px;">
          这一系列不仅是视觉产品，更是文化传播载体，在冷静色调中传递出地坛所承载的生命厚度与精神力量，为观者提供心灵的栖息之所。
        </p>
      </div>
    </div>
  </div>
</section>


  <section class="section" id="contact">
    <h2>联系我们</h2>
    <p>联系电话：17817964305</p>
    <div class="contact">
      <img src="wechat.png" alt="微信公众号二维码" />
      <img src="douyin.png" alt="抖音号二维码" />
    </div>
  </section>

</body>
</html>
