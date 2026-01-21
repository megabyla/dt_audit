# Trade Analytics

A modern, minimal trade journal and analytics platform built for futures traders. Track your trades, analyze your edge, and improve your execution with data-driven insights.

## Features

### Performance Analytics
- **Win Rate Tracking** - Monitor your overall performance
- **R-Multiple Analysis** - Track risk-adjusted returns
- **Setup Type Breakdown** - Identify which setups work best for you
- **Real-time Stats** - See your edge emerge from the data

### Smart Insights
- **Pattern Recognition** - Automatically identifies what's working
- **Checklist Compliance** - Tracks discipline vs. outcomes
- **Edge Discovery** - Highlights your highest-performing setups
- **Actionable Recommendations** - Get specific guidance based on your data

### Mobile-First Design
- Optimized for iPhone (and all mobile devices)
- Touch-friendly interface
- Safe area support for notch/home indicator
- Responsive layout adapts to any screen size

### Data Management
- **Cloud Backend** - Secure, scalable database
- **Export Function** - Download all trades as JSON
- **Backup & Archive** - Keep snapshots of your data
- **Migration Ready** - Easy to port to other platforms

## Usage

### Adding Trades

Paste your trade log in markdown format:

```markdown
# Trade Log - Jan 21, 2026

**NQ Long | Post-10 AM | WIN ✅ (+$400 / 2.0R)**

## Setup
Post-10 AM continuation setup with clear structure

**Entry:** 21,500  
**Stop:** 21,490  
**Target:** 21,520

## What Worked
- Used checklist
- Clear 15m SMT
- Waited for inversion

## What to Refine
- Could have waited for deeper pullback
- Trailing stop too tight
```

### Supported Assets
- **NQ** - E-mini NASDAQ
- **ES** - E-mini S&P 500
- **MNQ** - Micro E-mini NASDAQ
- **MES** - Micro E-mini S&P 500

### Recognized Setup Types
- Post-10 AM
- Pre-10 AM
- Post-SSL Sweep
- Nested Setup
- Range Breakout
- Gap Stack

## Analytics

### Key Metrics Tracked
- Total trades
- Win rate
- Average R-multiple (winning trades)
- Total R (net)

### Insights Generated
- **Checklist Discipline** - Win rate with vs. without checklist
- **Setup Performance** - Which setups have the highest edge
- **Pattern Recognition** - Automatically identifies what's working

### Minimum Data Requirements
- **5 trades** - Basic insights appear
- **10+ trades** - Setup type analysis
- **20+ trades** - Deep pattern recognition

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JavaScript
- **Database:** Supabase (PostgreSQL)
- **Hosting:** Cloudflare Pages
- **Design:** Custom CSS (slate + purple theme)

## Mobile Optimization

Built with mobile-first principles:
- Touch-optimized tap targets
- Safe area insets for iPhone
- Responsive grid layouts
- Compact padding on small screens
- Optimized font sizes
- No tap highlight flashing

## Philosophy

This isn't just a trade journal—it's a **trade audit system**.

The goal is to move from **"what happened"** to **"what conditions created the outcome."**

Traditional journals track emotions and memories. This tracks:
- What conditions were present
- What rules were followed or violated  
- What the market did afterward

That's how you turn trading into engineering.

## Roadmap

Future enhancements being considered:
- [ ] Compliance layer (rule violation tracking)
- [ ] Advanced filtering (by session, HTF sweep, etc.)
- [ ] Time-based analysis (best trading hours)
- [ ] Drawdown tracking
- [ ] Chart integration
- [ ] CSV export

---

**Built by a trader, for traders. May your edge be consistent and your drawdowns minimal.**
