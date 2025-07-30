# EEE6208 Interactive Review Guide

## 项目简介 / Project Description

这是一个关于EEE6208数字电路的交互式复习指南，支持中英文双语显示。

This is an interactive review guide for EEE6208 Digital Circuits, supporting both English and Chinese languages.

## 主要功能 / Main Features

### 🌐 多语言支持 / Multilingual Support
- **英文为主**：默认显示英文版本
- **中文切换**：点击右上角的"中文"按钮可切换到中文版本
- **实时切换**：所有内容（包括交互式分析结果）都会实时更新语言

- **English Primary**: Default display in English
- **Chinese Toggle**: Click the "中文" button in the top-right corner to switch to Chinese
- **Real-time Switching**: All content (including interactive analysis results) updates language in real-time

### 📚 学习模块 / Learning Modules

1. **MOSFET基础 / MOSFET Basics**
   - 交互式NMOS工作区分析器
   - 实时计算和显示晶体管工作状态

2. **CMOS逻辑设计 / CMOS Logic Design**
   - 复杂逻辑门生成器
   - 可视化PUN/PDN网络结构

3. **电路延迟分析 / Delay Analysis**
   - 逻辑努力延迟可视化
   - 交互式参数调整

4. **高级逻辑 / Advanced Logic**
   - PTL电压降模拟器
   - 弱维持器工作原理演示

5. **电路测试 / Circuit Testing**
   - 固定型故障模拟器
   - 测试向量分析

6. **专家问题 / Expert Questions**
   - 关键路径优化
   - 非对称晶体管尺寸设计

## 使用方法 / How to Use

1. **启动项目 / Start the Project**
   ```bash
   # 使用Python启动本地服务器
   python3 -m http.server 8000
   
   # 或使用Node.js
   npx http-server
   ```

2. **访问应用 / Access the Application**
   - 打开浏览器访问 `http://localhost:8000`
   - 默认显示英文版本

3. **切换语言 / Switch Language**
   - 点击页面右上角的语言切换按钮
   - 所有内容会立即更新为选择的语言

4. **交互学习 / Interactive Learning**
   - 点击导航栏在不同主题间切换
   - 使用各种交互式工具进行学习
   - 实时观察参数变化对结果的影响

## 技术特点 / Technical Features

- **响应式设计**：适配各种屏幕尺寸
- **实时交互**：所有分析结果实时更新
- **可视化图表**：使用Chart.js绘制交互式图表
- **现代UI**：使用Tailwind CSS构建美观界面
- **无依赖**：纯前端实现，无需后端服务

## 浏览器兼容性 / Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 项目结构 / Project Structure

```
/
├── index.html          # 主应用文件
├── README.md           # 项目说明
└── .git/              # Git版本控制
```

## 开发说明 / Development Notes

- 使用HTML5、CSS3、JavaScript ES6+
- 采用模块化设计，便于维护和扩展
- 支持添加更多语言版本
- 可扩展更多交互式学习模块

## 许可证 / License

本项目仅供学习和教学使用。

This project is for educational purposes only.