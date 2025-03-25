这是一个咖啡馆菜单网页项目

功能特点
多语言切换：支持中英文切换，点击语言切换按钮可实现页面内容的语言转换。
菜单展示：清晰展示咖啡和甜点的品类及价格。
样式美观：使用 CSS 进行样式设计，背景图和颜色搭配营造出咖啡馆氛围。
技术实现
HTML：构建网页结构，利用 属性存储多语言文本。data-lang
CSS：设置页面布局、字体、颜色等样式。
JavaScript：实现语言切换功能，根据用户点击动态更新页面文本。

<div style="overflow: hidden; width: 100%; height: 400px;">
  <div style="display: flex; animation: slide 10s infinite;">
    <img src="https://raw.githubusercontent.com/your-username/your-repo/main/images/pic1.jpg" alt="Pic 1" style="width: 100%;">
    <img src="https://raw.githubusercontent.com/your-username/your-repo/main/images/pic2.jpg" alt="Pic 2" style="width: 100%;">
    <img src="https://raw.githubusercontent.com/your-username/your-repo/main/images/pic3.jpg" alt="Pic 3" style="width: 100%;">
  </div>
</div>

<style>
  @keyframes slide {
    0% { transform: translateX(0); }
    33% { transform: translateX(-100%); }
    66% { transform: translateX(-200%); }
    100% { transform: translateX(-300%); }
  }
</style>
