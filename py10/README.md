# ☽ MANSA — Gold Intelligence Platform

**v6.0 · 16,366 lines · 37 pages · 10 themes · 5 languages**

Professional gold trading and design platform for traders, investors, jewellers,
shop owners, and buyers across the Arab world.

---

## 🚀 Quick Start

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Configure secrets
Copy `secrets.toml.template` to `.streamlit/secrets.toml` and fill in your API keys.

**Minimum for live prices:**
- `TWELVE_DATA_API_KEY` — [free at twelvedata.com](https://twelvedata.com) (800 calls/day)

**For AI advisor (pick one):**
- `GROQ_API_KEY` — [free, fast](https://console.groq.com) ⚡ *recommended*
- `GEMINI_API_KEY` — [free from Google](https://aistudio.google.com/apikey) ✨
- `ANTHROPIC_API_KEY` — [paid, premium](https://console.anthropic.com) 🌟

**For weekly email newsletter:**
- Gmail account with 2FA enabled
- App Password from [myaccount.google.com/apppasswords](https://myaccount.google.com/apppasswords)

### 3. Run
```bash
streamlit run mansa_dashboard.py
```

---

## 🌟 Features

### For Traders
- Live gold/silver/oil/forex prices with multi-source fallback
- Technical analysis (RSI, MACD, MA50/200, Bollinger, ATR)
- Buy/sell signals with accuracy tracker
- AI advisor with 4 providers (Claude/Gemini/Groq/Local)
- Predictions leaderboard
- Backtesting simulator + stress test

### For Jewellery Shops
- 🔴 Live shop price board with TV-fullscreen mode
- Market comparison (your price vs spot)
- Invoice calculator with VAT
- Production cost calculator with alloy recipes
- Fair price checker (±8% verdict)

### For Designers
- 💎 3D design visualizer (Three.js, 5 shapes, 3 colors, 6 gemstones)
- Live PBR rendering with IBL lighting
- Side-by-side color comparison mode
- PNG export of designs
- Piece pricing with gems + labour + margin

### For Investors
- Portfolio tracking with live P&L
- Savings plans (DCA, goal-based)
- Zakat calculator with PDF report
- Journal & alerts
- Gold map (nearby shops)
- Central bank reserves data

---

## 🎨 10 Themes

1. الحضارة الإسلامية ☽ — Islamic purple/gold
2. العملة الذهبية القديمة ⬡ — Classic brown/gold
3. قاعة التداول ◈ — Bloomberg teal/blue
4. الصحراء الحمراء 🔶 — Jordanian desert terracotta
5. ليل المدينة 🌃 — City night neon
6. الزمرد الملكي 💚 — Royal emerald
7. القمر الفضي ☾ — Silver moon minimalist
8. الياسمين الدمشقي 🌼 — Damascus jasmine olive
9. الشمس الفرعونية 𓂀 — Pharaonic Egyptian
10. البحر الأبيض 🌊 — Mediterranean coastal

---

## 🌐 5 Languages

- 🇸🇦 العربية (RTL)
- 🇬🇧 English
- 🇫🇷 Français
- 🇹🇷 Türkçe
- 🇵🇰 اردو (RTL)

---

## 🤖 AI Provider Comparison

| Provider | Cost | Speed | Quality | Setup |
|----------|------|-------|---------|-------|
| ⚡ Groq | FREE | Fastest | Excellent | 2 min |
| ✨ Gemini | FREE | Fast | Excellent | 2 min |
| 🌟 Claude | Paid | Medium | Best | Requires credits |
| 🧠 Local | FREE | Instant | Good | No setup |

The app auto-selects the best available provider, or the user can pick manually
in the advisor settings.

---

## 🔐 Security Notes

- **Never commit** `.streamlit/secrets.toml` to git (already in `.gitignore`)
- API keys should only live in:
  - Streamlit Cloud → Settings → Secrets (recommended)
  - Local `.streamlit/secrets.toml` (not tracked)
  - Environment variables (for self-hosted)
- If a key is exposed, revoke it immediately at the provider's console

---

## 📧 Support

Developed with Claude · Gold intelligence for the Arab world
