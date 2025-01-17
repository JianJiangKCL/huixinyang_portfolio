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
        <p>在过去的几年里，我有幸为众多知名品牌提供服务，包括：</p>
        <ul>
            <li>奢侈品牌：雅诗兰黛、Rémy Martin、歌帝梵</li>
            <li>科技品牌：小米、vivo、科大讯飞</li>
            <li>食品饮料：百事、康师傅、元气森林</li>
            <li>餐饮品牌：必胜客、麦当劳、KFC</li>
            <li>零售品牌：天猫、盒马鲜生、良品铺子</li>
        </ul>
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