<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PAI Mid-Term Notes | Pandas · NumPy · Matplotlib</title>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;600;700&family=Sora:wght@300;400;600;700;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0d0f1a;
    --surface: #131627;
    --surface2: #1a1e35;
    --border: #252a45;
    --pandas: #e94560;
    --numpy: #00c9a7;
    --mpl: #f7b731;
    --practice: #a78bfa;
    --text: #e2e8f0;
    --muted: #8892b0;
    --code-bg: #0a0c16;
    --output-bg: #0f1520;
    --accent: #64ffda;
    --white: #ffffff;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html { scroll-behavior: smooth; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Sora', sans-serif;
    font-size: 15px;
    line-height: 1.7;
    min-height: 100vh;
  }

  /* ─── HEADER ─── */
  header {
    background: linear-gradient(135deg, #0d0f1a 0%, #131627 50%, #1a1035 100%);
    border-bottom: 1px solid var(--border);
    padding: 3rem 2rem 2rem;
    text-align: center;
    position: relative;
    overflow: hidden;
  }
  header::before {
    content: '';
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: radial-gradient(ellipse at 30% 50%, rgba(233,69,96,0.07) 0%, transparent 60%),
                radial-gradient(ellipse at 70% 30%, rgba(0,201,167,0.07) 0%, transparent 60%);
    pointer-events: none;
  }
  .header-badge {
    display: inline-block;
    background: rgba(100,255,218,0.1);
    border: 1px solid rgba(100,255,218,0.3);
    color: var(--accent);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.7rem;
    letter-spacing: 3px;
    text-transform: uppercase;
    padding: 0.3rem 1rem;
    border-radius: 2rem;
    margin-bottom: 1rem;
  }
  header h1 {
    font-size: clamp(1.8rem, 5vw, 3rem);
    font-weight: 800;
    line-height: 1.2;
    margin-bottom: 0.5rem;
  }
  header h1 span.p { color: var(--pandas); }
  header h1 span.n { color: var(--numpy); }
  header h1 span.m { color: var(--mpl); }
  header p {
    color: var(--muted);
    font-size: 0.95rem;
    max-width: 600px;
    margin: 0 auto 2rem;
  }

  /* ─── NAV PILLS ─── */
  .nav-pills {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin-bottom: 0.5rem;
  }
  .nav-pill {
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    padding: 0.5rem 1.2rem;
    border-radius: 2rem;
    font-size: 0.82rem;
    font-weight: 600;
    text-decoration: none;
    border: 1px solid transparent;
    transition: all 0.2s;
    cursor: pointer;
  }
  .pill-pandas { background: rgba(233,69,96,0.15); border-color: rgba(233,69,96,0.4); color: var(--pandas); }
  .pill-numpy  { background: rgba(0,201,167,0.15); border-color: rgba(0,201,167,0.4); color: var(--numpy); }
  .pill-mpl    { background: rgba(247,183,49,0.15); border-color: rgba(247,183,49,0.4); color: var(--mpl); }
  .pill-practice { background: rgba(167,139,250,0.15); border-color: rgba(167,139,250,0.4); color: var(--practice); }
  .nav-pill:hover { transform: translateY(-2px); filter: brightness(1.2); }

  /* ─── MAIN LAYOUT ─── */
  main { max-width: 1100px; margin: 0 auto; padding: 2rem 1.5rem 4rem; }

  /* ─── SECTION HEADERS ─── */
  .section-header {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin: 3.5rem 0 2rem;
    padding-bottom: 1rem;
    border-bottom: 2px solid var(--border);
  }
  .section-icon {
    width: 50px; height: 50px;
    border-radius: 12px;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.5rem;
    flex-shrink: 0;
  }
  .icon-pandas { background: rgba(233,69,96,0.2); border: 1px solid rgba(233,69,96,0.4); }
  .icon-numpy  { background: rgba(0,201,167,0.2); border: 1px solid rgba(0,201,167,0.4); }
  .icon-mpl    { background: rgba(247,183,49,0.2); border: 1px solid rgba(247,183,49,0.4); }
  .icon-practice { background: rgba(167,139,250,0.2); border: 1px solid rgba(167,139,250,0.4); }
  .section-title { font-size: 1.6rem; font-weight: 800; }
  .section-title .s-pandas { color: var(--pandas); }
  .section-title .s-numpy  { color: var(--numpy); }
  .section-title .s-mpl    { color: var(--mpl); }
  .section-title .s-practice { color: var(--practice); }
  .section-sub { color: var(--muted); font-size: 0.85rem; margin-top: 0.2rem; }

  /* ─── TOPIC CARDS ─── */
  .topic-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 12px;
    margin-bottom: 1.5rem;
    overflow: hidden;
    transition: border-color 0.2s;
  }
  .topic-card:hover { border-color: #353a60; }

  .topic-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 1.4rem;
    cursor: pointer;
    user-select: none;
    gap: 1rem;
  }
  .topic-label {
    display: flex;
    align-items: center;
    gap: 0.7rem;
  }
  .topic-tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    padding: 0.2rem 0.6rem;
    border-radius: 4px;
    flex-shrink: 0;
  }
  .tag-pandas { background: rgba(233,69,96,0.2); color: var(--pandas); }
  .tag-numpy  { background: rgba(0,201,167,0.2); color: var(--numpy); }
  .tag-mpl    { background: rgba(247,183,49,0.2); color: var(--mpl); }
  .tag-practice { background: rgba(167,139,250,0.2); color: var(--practice); }

  .topic-title { font-size: 1rem; font-weight: 600; }
  .topic-arrow {
    color: var(--muted);
    font-size: 1.2rem;
    transition: transform 0.3s;
    flex-shrink: 0;
  }
  .topic-card.open .topic-arrow { transform: rotate(180deg); }

  .topic-body {
    display: none;
    padding: 0 1.4rem 1.4rem;
    border-top: 1px solid var(--border);
  }
  .topic-card.open .topic-body { display: block; }

  /* ─── EXPLANATION BOX ─── */
  .explain-box {
    background: var(--surface2);
    border-left: 3px solid var(--accent);
    border-radius: 0 8px 8px 0;
    padding: 0.8rem 1rem;
    margin: 1rem 0;
    font-size: 0.88rem;
    color: var(--text);
  }
  .explain-box strong { color: var(--accent); }

  /* ─── CODE BLOCK ─── */
  .code-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    color: var(--muted);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-top: 1rem;
    margin-bottom: 0.3rem;
  }
  pre {
    background: var(--code-bg);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 1rem 1.2rem;
    overflow-x: auto;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.82rem;
    line-height: 1.6;
    color: #cdd6f4;
  }
  .kw  { color: #cba6f7; } /* keyword */
  .fn  { color: #89b4fa; } /* function */
  .st  { color: #a6e3a1; } /* string */
  .cm  { color: #585b70; } /* comment */
  .nm  { color: #fab387; } /* number */
  .op  { color: #f38ba8; } /* operator */
  .cls { color: #f9e2af; } /* class */

  /* ─── OUTPUT BLOCK ─── */
  .output-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.68rem;
    color: var(--muted);
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-top: 0.8rem;
    margin-bottom: 0.3rem;
  }
  .output-block {
    background: var(--output-bg);
    border: 1px solid #1e3a2e;
    border-left: 3px solid #00c9a7;
    border-radius: 8px;
    padding: 0.9rem 1.2rem;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.8rem;
    line-height: 1.7;
    color: #a6e3a1;
    white-space: pre;
    overflow-x: auto;
  }

  /* ─── SHOW ANSWER BUTTON ─── */
  .show-btn {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    margin-top: 0.8rem;
    padding: 0.45rem 1.1rem;
    border-radius: 6px;
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.78rem;
    font-weight: 600;
    cursor: pointer;
    border: 1px solid;
    transition: all 0.2s;
    background: transparent;
  }
  .btn-pandas { color: var(--pandas); border-color: rgba(233,69,96,0.5); }
  .btn-pandas:hover { background: rgba(233,69,96,0.15); }
  .btn-numpy  { color: var(--numpy); border-color: rgba(0,201,167,0.5); }
  .btn-numpy:hover  { background: rgba(0,201,167,0.15); }
  .btn-mpl    { color: var(--mpl); border-color: rgba(247,183,49,0.5); }
  .btn-mpl:hover    { background: rgba(247,183,49,0.15); }
  .btn-practice { color: var(--practice); border-color: rgba(167,139,250,0.5); }
  .btn-practice:hover { background: rgba(167,139,250,0.15); }

  .answer-reveal { display: none; margin-top: 0.8rem; }
  .answer-reveal.visible { display: block; }

  /* ─── TABLE ─── */
  .comparison-table {
    width: 100%;
    border-collapse: collapse;
    margin: 1rem 0;
    font-size: 0.85rem;
  }
  .comparison-table th {
    background: var(--surface2);
    padding: 0.7rem 1rem;
    text-align: left;
    font-weight: 700;
    border: 1px solid var(--border);
  }
  .comparison-table td {
    padding: 0.6rem 1rem;
    border: 1px solid var(--border);
    vertical-align: top;
  }
  .comparison-table tr:nth-child(even) td { background: rgba(255,255,255,0.02); }
  .td-pandas { color: var(--pandas); font-family: 'JetBrains Mono', monospace; font-size: 0.8rem; }
  .td-numpy  { color: var(--numpy);  font-family: 'JetBrains Mono', monospace; font-size: 0.8rem; }

  /* ─── HIGHLIGHT BADGE ─── */
  .highlight-badge {
    display: inline-block;
    background: rgba(247,183,49,0.15);
    border: 1px solid rgba(247,183,49,0.4);
    color: var(--mpl);
    font-size: 0.72rem;
    font-weight: 700;
    padding: 0.15rem 0.5rem;
    border-radius: 4px;
    margin-left: 0.4rem;
    font-family: 'JetBrains Mono', monospace;
    vertical-align: middle;
  }

  /* ─── PRACTICE SECTION ─── */
  .quiz-card {
    background: var(--surface);
    border: 1px solid rgba(167,139,250,0.3);
    border-radius: 12px;
    padding: 1.2rem 1.4rem;
    margin-bottom: 1.2rem;
  }
  .quiz-q {
    font-weight: 600;
    margin-bottom: 0.6rem;
    display: flex;
    gap: 0.7rem;
    align-items: flex-start;
  }
  .q-num {
    background: rgba(167,139,250,0.2);
    color: var(--practice);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.75rem;
    font-weight: 700;
    padding: 0.15rem 0.5rem;
    border-radius: 4px;
    flex-shrink: 0;
    margin-top: 0.1rem;
  }

  /* ─── SUMMARY GRID ─── */
  .summary-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
    margin: 1rem 0;
  }
  .summary-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1rem;
  }
  .summary-card h4 {
    font-size: 0.85rem;
    font-weight: 700;
    margin-bottom: 0.6rem;
    font-family: 'JetBrains Mono', monospace;
  }
  .summary-card ul {
    list-style: none;
    font-size: 0.82rem;
    color: var(--muted);
  }
  .summary-card ul li::before { content: '→ '; color: var(--accent); }
  .summary-card ul li { margin-bottom: 0.25rem; }

  /* ─── MINI TASKS ─── */
  .mini-task {
    background: rgba(100,255,218,0.05);
    border: 1px solid rgba(100,255,218,0.2);
    border-radius: 8px;
    padding: 0.9rem 1rem;
    margin-bottom: 0.8rem;
    font-size: 0.88rem;
  }
  .mini-task strong { color: var(--accent); }

  /* ─── FOOTER ─── */
  footer {
    text-align: center;
    padding: 2rem;
    border-top: 1px solid var(--border);
    color: var(--muted);
    font-size: 0.8rem;
    font-family: 'JetBrains Mono', monospace;
  }

  /* ─── SCROLL TOP ─── */
  #scrollTop {
    position: fixed;
    bottom: 1.5rem;
    right: 1.5rem;
    background: var(--surface2);
    border: 1px solid var(--border);
    color: var(--muted);
    width: 40px; height: 40px;
    border-radius: 50%;
    font-size: 1.2rem;
    cursor: pointer;
    display: flex; align-items: center; justify-content: center;
    transition: all 0.2s;
    z-index: 100;
    opacity: 0;
    pointer-events: none;
  }
  #scrollTop.visible { opacity: 1; pointer-events: all; }
  #scrollTop:hover { background: var(--surface); color: var(--accent); border-color: var(--accent); }

  /* ─── PROGRESS BAR ─── */
  #progress-bar {
    position: fixed;
    top: 0; left: 0;
    height: 2px;
    background: linear-gradient(90deg, var(--pandas), var(--numpy), var(--mpl));
    z-index: 999;
    transition: width 0.1s;
  }
</style>
</head>
<body>

<div id="progress-bar" style="width:0%"></div>

<!-- HEADER -->
<header>
  <div class="header-badge">PAI Mid-Term Complete Notes</div>
  <h1><span class="p">Pandas</span> · <span class="n">NumPy</span> · <span class="m">Matplotlib</span></h1>
  <p>Full coverage notes with code, output, and practice questions — exam-ready reference.</p>
  <nav class="nav-pills">
    <a class="nav-pill pill-pandas" href="#pandas">🐼 Pandas</a>
    <a class="nav-pill pill-numpy"  href="#numpy">🔢 NumPy</a>
    <a class="nav-pill pill-mpl"    href="#matplotlib">📊 Matplotlib</a>
    <a class="nav-pill pill-practice" href="#practice">🎯 Practice</a>
    <a class="nav-pill pill-practice" href="#summary">📘 Summary</a>
  </nav>
</header>

<main>

<!-- ══════════════════════════════════════════════
     SECTION 1: PANDAS
══════════════════════════════════════════════ -->
<div id="pandas">
  <div class="section-header">
    <div class="section-icon icon-pandas">🐼</div>
    <div>
      <div class="section-title"><span class="s-pandas">Pandas</span> — Full Coverage</div>
      <div class="section-sub">DataFrames, Selection, Filtering, Sorting, Aggregation, Missing Data & More</div>
    </div>
  </div>

  <!-- DATASET INTRO -->
  <div class="topic-card open" id="tc-dataset">
    <div class="topic-header" onclick="toggle('tc-dataset')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Setup</span>
        <span class="topic-title">Our Practice Dataset — Students</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>📌 What is this?</strong> We create a student DataFrame with missing values (NaN). All Pandas examples below use this dataset. Think of a DataFrame like an Excel table — rows are students, columns are properties.
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="kw">import</span> pandas <span class="kw">as</span> pd
<span class="kw">import</span> numpy <span class="kw">as</span> np

data = {
    <span class="st">'Name'</span>:    [<span class="st">'Ali'</span>, <span class="st">'Sara'</span>, <span class="st">'Umar'</span>, <span class="st">'Zara'</span>, <span class="st">'Hassan'</span>, <span class="st">'Nida'</span>],
    <span class="st">'Age'</span>:     [<span class="nm">20</span>, <span class="nm">21</span>, np.nan, <span class="nm">22</span>, <span class="nm">20</span>, <span class="nm">23</span>],
    <span class="st">'Marks'</span>:   [<span class="nm">85</span>, <span class="nm">92</span>, <span class="nm">78</span>, np.nan, <span class="nm">95</span>, <span class="nm">88</span>],
    <span class="st">'Grade'</span>:   [<span class="st">'B'</span>, <span class="st">'A'</span>, <span class="st">'C'</span>, <span class="st">'B'</span>, <span class="st">'A'</span>, np.nan],
    <span class="st">'City'</span>:    [<span class="st">'Lahore'</span>, <span class="st">'Karachi'</span>, <span class="st">'Lahore'</span>, <span class="st">'Islamabad'</span>, <span class="st">'Karachi'</span>, <span class="st">'Lahore'</span>],
    <span class="st">'Passed'</span>:  [<span class="kw">True</span>, <span class="kw">True</span>, <span class="kw">True</span>, <span class="kw">False</span>, <span class="kw">True</span>, <span class="kw">True</span>]
}

df = pd.<span class="fn">DataFrame</span>(data)
<span class="fn">print</span>(df)</pre>
      <div class="output-label">Output</div>
      <div class="output-block">     Name   Age  Marks Grade       City  Passed
0     Ali  20.0   85.0     B     Lahore    True
1    Sara  21.0   92.0     A    Karachi    True
2    Umar   NaN   78.0     C     Lahore    True
3    Zara  22.0    NaN     B  Islamabad   False
4  Hassan  20.0   95.0     A    Karachi    True
5    Nida  23.0   88.0   NaN     Lahore    True</div>
    </div>
  </div>

  <!-- BASIC FUNCTIONS -->
  <div class="topic-card" id="tc-basic">
    <div class="topic-header" onclick="toggle('tc-basic')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Basic</span>
        <span class="topic-title">head() · tail() · info() · describe()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box"><strong>head(n)</strong> → first n rows &nbsp;|&nbsp; <strong>tail(n)</strong> → last n rows &nbsp;|&nbsp; <strong>info()</strong> → data types + nulls &nbsp;|&nbsp; <strong>describe()</strong> → statistics summary</div>
      <div class="code-label">Python Code</div>
<pre>df.<span class="fn">head</span>(<span class="nm">3</span>)       <span class="cm"># First 3 rows</span>
df.<span class="fn">tail</span>(<span class="nm">2</span>)       <span class="cm"># Last 2 rows</span>
df.<span class="fn">info</span>()        <span class="cm"># Column names, types, null counts</span>
df.<span class="fn">describe</span>()    <span class="cm"># Count, mean, std, min, max for numeric cols</span></pre>
      <div class="output-label">describe() Output (numeric columns)</div>
      <div class="output-block">        Age      Marks
count  5.000000   5.000000
mean  21.200000  87.600000
std    1.303840   6.580274
min   20.000000  78.000000
25%   20.000000  85.000000
50%   21.000000  88.000000
75%   22.000000  92.000000
max   23.000000  95.000000</div>
    </div>
  </div>

  <!-- SELECTION & INDEXING -->
  <div class="topic-card" id="tc-sel">
    <div class="topic-header" onclick="toggle('tc-sel')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Indexing</span>
        <span class="topic-title">Selecting Columns · loc[] · iloc[]</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Single column:</strong> df['Name'] &nbsp;|&nbsp; <strong>Multiple:</strong> df[['Name','Marks']]<br>
        <strong>loc[]</strong> = use LABELS (row name, column name)<br>
        <strong>iloc[]</strong> = use NUMBERS (row index, column index)
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Single column → Series</span>
df[<span class="st">'Name'</span>]

<span class="cm"># Multiple columns → DataFrame</span>
df[[<span class="st">'Name'</span>, <span class="st">'Marks'</span>, <span class="st">'Grade'</span>]]

<span class="cm"># loc[row_label, col_label]</span>
df.<span class="fn">loc</span>[<span class="nm">0</span>, <span class="st">'Name'</span>]           <span class="cm"># → 'Ali'</span>
df.<span class="fn">loc</span>[<span class="nm">0</span>:<span class="nm">2</span>, <span class="st">'Name'</span>:<span class="st">'Marks'</span>]   <span class="cm"># rows 0-2, cols Name to Marks</span>

<span class="cm"># iloc[row_num, col_num]</span>
df.<span class="fn">iloc</span>[<span class="nm">0</span>, <span class="nm">0</span>]      <span class="cm"># → 'Ali'  (row 0, col 0)</span>
df.<span class="fn">iloc</span>[<span class="nm">1</span>:<span class="nm">4</span>, <span class="nm">0</span>:<span class="nm">3</span>]  <span class="cm"># rows 1-3, cols 0-2</span></pre>
      <div class="output-label">loc[0:2, 'Name':'Marks'] Output</div>
      <div class="output-block">   Name   Age  Marks
0   Ali  20.0   85.0
1  Sara  21.0   92.0
2  Umar   NaN   78.0</div>
    </div>
  </div>

  <!-- FILTERING -->
  <div class="topic-card" id="tc-filter">
    <div class="topic-header" onclick="toggle('tc-filter')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Filtering</span>
        <span class="topic-title">Single Condition · AND · OR · Boolean Masking</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        Filtering means selecting rows that meet a condition. Think of it like: "Show me all students who scored above 85."
        <br>Use <strong>&amp;</strong> for AND, <strong>|</strong> for OR, and always wrap conditions in <strong>( )</strong>
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Single condition</span>
df[df[<span class="st">'Marks'</span>] > <span class="nm">85</span>]

<span class="cm"># Multiple conditions — AND (&)</span>
df[(df[<span class="st">'Marks'</span>] > <span class="nm">85</span>) & (df[<span class="st">'City'</span>] == <span class="st">'Karachi'</span>)]

<span class="cm"># Multiple conditions — OR (|)</span>
df[(df[<span class="st">'City'</span>] == <span class="st">'Lahore'</span>) | (df[<span class="st">'Marks'</span>] > <span class="nm">90</span>)]

<span class="cm"># Boolean masking (same thing, stored separately)</span>
mask = df[<span class="st">'Passed'</span>] == <span class="kw">True</span>
df[mask]</pre>
      <div class="output-label">df[df['Marks'] &gt; 85] Output</div>
      <div class="output-block">     Name   Age  Marks Grade     City  Passed
1    Sara  21.0   92.0     A  Karachi    True
4  Hassan  20.0   95.0     A  Karachi    True
5    Nida  23.0   88.0   NaN   Lahore    True</div>
    </div>
  </div>

  <!-- SORTING -->
  <div class="topic-card" id="tc-sort">
    <div class="topic-header" onclick="toggle('tc-sort')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Sorting</span>
        <span class="topic-title">sort_values() · sort_index()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>sort_values()</strong> → sort by column values &nbsp;|&nbsp; <strong>sort_index()</strong> → sort by row index number.<br>
        Use <strong>ascending=False</strong> for descending (highest first).
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Sort by Marks ascending (low to high)</span>
df.<span class="fn">sort_values</span>(<span class="st">'Marks'</span>)

<span class="cm"># Sort by Marks descending (high to low)</span>
df.<span class="fn">sort_values</span>(<span class="st">'Marks'</span>, ascending=<span class="kw">False</span>)

<span class="cm"># Sort by multiple columns</span>
df.<span class="fn">sort_values</span>([<span class="st">'City'</span>, <span class="st">'Marks'</span>], ascending=[<span class="kw">True</span>, <span class="kw">False</span>])

<span class="cm"># Sort by index</span>
df.<span class="fn">sort_index</span>(ascending=<span class="kw">False</span>)</pre>
      <div class="output-label">sort_values('Marks', ascending=False) Output</div>
      <div class="output-block">     Name   Age  Marks Grade       City  Passed
4  Hassan  20.0   95.0     A    Karachi    True
1    Sara  21.0   92.0     A    Karachi    True
5    Nida  23.0   88.0   NaN     Lahore    True
0     Ali  20.0   85.0     B     Lahore    True
2    Umar   NaN   78.0     C     Lahore    True
3    Zara  22.0    NaN     B  Islamabad   False</div>
    </div>
  </div>

  <!-- COLUMN OPERATIONS -->
  <div class="topic-card" id="tc-col">
    <div class="topic-header" onclick="toggle('tc-col')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Columns</span>
        <span class="topic-title">Add · Delete · Rename Columns</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">Think of columns like adding/removing/renaming headers in an Excel spreadsheet.</div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Add new column</span>
df[<span class="st">'Percentage'</span>] = df[<span class="st">'Marks'</span>] / <span class="nm">100</span> * <span class="nm">100</span>  <span class="cm"># same here</span>
df[<span class="st">'Status'</span>]     = <span class="st">'Active'</span>  <span class="cm"># constant value for all rows</span>

<span class="cm"># Delete column</span>
df.<span class="fn">drop</span>(<span class="st">'Status'</span>, axis=<span class="nm">1</span>, inplace=<span class="kw">True</span>)
<span class="cm"># axis=1 means column, inplace=True saves changes</span>

<span class="cm"># Rename column</span>
df.<span class="fn">rename</span>(columns={<span class="st">'Marks'</span>: <span class="st">'Score'</span>, <span class="st">'City'</span>: <span class="st">'Location'</span>}, inplace=<span class="kw">True</span>)

<span class="cm"># See all column names</span>
<span class="fn">print</span>(df.columns)</pre>
      <div class="output-label">After rename — columns</div>
      <div class="output-block">Index(['Name', 'Age', 'Score', 'Grade', 'Location', 'Passed', 'Percentage'], dtype='object')</div>
    </div>
  </div>

  <!-- ROW OPERATIONS -->
  <div class="topic-card" id="tc-row">
    <div class="topic-header" onclick="toggle('tc-row')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Rows</span>
        <span class="topic-title">Add Row · Delete Row</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Add row:</strong> use pd.concat() with a new 1-row DataFrame.<br>
        <strong>Delete row:</strong> use df.drop(index) — axis=0 means row (default).
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Add a new row</span>
new_row = pd.<span class="fn">DataFrame</span>([{
    <span class="st">'Name'</span>: <span class="st">'Ahmed'</span>, <span class="st">'Age'</span>: <span class="nm">22</span>, <span class="st">'Marks'</span>: <span class="nm">90</span>,
    <span class="st">'Grade'</span>: <span class="st">'A'</span>, <span class="st">'City'</span>: <span class="st">'Lahore'</span>, <span class="st">'Passed'</span>: <span class="kw">True</span>
}])
df = pd.<span class="fn">concat</span>([df, new_row], ignore_index=<span class="kw">True</span>)

<span class="cm"># Delete row by index (delete row 3)</span>
df = df.<span class="fn">drop</span>(<span class="nm">3</span>, axis=<span class="nm">0</span>)      <span class="cm"># axis=0 means row</span>

<span class="cm"># Delete multiple rows</span>
df = df.<span class="fn">drop</span>([<span class="nm">0</span>, <span class="nm">2</span>], axis=<span class="nm">0</span>).reset_index(drop=<span class="kw">True</span>)</pre>
      <div class="output-label">After adding Ahmed (last row)</div>
      <div class="output-block">     Name   Age  Marks Grade     City  Passed
0     Ali  20.0   85.0     B   Lahore    True
1    Sara  21.0   92.0     A  Karachi    True
2    Umar   NaN   78.0     C   Lahore    True
3    Zara  22.0    NaN     B   ...      False
...
6   Ahmed  22.0   90.0     A   Lahore    True</div>
    </div>
  </div>

  <!-- AGGREGATIONS -->
  <div class="topic-card" id="tc-agg">
    <div class="topic-header" onclick="toggle('tc-agg')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Aggregation</span>
        <span class="topic-title">mean() · sum() · count() · max() · min()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">These functions calculate a <strong>single summary value</strong> from a column. They automatically skip NaN values.</div>
      <div class="code-label">Python Code</div>
<pre>df[<span class="st">'Marks'</span>].<span class="fn">mean</span>()    <span class="cm"># Average marks</span>
df[<span class="st">'Marks'</span>].<span class="fn">sum</span>()     <span class="cm"># Total marks</span>
df[<span class="st">'Marks'</span>].<span class="fn">count</span>()   <span class="cm"># Number of non-NaN values</span>
df[<span class="st">'Marks'</span>].<span class="fn">max</span>()     <span class="cm"># Highest mark</span>
df[<span class="st">'Marks'</span>].<span class="fn">min</span>()     <span class="cm"># Lowest mark</span>

<span class="cm"># Get all at once</span>
df[<span class="st">'Marks'</span>].<span class="fn">agg</span>([<span class="st">'mean'</span>, <span class="st">'sum'</span>, <span class="st">'max'</span>, <span class="st">'min'</span>])</pre>
      <div class="output-label">agg() Output</div>
      <div class="output-block">mean     87.6
sum     438.0
max      95.0
min      78.0
Name: Marks, dtype: float64</div>
    </div>
  </div>

  <!-- GROUPBY -->
  <div class="topic-card" id="tc-group">
    <div class="topic-header" onclick="toggle('tc-group')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">GroupBy</span>
        <span class="topic-title">groupby() — Group and Aggregate <span class="highlight-badge">EXAM FAVOURITE</span></span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>groupby()</strong> groups rows together by a column value, then you can do calculations on each group.<br>
        Example: "What is the average marks of students in each city?"
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Average marks per city</span>
df.<span class="fn">groupby</span>(<span class="st">'City'</span>)[<span class="st">'Marks'</span>].<span class="fn">mean</span>()

<span class="cm"># Count of students per city</span>
df.<span class="fn">groupby</span>(<span class="st">'City'</span>)[<span class="st">'Name'</span>].<span class="fn">count</span>()

<span class="cm"># Multiple aggregations</span>
df.<span class="fn">groupby</span>(<span class="st">'City'</span>)[<span class="st">'Marks'</span>].<span class="fn">agg</span>([<span class="st">'mean'</span>, <span class="st">'max'</span>, <span class="st">'count'</span>])

<span class="cm"># Group by Grade, get average marks</span>
df.<span class="fn">groupby</span>(<span class="st">'Grade'</span>)[<span class="st">'Marks'</span>].<span class="fn">mean</span>()</pre>
      <div class="output-label">groupby('City')['Marks'].mean() Output</div>
      <div class="output-block">City
Islamabad     NaN
Karachi      93.5
Lahore       81.5
Name: Marks, dtype: float64</div>
    </div>
  </div>

  <!-- MISSING DATA -->
  <div class="topic-card" id="tc-null">
    <div class="topic-header" onclick="toggle('tc-null')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Missing Data</span>
        <span class="topic-title">isnull() · fillna() · dropna() <span class="highlight-badge">IMPORTANT</span></span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>isnull()</strong> → find where NaN is &nbsp;|&nbsp; <strong>fillna()</strong> → replace NaN with something &nbsp;|&nbsp; <strong>dropna()</strong> → remove rows with NaN
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Check nulls (True = missing)</span>
df.<span class="fn">isnull</span>()

<span class="cm"># Count nulls per column</span>
df.<span class="fn">isnull</span>().<span class="fn">sum</span>()

<span class="cm"># Fill NaN in Marks with the mean</span>
df[<span class="st">'Marks'</span>].<span class="fn">fillna</span>(df[<span class="st">'Marks'</span>].<span class="fn">mean</span>(), inplace=<span class="kw">True</span>)

<span class="cm"># Fill NaN in Grade with 'Unknown'</span>
df[<span class="st">'Grade'</span>].<span class="fn">fillna</span>(<span class="st">'Unknown'</span>, inplace=<span class="kw">True</span>)

<span class="cm"># Drop rows that have ANY NaN</span>
df_clean = df.<span class="fn">dropna</span>()

<span class="cm"># Drop rows where specific column has NaN</span>
df_clean = df.<span class="fn">dropna</span>(subset=[<span class="st">'Age'</span>])</pre>
      <div class="output-label">isnull().sum() Output</div>
      <div class="output-block">Name      0
Age       1
Marks     1
Grade     1
City      0
Passed    0
dtype: int64</div>
    </div>
  </div>

  <!-- FILE HANDLING -->
  <div class="topic-card" id="tc-file">
    <div class="topic-header" onclick="toggle('tc-file')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">File I/O</span>
        <span class="topic-title">read_csv() · to_csv()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">Load data from a CSV file into a DataFrame, or save a DataFrame as a CSV file. CSV = Comma Separated Values (like Excel but plain text).</div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Read CSV file into DataFrame</span>
df = pd.<span class="fn">read_csv</span>(<span class="st">'students.csv'</span>)

<span class="cm"># Read CSV with specific options</span>
df = pd.<span class="fn">read_csv</span>(<span class="st">'students.csv'</span>,
                 header=<span class="nm">0</span>,        <span class="cm"># row 0 is the header</span>
                 index_col=<span class="nm">0</span>)     <span class="cm"># use first column as index</span>

<span class="cm"># Save DataFrame to CSV</span>
df.<span class="fn">to_csv</span>(<span class="st">'output.csv'</span>, index=<span class="kw">False</span>)
<span class="cm"># index=False → don't save row numbers</span></pre>
      <div class="output-label">Explanation</div>
      <div class="output-block">read_csv('file.csv')   → Load file → creates DataFrame
to_csv('file.csv')     → Save DataFrame → creates CSV file
index=False            → Skip saving row numbers (0,1,2...)
header=0               → Row 0 is used as column names</div>
    </div>
  </div>

  <!-- VALUE_COUNTS, UNIQUE, APPLY -->
  <div class="topic-card" id="tc-extra">
    <div class="topic-header" onclick="toggle('tc-extra')">
      <div class="topic-label">
        <span class="topic-tag tag-pandas">Extra</span>
        <span class="topic-title">value_counts() · unique() · apply()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>value_counts()</strong> → frequency of each value &nbsp;|&nbsp; <strong>unique()</strong> → unique values only &nbsp;|&nbsp; <strong>apply()</strong> → apply a function to each value
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># How many students from each city?</span>
df[<span class="st">'City'</span>].<span class="fn">value_counts</span>()

<span class="cm"># What unique grades exist?</span>
df[<span class="st">'Grade'</span>].<span class="fn">unique</span>()

<span class="cm"># apply() — apply a custom function</span>
<span class="cm"># Add a column: Pass if Marks >= 80</span>
df[<span class="st">'Result'</span>] = df[<span class="st">'Marks'</span>].<span class="fn">apply</span>(<span class="kw">lambda</span> x: <span class="st">'Pass'</span> <span class="kw">if</span> x >= <span class="nm">80</span> <span class="kw">else</span> <span class="st">'Fail'</span>)

<span class="cm"># apply() with a named function</span>
<span class="kw">def</span> <span class="fn">grade_label</span>(mark):
    <span class="kw">if</span> mark >= <span class="nm">90</span>: <span class="kw">return</span> <span class="st">'Excellent'</span>
    <span class="kw">elif</span> mark >= <span class="nm">80</span>: <span class="kw">return</span> <span class="st">'Good'</span>
    <span class="kw">else</span>: <span class="kw">return</span> <span class="st">'Average'</span>

df[<span class="st">'Label'</span>] = df[<span class="st">'Marks'</span>].<span class="fn">apply</span>(grade_label)</pre>
      <div class="output-label">value_counts() + unique() Output</div>
      <div class="output-block">City
Lahore       3   ← value_counts()
Karachi      2
Islamabad    1

Grade unique: ['B' 'A' 'C' nan]   ← unique()

Result column: ['Pass' 'Pass' 'Pass' nan 'Pass' 'Pass']  ← apply()</div>
    </div>
  </div>
</div><!-- end pandas -->


<!-- ══════════════════════════════════════════════
     SECTION 2: NUMPY
══════════════════════════════════════════════ -->
<div id="numpy">
  <div class="section-header">
    <div class="section-icon icon-numpy">🔢</div>
    <div>
      <div class="section-title"><span class="s-numpy">NumPy</span> — Full Coverage</div>
      <div class="section-sub">Arrays, Shapes, Indexing, Operations, Masking, Aggregation, Random & More</div>
    </div>
  </div>

  <!-- ARRAY CREATION -->
  <div class="topic-card" id="tc-np-create">
    <div class="topic-header" onclick="toggle('tc-np-create')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Creation</span>
        <span class="topic-title">array() · zeros() · ones() · arange() · linspace()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        NumPy arrays are like Python lists but <strong>faster</strong> and can do math on ALL elements at once.<br>
        <strong>arange()</strong> = range with step &nbsp;|&nbsp; <strong>linspace()</strong> = evenly spaced between two values
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="kw">import</span> numpy <span class="kw">as</span> np

<span class="cm"># From a Python list</span>
a = np.<span class="fn">array</span>([<span class="nm">10</span>, <span class="nm">20</span>, <span class="nm">30</span>, <span class="nm">40</span>, <span class="nm">50</span>])

<span class="cm"># 2D array (matrix)</span>
b = np.<span class="fn">array</span>([[<span class="nm">1</span>, <span class="nm">2</span>, <span class="nm">3</span>],
               [<span class="nm">4</span>, <span class="nm">5</span>, <span class="nm">6</span>]])

<span class="cm"># All zeros</span>
np.<span class="fn">zeros</span>((<span class="nm">3</span>, <span class="nm">4</span>))   <span class="cm"># 3 rows, 4 cols of zeros</span>

<span class="cm"># All ones</span>
np.<span class="fn">ones</span>((<span class="nm">2</span>, <span class="nm">3</span>))    <span class="cm"># 2 rows, 3 cols of ones</span>

<span class="cm"># arange(start, stop, step)</span>
np.<span class="fn">arange</span>(<span class="nm">0</span>, <span class="nm">10</span>, <span class="nm">2</span>)   <span class="cm"># [0, 2, 4, 6, 8]</span>

<span class="cm"># linspace(start, stop, num_points)</span>
np.<span class="fn">linspace</span>(<span class="nm">0</span>, <span class="nm">1</span>, <span class="nm">5</span>)  <span class="cm"># 5 equally spaced from 0 to 1</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">array:        [10 20 30 40 50]
zeros(3,4):   [[0. 0. 0. 0.]
               [0. 0. 0. 0.]
               [0. 0. 0. 0.]]
arange:       [0 2 4 6 8]
linspace:     [0.   0.25  0.5  0.75  1.0]</div>
    </div>
  </div>

  <!-- SHAPE & STRUCTURE -->
  <div class="topic-card" id="tc-np-shape">
    <div class="topic-header" onclick="toggle('tc-np-shape')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Shape</span>
        <span class="topic-title">reshape() · ndim · shape · size</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>shape</strong> = (rows, cols) &nbsp;|&nbsp; <strong>ndim</strong> = number of dimensions &nbsp;|&nbsp; <strong>size</strong> = total elements<br>
        <strong>reshape()</strong> changes the shape but keeps all data. Rows × Cols must stay the same!
      </div>
      <div class="code-label">Python Code</div>
<pre>a = np.<span class="fn">array</span>([[<span class="nm">1</span>,<span class="nm">2</span>,<span class="nm">3</span>],[<span class="nm">4</span>,<span class="nm">5</span>,<span class="nm">6</span>]])

<span class="fn">print</span>(a.shape)    <span class="cm"># (2, 3)  → 2 rows, 3 cols</span>
<span class="fn">print</span>(a.ndim)     <span class="cm"># 2       → 2D</span>
<span class="fn">print</span>(a.size)     <span class="cm"># 6       → total 6 elements</span>

<span class="cm"># Reshape 2×3 to 3×2</span>
a.<span class="fn">reshape</span>(<span class="nm">3</span>, <span class="nm">2</span>)

<span class="cm"># Reshape to 1D (flatten)</span>
a.<span class="fn">reshape</span>(<span class="nm">6</span>)      <span class="cm"># [1 2 3 4 5 6]</span>
a.<span class="fn">flatten</span>()      <span class="cm"># same result</span>

<span class="cm"># Reshape: -1 means "figure it out"</span>
np.<span class="fn">arange</span>(<span class="nm">12</span>).<span class="fn">reshape</span>(<span class="nm">3</span>, -<span class="nm">1</span>)  <span class="cm"># 3 rows, auto cols=4</span></pre>
      <div class="output-label">reshape(3,2) Output</div>
      <div class="output-block">Original shape: (2, 3)
Reshaped (3,2):
[[1 2]
 [3 4]
 [5 6]]</div>
    </div>
  </div>

  <!-- INDEXING & SLICING -->
  <div class="topic-card" id="tc-np-idx">
    <div class="topic-header" onclick="toggle('tc-np-idx')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Indexing</span>
        <span class="topic-title">Array Indexing & Slicing <span class="highlight-badge">EXAM FAVOURITE</span></span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        For 1D: <strong>arr[2]</strong> = element at index 2 | <strong>arr[1:4]</strong> = slice from index 1 to 3<br>
        For 2D: <strong>arr[row, col]</strong> | <strong>arr[row_start:row_end, col_start:col_end]</strong>
      </div>
      <div class="code-label">Python Code</div>
<pre>a = np.<span class="fn">array</span>([<span class="nm">10</span>, <span class="nm">20</span>, <span class="nm">30</span>, <span class="nm">40</span>, <span class="nm">50</span>])
b = np.<span class="fn">array</span>([[<span class="nm">1</span>,<span class="nm">2</span>,<span class="nm">3</span>],[<span class="nm">4</span>,<span class="nm">5</span>,<span class="nm">6</span>],[<span class="nm">7</span>,<span class="nm">8</span>,<span class="nm">9</span>]])

<span class="cm"># 1D Indexing</span>
a[<span class="nm">0</span>]       <span class="cm"># 10 (first)</span>
a[-<span class="nm">1</span>]      <span class="cm"># 50 (last)</span>
a[<span class="nm">1</span>:<span class="nm">4</span>]     <span class="cm"># [20 30 40]</span>
a[:<span class="nm">3</span>]      <span class="cm"># [10 20 30] (first 3)</span>
a[<span class="nm">2</span>:]      <span class="cm"># [30 40 50] (from index 2)</span>
a[::-<span class="nm">1</span>]    <span class="cm"># [50 40 30 20 10] (reversed)</span>

<span class="cm"># 2D Indexing [row, col]</span>
b[<span class="nm">0</span>, <span class="nm">0</span>]    <span class="cm"># 1  (row 0, col 0)</span>
b[<span class="nm">1</span>, <span class="nm">2</span>]    <span class="cm"># 6  (row 1, col 2)</span>
b[<span class="nm">0</span>, :]    <span class="cm"># [1 2 3]  (entire row 0)</span>
b[:, <span class="nm">1</span>]    <span class="cm"># [2 5 8]  (entire col 1)</span>
b[<span class="nm">0</span>:<span class="nm">2</span>, <span class="nm">1</span>:<span class="nm">3</span>]  <span class="cm"># rows 0-1, cols 1-2</span></pre>
      <div class="output-label">2D Slicing Output</div>
      <div class="output-block">b[0:2, 1:3]:
[[2 3]
 [5 6]]

b[:, 1]:   [2 5 8]  ← full column 1</div>
    </div>
  </div>

  <!-- ARITHMETIC OPERATIONS -->
  <div class="topic-card" id="tc-np-arith">
    <div class="topic-header" onclick="toggle('tc-np-arith')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Operations</span>
        <span class="topic-title">Arithmetic · Vectorization</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Vectorization</strong> = applying math to ALL elements at once (no loop needed!). This is what makes NumPy faster than regular Python lists.
      </div>
      <div class="code-label">Python Code</div>
<pre>a = np.<span class="fn">array</span>([<span class="nm">10</span>, <span class="nm">20</span>, <span class="nm">30</span>])
b = np.<span class="fn">array</span>([<span class="nm">1</span>,  <span class="nm">2</span>,  <span class="nm">3</span>])

<span class="cm"># Element-wise operations</span>
a + b      <span class="cm"># [11 22 33]</span>
a - b      <span class="cm"># [ 9 18 27]</span>
a * b      <span class="cm"># [10 40 90]</span>
a / b      <span class="cm"># [10. 10. 10.]</span>
a ** <span class="nm">2</span>     <span class="cm"># [100 400 900] (power)</span>

<span class="cm"># Scalar operations (broadcasts to all)</span>
a + <span class="nm">5</span>      <span class="cm"># [15 25 35]</span>
a * <span class="nm">2</span>      <span class="cm"># [20 40 60]</span>
a / <span class="nm">10</span>     <span class="cm"># [1. 2. 3.]</span>

<span class="cm"># Math functions</span>
np.<span class="fn">sqrt</span>(a)  <span class="cm"># square root of each</span>
np.<span class="fn">abs</span>(a)   <span class="cm"># absolute value</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">a + b  = [11 22 33]
a * b  = [10 40 90]
a ** 2 = [100 400 900]
a * 2  = [20 40 60]  ← scalar broadcast</div>
    </div>
  </div>

  <!-- BOOLEAN MASKING -->
  <div class="topic-card" id="tc-np-mask">
    <div class="topic-header" onclick="toggle('tc-np-mask')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Masking</span>
        <span class="topic-title">Boolean Masking <span class="highlight-badge">VERY IMPORTANT</span></span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        A <strong>boolean mask</strong> is an array of True/False values. When you use it to index, you only get the True positions back.<br>
        Think: "Give me all elements where the condition is True."
      </div>
      <div class="code-label">Python Code</div>
<pre>marks = np.<span class="fn">array</span>([<span class="nm">85</span>, <span class="nm">92</span>, <span class="nm">78</span>, <span class="nm">95</span>, <span class="nm">88</span>, <span class="nm">60</span>])

<span class="cm"># Step 1: Create mask (True where marks > 80)</span>
mask = marks > <span class="nm">80</span>
<span class="cm"># mask = [True True False True True False]</span>

<span class="cm"># Step 2: Apply mask to get values</span>
marks[mask]   <span class="cm"># [85 92 95 88]</span>

<span class="cm"># Shortcut (one line)</span>
marks[marks > <span class="nm">80</span>]   <span class="cm"># same result</span>

<span class="cm"># Multiple conditions</span>
marks[(marks > <span class="nm">80</span>) & (marks < <span class="nm">95</span>)]   <span class="cm"># [85 92 88]</span>

<span class="cm"># Count how many passed</span>
np.<span class="fn">sum</span>(marks > <span class="nm">80</span>)   <span class="cm"># 4</span>

<span class="cm"># Set values using mask</span>
marks[marks < <span class="nm">80</span>] = <span class="nm">0</span>   <span class="cm"># zero out fails</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">mask:           [ True  True False  True  True False]
marks[mask]:    [85 92 95 88]
AND condition:  [85 92 88]
count > 80:     4</div>
    </div>
  </div>

  <!-- AGGREGATIONS NUMPY -->
  <div class="topic-card" id="tc-np-agg">
    <div class="topic-header" onclick="toggle('tc-np-agg')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Aggregation</span>
        <span class="topic-title">mean() · max() · min() · sum() · axis parameter</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>axis=0</strong> = column-wise (down the rows) &nbsp;|&nbsp; <strong>axis=1</strong> = row-wise (across the columns)
      </div>
      <div class="code-label">Python Code</div>
<pre>a = np.<span class="fn">array</span>([[<span class="nm">85</span>, <span class="nm">92</span>, <span class="nm">78</span>],
               [<span class="nm">90</span>, <span class="nm">88</span>, <span class="nm">95</span>]])

np.<span class="fn">mean</span>(a)           <span class="cm"># mean of ALL = 88.0</span>
np.<span class="fn">mean</span>(a, axis=<span class="nm">0</span>)   <span class="cm"># col means: [87.5, 90., 86.5]</span>
np.<span class="fn">mean</span>(a, axis=<span class="nm">1</span>)   <span class="cm"># row means: [85. 91.]</span>

np.<span class="fn">max</span>(a)             <span class="cm"># 95</span>
np.<span class="fn">min</span>(a, axis=<span class="nm">1</span>)    <span class="cm"># [78 88]  (min per row)</span>
np.<span class="fn">sum</span>(a, axis=<span class="nm">0</span>)    <span class="cm"># [175 180 173]  (sum per col)</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">mean(all):     88.0
mean(axis=0):  [87.5 90.  86.5]  ← column means
mean(axis=1):  [85.  91. ]       ← row means
sum(axis=0):   [175 180 173]     ← column sums</div>
    </div>
  </div>

  <!-- COMBINING ARRAYS -->
  <div class="topic-card" id="tc-np-combine">
    <div class="topic-header" onclick="toggle('tc-np-combine')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Combining</span>
        <span class="topic-title">concatenate() · vstack() · hstack()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>vstack()</strong> = stack vertically (add rows) &nbsp;|&nbsp; <strong>hstack()</strong> = stack horizontally (add columns)<br>
        <strong>concatenate()</strong> = general purpose, specify axis
      </div>
      <div class="code-label">Python Code</div>
<pre>a = np.<span class="fn">array</span>([[<span class="nm">1</span>, <span class="nm">2</span>], [<span class="nm">3</span>, <span class="nm">4</span>]])
b = np.<span class="fn">array</span>([[<span class="nm">5</span>, <span class="nm">6</span>], [<span class="nm">7</span>, <span class="nm">8</span>]])

<span class="cm"># vstack: add rows on top of each other</span>
np.<span class="fn">vstack</span>([a, b])
<span class="cm"># [[1,2],[3,4],[5,6],[7,8]]</span>

<span class="cm"># hstack: add columns side by side</span>
np.<span class="fn">hstack</span>([a, b])
<span class="cm"># [[1,2,5,6],[3,4,7,8]]</span>

<span class="cm"># concatenate (axis=0=rows, axis=1=cols)</span>
np.<span class="fn">concatenate</span>([a, b], axis=<span class="nm">0</span>)  <span class="cm"># same as vstack</span>
np.<span class="fn">concatenate</span>([a, b], axis=<span class="nm">1</span>)  <span class="cm"># same as hstack</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">vstack:           hstack:
[[1 2]            [[1 2 5 6]
 [3 4]             [3 4 7 8]]
 [5 6]
 [7 8]]</div>
    </div>
  </div>

  <!-- RANDOM -->
  <div class="topic-card" id="tc-np-rand">
    <div class="topic-header" onclick="toggle('tc-np-rand')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Random</span>
        <span class="topic-title">random.rand() · random.randint()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>rand()</strong> = random floats between 0 and 1 &nbsp;|&nbsp; <strong>randint()</strong> = random whole numbers in a range.<br>
        Use <strong>np.random.seed(42)</strong> to get the same random numbers every time (reproducibility).
      </div>
      <div class="code-label">Python Code</div>
<pre>np.random.<span class="fn">seed</span>(<span class="nm">42</span>)  <span class="cm"># for reproducibility</span>

<span class="cm"># rand: floats 0 to 1</span>
np.random.<span class="fn">rand</span>(<span class="nm">3</span>)         <span class="cm"># 1D: 3 values</span>
np.random.<span class="fn">rand</span>(<span class="nm">2</span>, <span class="nm">3</span>)      <span class="cm"># 2D: 2 rows, 3 cols</span>

<span class="cm"># randint(low, high, size)</span>
np.random.<span class="fn">randint</span>(<span class="nm">0</span>, <span class="nm">100</span>, <span class="nm">5</span>)         <span class="cm"># 5 ints between 0-99</span>
np.random.<span class="fn">randint</span>(<span class="nm">50</span>, <span class="nm">100</span>, (<span class="nm">3</span>, <span class="nm">3</span>))  <span class="cm"># 3×3 matrix</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">rand(3):       [0.374 0.951 0.732]
rand(2,3):     [[0.599 0.156 0.058]
                [0.866 0.708 0.021]]
randint 0-99:  [51 92 14 71 60]</div>
    </div>
  </div>

  <!-- FILE HANDLING NUMPY -->
  <div class="topic-card" id="tc-np-file">
    <div class="topic-header" onclick="toggle('tc-np-file')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">File I/O</span>
        <span class="topic-title">loadtxt() — Load CSV with NumPy</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">NumPy can load simple CSV files directly into an array. For complex CSVs (with strings/NaN), use Pandas instead.</div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Load CSV (numbers only, comma separated)</span>
data = np.<span class="fn">loadtxt</span>(<span class="st">'data.csv'</span>, delimiter=<span class="st">','</span>, skiprows=<span class="nm">1</span>)
<span class="cm"># delimiter=',' → values separated by comma
# skiprows=1    → skip the header row</span>

<span class="cm"># Save array as CSV</span>
np.<span class="fn">savetxt</span>(<span class="st">'output.csv'</span>, data, delimiter=<span class="st">','</span>, fmt=<span class="st">'%d'</span>)</pre>
      <div class="output-label">When to use what</div>
      <div class="output-block">np.loadtxt()  → simple numeric CSV (all numbers, no text)
pd.read_csv() → complex CSV (strings, NaN, mixed types)
                 ← USE THIS for most real datasets</div>
    </div>
  </div>

  <!-- NUMPY VS PANDAS COMPARISON -->
  <div class="topic-card open" id="tc-np-compare">
    <div class="topic-header" onclick="toggle('tc-np-compare')">
      <div class="topic-label">
        <span class="topic-tag tag-numpy">Compare</span>
        <span class="topic-title">NumPy vs Pandas — Side-by-Side Table</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <table class="comparison-table">
        <thead>
          <tr>
            <th>Feature</th>
            <th style="color:var(--numpy)">NumPy</th>
            <th style="color:var(--pandas)">Pandas</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Main Object</td><td class="td-numpy">ndarray</td><td class="td-pandas">DataFrame / Series</td></tr>
          <tr><td>Data Types</td><td class="td-numpy">Single type (all int/float)</td><td class="td-pandas">Mixed types allowed</td></tr>
          <tr><td>Column Names</td><td class="td-numpy">No (numbers only)</td><td class="td-pandas">Yes (labels)</td></tr>
          <tr><td>Missing Data</td><td class="td-numpy">No NaN handling</td><td class="td-pandas">isnull(), fillna(), dropna()</td></tr>
          <tr><td>Speed</td><td class="td-numpy">Faster for math</td><td class="td-pandas">Slightly slower</td></tr>
          <tr><td>Indexing</td><td class="td-numpy">arr[row, col]</td><td class="td-pandas">loc[], iloc[]</td></tr>
          <tr><td>GroupBy</td><td class="td-numpy">Not built-in</td><td class="td-pandas">groupby()</td></tr>
          <tr><td>File I/O</td><td class="td-numpy">loadtxt() (numeric only)</td><td class="td-pandas">read_csv() (any format)</td></tr>
          <tr><td>Best For</td><td class="td-numpy">Numerical computation, ML math</td><td class="td-pandas">Data analysis, tables, stats</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div><!-- end numpy -->


<!-- ══════════════════════════════════════════════
     SECTION 3: MATPLOTLIB
══════════════════════════════════════════════ -->
<div id="matplotlib">
  <div class="section-header">
    <div class="section-icon icon-mpl">📊</div>
    <div>
      <div class="section-title"><span class="s-mpl">Matplotlib</span> — Data Visualization</div>
      <div class="section-sub">Line Plot · Bar Chart · Histogram · Pie Chart</div>
    </div>
  </div>

  <!-- SETUP -->
  <div class="topic-card open" id="tc-mpl-setup">
    <div class="topic-header" onclick="toggle('tc-mpl-setup')">
      <div class="topic-label">
        <span class="topic-tag tag-mpl">Setup</span>
        <span class="topic-title">Import & Basic Structure</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        Every Matplotlib plot follows this pattern: <strong>import → create data → plot → add labels → show</strong>.<br>
        Always use <strong>plt.show()</strong> at the end to display the graph.
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="kw">import</span> matplotlib.pyplot <span class="kw">as</span> plt
<span class="kw">import</span> pandas <span class="kw">as</span> pd
<span class="kw">import</span> numpy <span class="kw">as</span> np

<span class="cm"># Using our student dataset</span>
df = pd.<span class="fn">DataFrame</span>({
    <span class="st">'Name'</span>:  [<span class="st">'Ali'</span>, <span class="st">'Sara'</span>, <span class="st">'Umar'</span>, <span class="st">'Zara'</span>, <span class="st">'Hassan'</span>],
    <span class="st">'Marks'</span>: [<span class="nm">85</span>, <span class="nm">92</span>, <span class="nm">78</span>, <span class="nm">88</span>, <span class="nm">95</span>],
    <span class="st">'Age'</span>:   [<span class="nm">20</span>, <span class="nm">21</span>, <span class="nm">22</span>, <span class="nm">20</span>, <span class="nm">21</span>]
})</pre>
      <div class="output-label">Basic Plot Template</div>
      <div class="output-block">plt.figure(figsize=(8, 5))   ← set figure size
plt.title('My Plot')         ← title
plt.xlabel('X axis label')   ← x-axis
plt.ylabel('Y axis label')   ← y-axis
plt.legend()                 ← show legend
plt.tight_layout()           ← fix spacing
plt.show()                   ← DISPLAY the graph</div>
    </div>
  </div>

  <!-- LINE PLOT -->
  <div class="topic-card" id="tc-mpl-line">
    <div class="topic-header" onclick="toggle('tc-mpl-line')">
      <div class="topic-label">
        <span class="topic-tag tag-mpl">Plot</span>
        <span class="topic-title">Line Plot — plt.plot()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Purpose:</strong> Show trends over time or a sequence. Good for: exam scores over semesters, temperature over days, etc.
      </div>
      <div class="code-label">Python Code</div>
<pre>plt.<span class="fn">figure</span>(figsize=(<span class="nm">8</span>, <span class="nm">5</span>))

plt.<span class="fn">plot</span>(df[<span class="st">'Name'</span>], df[<span class="st">'Marks'</span>],
         color=<span class="st">'blue'</span>,      <span class="cm"># line color</span>
         marker=<span class="st">'o'</span>,        <span class="cm"># circle at each point</span>
         linewidth=<span class="nm">2</span>,        <span class="cm"># line thickness</span>
         linestyle=<span class="st">'--'</span>,    <span class="cm"># dashed line</span>
         label=<span class="st">'Marks'</span>)     <span class="cm"># legend label</span>

plt.<span class="fn">title</span>(<span class="st">'Student Marks'</span>)
plt.<span class="fn">xlabel</span>(<span class="st">'Student Name'</span>)
plt.<span class="fn">ylabel</span>(<span class="st">'Marks'</span>)
plt.<span class="fn">legend</span>()
plt.<span class="fn">grid</span>(<span class="kw">True</span>)   <span class="cm"># show grid lines</span>
plt.<span class="fn">show</span>()</pre>
      <div class="output-label">Key Parameters</div>
      <div class="output-block">color='red'/'blue'/'green' or '#ff0000' hex
marker='o' (circle) | 's' (square) | '^' (triangle)
linestyle='-' (solid) | '--' (dashed) | ':' (dotted)
linewidth=2  → thickness of line
label='...'  → text shown in legend</div>
    </div>
  </div>

  <!-- BAR CHART -->
  <div class="topic-card" id="tc-mpl-bar">
    <div class="topic-header" onclick="toggle('tc-mpl-bar')">
      <div class="topic-label">
        <span class="topic-tag tag-mpl">Plot</span>
        <span class="topic-title">Bar Chart — plt.bar()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Purpose:</strong> Compare values between categories. Good for: comparing marks of different students, sales per region, etc.
      </div>
      <div class="code-label">Python Code</div>
<pre><span class="cm"># Vertical bar chart</span>
plt.<span class="fn">figure</span>(figsize=(<span class="nm">8</span>, <span class="nm">5</span>))

plt.<span class="fn">bar</span>(df[<span class="st">'Name'</span>], df[<span class="st">'Marks'</span>],
        color=[<span class="st">'red'</span>, <span class="st">'blue'</span>, <span class="st">'green'</span>, <span class="st">'orange'</span>, <span class="st">'purple'</span>],
        edgecolor=<span class="st">'black'</span>,  <span class="cm"># border of bars</span>
        width=<span class="nm">0.6</span>)          <span class="cm"># bar width</span>

plt.<span class="fn">title</span>(<span class="st">'Marks Comparison'</span>)
plt.<span class="fn">xlabel</span>(<span class="st">'Student'</span>)
plt.<span class="fn">ylabel</span>(<span class="st">'Marks'</span>)
plt.<span class="fn">ylim</span>(<span class="nm">0</span>, <span class="nm">100</span>)  <span class="cm"># y-axis range</span>
plt.<span class="fn">show</span>()

<span class="cm"># Horizontal bar chart</span>
plt.<span class="fn">barh</span>(df[<span class="st">'Name'</span>], df[<span class="st">'Marks'</span>], color=<span class="st">'steelblue'</span>)</pre>
      <div class="output-label">Key Parameters</div>
      <div class="output-block">plt.bar(x, height)      ← vertical bars
plt.barh(y, width)      ← horizontal bars
color='...'             ← fill color
edgecolor='black'       ← outline color
width=0.6               ← bar width (default 0.8)
plt.ylim(0, 100)        ← set y-axis limits</div>
    </div>
  </div>

  <!-- HISTOGRAM -->
  <div class="topic-card" id="tc-mpl-hist">
    <div class="topic-header" onclick="toggle('tc-mpl-hist')">
      <div class="topic-label">
        <span class="topic-tag tag-mpl">Plot</span>
        <span class="topic-title">Histogram — plt.hist()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Purpose:</strong> Show the distribution/spread of data. Divides data into <strong>bins</strong> (ranges) and shows frequency.<br>
        Good for: "How many students scored between 80-90?" kind of questions.
      </div>
      <div class="code-label">Python Code</div>
<pre>marks = np.<span class="fn">array</span>([<span class="nm">55</span>, <span class="nm">60</span>, <span class="nm">65</span>, <span class="nm">70</span>, <span class="nm">72</span>, <span class="nm">75</span>,
                  <span class="nm">78</span>, <span class="nm">80</span>, <span class="nm">82</span>, <span class="nm">85</span>, <span class="nm">88</span>, <span class="nm">90</span>,
                  <span class="nm">92</span>, <span class="nm">95</span>, <span class="nm">97</span>])

plt.<span class="fn">figure</span>(figsize=(<span class="nm">8</span>, <span class="nm">5</span>))

plt.<span class="fn">hist</span>(marks,
         bins=<span class="nm">5</span>,             <span class="cm"># divide into 5 groups</span>
         color=<span class="st">'skyblue'</span>,
         edgecolor=<span class="st">'black'</span>)

plt.<span class="fn">title</span>(<span class="st">'Mark Distribution'</span>)
plt.<span class="fn">xlabel</span>(<span class="st">'Marks Range'</span>)
plt.<span class="fn">ylabel</span>(<span class="st">'Number of Students'</span>)
plt.<span class="fn">show</span>()</pre>
      <div class="output-label">Explanation</div>
      <div class="output-block">bins=5   → 5 groups (e.g. 55-65, 65-75, 75-85, 85-95, 95-100)
Each bar height = how many values fall in that range
Useful to see: Is the data skewed? Normally distributed?</div>
    </div>
  </div>

  <!-- PIE CHART -->
  <div class="topic-card" id="tc-mpl-pie">
    <div class="topic-header" onclick="toggle('tc-mpl-pie')">
      <div class="topic-label">
        <span class="topic-tag tag-mpl">Plot</span>
        <span class="topic-title">Pie Chart — plt.pie()</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <div class="explain-box">
        <strong>Purpose:</strong> Show proportion/percentage of a whole. Good for: "What % of students are from each city?"<br>
        <strong>Tip:</strong> Use <strong>explode</strong> to pull a slice out for emphasis.
      </div>
      <div class="code-label">Python Code</div>
<pre>cities  = [<span class="st">'Lahore'</span>, <span class="st">'Karachi'</span>, <span class="st">'Islamabad'</span>]
counts  = [<span class="nm">3</span>, <span class="nm">2</span>, <span class="nm">1</span>]   <span class="cm"># students from each city</span>

plt.<span class="fn">figure</span>(figsize=(<span class="nm">7</span>, <span class="nm">7</span>))

plt.<span class="fn">pie</span>(counts,
        labels=cities,
        autopct=<span class="st">'%1.1f%%'</span>,     <span class="cm"># show percentages</span>
        colors=[<span class="st">'#ff6b6b'</span>, <span class="st">'#4ecdc4'</span>, <span class="st">'#45b7d1'</span>],
        explode=[<span class="nm">0.1</span>, <span class="nm">0</span>, <span class="nm">0</span>],    <span class="cm"># pull Lahore slice out</span>
        startangle=<span class="nm">90</span>)           <span class="cm"># start from top</span>

plt.<span class="fn">title</span>(<span class="st">'Students by City'</span>)
plt.<span class="fn">show</span>()</pre>
      <div class="output-label">Key Parameters</div>
      <div class="output-block">autopct='%1.1f%%'  → show "50.0%" on each slice
explode=[0.1,0,0]  → pull first slice out by 10%
startangle=90      → rotate so first slice starts at top
shadow=True        → add shadow effect</div>
    </div>
  </div>
</div><!-- end matplotlib -->


<!-- ══════════════════════════════════════════════
     SECTION 4: PRACTICE QUESTIONS
══════════════════════════════════════════════ -->
<div id="practice">
  <div class="section-header">
    <div class="section-icon icon-practice">🎯</div>
    <div>
      <div class="section-title"><span class="s-practice">Practice Questions</span> — Exam Style</div>
      <div class="section-sub">Click "Show Answer" to reveal the solution</div>
    </div>
  </div>

  <!-- Q1 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q1</span>
      <span>Given df with columns ['Name', 'Age', 'Marks', 'City'], write code to select only students from 'Karachi' with Marks greater than 85.</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a1')">▶ Show Answer</button>
    <div class="answer-reveal" id="a1">
      <div class="code-label">Answer</div>
<pre>df[(df[<span class="st">'City'</span>] == <span class="st">'Karachi'</span>) & (df[<span class="st">'Marks'</span>] > <span class="nm">85</span>)]</pre>
      <div class="explain-box">Use <strong>&</strong> for AND. Both conditions must be in <strong>( )</strong> brackets. This is boolean masking with multiple conditions.</div>
    </div>
  </div>

  <!-- Q2 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q2</span>
      <span>How do you find the average marks of students grouped by their City?</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a2')">▶ Show Answer</button>
    <div class="answer-reveal" id="a2">
      <div class="code-label">Answer</div>
<pre>df.<span class="fn">groupby</span>(<span class="st">'City'</span>)[<span class="st">'Marks'</span>].<span class="fn">mean</span>()</pre>
      <div class="explain-box">groupby('City') → groups rows by city value → ['Marks'].mean() → calculates average marks for each group.</div>
    </div>
  </div>

  <!-- Q3 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q3</span>
      <span>A DataFrame has NaN values in the 'Age' column. Write code to: (a) count how many NaN values exist, (b) fill them with the mean age.</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a3')">▶ Show Answer</button>
    <div class="answer-reveal" id="a3">
      <div class="code-label">Answer</div>
<pre><span class="cm"># (a) Count NaN in Age column</span>
df[<span class="st">'Age'</span>].<span class="fn">isnull</span>().<span class="fn">sum</span>()

<span class="cm"># (b) Fill NaN with mean</span>
df[<span class="st">'Age'</span>].<span class="fn">fillna</span>(df[<span class="st">'Age'</span>].<span class="fn">mean</span>(), inplace=<span class="kw">True</span>)</pre>
    </div>
  </div>

  <!-- Q4 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q4</span>
      <span>Create a NumPy array of numbers 1–12, then reshape it into a 3×4 matrix. Then get the element at row 2, column 3.</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a4')">▶ Show Answer</button>
    <div class="answer-reveal" id="a4">
      <div class="code-label">Answer</div>
<pre>a = np.<span class="fn">arange</span>(<span class="nm">1</span>, <span class="nm">13</span>).<span class="fn">reshape</span>(<span class="nm">3</span>, <span class="nm">4</span>)
<span class="cm"># [[ 1  2  3  4]
#  [ 5  6  7  8]
#  [ 9 10 11 12]]</span>

a[<span class="nm">2</span>, <span class="nm">3</span>]  <span class="cm"># → 12 (row 2, col 3)</span></pre>
      <div class="explain-box">arange(1,13) creates [1,2,3...12]. reshape(3,4) makes it 3 rows × 4 cols. Index [2,3] → row 2 (third row), col 3 (fourth col) = 12.</div>
    </div>
  </div>

  <!-- Q5 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q5</span>
      <span>Using NumPy boolean masking, from the array [45, 78, 92, 55, 88, 70, 95], select only values greater than 75.</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a5')">▶ Show Answer</button>
    <div class="answer-reveal" id="a5">
      <div class="code-label">Answer</div>
<pre>scores = np.<span class="fn">array</span>([<span class="nm">45</span>, <span class="nm">78</span>, <span class="nm">92</span>, <span class="nm">55</span>, <span class="nm">88</span>, <span class="nm">70</span>, <span class="nm">95</span>])
scores[scores > <span class="nm">75</span>]   <span class="cm"># → [78 92 88 95]</span></pre>
    </div>
  </div>

  <!-- Q6 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q6</span>
      <span>What is the difference between loc[] and iloc[]? Give one example of each using a DataFrame.</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a6')">▶ Show Answer</button>
    <div class="answer-reveal" id="a6">
      <div class="explain-box">
        <strong>loc[]</strong> = uses LABELS (column names, index labels)<br>
        <strong>iloc[]</strong> = uses NUMBERS (integer positions only)
      </div>
      <div class="code-label">Answer</div>
<pre><span class="cm"># loc: use labels</span>
df.<span class="fn">loc</span>[<span class="nm">0</span>, <span class="st">'Name'</span>]        <span class="cm"># row 0, column named 'Name'</span>
df.<span class="fn">loc</span>[<span class="nm">0</span>:<span class="nm">3</span>, <span class="st">'Name'</span>:<span class="st">'Marks'</span>]  <span class="cm"># INCLUSIVE of end</span>

<span class="cm"># iloc: use numbers</span>
df.<span class="fn">iloc</span>[<span class="nm">0</span>, <span class="nm">0</span>]        <span class="cm"># row 0, col 0</span>
df.<span class="fn">iloc</span>[<span class="nm">0</span>:<span class="nm">3</span>, <span class="nm">0</span>:<span class="nm">3</span>]  <span class="cm"># EXCLUSIVE of end (like Python slicing)</span></pre>
      <div class="output-label">Key Difference</div>
      <div class="output-block">loc[0:3]  → rows 0, 1, 2, 3  (3 IS included)
iloc[0:3] → rows 0, 1, 2    (3 is NOT included)</div>
    </div>
  </div>

  <!-- Q7 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q7</span>
      <span>Add a new column 'Grade_Label' to the DataFrame where: if Marks ≥ 90 → 'A', if 80–89 → 'B', else → 'C'. Use apply().</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a7')">▶ Show Answer</button>
    <div class="answer-reveal" id="a7">
      <div class="code-label">Answer</div>
<pre><span class="kw">def</span> <span class="fn">assign_grade</span>(mark):
    <span class="kw">if</span> mark >= <span class="nm">90</span>:
        <span class="kw">return</span> <span class="st">'A'</span>
    <span class="kw">elif</span> mark >= <span class="nm">80</span>:
        <span class="kw">return</span> <span class="st">'B'</span>
    <span class="kw">else</span>:
        <span class="kw">return</span> <span class="st">'C'</span>

df[<span class="st">'Grade_Label'</span>] = df[<span class="st">'Marks'</span>].<span class="fn">apply</span>(assign_grade)</pre>
    </div>
  </div>

  <!-- Q8 -->
  <div class="quiz-card">
    <div class="quiz-q">
      <span class="q-num">Q8</span>
      <span>Stack these two arrays vertically AND horizontally:<br>a = [[1,2],[3,4]] &nbsp; b = [[5,6],[7,8]]</span>
    </div>
    <button class="show-btn btn-practice" onclick="toggleAnswer('a8')">▶ Show Answer</button>
    <div class="answer-reveal" id="a8">
      <div class="code-label">Answer</div>
<pre>a = np.<span class="fn">array</span>([[<span class="nm">1</span>,<span class="nm">2</span>],[<span class="nm">3</span>,<span class="nm">4</span>]])
b = np.<span class="fn">array</span>([[<span class="nm">5</span>,<span class="nm">6</span>],[<span class="nm">7</span>,<span class="nm">8</span>]])

np.<span class="fn">vstack</span>([a, b])  <span class="cm"># vertical:   4 rows, 2 cols</span>
np.<span class="fn">hstack</span>([a, b])  <span class="cm"># horizontal: 2 rows, 4 cols</span></pre>
      <div class="output-label">Output</div>
      <div class="output-block">vstack: [[1 2]   hstack: [[1 2 5 6]
         [3 4]            [3 4 7 8]]
         [5 6]
         [7 8]]</div>
    </div>
  </div>

  <!-- MINI TASKS -->
  <div class="section-header" style="margin-top:3rem">
    <div class="section-icon icon-practice">✏️</div>
    <div>
      <div class="section-title"><span class="s-practice">Mini Tasks</span></div>
      <div class="section-sub">Try these yourself before checking answers</div>
    </div>
  </div>

  <div class="mini-task"><strong>Task 1:</strong> Create a DataFrame with 5 students. Add a column that shows "Pass" if Marks ≥ 60, "Fail" otherwise using apply().</div>
  <div class="mini-task"><strong>Task 2:</strong> From a NumPy array of 20 random integers (0–100), find: count of values above 50, their mean, and their maximum.</div>
  <div class="mini-task"><strong>Task 3:</strong> Load a CSV file into a DataFrame, drop rows where 'Salary' is NaN, then save the cleaned DataFrame to a new CSV file.</div>
  <div class="mini-task"><strong>Task 4:</strong> Using Matplotlib, plot a bar chart showing the count of students from each city in the student DataFrame.</div>
  <div class="mini-task"><strong>Task 5:</strong> Create a 4×4 NumPy matrix using arange(). Slice out the bottom-right 2×2 corner of the matrix.</div>
</div><!-- end practice -->


<!-- ══════════════════════════════════════════════
     SECTION 5: QUICK REVISION SUMMARY
══════════════════════════════════════════════ -->
<div id="summary">
  <div class="section-header">
    <div class="section-icon icon-practice">📘</div>
    <div>
      <div class="section-title"><span class="s-practice">Quick Revision Summary</span></div>
      <div class="section-sub">Everything you need — one final look before the exam</div>
    </div>
  </div>

  <div class="summary-grid">
    <div class="summary-card">
      <h4 style="color:var(--pandas)">🐼 PANDAS — Must Know</h4>
      <ul>
        <li>df['col'] → single column</li>
        <li>df[['c1','c2']] → multiple</li>
        <li>loc[] → label-based</li>
        <li>iloc[] → index-based</li>
        <li>df[condition] → filter</li>
        <li>& = AND | = OR (use brackets!)</li>
        <li>groupby().mean() → aggregation</li>
        <li>isnull().sum() → count NaN</li>
        <li>fillna(value) → replace NaN</li>
        <li>dropna() → remove NaN rows</li>
        <li>apply(func) → per element</li>
        <li>value_counts() → frequency</li>
      </ul>
    </div>
    <div class="summary-card">
      <h4 style="color:var(--numpy)">🔢 NUMPY — Must Know</h4>
      <ul>
        <li>np.array([...]) → create</li>
        <li>zeros(), ones() → fill arrays</li>
        <li>arange(start,stop,step)</li>
        <li>linspace(start,stop,n)</li>
        <li>reshape(rows, cols)</li>
        <li>arr[row, col] → 2D index</li>
        <li>arr[1:4] → slicing</li>
        <li>arr[arr > 80] → masking</li>
        <li>mean/max/min/sum</li>
        <li>axis=0 → columns, axis=1 → rows</li>
        <li>vstack(), hstack()</li>
        <li>random.randint(low,high,size)</li>
      </ul>
    </div>
    <div class="summary-card">
      <h4 style="color:var(--mpl)">📊 MATPLOTLIB — Must Know</h4>
      <ul>
        <li>plt.plot(x, y) → line</li>
        <li>plt.bar(x, height) → bar</li>
        <li>plt.hist(data, bins) → histogram</li>
        <li>plt.pie(data, labels) → pie</li>
        <li>plt.title('...') → title</li>
        <li>plt.xlabel/ylabel('...')</li>
        <li>plt.legend() → show legend</li>
        <li>plt.grid(True) → grid lines</li>
        <li>plt.show() → display!</li>
        <li>figsize=(w, h) → size</li>
        <li>color, marker, linewidth</li>
        <li>autopct='%1.1f%%' → pie %</li>
      </ul>
    </div>
    <div class="summary-card">
      <h4 style="color:var(--accent)">⚡ Common Mistakes</h4>
      <ul>
        <li>Forgot ( ) around filter conditions</li>
        <li>Used , instead of & or |</li>
        <li>loc end is inclusive, iloc is not</li>
        <li>axis=0 = column direction</li>
        <li>axis=1 = row direction</li>
        <li>inplace=True saves changes</li>
        <li>Forgot plt.show() at end</li>
        <li>NaN ≠ 0, handle separately</li>
        <li>reshape: rows×cols must match</li>
        <li>df.drop needs axis=1 for col</li>
      </ul>
    </div>
  </div>

  <!-- CHEAT SHEET TABLE -->
  <div class="topic-card open" id="tc-cheat" style="margin-top:1.5rem">
    <div class="topic-header" onclick="toggle('tc-cheat')">
      <div class="topic-label">
        <span class="topic-tag tag-practice">Cheat Sheet</span>
        <span class="topic-title">One-Line Command Reference</span>
      </div>
      <span class="topic-arrow">▼</span>
    </div>
    <div class="topic-body">
      <table class="comparison-table">
        <thead><tr><th>What you want to do</th><th>Command</th></tr></thead>
        <tbody>
          <tr><td>See first 5 rows</td><td class="td-numpy">df.head()</td></tr>
          <tr><td>Count rows & cols</td><td class="td-numpy">df.shape</td></tr>
          <tr><td>Column data types</td><td class="td-numpy">df.dtypes</td></tr>
          <tr><td>Count missing values</td><td class="td-numpy">df.isnull().sum()</td></tr>
          <tr><td>Fill NaN with mean</td><td class="td-numpy">df['col'].fillna(df['col'].mean())</td></tr>
          <tr><td>Filter rows</td><td class="td-numpy">df[df['col'] > value]</td></tr>
          <tr><td>Sort by column</td><td class="td-numpy">df.sort_values('col', ascending=False)</td></tr>
          <tr><td>Group + aggregate</td><td class="td-numpy">df.groupby('col')['val'].mean()</td></tr>
          <tr><td>Add new column</td><td class="td-numpy">df['new'] = df['a'] + df['b']</td></tr>
          <tr><td>Delete column</td><td class="td-numpy">df.drop('col', axis=1, inplace=True)</td></tr>
          <tr><td>Rename column</td><td class="td-numpy">df.rename(columns={'old':'new'})</td></tr>
          <tr><td>Unique values</td><td class="td-numpy">df['col'].unique()</td></tr>
          <tr><td>Value frequency</td><td class="td-numpy">df['col'].value_counts()</td></tr>
          <tr><td>Apply function</td><td class="td-numpy">df['col'].apply(lambda x: x*2)</td></tr>
          <tr><td>Read CSV</td><td class="td-numpy">pd.read_csv('file.csv')</td></tr>
          <tr><td>Save CSV</td><td class="td-numpy">df.to_csv('file.csv', index=False)</td></tr>
          <tr><td>NumPy 1–10</td><td class="td-numpy">np.arange(1, 11)</td></tr>
          <tr><td>NumPy zeros 3×3</td><td class="td-numpy">np.zeros((3,3))</td></tr>
          <tr><td>NumPy reshape</td><td class="td-numpy">arr.reshape(3, 4)</td></tr>
          <tr><td>NumPy mask</td><td class="td-numpy">arr[arr > 80]</td></tr>
          <tr><td>NumPy column mean</td><td class="td-numpy">np.mean(arr, axis=0)</td></tr>
          <tr><td>Stack vertically</td><td class="td-numpy">np.vstack([a, b])</td></tr>
          <tr><td>Stack horizontally</td><td class="td-numpy">np.hstack([a, b])</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div><!-- end summary -->

</main>

<footer>
  BAI243044 · Rayyan Qaiser &nbsp;|&nbsp; PAI Mid-Term Notes &nbsp;|&nbsp; Pandas · NumPy · Matplotlib
</footer>

<button id="scrollTop" onclick="window.scrollTo({top:0,behavior:'smooth'})">↑</button>

<script>
  // Toggle topic cards
  function toggle(id) {
    const card = document.getElementById(id);
    card.classList.toggle('open');
  }

  // Toggle answer reveal
  function toggleAnswer(id) {
    const el = document.getElementById(id);
    const btn = el.previousElementSibling;
    const isVisible = el.classList.contains('visible');
    el.classList.toggle('visible');
    btn.textContent = isVisible ? '▶ Show Answer' : '▼ Hide Answer';
  }

  // Progress bar
  window.addEventListener('scroll', () => {
    const scrollTop = document.documentElement.scrollTop;
    const scrollHeight = document.documentElement.scrollHeight - document.documentElement.clientHeight;
    const progress = (scrollTop / scrollHeight) * 100;
    document.getElementById('progress-bar').style.width = progress + '%';

    const btn = document.getElementById('scrollTop');
    if (scrollTop > 300) btn.classList.add('visible');
    else btn.classList.remove('visible');
  });
</script>
</body>
</html>
