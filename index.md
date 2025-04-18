<!DOCTYPE html>
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
    <h2>《千里江山图》系列</h2>
    <div class="product-list">
      <div class="product-item">
        <img src="images/jiangshan_touka.jpg" alt="千里江山图透卡">
        <h3>透卡</h3>
        <p>定价：5元/张</p>
        <p>规格：85mm × 108mm</p>
        <p>材质：透明PVC</p>
      </div>
      <div class="product-item">
        <img src="images/jiangshan_keychain.jpg" alt="千里江山图钥匙扣">
        <h3>钥匙扣</h3>
        <p>定价：8元/个</p>
        <p>规格：30mm × 30mm</p>
        <p>材质：透明亚克力板</p>
      </div>
      <div class="product-item">
        <img src="images/jiangshan_notes.jpg" alt="千里江山图便利贴">
        <h3>便利贴</h3>
        <p>定价：10元/本</p>
        <p>规格：30mm × 30mm</p>
        <p>材质：书写纸、环保胶水</p>
      </div>
      <div class="product-item">
        <img src="images/jiangshan_bag.jpg" alt="千里江山图帆布包">
        <h3>帆布包</h3>
        <p>定价：48元/件</p>
        <p>规格：35cm × 40cm</p>
        <p>材质：牛津布</p>
      </div>
    </div>

    <h2>《红楼梦》系列</h2>
    <div class="product-list">
      <div class="product-item two-images">
        <img src="images/honglou_notes1.jpg" alt="红楼梦便利贴1">
        <img src="images/honglou_notes2.jpg" alt="红楼梦便利贴2">
        <h3>便利贴</h3>
        <p>定价：单本3元，两本5元</p>
        <p>规格：30mm × 30mm</p>
        <p>材质：优质纸张，环保油墨</p>
      </div>
      <div class="product-item two-images">
        <img src="images/honglou_touka1.jpg" alt="红楼梦透卡1">
        <img src="images/honglou_touka2.jpg" alt="红楼梦透卡2">
        <h3>透卡</h3>
        <p>定价：5元/张</p>
        <p>规格：85mm × 108mm</p>
        <p>材质：透明PVC</p>
      </div>
      <div class="product-item two-images">
        <img src="images/honglou_keychain1.jpg" alt="红楼梦钥匙扣1">
        <img src="images/honglou_keychain2.jpg" alt="红楼梦钥匙扣2">
        <h3>钥匙扣</h3>
        <p>定价：8元/个</p>
        <p>规格：30mm × 30mm</p>
        <p>材质：透明亚克力板</p>
      </div>
      <div class="product-item two-images">
        <img src="images/honglou_badge1.jpg" alt="红楼梦徽章1">
        <img src="images/honglou_badge2.jpg" alt="红楼梦徽章2">
        <h3>毛绒徽章</h3>
        <p>定价：10元/个</p>
        <p>规格：58mm × 58mm</p>
        <p>材质：马口铁+塑料膜+毛绒材料</p>
      </div>
      <div class="product-item two-images">
        <img src="images/honglou_fridge1.jpg" alt="红楼梦冰箱贴1">
        <img src="images/honglou_fridge2.jpg" alt="红楼梦冰箱贴2">
        <h3>冰箱贴</h3>
        <p>定价：10元/个</p>
        <p>规格：40mm × 40mm</p>
        <p>材质：橡胶软磁贴+透明亚克力</p>
      </div>
    </div>

    <h2>《我与地坛》系列</h2>
    <div class="product-list">
      <div class="product-item">
        <img src="images/ditan_postcard.jpg" alt="我与地坛明信片套组">
        <h3>明信片</h3>
        <p>定价：5元/张，套组19.9元</p>
        <p>规格：148mm × 100mm</p>
        <p>材质：卡纸、哑粉纸、珠光纸</p>
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
