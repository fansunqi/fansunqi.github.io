---
layout: page
permalink: /analytics/
title: Analytics
nav: true
nav_order: 5
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <h2>访问统计</h2>
        <div id="visitor-stats">
            <div class="stats-container">
                <div class="stat-box">
                    <h3>总访问量</h3>
                    <p id="total-visits">加载中...</p>
                </div>
                <div class="stat-box">
                    <h3>今日访问</h3>
                    <p id="today-visits">加载中...</p>
                </div>
            </div>
        </div>
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <h2>访问地图</h2>
        <div style="display: flex; justify-content: space-between; align-items: center; height: 300px;">
            <div style="width: 64%; height: 100%; display: flex; align-items: center;">
                <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=is9r4--UPPK1Lfc_xuRS3rZjQSDjGDJg84StK-jDI0s&cl=ffffff&w=a"></script>
            </div>
        </div>
    </div>
</div>

<style>
.stats-container {
    display: flex;
    justify-content: space-around;
    margin: 20px 0;
}

.stat-box {
    text-align: center;
    padding: 20px;
    border-radius: 8px;
    background-color: #f8f9fa;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.stat-box h3 {
    margin-bottom: 10px;
    color: #333;
}

.stat-box p {
    font-size: 24px;
    font-weight: bold;
    color: #007bff;
    margin: 0;
}
</style>