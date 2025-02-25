# 全球艺术百科 - UI/UX设计规范

## 一、设计理念

### 1. 核心价值
- 简约优雅：体现艺术气质
- 清晰易用：降低使用门槛
- 沉浸体验：突出艺术作品
- 人性化：符合用户习惯

### 2. 设计原则
- 以内容为王：突出艺术作品展示
- 减少干扰：简化界面元素
- 引导式交互：降低学习成本
- 一致性：统一的视觉语言
- 响应式：适配不同设备

## 二、视觉规范

### 1. 色彩系统
#### 1.1 主色调
- 主色：#FFFFFF（纯白）
- 次色：#F5F5F5（浅灰白）
- 强调色：#1E88E5（深蓝）
- 辅助色：#FFB300（金黄）

#### 1.2 功能色
- 成功：#4CAF50
- 警告：#FF9800
- 错误：#F44336
- 链接：#2196F3

#### 1.3 文字颜色
- 主要文字：#333333
- 次要文字：#666666
- 辅助文字：#999999
- 反白文字：#FFFFFF

### 2. 字体规范
#### 2.1 中文字体
- 默认字体：PingFang SC
- 备选字体：Microsoft YaHei

#### 2.2 英文字体
- 默认字体：SF Pro Text
- 备选字体：Arial

#### 2.3 字号规范
- 标题大号：24px
- 标题常规：20px
- 副标题：18px
- 正文：16px
- 辅助文字：14px
- 注释文字：12px

### 3. 间距规范
- 基础间距：8px
- 组件间距：16px
- 区块间距：24px
- 页面边距：16px

### 4. 圆角规范
- 小圆角：4px
- 中圆角：8px
- 大圆角：12px

## 三、组件规范

### 1. 导航栏
- 高度：56px
- 背景色：#FFFFFF
- 阴影：0 2px 4px rgba(0,0,0,0.1)
- 图标尺寸：24px

### 2. 按钮
#### 2.1 主要按钮
- 高度：44px
- 圆角：8px
- 背景色：#1E88E5
- 文字颜色：#FFFFFF

#### 2.2 次要按钮
- 高度：44px
- 圆角：8px
- 边框：1px solid #1E88E5
- 文字颜色：#1E88E5

### 3. 卡片
- 圆角：12px
- 阴影：0 2px 8px rgba(0,0,0,0.1)
- 背景色：#FFFFFF
- 内边距：16px

### 4. 输入框
- 高度：44px
- 圆角：8px
- 边框：1px solid #E0E0E0
- 内边距：12px

## 四、交互规范

### 1. 过渡动画
- 持续时间：300ms
- 缓动函数：ease-in-out
- 页面切换：淡入淡出
- 列表加载：渐显

### 2. 反馈机制
- 点击反馈：波纹效果
- 加载状态：进度条/骨架屏
- 操作结果：轻提示
- 错误提示：对话框

### 3. 手势操作
- 下拉刷新
- 左右滑动切换
- 双指缩放
- 长按操作

## 五、布局规范

### 1. 网格系统
- 列数：12列
- 列间距：16px
- 边距：16px

### 2. 自适应断点
- 手机：< 600px
- 平板：600px - 1024px
- 桌面：> 1024px

### 3. 内容布局
- 图片展示：瀑布流
- 列表展示：垂直列表
- 详情页：上图下文
- 个人中心：卡片式

## 六、特殊页面规范

### 1. 导航栏设计
#### 1.1 收起状态
- 宽度：60px
- 背景色：#FFFFFF
- 图标尺寸：24px
- 图标颜色：#333333
- 选中状态：#1E88E5
- 间距：16px垂直间距

#### 1.2 展开状态
- 宽度：320px
- 文字大小：16px
- 行高：44px
- 左侧内边距：24px
- 图标与文字间距：12px

### 2. 艺术博物志页面
#### 2.1 页面标题
- 字体大小：24px
- 字重：Medium
- 上下边距：24px
- 左边距：24px

#### 2.2 博物志封面
- 尺寸：320px × 400px
- 圆角：12px
- 阴影：0 4px 12px rgba(0,0,0,0.1)
- 背景图片：模糊处理（blur: 2px）
- 标题覆盖：
  - 背景：线性渐变（透明到半透明黑）
  - 文字颜色：#FFFFFF
  - 文字大小：20px
  - 内边距：24px

#### 2.3 展示模式切换器
- 高度：44px
- 背景色：#F5F5F5
- 圆角：22px
- 选项间距：8px
- 文字大小：14px
- 图标尺寸：18px
- 选中状态：
  - 背景色：#FFFFFF
  - 文字颜色：#1E88E5
  - 阴影：0 2px 4px rgba(0,0,0,0.1)

#### 2.4 文件夹视图
- 文件夹图标：24px
- 文件夹名称：16px
- 行高：44px
- 缩进距离：24px
- 展开/收起图标：
  - 尺寸：16px
  - 颜色：#666666
- hover状态：
  - 背景色：#F5F5F5
- 选中状态：
  - 背景色：#E3F2FD
  - 文字颜色：#1E88E5

#### 2.5 目录视图
- 文字大小：14px
- 行高：32px
- 缩进距离：20px
- 层级标识：
  - 颜色：#CCCCCC
  - 宽度：1px
- hover状态：
  - 文字颜色：#1E88E5

#### 2.6 缩略图视图
- 图片尺寸：160px × 160px
- 圆角：8px
- 间距：16px
- 阴影：0 2px 8px rgba(0,0,0,0.1)
- 标题：
  - 文字大小：14px
  - 行数限制：2行
  - 行高：20px

### 3. 交互动效

#### 3.1 视图切换动画
- 持续时间：300ms
- 缓动函数：ease-in-out
- 过渡效果：fade + slide

#### 3.2 文件夹展开/收起
- 持续时间：200ms
- 缓动函数：ease-out
- 高度过渡
- 箭头旋转过渡

#### 3.3 拖拽交互
- 拖拽项透明度：0.8
- 拖拽时阴影：0 4px 16px rgba(0,0,0,0.2)
- 放置区域提示：
  - 背景色：#E3F2FD
  - 边框：1px dashed #1E88E5

#### 3.4 批量操作
- 选中框尺寸：18px
- 选中状态颜色：#1E88E5
- 批量操作栏：
  - 高度：56px
  - 背景色：#FFFFFF
  - 阴影：0 -2px 8px rgba(0,0,0,0.1)

### 4. 响应式适配

#### 4.1 平板布局（≥768px）
- 导航栏可收起
- 网格列数：2列
- 边距：24px

#### 4.2 桌面布局（≥1024px）
- 导航栏默认展开
- 网格列数：3列
- 边距：32px

#### 4.3 大屏布局（≥1440px）
- 网格列数：4列
- 最大内容宽度：1400px
- 居中显示 