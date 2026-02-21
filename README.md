# AI Language Learning Platform

> An interactive platform for practicing reading, writing, and speaking in target languages with AI-powered feedback.

## English

### Overview
Welcome to the **AI Language Learning Platform**! This project helps language learners practice writing and speaking with real-time AI feedback. Get instant corrections, grammar explanations, vocabulary tips, and conversational practice tailored to your target language.

### Key Features

#### Writing Practice (`index.html`)
- 📝 **Full Text Correction** — Write freely and get comprehensive feedback
- ✅ **Error Detection** — Identifies grammar, spelling, vocabulary, and style issues
- 🔄 **Suggested Improvements** — See corrected versions with explanations
- 💬 **Follow-up Questions** — Ask the AI to clarify grammar rules and explanations
- 📊 **Writing Assessment** — Get a score (1-10) and detailed feedback on your work

#### Speaking Practice (`speaking.html`)
- 🗣️ **Natural Conversation** — Chat with an AI in your target language
- 🎭 **9 Conversation Scenarios**:
  - Free Conversation
  - At a Restaurant
  - Shopping
  - Travel & Directions
  - At the Doctor
  - Job Interview
  - Hotel Check-in
  - Phone Call
  - Meeting a Friend
- ✏️ **Per-Message Corrections** — Get immediate feedback on every sentence
- 💡 **Language Tips** — Learn grammar rules and vocabulary in your native language
- ✨ **Enhancement Suggestions** — See more natural ways to express your thoughts

#### Shared Features
- 🌐 **30+ Languages Supported** — Practice with any combination of native and target language
- 🎨 **Customizable Theme** — Light/Dark/System themes with 9 accent colors
- 📱 **Responsive Design** — Works on desktop and mobile browsers
- 🔑 **Multiple AI Providers**:
  - OpenAI (GPT-4o, GPT-4o Mini, GPT-4 Turbo, GPT-3.5 Turbo)
  - Alibaba Qwen (Qwen-Max, Qwen-Plus, Qwen-Turbo)
  - Google Gemini (2.0 Flash, 2.0 Flash Lite, 1.5 Pro, 1.5 Flash)
  - Anthropic Claude (Sonnet 4, 3.5 Sonnet, 3 Haiku)
- 💾 **Local Storage** — All settings (theme, language, API key) saved locally

### Project Structure
```
LanguageLearning/
├── index.html          # AI Writing Practice page
├── speaking.html       # AI Speaking Practice page
├── README.md           # This file
└── LICENSE             # MIT License
```

### Requirements
- **Modern Web Browser** — Chrome, Firefox, Safari, Edge (with JavaScript enabled)
- **API Key** — From OpenAI, Anthropic, Google, or Alibaba (free tier available for some providers)
- **Internet Connection** — To communicate with AI APIs

### Getting Started

1. **Open the Platform**
   - Write Practice: Open `index.html` in your browser
   - Speaking Practice: Open `speaking.html` in your browser

2. **Configure Your Settings**
   - Select your **Native Language** (dropdown in navbar)
   - Select your **Target Language** (dropdown in navbar)
   - Choose your **AI Provider** and **Model**
   - Enter your **API Key** in the top navbar

3. **Start Practicing**
   
   **For Writing:**
   - Type or paste text in your target language
   - Click **"Check My Writing"**
   - Review corrections with explanations
   - Ask follow-up questions about grammar or corrections
   
   **For Speaking:**
   - Choose a conversation topic from the dropdown
   - Click **"New Chat"** to start
   - Type your response in the target language
   - Review corrections and tips in the right panel

### How It Works

#### Writing Correction Flow
1. User writes text in the target language
2. AI analyzes the text for all types of errors
3. AI returns:
   - Overall score (1-10) and assessment
   - List of corrections with explanations
   - Fully corrected version
4. User can ask follow-up questions for clarification

