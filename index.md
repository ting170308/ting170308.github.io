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

  <section class="company" id="company">
  <div class="container">
    <h2>公司介绍</h2>
    <p>
      云游书景传媒有限公司是一家专注于<span class="highlight">"文化+旅游+数字内容"</span>创新融合的现代传媒企业。
      公司以经典教材、文学名著、艺术名画为内容载体，通过
      <span class="highlight">"跟着名作去旅行"</span>的核心产品理念，打造线上线下相结合的文旅新业态。
    </p>
    <h3>核心业务模式：</h3>
    <ul>
      <li>1. <strong>数字内容生产：</strong>将经典作品中的场景进行影视化再现，制作高品质的短视频、纪录片及图文内容</li>
      <li>2. <strong>新媒体矩阵运营：</strong>构建抖音、小红书、B站等多平台自媒体矩阵，实现文化内容的精准传播</li>
      <li>3. <strong>文创产品开发：</strong>基于IP内容衍生开发"云游书景"系列文创产品，拓展商业变现渠道</li>
    </ul>
    <p>
      公司致力于通过现代传媒技术，让经典文化以更生动的方式走进大众生活，
      推动文旅产业的内容升级与价值创新。
    </p>
  </div>
</section>


<section id="team" class="team-section">
  <div class="container">
    <h2 class="section-title">核心团队介绍</h2>
    <div class="team-intro short" id="team-content">
      <h3><i class="fas fa-building"></i> 公司简介</h3>
      <p>云游书景传媒有限公司是一家专注于"文化+旅游+数字内容"创新融合的现代传媒企业。公司以经典教材、文学名著、艺术名画为内容载体，通过"跟着名作去旅行"的核心产品理念，打造线上线下相结合的文旅新业态。</p>

      <h3><i class="fas fa-rocket"></i> 核心业务模式</h3>
      <ol>
        <li><strong>数字内容生产：</strong>将经典作品中的场景进行影视化再现，制作高品质的短视频、纪录片及图文内容</li>
        <li><strong>新媒体矩阵运营：</strong>构建抖音、小红书、B站等多平台自媒体矩阵，实现文化内容的精准传播</li>
        <li><strong>文创产品开发：</strong>基于IP内容衍生开发"云游书景"系列文创产品，拓展商业变现渠道</li>
      </ol>

      <h3><i class="fas fa-users"></i> 核心团队构成</h3>
      <p>云游书景汇聚了一支多学科融合的专业团队，成员来自汉语言文学、汉语国际教育、网络与新媒体、教育技术、财务会计教育、市场营销、环境艺术与设计、美术学、统计学等九大专业领域，共同构建"文化+旅游+数字媒体"的创新生态。</p>

      <ul>
        <li><strong>① 内容创作中心：</strong>
          汉语言文学团队负责经典文本深度解读，汉语国际教育团队提供跨文化传播视角，美术学与环境艺术设计团队主导视觉艺术呈现。
        </li>
        <li><strong>② 数字媒体中心：</strong>
          网络与新媒体团队负责全媒体内容策划与平台运营，教育技术团队开发沉浸式数字体验产品，统计学团队提供数据分析支持。
        </li>
        <li><strong>③ 商业运营中心：</strong>
          市场营销团队制定推广策略，财务会计团队优化商业模型与成本控制。
        </li>
      </ul>

      <h3><i class="fas fa-lightbulb"></i> 团队优势</h3>
      <ul>
        <li>✅ 文化内涵的学术性保障</li>
        <li>🎨 视觉呈现的艺术性表达</li>
        <li>💻 数字传播的技术性支撑</li>
        <li>📈 商业运营的科学性管理</li>
      </ul>

      <p>这支复合型团队将持续以专业能力推动文化创意产业的创新发展。</p>
    </div>

    <a href="javascript:void(0);" id="toggleBtn">展开更多</a>
  </div>
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
<script>
  const btn = document.getElementById("toggleBtn");
  const content = document.getElementById("team-content");
  btn.onclick = () => {
    content.classList.toggle("short");
    btn.innerText = content.classList.contains("short") ? "展开更多" : "收起内容";
  };
</script>

</body>
</html>
