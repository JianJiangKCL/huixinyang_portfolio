---
layout: default
title: 关于我
permalink: /about/
---

<style>
.about-container {
    max-width: 800px;
    margin: 120px auto 0;
    padding: 0 20px;
}

.about-section {
    margin-bottom: 40px;
}

.skills-list {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 20px;
}

.skill-item {
    background: #f8f9fa;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
}

.work-experience {
    margin-bottom: 30px;
    border-left: 3px solid #007bff;
    padding-left: 20px;
}

.work-period {
    color: #6c757d;
    margin-top: 0;
    font-style: italic;
}

.brands-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
    margin-top: 20px;
}

.brand-category {
    background: #f8f9fa;
    padding: 15px 20px;
    border-radius: 8px;
}

.brand-category h5 {
    margin-top: 0;
    color: #343a40;
    border-bottom: 1px solid #dee2e6;
    padding-bottom: 8px;
    margin-bottom: 10px;
}

.brand-category p {
    line-height: 1.6;
    margin: 8px 0;
    color: #495057;
}

@media (min-width: 768px) {
    .brands-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}
</style>

<div class="about-container">
    <div class="about-section">
        <h1>关于我</h1>
        <p>我是杨慧鑫，一位拥有四年经验的资深广告艺术指导。在这个充满创意和挑战的领域中，我始终保持着对艺术的热情和对完美的追求。</p>
    </div>

    <div class="about-section">
        <h2>专业技能</h2>
        <div class="skills-list">
            <div class="skill-item">视觉策划</div>
            <div class="skill-item">艺术指导</div>
            <div class="skill-item">品牌视觉构建</div>
            <div class="skill-item">创意团队管理</div>
            <div class="skill-item">跨部门协作</div>
            <div class="skill-item">设计软件应用</div>
        </div>
    </div>

    <div class="about-section">
        <h2>工作经验</h2>
        
        <div class="work-experience">
            <h3>FOODOGRAPHY — 资深艺术指导</h3>
            <p class="work-period">2021.10 - 2025.1</p>
            
            <h4>工作职责：</h4>
            <ul>
                <li>主导品牌视觉策划：制定拍摄方案，确保作品契合品牌调性与市场定位</li>
                <li>统筹现场创意执行：包括场景搭建、道具选配、模特与食品造型指导</li>
                <li>全案把控摄影流程：协调跨部门资源，把控拍摄质量与进度</li>
                <li>驱动项目高效交付：把控质量标准，实现品牌内容的精准上线</li>
            </ul>
        </div>

        <h4>合作品牌：</h4>
        <div class="brands-grid">
            <div class="brand-category">
                <h5>奢侈与生活品牌</h5>
                <p>雅诗兰黛 | Rémy Martin | 歌帝梵 | 半岛酒店 | Casetify | 泡泡骚</p>
            </div>
            
            <div class="brand-category">
                <h5>科技品牌</h5>
                <p>小米 | vivo | 科大讯飞 | 小天才</p>
            </div>
            
            <div class="brand-category">
                <h5>食品饮料</h5>
                <p>百事 | 康师傅 | 元气森林 | 伊利 | 蒙牛 | 悸动烧仙草 | 三只松鼠 | 良品铺子</p>
                <p>卡士 | 徐福记 | 乐芝牛 | 加州巴旦木 | 来伊份 | Rio | 菌小宝</p>
            </div>
            
            <div class="brand-category">
                <h5>餐饮品牌</h5>
                <p>必胜客 | 麦当劳 | KFC | 永和大王 | 裕莲茶楼 | 霸王茶姬 | wonderwall | 拉面说</p>
            </div>
            
            <div class="brand-category">
                <h5>零售与电商</h5>
                <p>天猫 | 盒马鲜生 | 美团 | 罗森 | 满小饱 | 小熊电器</p>
            </div>
        </div>
    </div>

    <div class="about-section">
        <h2>工作理念</h2>
        <p>我深信优秀的视觉创意源于对品牌深刻的理解和独特的艺术表达。在每个项目中，我都致力于：</p>
        <ul>
            <li>深入理解品牌核心价值</li>
            <li>创新视觉表现手法</li>
            <li>注重细节完善</li>
            <li>保持高效团队协作</li>
        </ul>
    </div>

    <div class="about-section">
        <h2>联系方式</h2>
        <p>电话：{{ site.social.phone }}</p>
        <p>邮箱：{{ site.social.email }}</p>
        <p>地址：静安区共和新路</p>
    </div>
</div> 