#### Speaking Conversation Flow
1. AI initiates conversation in the target language based on chosen scenario
2. User responds in the target language
3. AI provides:
   - Natural conversational reply
   - Corrections (if any errors)
   - Enhanced phrasing (more natural way to say it)
   - Language tips and cultural notes
4. Conversation continues naturally with per-message feedback

### Customization

**Appearance Settings** (click ⚙️ icon):
- **Theme**: Light, Dark, or follow System preference
- **Accent Color**: Choose from 9 colors (Blue, Purple, Pink, Red, Orange, Amber, Green, Teal, Cyan)
- **Font Size**: Adjust editor text size (12px - 28px)

**Focus Mode** (click arrow button on editor):
- Hide the correction panel for distraction-free writing/speaking
- Useful when typing on smaller screens

### API Key Setup

**Important**: The application sends text to AI APIs for processing. Your API key is stored locally in your browser (not sent to any server).

#### OpenAI
1. Sign up at https://platform.openai.com
2. Go to API Keys section
3. Create a new API key
4. Paste it in the navbar

#### Anthropic Claude
1. Sign up at https://console.anthropic.com
2. Create an API key
3. Paste it in the navbar

#### Google Gemini
1. Sign up at https://ai.google.dev
2. Create an API key
3. Paste it in the navbar

#### Alibaba Qwen
1. Sign up at https://dashscope.aliyuncs.com
2. Create an API key
3. Paste it in the navbar

### Supported Languages
Arabic, Bengali, Chinese (Simplified), Chinese (Traditional), Czech, Danish, Dutch, English, Finnish, French, German, Greek, Hebrew, Hindi, Hungarian, Indonesian, Italian, Japanese, Korean, Malay, Norwegian, Persian, Polish, Portuguese, Romanian, Russian, Spanish, Swedish, Thai, Turkish, Ukrainian, Vietnamese

### Browser Storage
The app stores the following locally (no cloud sync):
- Theme preference and colors
- Selected languages
- Font size
- API keys (encrypted preference)
- Conversation history (temporary, cleared on page refresh)

### Tips & Best Practices

- **Start with shorter sentences** to get immediate feedback before writing longer texts
- **Choose relevant conversation topics** to practice vocabulary in specific contexts
- **Review explanations carefully** — they help you understand grammar rules in your native language
- **Use focus mode** when you want to concentrate on writing without distractions
- **Try different AI models** — some are faster, others more detailed

### Troubleshooting

**"Please enter your API key"**
- Add your API key in the navbar and make sure it's saved

**Response seems incorrect or generic**
- Check that you selected the correct target and native languages
- Try a different AI model (some are more reliable than others)
- Ensure your internet connection is stable

**Text not saving between sessions**
- Writing/speaking content is reset when you refresh; use browser session storage
- Settings and API keys are saved permanently

### Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for bugs and feature requests.

### License
MIT License — See LICENSE file for details

### Support
For questions or issues, please open an issue in the project repository.

---

## 中文版本 (Chinese)

### 概述
欢迎来到 **AI 语言学习平台**！本项目帮助语言学习者在目标语言中进行写作和对话练习，并获得实时的 AI 反馈。获得即时的语法纠正、语法解释、词汇提示和根据您的目标语言定制的对话练习。

### 主要特性

#### 写作练习 (`index.html`)
- 📝 **全面文本纠正** — 自由写作并获得全面反馈
- ✅ **错误检测** — 识别语法、拼写、词汇和风格问题
- 🔄 **改进建议** — 查看更正版本及解释
- 💬 **后续问题** — 询问 AI 澄清语法规则
- 📊 **写作评估** — 获得评分（1-10）和详细反馈

#### 口语练习 (`speaking.html`)
- 🗣️ **自然对话** — 用目标语言与 AI 聊天
- 🎭 **9 个对话场景**：
  - 自由对话
  - 餐厅用餐
  - 购物
  - 旅游和方向
  - 看医生
  - 求职面试
  - 酒店入住
  - 电话通话
  - 与朋友相聚
