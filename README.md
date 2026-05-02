# 🔍 WhatsApp Number Checker Pro



![WhatsApp Check](https://img.shields.io/badge/Active-0%2F0%20(0%25)

-lightgrey)


![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/shanzyxcl/wa-cheker/main.yml)




![Last Commit](https://img.shields.io/github/last-commit/shanzyxcl/wa-cheker)



Automated WhatsApp number validation using GitHub Actions with multiple check methods.

## ✨ Features

- 🔄 **Multiple Methods**: API, Selenium, or Both
- 📊 **Detailed Reports**: JSON, Excel, Markdown
- 📈 **Trend Analysis**: Historical tracking
- 🔔 **Telegram Notifications**: Real-time updates
- 🕐 **Scheduled Runs**: Daily automatic checks
- 💾 **Auto-save Results**: Commit to repository
- 🎯 **High Accuracy**: Cross-verification option

## 🚀 Quick Start

### Manual Run

1. Go to **Actions** tab
2. Click **WhatsApp Number Checker Pro**
3. Click **Run workflow**
4. Select options:
   - **Delay**: 3-5 seconds (recommended)
   - **Method**: `api` (fast), `selenium` (accurate), `both` (best)
   - **Notify**: Enable Telegram notification
5. Wait for completion (~5-10 minutes)
6. Download results from **Artifacts**

### Scheduled Run

Automatically runs **daily at 00:00 UTC**. Check the Actions tab for results.

## 📊 Results

Last checked: 2025-05-03 12:00 UTC

### Latest Results

- ✅ Active: [View](results/latest/active.txt)
- 📊 Summary: [View](results/latest/REPORT.md)
- 📈 Trends: [View](results/latest/TREND.md)
- 📥 Excel: [Download](results/latest/report.xlsx)

### History

All runs are saved in [results/history](results/history)

## 🔔 Telegram Notifications

1. Create bot: [@BotFather](https://t.me/botfather)
2. Get chat ID: [@userinfobot](https://t.me/userinfobot)
3. Add secrets:
   - `TELEGRAM_BOT_TOKEN`
   - `TELEGRAM_CHAT_ID`

## 📝 Add/Update Numbers

Edit `numbers.txt` and push to trigger automatic check:

```bash
echo "584123456789" >> numbers.txt
git add numbers.txt
git commit -m "Add new number"
git push
