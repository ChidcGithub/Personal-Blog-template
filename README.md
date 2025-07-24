# Personal-Blog-template
A template for personal blogger
# 个人作品集网站

这是一个现代化、响应式的个人作品集网站，专为展示个人技能、项目和经历而设计。网站支持浅色/深色模式切换，包含精美的动画效果和交互体验。

## 功能特点

- 响应式设计，适配从移动设备到桌面的各种屏幕尺寸
- 支持浅色/深色模式切换，自动记住用户偏好
- 丰富的动画和过渡效果，提升用户体验
- 技能雷达图可视化展示
- 项目筛选功能，可按类别查看不同项目
- 时间线展示个人经历
- 联系表单功能
- 彩蛋和交互元素，增加趣味性


## 快速开始

1. 克隆或下载本项目到本地
2. 直接打开 `index.html` 文件即可在浏览器中查看网站
3. 无需额外依赖，所有资源均使用CDN加载

## 自定义指南

### 个人信息修改

1. 打开 `index.html` 文件
2. 查找并替换以下内容：
   - 个人名称和标题
   - 关于我部分的介绍文本
   - 联系信息（邮箱、GitHub等）
   - 个人经历时间线内容

### 替换图片

1. 将个人头像替换为 `assets/images/profile.jpg`
2. 将项目图片替换到 `assets/images/projects/` 目录下，并在HTML中更新对应路径

### 技能数据修改

1. 打开 `index.html` 文件
2. 在JavaScript部分找到技能图表数据：
   ```javascript
   data: [95, 80, 65, 45, 40, 90, 70, 45]
   ```
3. 修改这些数值以反映你的技能水平（0-100）
4. 同时修改对应的技能标签：
   ```javascript
   labels: ['HTML/CSS', 'JavaScript', 'Python', 'React', 'Node.js', 'MySQL', 'Git', 'UI设计']
   ```

### 项目内容更新

1. 在 `index.html` 中找到项目网格部分
2. 每个项目卡片的结构如下：
   ```html
   <div class="project-card" data-category="web">
       <div style="overflow: hidden;">
           <img src="assets/images/projects/project1.jpg" alt="项目名称" class="project-img">
       </div>
       <div class="project-content">
           <span class="project-category">网站开发</span>
           <h3 class="project-title">项目名称</h3>
           <p class="project-desc">项目描述</p>
           <div class="project-tags">
               <span class="tech-tag">技术1</span>
               <span class="tech-tag">技术2</span>
           </div>
           <div class="project-links">
               <a href="#" class="btn btn-sm"><i class="fas fa-eye"></i> 查看</a>
               <a href="#" class="btn btn-sm btn-outline"><i class="fab fa-github"></i> 代码</a>
           </div>
       </div>
   </div>
   ```
3. 根据需要添加、删除或修改项目卡片

## 技术栈

- HTML5
- CSS3 (使用Tailwind CSS v3)
- JavaScript
- Font Awesome 图标
- Chart.js (技能图表)

## 浏览器兼容性

- 现代浏览器（Chrome, Firefox, Safari, Edge）
- 响应式设计，支持移动设备

## 许可证

本项目采用MIT许可证 - 详见LICENSE文件

## 致谢

- 设计灵感来自现代作品集网站趋势
- 使用的第三方库：Tailwind CSS, Font Awesome, Chart.js
    