- ✏️ **逐句纠正** — 获得每个句子的即时反馈
- 💡 **语言技巧** — 用您的母语学习语法规则和词汇
- ✨ **表达优化建议** — 看更自然的表达方式

#### 共享功能
- 🌐 **30+ 种语言支持** — 任何母语和目标语言组合
- 🎨 **可自定义主题** — 浅色/深色/系统主题，9 种强调色
- 📱 **响应式设计** — 在桌面和移动浏览器上运行
- 🔑 **多个 AI 提供商**：
  - OpenAI (GPT-4o, GPT-4o Mini, 等)
  - 阿里巴巴通义千问 (Qwen-Max, Qwen-Plus, 等)
  - 谷歌 Gemini (2.0 Flash, 1.5 Pro, 等)
  - Anthropic Claude (Sonnet 4, 3.5 Sonnet, 等)
- 💾 **本地存储** — 所有设置保存在本地浏览器中

### 项目结构
```
LanguageLearning/
├── index.html          # AI 写作练习页面
├── speaking.html       # AI 口语练习页面
├── README.md           # 此文件
└── LICENSE             # MIT 许可证
```

### 系统要求
- **现代网络浏览器** — Chrome、Firefox、Safari、Edge（启用 JavaScript）
- **API 密钥** — 来自 OpenAI、Anthropic、Google 或阿里巴巴
- **互联网连接** — 与 AI API 通信

### 快速开始

1. **打开平台**
   - 写作练习：在浏览器中打开 `index.html`
   - 口语练习：在浏览器中打开 `speaking.html`

2. **配置设置**
   - 选择您的**母语**（导航栏下拉菜单）
   - 选择您的**目标语言**（导航栏下拉菜单）
   - 选择您的 **AI 提供商**和**模型**
   - 在导航栏中输入您的 **API 密钥**

3. **开始练习**
   
   **写作**：
   - 用目标语言输入或粘贴文本
   - 点击**"检查我的写作"**
   - 查看带解释的纠正
   - 对语法或纠正提问
   
   **口语**：
   - 从下拉菜单中选择对话主题
   - 点击**"新对话"**开始
   - 用目标语言输入您的回应
   - 在右侧面板中查看纠正和提示

### 自定义

**外观设置**（点击 ⚙️ 图标）：
- **主题**：浅色、深色或跟随系统偏好
- **强调色**：从 9 种颜色中选择
- **字体大小**：调整编辑器文本大小（12px - 28px）

**专注模式**（点击编辑器上的箭头按钮）：
- 隐藏纠正面板以进行无干扰的写作/口语
- 在小屏幕上输入时很有用

### 支持的语言
阿拉伯语、孟加拉语、汉语（简体）、汉语（繁体）、捷克语、丹麦语、荷兰语、英语、芬兰语、法语、德语、希腊语、希伯来语、印地语、匈牙利语、印度尼西亚语、意大利语、日语、韩语、马来语、挪威语、波斯语、波兰语、葡萄牙语、罗马尼亚语、俄语、西班牙语、瑞典语、泰语、土耳其语、乌克兰语、越南语

### 浏览器存储
该应用本地存储以下内容（无云同步）：
- 主题偏好和颜色
- 选定的语言
- 字体大小
- API 密钥
- 对话历史（临时，页面刷新时清除）

### 提示和最佳实践

- **从较短的句子开始** — 在写较长文本前获得即时反馈
- **选择相关的对话主题** — 在特定背景下练习词汇
- **仔细阅读解释** — 它们帮助您在母语中理解语法规则
- **使用专注模式** — 当您想集中注意力而不被打扰时
- **尝试不同的 AI 模型** — 有些速度更快，有些更详细

### 许可证
MIT 许可证 — 详见 LICENSE 文件

### Support （支持）
如有任何问题，请在项目存储库中打开一个议题。
