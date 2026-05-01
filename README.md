# citytravelguide
City Travel Guide — A smart travel planner for Chinese cities. Generates optimized itineraries with route planning (far-first + one-way), 3 speed modes (easy/standard/blitz), weather-aware adjustments, 🚨 holiday ticket alerts, 7-point attraction details, city database (20+ cities), and detailed packing checklists.
📖 Project Overview
City Travel Guide is an OpenClaw skill that generates intelligent, weather-aware travel itineraries for any Chinese city. It handles everything from route optimization and ticket reminders to packing checklists — all in one structured output.
🛠️ Installation
Method 1 — Via ClawhHub (recommended)
Visit https://clawhub.ai and search for "city-travel-guide"
Click Install → select your agent workspace
Done
Method 2 — Manual
Download city-travel-guide-full.zip
Extract to .openclaw/workspace/skills/city-travel-guide/
Ensure file is named SKILL.md
Restart OpenClaw or run openclaw skills reload
📖 Usage Tutorial
Step 1 — Trigger the skill
Say something like:
"沈阳5月2日旅游规划"
"成都3日游攻略"
"去大理玩，2天"
Step 2 — Skill asks for input (if not provided):
Info
Required?
City
✅
Days
✅
Date
⚠️
Travel mode
❌ (defaults to Standard)
Step 3 — Receive complete itinerary:
【沈阳1日游 | 5月2日】
├── 🚨 Ticket reminder (holiday alert)
├── 🌤️ Weather info + outfit tips
├── 🗺️ Optimized route map
├── ⭐ 7-dimension attraction details
├── 🕐 Detailed schedule (time-specific)
├── 🍜 Food recommendations
├── 🚇 Transport guide with costs
├── 🎒 Packing checklist
└── ⚠️ Important notes
🖼️ Screenshots / Examples
Example 1 — Input:
"沈阳5月2日旅游规划，用城市旅行技能"
Example Output (condensed):
> 🚨 【出行前必读】热门景点购票提醒
> - 沈阳故宫：今天必须买好明天的票！
## 🌤️ 出行天气参考
| 日期 | 天气 | 温度 | 穿衣 |
| 5月2日 | ☀️晴 | 22/11°C | 薄外套 |
## 📅 今日路线
市中心 → 沈阳故宫 → 中街 → 张氏帅府 → 北陵 → 返程
## ⭐ 景点深度介绍
### 📍 沈阳故宫
| 历史背景 | 🎭文化内涵 | ✨游览亮点 | 📍方位 | 🏔️建筑 | 📜典故 | 🎫门票 |
| 历史背景 | ... | ... | ... | ... | ... | ¥50 |
✨ Feature List
#
Feature
Description
1
Route Optimization
3铁律：远端优先、地理聚类、单向不回头
2
3 Travel Modes
🐌 Easy / 🚶 Standard / 💪 Blitz
3
Weather-Aware
Auto-adjusts itinerary based on real weather
4
Holiday Ticket Alert
🚨 Urgent reminder during 五一/端午/国庆
5
7-Point Attraction Details
History/Culture/Highlights/Location/Architecture/Fun Facts/Tickets
6
City Database
20+ cities: Northeast / Hot Spots / Coastal / Southwest
7
Ticket Booking Links
Direct links to official WeChat/携程/美团
8
Detailed Checklists
Tickets / ID / Payment / Electronics / Medicine / Backpack
9
Transport Calculator
Per-segment time + cost estimates
10
Budget Estimator
Transport + Tickets + Food + Shopping
1/2


🚀 Development Plan
Phase
Status
Description
v1.0
✅ Done
Basic itinerary generation
v1.5
✅ Done
Route optimization (3铁律) + 3 modes
v2.0
✅ Done
Weather API + auto-adjust
v2.5
✅ Done
Ticket booking link library
v3.0
✅ Done
Packing checklist + budget estimator
v3.5
🔄 Next
Interactive real-time booking — directly fetch live ticket availability via API
v4.0
📋
AI language switch — output itinerary in English/Japanese/Korean for foreign tourists
v4.5
📋
Custom agent routing — selector/keyword/reporter sub-agents collaborate on complex multi-city trips
