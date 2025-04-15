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
    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .product {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      overflow: hidden;
      width: 250px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .product:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
    }
    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product-description {
      padding: 10px;
      font-size: 14px;
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
      “云游书景文创集”是一个融合了教育与旅游文化的新型文创项目，致力于将语文教材中的名著、名画与中国各地的风景名胜地结合，打造具有教育意义和审美价值的原创内容与文创产品。我们旨在用镜头讲述书中风景的真实模样，让学习更具趣味性和探索性，推动传统文化走进生活。
    </p>
  </section>

  <section class="section" id="team">
    <h2>团队介绍</h2>
    <p>
      我们是一群热爱教育与传统文化的年轻创作者，怀揣着“让语文走出课本”的初心，希望通过短视频、微电影和文创产品等多种形式，将语文教材中的名著、名画与现实风景相连接，打造富有情怀和温度的文化产品。团队目标是将经典文化以现代视角重新演绎，并借助新媒体平台影响更多人。
    </p>
  </section>

  <section class="section" id="products">
    <h2>文创产品</h2>
    <div class="products">

      <!-- 千里江山图系列 -->
      <div class="product">
        <img src="qianli_keychain.jpg" alt="千里江山图钥匙扣" />
        <div class="product-description">千里江山图钥匙扣</div>
      </div>
      <div class="product">
        <img src="qianli_fridge.jpg" alt="千里江山图冰箱贴" />
        <div class="product-description">千里江山图冰箱贴</div>
      </div>
      <div class="product">
        <img src="qianli_card.jpg" alt="千里江山图透卡" />
        <div class="product-description">千里江山图透卡</div>
      </div>
      <div class="product">
        <img src="qianli_bag.jpg" alt="千里江山图帆布袋" />
        <div class="product-description">千里江山图帆布袋</div>
      </div>
      <div class="product">
        <img src="qianli_bookmark.jpg" alt="千里江山图书签" />
        <div class="product-description">千里江山图书签</div>
      </div>

      <!-- 红楼梦系列 -->
      <div class="product">
        <img src="honglou_keychain.jpg" alt="红楼梦钥匙扣" />
        <div class="product-description">红楼梦钥匙扣</div>
      </div>
      <div class="product">
        <img src="honglou_fridge.jpg" alt="红楼梦冰箱贴" />
        <div class="product-description">红楼梦冰箱贴</div>
      </div>
      <div class="product">
        <img src="honglou_card.jpg" alt="红楼梦透卡" />
        <div class="product-description">红楼梦透卡</div>
      </div>
      <div class="product">
        <img src="honglou_badge.jpg" alt="红楼梦徽章" />
        <div class="product-description">红楼梦徽章</div>
      </div>
      <div class="product">
        <img src="honglou_note.jpg" alt="红楼梦便利贴" />
        <div class="product-description">红楼梦便利贴</div>
      </div>

      <!-- 我与地坛系列 -->
      <div class="product">
        <img src="ditan_postcard.jpg" alt="我与地坛明信片" />
        <div class="product-description">我与地坛明信片</div>
      </div>
      <div class="product">
        <img src="ditan_stamp.jpg" alt="我与地坛邮票" />
        <div class="product-description">我与地坛邮票</div>
      </div>
      <div class="product">
        <img src="ditan_sticker.jpg" alt="我与地坛贴纸" />
        <div class="product-description">我与地坛贴纸</div>
      </div>
      <div class="product">
        <img src="ditan_polaroid.jpg" alt="我与地坛胶片拍立得" />
        <div class="product-description">我与地坛胶片拍立得</div>
      </div>
      <div class="product">
        <img src="ditan_wood.jpg" alt="我与地坛木质挂件" />
        <div class="product-description">我与地坛木质挂件</div>
      </div>
      <div class="product">
        <img src="ditan_bag.jpg" alt="我与地坛帆布包" />
        <div class="product-description">我与地坛帆布包</div>
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
