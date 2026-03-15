<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Sahil's Dashboard</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>
:root {
  --bg: #0d0d0f;
  --surface: #16161a;
  --surface2: #1e1e24;
  --border: #2a2a35;
  --accent: #c8f135;
  --accent2: #7c6af7;
  --text: #f0f0f0;
  --muted: #6b6b7b;
  --danger: #ff5a5a;
  --warn: #ffb547;
  --success: #4ade80;
}
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: 'DM Sans', sans-serif; background: var(--bg); color: var(--text); min-height: 100vh; overflow-x: hidden; }

/* background grid */
body::before {
  content: '';
  position: fixed; inset: 0;
  background-image:
    linear-gradient(rgba(200,241,53,0.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(200,241,53,0.03) 1px, transparent 1px);
  background-size: 40px 40px;
  pointer-events: none; z-index: 0;
}

.wrap { position: relative; z-index: 1; max-width: 900px; margin: 0 auto; padding: 0 1.5rem; }

/* HEADER */
header { padding: 2rem 0 0; }
.header-inner { display: flex; align-items: flex-start; justify-content: space-between; gap: 1rem; flex-wrap: wrap; }
.greeting { font-family: 'Syne', sans-serif; font-size: 2.4rem; font-weight: 800; line-height: 1.15; letter-spacing: -0.03em; }
.greeting span { color: var(--accent); }
.tagline { font-size: 0.9rem; color: var(--muted); margin-top: 0.5rem; line-height: 1.6; max-width: 420px; }
.header-right { text-align: right; }
.date-box { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 0.75rem 1.1rem; display: inline-block; }
.date-box .time { font-family: 'Syne', sans-serif; font-size: 1.5rem; font-weight: 700; color: var(--accent); }
.date-box .datestr { font-size: 0.75rem; color: var(--muted); margin-top: 2px; }

/* DIVIDER */
.divider { border: none; border-top: 1px solid var(--border); margin: 2rem 0; }

/* SECTION LABEL */
.section-label { font-size: 0.7rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.1em; color: var(--muted); margin-bottom: 1rem; }

/* TOOL CARDS */
.tools-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 16px; margin-bottom: 2rem; }
.tool-card {
  background: var(--surface);
  border: 1px solid var(--border);
  border-radius: 18px;
  padding: 1.75rem;
  text-decoration: none;
  display: block;
  transition: all 0.25s;
  position: relative;
  overflow: hidden;
}
.tool-card::before {
  content: '';
  position: absolute; top: 0; left: 0; right: 0; height: 2px;
  background: var(--card-accent, var(--accent));
  opacity: 0;
  transition: opacity 0.25s;
}
.tool-card:hover { border-color: var(--card-accent, var(--accent)); transform: translateY(-3px); background: var(--surface2); }
.tool-card:hover::before { opacity: 1; }
.tool-card.nepse { --card-accent: #c8f135; }
.tool-card.habit { --card-accent: #7c6af7; }

.tool-icon { font-size: 2rem; margin-bottom: 1rem; display: block; }
.tool-name { font-family: 'Syne', sans-serif; font-size: 1.15rem; font-weight: 700; color: var(--text); margin-bottom: 0.4rem; }
.tool-desc { font-size: 0.83rem; color: var(--muted); line-height: 1.6; margin-bottom: 1.1rem; }
.tool-features { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 1.25rem; }
.feat-tag { font-size: 0.7rem; padding: 3px 10px; border-radius: 20px; background: var(--surface2); color: var(--muted); border: 1px solid var(--border); }
.tool-link { display: inline-flex; align-items: center; gap: 6px; font-size: 0.82rem; font-weight: 500; color: var(--card-accent, var(--accent)); }
.tool-link::after { content: '→'; transition: transform 0.2s; }
.tool-card:hover .tool-link::after { transform: translateX(4px); }

/* STATS ROW */
.stats-row { display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 10px; margin-bottom: 2rem; }
.stat-mini { background: var(--surface); border: 1px solid var(--border); border-radius: 12px; padding: 0.9rem 1rem; }
.stat-mini .lbl { font-size: 0.68rem; color: var(--muted); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 5px; }
.stat-mini .val { font-family: 'Syne', sans-serif; font-size: 1.25rem; font-weight: 700; }
.val-green { color: var(--accent); }
.val-purple { color: var(--accent2); }
.val-warn { color: var(--warn); }

/* QUOTE */
.quote-box { background: linear-gradient(135deg, rgba(124,106,247,0.08), rgba(200,241,53,0.04)); border: 1px solid rgba(124,106,247,0.2); border-radius: 14px; padding: 1.25rem 1.5rem; margin-bottom: 2rem; }
.quote-text { font-size: 0.92rem; line-height: 1.7; color: var(--text); font-style: italic; }
.quote-author { font-size: 0.75rem; color: var(--muted); margin-top: 0.5rem; }

/* QUICK LINKS */
.links-row { display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 2.5rem; }
.quick-link { display: inline-flex; align-items: center; gap: 7px; padding: 0.55rem 1rem; border-radius: 30px; border: 1px solid var(--border); background: var(--surface); color: var(--muted); font-size: 0.8rem; text-decoration: none; transition: all 0.18s; }
.quick-link:hover { border-color: var(--accent2); color: var(--text); }
.quick-link .dot { width: 6px; height: 6px; border-radius: 50%; background: var(--accent); }

/* FOOTER */
footer { border-top: 1px solid var(--border); padding: 1.5rem 0; text-align: center; }
footer p { font-size: 0.75rem; color: var(--muted); }
footer span { color: var(--accent); }

@media (max-width: 500px) {
  .greeting { font-size: 1.8rem; }
  .header-right { display: none; }
}
</style>
</head>
<body>
<div class="wrap">

  <header>
    <div class="header-inner">
      <div>
        <div class="greeting">Hey, <span>Sahil</span> 👋</div>
        <p class="tagline">Your personal finance & productivity dashboard. Track markets, build habits, stay disciplined.</p>
      </div>
      <div class="header-right">
        <div class="date-box">
          <div class="time" id="clock">--:--</div>
          <div class="datestr" id="datestr">Loading...</div>
        </div>
      </div>
    </div>
  </header>

  <hr class="divider"/>

  <div class="section-label">Quick Stats</div>
  <div class="stats-row">
    <div class="stat-mini"><div class="lbl">Today's Habits</div><div class="val val-green" id="stat-habits">—</div></div>
    <div class="stat-mini"><div class="lbl">Weekly Score</div><div class="val val-purple" id="stat-weekly">—</div></div>
    <div class="stat-mini"><div class="lbl">Portfolio Items</div><div class="val val-green" id="stat-portfolio">—</div></div>
    <div class="stat-mini"><div class="lbl">Watchlist</div><div class="val val-warn" id="stat-watchlist">—</div></div>
    <div class="stat-mini"><div class="lbl">Best Streak</div><div class="val val-green" id="stat-streak">—</div></div>
  </div>

  <div class="section-label">My Tools</div>
  <div class="tools-grid">

    <a href="index.html" class="tool-card nepse">
      <span class="tool-icon">📈</span>
      <div class="tool-name">NEPSE Tracker</div>
      <div class="tool-desc">Track your Nepal stock market portfolio, monitor watchlist stocks, log transactions and analyze any stock with PE, PB and dividend yield metrics.</div>
      <div class="tool-features">
        <span class="feat-tag">Portfolio</span>
        <span class="feat-tag">Watchlist</span>
        <span class="feat-tag">Transactions</span>
        <span class="feat-tag">Stock Analysis</span>
      </div>
      <div class="tool-link">Open NEPSE Tracker</div>
    </a>

    <a href="habit-tracker.html" class="tool-card habit">
      <span class="tool-icon">💪</span>
      <div class="tool-name">Habit Coach</div>
      <div class="tool-desc">Build discipline through daily check-ins, weekly reviews and behavioral analysis. Your personal performance coach that holds you accountable.</div>
      <div class="tool-features">
        <span class="feat-tag">Daily Check-in</span>
        <span class="feat-tag">Streak Tracking</span>
        <span class="feat-tag">Weekly Review</span>
        <span class="feat-tag">Coach Analysis</span>
      </div>
      <div class="tool-link">Open Habit Coach</div>
    </a>

  </div>

  <div class="section-label">Daily Motivation</div>
  <div class="quote-box">
    <div class="quote-text" id="quote-text">"Loading..."</div>
    <div class="quote-author" id="quote-author">—</div>
  </div>

  <div class="section-label">Useful Links</div>
  <div class="links-row">
    <a href="https://merolagani.com" target="_blank" class="quick-link"><span class="dot"></span>MeroLagani</a>
    <a href="https://sharesansar.com" target="_blank" class="quick-link"><span class="dot"></span>ShareSansar</a>
    <a href="https://nepseindex.com" target="_blank" class="quick-link"><span class="dot"></span>NEPSE Index</a>
    <a href="https://idp.icai.org" target="_blank" class="quick-link"><span class="dot"></span>ICAI Portal</a>
    <a href="https://meroshare.cdsc.com.np" target="_blank" class="quick-link"><span class="dot"></span>MeroShare</a>
    <a href="https://app.quickbooks.com" target="_blank" class="quick-link"><span class="dot"></span>QuickBooks</a>
  </div>

</div>

<footer>
  <div class="wrap">
    <p>Built by <span>Sahil</span> · Kathmandu, Nepal · CA Final 2028 🎯</p>
  </div>
</footer>

<script>
// Clock
function updateClock() {
  const now = new Date();
  document.getElementById('clock').textContent = now.toLocaleTimeString('en-US', {hour:'2-digit', minute:'2-digit'});
  document.getElementById('datestr').textContent = now.toLocaleDateString('en-GB', {weekday:'short', day:'numeric', month:'short', year:'numeric'});
}
setInterval(updateClock, 1000); updateClock();

// Pull stats from localStorage (set by the other tools)
function loadStats() {
  try {
    const habits = JSON.parse(localStorage.getItem('hc_habits') || '[]');
    const checkins = JSON.parse(localStorage.getItem('hc_checkins') || '[]');
    const portfolio = JSON.parse(localStorage.getItem('nepse_portfolio') || '[]');
    const watchlist = JSON.parse(localStorage.getItem('nepse_watchlist') || '[]');

    // Today's check-in
    const today = new Date().toISOString().slice(0,10);
    const tc = checkins.find(c => c.date === today);
    document.getElementById('stat-habits').textContent = tc ? tc.score + '%' : (habits.length ? '0/' + habits.length : '—');

    // Weekly avg
    const last7 = checkins.slice(0, 7);
    const weekAvg = last7.length ? Math.round(last7.reduce((s,c) => s+c.score, 0) / last7.length) + '%' : '—';
    document.getElementById('stat-weekly').textContent = weekAvg;

    // Portfolio & watchlist
    document.getElementById('stat-portfolio').textContent = portfolio.length || '—';
    document.getElementById('stat-watchlist').textContent = watchlist.length || '—';

    // Best streak
    let bestStreak = 0;
    habits.forEach(h => {
      let streak = 0, max = 0;
      [...checkins].sort((a,b) => a.date < b.date ? 1 : -1).forEach(c => {
        if (c.statuses && c.statuses[h.id] === 'done') { streak++; max = Math.max(max, streak); } else streak = 0;
      });
      bestStreak = Math.max(bestStreak, max);
    });
    document.getElementById('stat-streak').textContent = bestStreak ? bestStreak + 'd' : '—';
  } catch(e) {}
}
loadStats();

// Quotes
const quotes = [
  { text: "Success is the sum of small efforts, repeated day in and day out.", author: "Robert Collier" },
  { text: "Discipline is the bridge between goals and accomplishment.", author: "Jim Rohn" },
  { text: "The secret of getting ahead is getting started.", author: "Mark Twain" },
  { text: "It does not matter how slowly you go as long as you do not stop.", author: "Confucius" },
  { text: "We are what we repeatedly do. Excellence, then, is not an act, but a habit.", author: "Aristotle" },
  { text: "Your future is created by what you do today, not tomorrow.", author: "Robert Kiyosaki" },
  { text: "Push yourself, because no one else is going to do it for you.", author: "Unknown" },
  { text: "Hard work beats talent when talent doesn't work hard.", author: "Tim Notke" },
  { text: "Don't watch the clock; do what it does — keep going.", author: "Sam Levenson" },
  { text: "The man who moves a mountain begins by carrying away small stones.", author: "Confucius" },
  { text: "Financial freedom is available to those who learn about it and work for it.", author: "Robert Kiyosaki" },
  { text: "An investment in knowledge pays the best interest.", author: "Benjamin Franklin" },
];
const q = quotes[new Date().getDate() % quotes.length];
document.getElementById('quote-text').textContent = '"' + q.text + '"';
document.getElementById('quote-author').textContent = '— ' + q.author;
</script>
</body>
</html>
