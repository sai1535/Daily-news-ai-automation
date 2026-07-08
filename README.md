# Daily-news-ai-automation


A Zapier automation that fetches AI and tech news daily and sends a curated digest to your email.

## What It Does

1. **Triggers daily at 8:00 AM** via Schedule by Zapier
2. **Fetches AI news** from Hacker News RSS (AI topic)
3. **Fetches general tech news** from Hacker News RSS
4. **Formats stories** as structured line items using Formatter
5. **Uses GPT-4.1 AI** to create a professional news digest with top 5-8 stories
6. **Emails the digest** to reddygirl1535@gmail.com

## Paid Features Used

- ✅ **Multi-Step Zaps** (6 steps) — Requires Professional plan or higher
- ✅ **AI by Zapier** (GPT-4.1 with web browsing) — Available on Professional tier

## Setup Instructions

### Prerequisites
- Zapier account (Professional trial or paid plan)
- OpenAI account (for GPT-4.1 access)
- Email address to receive digests

### Import to Zapier
1. Copy the contents of `zap-definition.json`
2. Go to Zapier Dashboard → **Import/Export**
3. Paste the ZDL and click Import
4. Update the recipient email in Step 6
5. Test and publish

## Customization

- **Frequency**: Change the time in Step 1 (currently 8:00 AM)
- **News Topics**: Modify RSS URLs in Steps 2-3
- **AI Model**: Switch to GPT-4o or Claude in Step 5
- **Email Recipients**: Update email address in Step 6

## Data Flow

Schedule (Daily 8:00 AM)

↓
Fetch AI News (Hacker News RSS)

↓
Fetch Tech News (Hacker News RSS)

↓
Format as Line Items

↓
Generate Digest with AI (GPT-4.1)

↓
Send Email
project link https://zapier.com/app/zap/371874310
