# 传智网课答题助手

一个基于油猴脚本的传智教育在线考试答题辅助工具。

## 功能特性

- 自动答题功能
- AI智能解答(支持GPT)
- 题库查询
- 答案显示控制
- 快捷键操作

## 安装说明

1. 安装油猴插件(Tampermonkey)
2. 点击[此处]()安装脚本
3. 配置API密钥:
   - 在脚本编辑页面找到以下变量并填入对应的API密钥:
   ```javascript
   const API_KEY = ''; // 填入你的AI API密钥
   const QUESTION_API_KEY = ''; // 填入题库API密钥
   ```

## 使用方法

### 快捷键
- `~` : 自动搜索下一题答案
- `?` : 进入AI搜题模式
- `M` : 切换答案显示/隐藏
- `N` : 调整答案透明度

### AI搜题模式
1. 按 `?` 进入搜题模式
2. 输入题目序号(如:1,2,3...)
3. 再次按 `?` 开始搜索

## API配置说明

### AI API
- 默认使用GPT API
- 支持自定义API地址,在以下变量中修改:
```javascript
const API_URL = 'https://openai.proxy.com/v1/chat/completions'; 
```
### 题库API
- 需要配置题库API密钥
- 获取方式:[EveryAPI](https://q.icodef.com/)

## 注意事项

- 本工具仅供学习交流使用
- 使用前请确保API配置正确
- 建议合理使用,不要频繁请求

## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 贡献者

- 原作者：土豆
- 二开作者：HCG_Sky
- 三开作者：yichen11818

## 更新日志

### v3.2
- 添加AI搜题功能
- 优化答案显示效果
- 增加快捷键功能