<div align="center">
  <h1>🌾 Mandi Vision (मंडी विज़न)</h1>
  <p><strong>Strengthening Market Linkages & Price Discovery for Farmers</strong></p>
  <p>
    <em>Smart India Hackathon 2026 | Problem Statement ID: <b>SIH26132</b></em><br>
    <em>Developed with 💡 by <b>Team Solvers</b></em>
  </p>
  
  <p>
    <img src="https://img.shields.io/badge/Domain-Rural%20Development%20%26%20Digital%20Village-2E7D32?style=for-the-badge" alt="Domain" />
    <img src="https://img.shields.io/badge/Stack-FastAPI%20%7C%20React%20%7C%20PostgreSQL-0288D1?style=for-the-badge" alt="Tech Stack" />
    <img src="https://img.shields.io/badge/ML%20Engine-Prophet%20%7C%20XGBoost-FFA000?style=for-the-badge" alt="ML" />
    <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" />
  </p>
</div>

<hr />

<h2>📌 Project Overview</h2>
<p>
  <b>Mandi Vision</b> transforms agricultural pricing into a transparent, stock-market-style commodity intelligence and market linkage platform. By aggregating real-time data from 3,000+ APMC mandis and applying predictive Machine Learning models, Mandi Vision provides farmers with 7-day price forecasts, net transport-adjusted profit discovery, and smart <b>Hold vs. Sell</b> signals to prevent distress selling.
</p>

---

<h2>📊 Mandi Vision Master Produce Exchange Dashboard</h2>
<p>The primary user interface on the web and mobile platform displays a real-time, stock-market-style commodity board:</p>

<table>
  <thead>
    <tr>
      <th>Commodity / Grain</th>
      <th>Nearest Mandi & Distance</th>
      <th>Current Modal Price (₹/Qtl)</th>
      <th>45-Day ML Forecast</th>
      <th>Predicted Change (%)</th>
      <th>Net Profit After Transport (₹/Qtl)</th>
      <th>Confidence & Data Source</th>
      <th>Smart Action / Recommendation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Wheat (Sharbati)</b></td>
      <td>Bhopal Mandi (12 km)</td>
      <td>₹2,750</td>
      <td>₹2,880</td>
      <td><span style="color:green;"><b>+4.80% 📈</b></span></td>
      <td><b>₹2,705</b> (₹45/Qtl transit)</td>
      <td>91% (Agmarknet API)</td>
      <td><span style="color:blue;"><b>HOLD</b></span> (Sell in 5 days)</td>
    </tr>
    <tr>
      <td><b>Soybean (Yellow)</b></td>
      <td>Sehore Mandi (38 km)</td>
      <td>₹4,400</td>
      <td>₹4,220</td>
      <td><span style="color:red;"><b>-4.1% 📉</b></span></td>
      <td><b>₹4,280</b> (₹120/Qtl transit)</td>
      <td>84% (Data.gov.in)</td>
      <td><span style="color:red;"><b>SELL NOW</b></span> (Supply influx)</td>
    </tr>
    <tr>
      <td><b>Gram (Chana / Desi)</b></td>
      <td>Vidisha Mandi (54 km)</td>
      <td>₹5,850</td>
      <td>₹5,870</td>
      <td><span style="color:gray;"><b>+0.3% ➡️</b></span></td>
      <td><b>₹5,690</b> (₹160/Qtl transit)</td>
      <td>95% (Agmarknet API)</td>
      <td><span style="color:gray;"><b>NEUTRAL</b></span> (Stable rates)</td>
    </tr>
    <tr>
      <td><b>Mustard (Sarson)</b></td>
      <td>Hoshangabad Mandi (72 km)</td>
      <td>₹5,200</td>
      <td>₹5,480</td>
      <td><span style="color:green;"><b>+5.4% 📈</b></span></td>
      <td><b>₹4,990</b> (₹210/Qtl transit)</td>
      <td>88% (e-NAM Portal)</td>
      <td><span style="color:blue;"><b>HOLD / STORE</b></span> (High demand)</td>
    </tr>
    <tr>
      <td><b>Maize (Yellow)</b></td>
      <td>Raisen Mandi (45 km)</td>
      <td>₹2,150</td>
      <td>₹2,020</td>
      <td><span style="color:red;"><b>-6.0% 📉</b></span></td>
      <td><b>₹2,015</b> (₹135/Qtl transit)</td>
      <td>82% (Data.gov.in)</td>
      <td><span style="color:red;"><b>SELL NOW</b></span> (Prices dropping)</td>
    </tr>
  </tbody>
</table>

---

<h2>✨ Key Features</h2>

<table>
  <thead>
    <tr>
      <th width="30%">Feature</th>
      <th width="70%">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>📊 Live Mandi Ticker</b></td>
      <td>Real-time commodity modal prices, daily arrivals, and volume fluctuations across nearby and state-level APMC mandis.</td>
    </tr>
    <tr>
      <td><b>📈 7-Day ML Price Forecast</b></td>
      <td>Time-series forecasting (XGBoost/Prophet) trained on 5+ years of Agmarknet historical data with confidence scoring.</td>
    </tr>
    <tr>
      <td><b>⚖️ Smart "Hold vs. Sell" Engine</b></td>
      <td>Actionable advisory calculating whether waiting 1–2 weeks covers local warehouse/cold-storage costs versus immediate liquidation.</td>
    </tr>
    <tr>
      <td><b>🚚 Inter-Mandi Arbitrage & Transport Calculator</b></td>
      <td>Calculates <i>Net Realizable Profit</i> by factoring in distance, vehicle type, toll charges, and diesel costs to identify the best market.</td>
    </tr>
    <tr>
      <td><b>🤝 Shared Logistics Pooling</b></td>
      <td>Allows smallholder farmers with sub-truck loads to aggregate produce transportation to high-paying regional mandis.</td>
    </tr>
    <tr>
      <td><b>🗣️ Multilingual WhatsApp & Voice Bot</b></td>
      <td>Low-bandwidth regional accessibility using Bhashini AI / Whisper for voice queries (e.g., audio message: <i>"Bhopal mandi me gehu ka bhav kya hai?"</i>).</td>
    </tr>
  </tbody>
</table>

---

<h2>🛠️ Tech Stack & Architecture</h2>

<ul>
  <li><b>Machine Learning & Data Pipeline:</b> Python, Pandas, Scikit-learn, XGBoost, Prophet, Agmarknet OGD API</li>
  <li><b>Backend & APIs:</b> FastAPI / Node.js Express, PostgreSQL (with PostGIS for geolocation routing), Redis Caching</li>
  <li><b>Frontend & Mobile UI:</b> React.js / Next.js, Tailwind CSS, Chart.js, Progressive Web App (PWA)</li>
  <li><b>Accessibility & Voice:</b> Twilio WhatsApp Business API, Bhashini AI / Whisper ASR</li>
</ul>

---

<h2>🚀 Getting Started</h2>

<h3>1. Clone the Repository</h3>
<pre><code>git clone https://github.com/Team-Solvers/Mandi-Vision.git
cd Mandi-Vision</code></pre>

<h3>2. Backend Setup</h3>
<pre><code>cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload</code></pre>

<h3>3. Frontend Setup</h3>
<pre><code>cd ../frontend
npm install
npm run dev</code></pre>

---

<h2>👥 Team Solvers</h2>
<p>
  Developed by <b>Team Solvers</b> for the <b>Smart India Hackathon 2026</b>.<br>
  For queries and contributions, feel free to open an issue or pull request.
</p>