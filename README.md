<div align="center">

# 🤖 Rasta AI Telegram Bot | چت بات هوش مصنوعی «رستا»

**دستیار هوش مصنوعی چندمدله تلگرام با شخصیت‌های تخصصی (`persona`)، وب‌سرچ زنده چندموتوره، استریمینگ زنده، حالت روح (Inline)، پردازش ویس و تصویر، ابزارهای لحظه‌ای بازار ایران و سیستم پرداخت خودکار کارت‌به‌کارت**

*A Next-Generation Multi-Model Telegram AI Assistant with Specialized Personas (`persona`), Multi-Engine Live Web Search, Rich Streaming, Inline Ghost Mode, Voice & Vision, Real-Time Iran Market Tools, and Automated SMS Card-to-Card Payments*

[![Python 3.11+](https://img.shields.io/badge/Python-3.11%2B-3776AB?logo=python&logoColor=white)](#)
[![aiogram 3.31](https://img.shields.io/badge/aiogram-3.31.0-2CA5E0?logo=telegram&logoColor=white)](#)
[![SQLite Async](https://img.shields.io/badge/Database-aiosqlite-003B57?logo=sqlite&logoColor=white)](#)
[![Models](https://img.shields.io/badge/LLMs-Rasta%20Auto%20%7C%20Gemini%203.8%20%7C%20Claude%205.5%20%7C%20PyCourse%20Lite-8E75B2)](#)
[![Payments](https://img.shields.io/badge/Payment-CartBeCart%20Auto%20SMS-00C853)](#)
[![License](https://img.shields.io/badge/License-Proprietary-red)](#)

[**🇮🇷 مستندات فارسی**](#-مستندات-فارسی) • [**🇬🇧 English Documentation**](#-english-documentation)

</div>

---

# 🇮🇷 مستندات فارسی

## ✨ معرفی پروژه
**رستا (Rasta)** یک ربات هوش مصنوعی پیشرفته و دوزبانه (فارسی/انگلیسی) در تلگرام است که روی `aiogram 3.31` و معماری کاملاً ناهمگام (`asyncio`) توسعه داده شده است. رستا از **۴ مدل هوش مصنوعی مکمل**، **۶ شخصیت تخصصی قابل انتخاب (`/persona`)**، **وب‌سرچ زنده و تقویم لحظه‌ای روز**، استریمینگ زنده پیام‌ها با شمارنده ثانیه فکر کردن (`Thinking Timer`)، حالت روح (`Ghost Mode`) در تمام چت‌های تلگرام، پردازش صدا و تصویر، موزیک‌یاب، نرخ لحظه‌ای طلا و دلار و سیستم اشتراک با درگاه **کارت‌به‌کارت خودکار پیامکی (`pay.pycourse.ir`) + تأیید دستی رسید** بهره می‌برد.

---

## 🧠 معماری مدل‌های هوش مصنوعی (`model`)

رستا از ۴ مدل مکمل پشتیبانی می‌کند که کاربر از منوی `/model` می‌تواند در هر لحظه بین آن‌ها جابه‌جا شود:

| مدل | ویژگی‌ها و کاربرد | سهمیه | دسترسی |
| :--- | :--- | :--- | :--- |
| **🚀 Rasta Auto** | ترکیبی از چند مدل پرسرعت و سطح پایه، بهینه‌شده برای کارهای روزمره، ترجمه، خلاصه‌سازی و پرسش‌های عمومی | ۳۰ پیام ۲۰۰ توکنی / روز | **رایگان همیشگی برای همه کاربران** (بدون محدودیت ۲ ماهه) |
| **🔮 Gemini 3.8 Flash** | مدل اصلی همه‌فن‌حریف با پشتیبانی از بینایی ماشین (تحلیل عکس)، ویس، موزیک‌یاب و ابزارهای زنده بازار ایران | روزانه (واحد ۱۵۰ توکنی) | رایگان تا ۲ ماه (۲۰ پیام/روز) + افزایش سهمیه در اشتراک‌ها |
| **🧠 Claude Sonnet 5.5** | مدل قدرتمند استدلال، کدنویسی حرفه‌ای، تحلیل عمیق و پاسخ‌های دقیق | روزانه (واحد ۱۵۰ توکنی) | ویژه اشتراک‌های **فلاور، گلد، رستا و هدیه** 🔒 |
| **🔹 PyCourse Lite** | مدل سبک و متنی با مصرف بهینه و محاسبه دقیق بر پایه توکن خروجی | ماهانه (ماه شمسی) | ویژه اشتراک‌های **پولی و هدیه** 🔒 |

---

## 🎭 شخصیت‌ها و حالت‌های تخصصی (`persona`)

کاربران می‌توانند با دستور `/persona` یا دکمه **«🎭 شخصیت رستا»** در منوی اصلی، نقش و لحن دستیار را با یک کلیک تغییر دهند:

- **🤝 حالت عادی رستا:** همه‌فن‌حریف، خودمانی و روان برای مکالمات روزمره
- **🎓 معلم خصوصی:** آموزش گام‌به‌گام ریاضی، فیزیک، زبان و دروس با مثال ساده
- **🌐 مترجم حرفه‌ای:** ترجمه روان و دقیق فارسی ↔ انگلیسی بدون توضیح اضافه
- **💻 دستیار برنامه‌نویسی:** کدنویسی تمیز، دیباگ سریع و معماری نرم‌افزار *(ویژه اشتراک فلاور+)*
- **📝 خلاصه‌ساز و ویراستار:** خلاصه‌سازی منظم، اصلاح غلط املایی/نیم‌فاصله و رسمی کردن متن
- **🎮 گیمر حرفه‌ای:** رفیق گیمر با اصطلاحات واقعی گیمینگ، بیلد، تنظیمات FPS و راهنمای بازی‌ها

---

## 🔥 قابلیت‌های کلیدی

### ۱. وب‌سرچ زنده چندموتوره و آگاهی از زمان حال
- تزریق خودکار تاریخ دقیق شمسی و میلادی به تمام مدل‌ها برای پاسخ‌گویی به‌روز و دقیق.
- پشتیبانی همزمان از **موتور ۵گانه داخلی (`ddgs` + ویکی‌پدیا فارسی/انگلیسی + Google News RSS + `iran_news_mcp`)** و **اسکیل جستجوی هوشمند با قابلیت سوییچ زنده و Fallback خودکار.**

### ۲. استریمینگ زنده و رابط کاربری RichMessage
- **استریم زنده (`draft` / `edit` / `inline`):** پشتیبانی از `sendRichMessageDraft` تلگرام همراه با عقب‌گرد خودکار به ویرایش زنده پیام.
- **ثانیه‌شمار زنده تفکر (`Thinking Timer`):** نمایش فوری و لحظه‌ای زمان پردازش مدل پیش از شروع استریم متن.
- **قالب‌بندی هوشمند RTL و نقل‌قول کشویی:** تیتر بولد در خط اول و ادامه پاسخ درون باکس نقل‌قول کشویی (`expandable_blockquote`) با رعایت جهت راست‌به‌چپ فارسی.

### ۳. حالت روح (`Ghost Mode` — Inline Query)
- با تایپ `@bot_username سؤالت` در **هر پی‌وی، گروه یا کانال**، بدون هیچ کارت اضافی در حالت خالی، پاسخ هوش مصنوعی مستقیماً داخل همان چت استریم می‌شود.

### ۴. چندرسانه‌ای: ویس، تصویر و موزیک‌یاب
- **تبدیل ویس به متن (`Speech-to-Text`):** ارسال ویس فارسی یا انگلیسی و دریافت پاسخ مستقیم.
- **بینایی ماشین (`Vision`):** ارسال یا ریپلای روی عکس برای تحلیل، استخراج متن و حل مسئله.
- **موزیک‌یاب هوشمند (`Music Finder`):** جستجو و ارسال مستقیم فایل صوتی آهنگ‌ها از طریق `yt-dlp`.

### ۵. ابزارهای زنده بازار ایران (`/dollar` و `/gold`)
- **💵 نرخ لحظه‌ای دلار و ارز (`/dollar`):** تابلو زنده دلار، تتر، یورو، درهم، پوند و لیر از `tgju-mcp`.
- **🪙 نرخ طلا و سکه (`/gold`):** تابلو لحظه‌ای طلای ۱۸ و ۲۴ عیار، مثقال، سکه امامی، بهار آزادی، نیم، ربع و انس جهانی.
- **🛒 استعلام قیمت دیجی‌کالا:** جستجوی قیمت روز کالاها از طریق `digikala-mcp`.

### ۶. گاردریل‌های امنیتی چندلایه و معنایی
- ترکیب فیلترهای سریع Regex با گارد معنایی Embedding (همراه با Circuit Breaker و سقف زمانی ۱.۵ ثانیه) برای جلوگیری از Prompt Injection، افشای اطلاعات حساس، محتوای نامناسب و قفل کدنویسی در پلن‌های رایگان و برنز.

---

## 💎 جدول اشتراک‌ها و سهمیه‌ها (`/subs`)

سهمیه `Rasta Auto` بر پایه **واحد ۲۰۰ توکنی** (روزانه)، سهمیه `Gemini` و `Claude` بر پایه **واحد ۱۵۰ توکنی** (روزانه، ریست در `00:00` تهران) و سهمیه `PyCourse Lite` بر پایه **توکن خروجی ماهانه** محاسبه می‌شود:

| پلن اشتراک | Rasta Auto (روزانه) | Gemini 3.8 (روزانه) | Claude 5.5 (روزانه) | ویس روزانه | کدنویسی | PyCourse Lite (ماهانه) | قیمت (۳۰ روزه) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **🌱 عادی (رایگان)** | ۳۰ پیام (همیشگی) | ۲۰ پیام *(تا ۲ ماه)* | 🔒 قفل | ۵ ویس | ❌ قفل | 🔒 ویژه اشتراک | رایگان |
| **🥉 برنز (`bronze`)** | ۳۰ پیام | ۶۰ پیام | 🔒 قفل | ۱۰ ویس | ❌ قفل | `1.75x/ماه` (۱,۷۵۰ توکن) | ۷۵,۰۰۰ تومان |
| **🌸 فلاور (`flower`)** | ۳۰ پیام | ۱۰۰ پیام | **۵۰ پیام** | ۲۰ ویس | ✅ باز | `2.25x/ماه` (۲,۲۵۰ توکن) | ۱۱۰,۰۰۰ تومان |
| **🥇 گلد (`gold`)** | ۳۰ پیام | ۳۰۰ پیام | **۹۵ پیام** | ۴۰ ویس | ✅ باز | `3x/ماه` (۳,۰۰۰ توکن) | ۲۶۷,۰۰۰ تومان |
| **👑 رستا (`rasta`)** | ۳۰ پیام | ۷۰۰+ پیام | **۳۰۰ پیام** | ۷۰ ویس | ✅ باز | `4x/ماه` (۴,۰۰۰ توکن) | ۳۵۱,۰۰۰ تومان |
| **🎁 هدیه (`gift`)** | ۳۰ پیام | ۱۵۰ پیام | **۳۰ پیام** | ۱۵ ویس | ✅ باز | `2.25x/ماه` (۲,۲۵۰ توکن) | ۵ دعوت با خرید موفق |

---

## 💳 سیستم پرداخت دوگانه کارت‌به‌کارت (خودکار پیامکی + رسید تصویری)

فرآیند خرید اشتراک در رستا هم **تأیید خودکار پیامکی آنی** دارد و هم **پشتیبان دستی رسید برای مدیریت**:

1. **پیش‌فاکتور قبل از پرداخت:** نمایش مشخصات کامل اشتراک و قیمت پایه با دکمه‌های ریچ‌مسیجی **ادامه** و **انصراف**.
2. **مبلغ یکتای ریالی و تایمر لایو:** نمایش مبلغ دقیق ریالی (همراه با خورده‌ریال یکتا جهت تطبیق خودکار پیامک بانک)، دکمه‌های کپی سریع شماره کارت و مبلغ دقیق و تایمر زنده (`⏳ MM:SS`).
3. **تأیید خودکار پیامکی + پشتیبانی از تأخیر پیامک (`paid_late`):** به‌محض دریافت پیامک بانکی با مبلغ دقیق، اشتراک کاربر به‌صورت خودکار فعال می‌شود.
4. **حفظ ارسال رسید تصویری:** کاربر همچنان می‌تواند عکس رسید را روی پیام فاکتور ریپلای کند تا برای مدیر یا گروه مدیریت فوروارد شود.

---

## ⌨️ دستورات کاربران

| دستور | توضیح |
| :--- | :--- |
| `/start` | منوی اصلی، معرفی قابلیت‌ها و ثبت لینک دعوت (`referral`) |
| `/model` | مشاهده و تغییر مدل فعال (`Rasta Auto`، `Gemini 3.8`، `Claude Sonnet 5.5`، `PyCourse Lite`) |
| `/persona` | تغییر شخصیت و لحن رستا (عادی، معلم خصوصی، مترجم، برنامه‌نویس، ویراستار، گیمر) |
| `/subs` | جدول اشتراک‌های ویژه، لینک دعوت اختصاصی و خرید اشتراک |
| `/usage` | مشاهده دقیق میزان مصرف، سهمیه باقی‌مانده و زمان بازنشانی |
| `/dollar` | تابلوی لحظه‌ای نرخ دلار، تتر، یورو، درهم، پوند و لیر |
| `/gold` | تابلوی لحظه‌ای نرخ طلای ۱۸ و ۲۴ عیار، سکه و انس جهانی |
| `/lang` | تغییر زبان رابط کاربری ربات (فارسی 🇮🇷 / انگلیسی 🇬🇧) |
| `/feedback` | ارسال نظر، پیشنهاد یا گزارش باگ به تیم مدیریت |
| `/reset` | پاک‌سازی تاریخچه گفتگوی فعلی با هوش مصنوعی |
| `/help` | راهنمای کامل دستورات و امکانات ربات |

---
---

# 🇬🇧 English Documentation

## ✨ Overview
**Rasta** is a proprietary, production-grade bilingual (Persian/English) AI Telegram bot built on Python `asyncio` and `aiogram 3.31`. It orchestrates **four complementary AI models** (**Rasta Auto**, **Gemini 3.8 Flash**, **Claude Sonnet 5.5**, and **PyCourse Lite**), offers **six switchable personas (`persona`)**, integrates **multi-engine live web search** with real-time date awareness, streams replies live with a thinking timer, runs in any chat via **Inline Ghost Mode**, supports voice/vision/music, and provides a hybrid **Automated SMS Card-to-Card Payment System (`pay.pycourse.ir`) + Manual Receipt Verification**.

---

## 🧠 Multi-Model Architecture (`model`)

- **🚀 Rasta Auto:** A fast multi-model everyday blend — **permanently free** for all users (**30 messages × 200 tokens/day**, exempt from the 2-month free trial cap).
- **🔮 Gemini 3.8 Flash:** Multimodal powerhouse supporting photos, voice notes, music search, and live Iranian market tools (free for 2 months at 20 msgs/day, expanded on paid plans).
- **🧠 Claude Sonnet 5.5:** High-precision reasoning and coding model — exclusive to **Flower, Gold, Rasta, and Gift** subscribers.
- **🔹 PyCourse Lite:** Lightweight text-only model billed strictly on **monthly output tokens** — exclusive to **paid and gift** subscribers.

---

## 🎭 Specialized Personas (`persona`)

Switch Rasta's role in one tap via `/persona`:
- **🤝 Normal Rasta** — Friendly, natural everyday assistant
- **🎓 Private Tutor** — Step-by-step math, science & study coaching
- **🌐 Pro Translator** — Clean, fluent Persian ↔ English translation
- **💻 Coding Assistant** — Clean code & debugging *(Flower+ plans)*
- **📝 Editor & Summarizer** — Concise summaries, proofreading & formal rewriting
- **🎮 Pro Gamer** — Gaming buddy for builds, FPS tweaks, lore & walkthroughs

---

## 🔥 Key Features

- **Multi-Engine Live Web Search:** Combines a 5-engine concurrent search pipeline (`ddgs`, Persian/English Wikipedia API, Google News RSS, DuckDuckGo HTML, `iran_news_mcp`) with optional Skill support and automatic fallback, plus live Jalali/Gregorian date awareness.
- **Live Rich Streaming & Thinking Timer:** Uses Telegram's `sendRichMessageDraft` (with automatic edit fallback) and starts the live thinking counter immediately.
- **Inline Ghost Mode (`@bot_username <prompt>`):** Ask Rasta inside any private chat or group with clean inline results and live answer streaming.
- **Voice, Vision & Music Finder:** Processes voice notes, analyzes images, and fetches audio tracks via `yt-dlp`.
- **Real-Time Iran Market Dashboards:** Built-in `/dollar`, `/gold` (`tgju-mcp`), and Digikala price lookup (`digikala-mcp`).
- **Multi-Layer Security Guardrails:** Fast local regex checks paired with timeout-bounded semantic embedding guards.

---

## 💎 Subscription Plans & Quotas (`/subs`)

| Plan | Rasta Auto (Daily) | Gemini 3.8 (Daily) | Claude 5.5 (Daily) | Daily Voice | Coding | PyCourse Lite (Monthly) | Price (30 Days) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **🌱 Free** | 30 msgs (Always Free) | 20 msgs *(2 Months)* | 🔒 Locked | 5 | ❌ Locked | 🔒 Paid Plans | Free |
| **🥉 Bronze** | 30 msgs | 60 msgs | 🔒 Locked | 10 | ❌ Locked | `1.75x/month` (1,750 tok) | 75,000 Toman |
| **🌸 Flower** | 30 msgs | 100 msgs | **50 msgs** | 20 | ✅ Unlocked | `2.25x/month` (2,250 tok) | 110,000 Toman |
| **🥇 Gold** | 30 msgs | 300 msgs | **95 msgs** | 40 | ✅ Unlocked | `3x/month` (3,000 tok) | 267,000 Toman |
| **👑 Rasta** | 30 msgs | 700+ msgs | **300 msgs** | 70 | ✅ Unlocked | `4x/month` (4,000 tok) | 351,000 Toman |
| **🎁 Gift** | 30 msgs | 150 msgs | **30 msgs** | 15 | ✅ Unlocked | `2.25x/month` (2,250 tok) | 5 Paid Referrals |

---

## 💳 Hybrid Card-to-Card Payment System (`pay.pycourse.ir`)

1. **Pre-Invoice Preview:** Displays full plan specifications, base price, and RichMessage **Continue** / **Cancel** buttons.
2. **Unique Rial Amount & Live Countdown:** Generates a unique Rial amount (`base + 1..9999 Rial`), one-tap copy buttons for card number & exact Rial amount, and a live countdown timer (`⏳ MM:SS`).
3. **Auto SMS Confirmation + Manual Receipt Backup:** Automatically activates the 30-day subscription as soon as the bank SMS matches (including `paid_late` handling), while preserving photo receipt replies forwarded to the Management Group / Owner.

---
Rasta Isn't a Open-Source Project, Maybe soon..!
Rasta.Ai | By mfvictor | mfvictor.ir - t.me/mfvictor2
---

<div align="center">
<sub>© Rasta AI Bot — Proprietary Software. All rights reserved.</sub>
</div>
