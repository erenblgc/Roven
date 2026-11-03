◈ Roven
Hold your money in any unit, all in one account.

onchain payouts for bankless freelancers

Show Image Show Image Show Image Show Image Show Image

Features • Run It • Screens • Global Payouts • Tech • Note

</div>
📖 About

Roven is a simple multi-currency wallet web app. You can hold Turkish lira, USD, EUR, JPY, gold and Bitcoin in one account, convert between them, send money, and see your total balance in whichever unit you prefer.

The idea: freelancers working with foreign clients shouldn't need a separate account for every currency.

✨ Features
	
💱 Multi-asset account	TRY, USD, EUR, JPY, gold (grams) and BTC in one place
🔄 Convert	Exchange between any two units with an instant quote
📤 Transfer	Send money and save frequent recipients
📈 Market ticker	Live-looking rates with profit/loss per asset
🌐 Freelancer mode	Payment link page and a simulated overseas payment
🧾 History	All transactions with a generated transaction hash
🌙 Dark / light theme	Switch with one click
🇹🇷 🇬🇧 Two languages	Turkish and English interface
🚀 How to Run

No installation needed, it's a single HTML file.

bash
git clone https://github.com/<your-username>/roven.git
cd roven
# open index.html in your browser

Or run a local server:

bash
python3 -m http.server 8080

To skip registration, press Quick Start with Demo Balance on the login screen.

Demo starting balance:

₺ TRY	₿ BTC	$ USD	€ EUR	¥ JPY	g Gold
18,450	0.0125	820	240	35,000	12.4
🧭 Screens
Screen	What it does
🏠 Home	Total balance (switchable display unit), daily in/out, rates, recent activity
💼 Units	Every asset with cost, current value and net change
📤 Transfer	Send money, pick from saved recipients, MAX button for full balance
🔄 Convert	Pick source and target unit, quick-buy buttons for BTC, gold and USD
🌐 Global Payouts	Payment link and overseas payment simulation
🧾 History	Time, description, unit, amount and transaction hash
🌐 Global Payouts

Freelancer mode is built around receiving payments from clients abroad.

Payment link
~400 ms
🌍 Foreign client
◈ Roven
👤 Freelancer account
💵 USD
💶 EUR
₺ TRY
Share your personal payment link with the client
The client pays in their own currency
The amount shows up in your account as USD, EUR or TRY

There is also a button that simulates a $1,250 payment from a sample client, so you can see the flow without anything real happening.

🛠️ Built With
	
UI	HTML5, CSS3 (variables, grid, flexbox)
Logic	Vanilla JavaScript
Fonts	Fraunces and Outfit (Google Fonts)
Exchange rates	open.er-api.com for USD, EUR, JPY. Gold and BTC are simulated
Storage	localStorage
roven/
├── index.html   # the whole app (HTML + CSS + JS)
└── README.md

Reset the demo data (browser console):

js
localStorage.removeItem('roven-state-v7'); location.reload();
⚠️ Note

This is a student project and a UI prototype.

There is no real backend, bank or blockchain connection
Balances, transfers, KYC and "onchain" transactions are all simulated
Everything you enter stays in your own browser (localStorage) and is not sent anywhere
Gold and BTC prices and the profit/loss numbers are for demo purposes only
Please don't use real money, real ID numbers or real passwords
🔮 Ideas for Later
 Real gold and BTC prices
 A real backend and login system
 Portfolio performance charts
 Export transactions as CSV
