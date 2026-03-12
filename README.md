# Personal_Portfolio_Website

## PART 1: CONTENT

**What is your full name as you want it displayed professionally?**

Kenneth LeGare.

**What is the purpose of your portfolio website?**

To showcase my quantitative research frameworks, deep reinforcement learning models, and risk analytics to demonstrate my capability in market microstructure and algorithmic trading.

**Who is the target audience (employers, clients, peers, etc.)?**

Quantitative finance recruiters, PhD admissions committees, and fellow quantitative researchers.

**What skills do you want to highlight?**

Deep Reinforcement Learning (DQN, PPO, DDPG), Risk Modeling (Monte Carlo, VaR, CVaR, GARCH), Market Microstructure simulation, and Machine Learning experiment tracking.

**What projects or work will you showcase?**

I will showcase four main case studies:

- Reinforcement Learning for Market Making
- Reinforcement Learning Agent for Intraday Execution Optimization
- Intelligent Risk Analytics for Retail Options Trading
- Hierarchical DRL Multi-Strategy Fund

**How will you describe yourself in a short professional bio?**

I am a quantitative researcher and developer specializing in the application of deep reinforcement learning to financial markets, with a focus on execution optimization, dynamic capital allocation, and rigorous tail-risk management.

**What pages will your site include (Home, About, Projects, Contact, etc.)?**

Home, About, Contact, and dedicated case study pages for Market Making, Intraday Execution, Risk Analytics, and my Hierarchical DRL Fund.

**What is your career goal or desired role?**

To enter a PhD program in Applied Mathematics and Statistics and pursue a career as a Quantitative Researcher.

**What technologies or tools do you have experience with?**

Python, PyTorch, Gymnasium, MLflow, Pandas, NumPy, SciPy, Matplotlib, Seaborn, and ArcticDB.

**What achievements or experiences are worth highlighting?**

Designing a Master CIO agent that achieved a 1.60 Sharpe ratio with a -0.80% max drawdown, simulating realistic limit order books, and implementing HMM regime detection for options trading.

**What call-to-action should visitors take (contact you, view projects, download resume)?**

Review my methodology and open the corresponding project repositories on GitHub.

**Will you include a resume? In what format?**

Yes, as a downloadable PDF.

**What social or professional links will you include (GitHub, LinkedIn, etc.)?**

My GitHub profile (DataHiveMind) and LinkedIn profile.

## PART 2: DESIGN

**What overall style will best represent you (minimalist, creative, professional, etc.)?**

A professional, structured "research report" style that emphasizes data, methodology, and empirical results over decorative elements.

**What color scheme will you use and why?**

A clean, high-contrast scheme that ensures my data visualizations (like PnL distributions and equity curves) stand out clearly.

**What fonts will you use for headings and body text?**

Clean, readable sans-serif fonts suitable for dense technical documentation and financial metrics.

**How will your design reflect your personality or field?**

The design mirrors academic quantitative finance papers and institutional model documentation, breaking information down strictly by Methodology, Results, Charts, and Tech Stack.

**What layout will your homepage follow?**

A clean introduction followed by a grid layout showcasing the four main quantitative research projects.

**How will you organize project sections visually?**

I am utilizing CSS grids, specifically signal-grid for quick summaries and project-grid compact-grid for performance metrics and technical stacks.

**Will the site be mobile-friendly? How will you ensure responsiveness?**

Yes, using `<meta name="viewport" content="width=device-width, initial-scale=1.0">` and responsive CSS grids to ensure charts and data cards scale appropriately.

**What visual hierarchy will guide visitors?**

An "eyebrow" tag for context, a main `<h1>` title, a technical subtitle, followed by core results, and finally deep-dive methodologies.

**How will consistency be maintained across pages?**

All project pages link to a single, central `../design.css` stylesheet and share the exact same navigation and footer structure.

**How will accessibility be considered (contrast, font size, readability)?**

By using semantic HTML structure (`<section>`, `<nav>`, `<footer>`) and ensuring every performance chart and plot has descriptive alt text explaining its purpose.

**Will you use icons, images, or illustrations? Why?**

Yes, I will heavily feature data visualizations, such as DQN training metrics, Monte Carlo distributions, GARCH volatility forecasts, and equity curves, to provide empirical proof of my models' performance.

**What portfolio websites inspired your design?**

Institutional quant research blogs (like Two Sigma or AQR) and standard academic preprint layouts.

## PART 3: INTERACTIVITY

**What interactive elements will your site include (navigation menus, buttons, forms)?**

In-page anchor navigation menus that allow users to jump directly to specific sections like Methodology, Performance, or Repository.

**Will your site include a contact form? How will it work?**

Yes, an HTML form integrated with a lightweight backend service like Formspree to route emails directly to me.

**What JavaScript features will you implement?**

A global `function.js` script to handle smooth scrolling for the in-page navigation anchors and intersection observers to trigger visibility classes (like `.visible`) as the user scrolls down the research reports.

**How will users receive feedback from interactions?**

Hover states on the navigation links and GitHub repository outbound links.

**How does interactivity improve the user experience?**

By using a sticky or quick-jump navigation bar, technical recruiters or researchers can instantly bypass the methodology text and jump straight to the performance charts or the GitHub code if they are short on time.