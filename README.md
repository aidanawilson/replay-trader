# Future Simulator

A browser-based trading replay simulator built as a single static HTML file. It is designed for private educational practice, chart replay, and trade setup review.

## What it does

Future Simulator lets users practice historical chart replay in a browser with a prop-firm-style practice interface.

Core features include:

- Historical chart replay
- Buy/sell practice controls
- Entry, stop, and target placement
- Risk/reward display
- Recent trade tracking
- Account and drawdown-style practice stats
- Drawing tools for chart markup
- Timeframe controls
- Dark/light theme toggle
- Mobile-friendly chart layout
- Local browser storage for saved settings and practice stats

## Access

This project is intended for private educational use. The current version includes a simple password splash screen for casual access control.

This is not true server-side authentication. Because this is a static HTML file, any password included in the page can potentially be found by someone inspecting the source code.

## Important disclaimer

This simulator is for educational and practice use only.

It is not financial advice, investment advice, trading advice, tax advice, legal advice, brokerage software, a signal service, or a recommendation system.

Simulated trading results do not represent real trading results and do not guarantee future performance. Simulated trading cannot fully account for real-world factors such as slippage, liquidity, commissions, execution delays, emotional pressure, platform outages, or live-market risk.

Trading financial markets involves substantial risk. Users are solely responsible for any real trading decisions they make outside this simulator.

## Market data notice

Any market data used with this simulator is for private educational replay practice only. Users are responsible for ensuring they have the right to use any data they import or view through the simulator.

This project is not affiliated with Fidelity, TradingView, CME Group, Nasdaq, S&P Dow Jones Indices, any broker, exchange, market-data provider, or prop firm.

## Privacy

This static site does not create accounts, collect names, collect emails, process payments, or send simulator stats to the creator.

Settings, simulator preferences, and practice statistics may be saved locally in the user's browser storage. Clearing browser data may reset saved simulator settings and stats.

If hosted on GitHub Pages, GitHub may process basic technical data such as IP addresses and security logs according to GitHub's own policies.


The simulator runs as a standalone static browser app. No backend server is required.

## Development notes

This project is intentionally kept as a single HTML file for easy sharing and hosting. Desktop and mobile layouts are handled inside the same file.

When editing the simulator, preserve desktop behavior unless intentionally changing it. Mobile layout changes should be scoped to mobile-specific CSS and JavaScript behavior.

## License

No license has been selected yet. Until a license is added, all rights are reserved by the creator.
