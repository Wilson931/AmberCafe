<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>篮球鞋店</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <!-- 头部 -->
    <header>
        <h1>篮球鞋店</h1>
    </header>

    <!-- 导航栏 -->
    <nav>
        <ul>
            <li><a href="#">首页</a></li>
            <li><a href="#">商品列表</a></li>
            <li><a href="#">关于我们</a></li>
            <li><a href="#">联系我们</a></li>
        </ul>
    </nav>

    <!-- 商品展示区 -->
    <section class="product-section">
        <h2>热门商品</h2>
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Basketball+Shoes+1" alt="篮球鞋 1">
            <h3>篮球鞋 1</h3>
            <p>这是一款非常舒适的篮球鞋，适合各种篮球比赛。</p>
            <p class="price">$120</p>
            <button>加入购物车</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Basketball+Shoes+2" alt="篮球鞋 2">
            <h3>篮球鞋 2</h3>
            <p>高性能篮球鞋，提供出色的支撑和稳定性。</p>
            <p class="price">$150</p>
            <button>加入购物车</button>
        </div>
    </section>

    <!-- 关于我们 -->
    <section class="about-section">
        <h2>关于我们</h2>
        <p>我们是一家专注于篮球鞋销售的店铺，致力于为广大篮球爱好者提供高品质、时尚的篮球鞋。我们拥有丰富的产品线，涵盖了各种品牌和款式，满足不同客户的需求。</p>
    </section>

    <!-- 页脚 -->
    <footer>
        <p>&copy; 2025 篮球鞋店. 保留所有权利.</p>
    </footer>

    <script src="script.js"></script>
</body>

</html>
/* 全局样式 */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px;
}

nav {
    background-color: #444;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 10px;
}

nav ul li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

nav ul li a:hover {
    background-color: #555;
}

.product-section {
    padding: 20px;
    text-align: center;
}

.product {
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 20px;
    margin: 20px;
    display: inline-block;
    width: 300px;
}

.product img {
    width: 100%;
    height: auto;
}

.price {
    font-weight: bold;
    color: #ff5722;
}

button {
    background-color: #ff5722;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #f44336;
}

.about-section {
    padding: 20px;
    text-align: center;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
