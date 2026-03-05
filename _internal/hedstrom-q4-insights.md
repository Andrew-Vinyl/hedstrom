---
marp: true
theme: vinyl
size: 16:9
---

<!-- _class: title-slide -->

<h1>Hedstrom <span>Analytics Insights</span></h1>

<p>Google Analytics 4 • Q4 2025</p>

---

## Date Ranges Analyzed

<div class="grid-3" style="margin-top: 4rem;">
  <div class="card highlight">
    <h3>Current Quarter</h3>
    <p><strong>Q4 2025</strong><br>Oct 1, 2025 – Dec 31, 2025</p>
  </div>
  <div class="card">
    <h3>Previous Quarter</h3>
    <p><strong>Q3 2025</strong><br>Jul 1, 2025 – Sep 30, 2025</p>
  </div>
  <div class="card">
    <h3>Prior Year</h3>
    <p><strong>Q4 2024</strong><br>Oct 1, 2024 – Dec 31, 2024</p>
  </div>
</div>

---

## Significant YoY Traffic Growth (With Lower Depth)

<div class="grid-3">
  <div class="metric">
    <span class="number">8.7k</span>
    <span class="label">Total Sessions</span>
    <span class="delta">+29.9% YoY</span>
  </div>
  <div class="metric">
    <span class="number">7.0k</span>
    <span class="label">Active Users</span>
    <span class="delta">+30.1% YoY</span>
  </div>
  <div class="metric" style="border-color: #b82105;">
    <span class="number" style="color: #0d5a67;">19.6k</span>
    <span class="label">Pageviews</span>
    <span class="delta negative">-12.8% YoY</span>
  </div>
</div>

<div class="callout" style="font-size: 28px; padding: 1.5rem; margin-top: 2rem;">
  <strong>Insight:</strong> Hedstrom is driving ~30% more users than last year, but users are viewing fewer pages. They are either finding what they need instantly, or bouncing without clicking deeper.
</div>

---

## Channel Performance is Highly Concentrated

<div class="grid-2">
  <div>
    <p style="font-size: 24px; margin-bottom: 2rem;">SEO and brand awareness are extremely strong, driving <strong>96% of total traffic</strong>. However, this is a risky single-point dependency. There is tapable potential in Paid Search and Organic Social.</p>
    
    <div class="css-bar-chart">
      <div class="bar-row">
        <div class="bar-label">Org Search</div>
        <div class="bar-container"><div class="bar-fill highlight" style="width: 51%;">4,499 (51%)</div></div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Direct</div>
        <div class="bar-container"><div class="bar-fill" style="width: 45%;">3,957 (45%)</div></div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Org Social</div>
        <div class="bar-container"><div class="bar-fill" style="width: 2%;">130 (~1.5%)</div></div>
      </div>
      <div class="bar-row">
        <div class="bar-label">Referral</div>
        <div class="bar-container"><div class="bar-fill" style="width: 1%;">103 (~1.1%)</div></div>
      </div>
    </div>
  </div>
  <div class="card" style="display: flex; flex-direction: column; justify-content: center; align-items: center; border-left: none; background-color: var(--accent-teal); color: white;">
     <div class="donut-chart-container">
       <div class="donut-chart">
         <div class="donut-hole">
           <span class="number" style="font-size: 80px; font-weight: bold; color: var(--secondary);">96%</span>
           <span class="label" style="font-size: 16px; text-transform: uppercase; letter-spacing: 2px; text-align: center;">Search &<br>Direct</span>
         </div>
       </div>
     </div>
  </div>
</div>

---

## The "Retailers" Page is Gaining Traction

<p style="margin-bottom: 2rem;">Unlike overall page views which trended downward, the <code>/retailers/</code> page actually increased QoQ and YoY. This signals a growing interest—either from B2B partners or consumers looking for physical store locations.</p>

<div class="grid-3">
  <div class="metric">
    <span class="label">Q4 2025</span>
    <span class="number" style="font-size: 60px;">1,875</span>
    <span class="label" style="text-transform: none;">views</span>
  </div>
  <div class="metric" style="opacity: 0.8; border-color: transparent;">
    <span class="label">Q3 2025</span>
    <span class="number" style="font-size: 60px; color: var(--primary);">1,647</span>
    <span class="label" style="text-transform: none;">views</span>
  </div>
  <div class="metric" style="opacity: 0.8; border-color: transparent;">
    <span class="label">Q4 2024</span>
    <span class="number" style="font-size: 60px; color: var(--primary);">1,550</span>
    <span class="label" style="text-transform: none;">views</span>
  </div>
</div>

---

## Top Performing Product Lines Show Clear Favorites

<table>
  <thead>
    <tr>
      <th>Rank</th>
      <th>Product Category</th>
      <th>Q4 2025 Pageviews</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td><strong>/products/</strong> (Base Hub)</td>
      <td>3,139</td>
    </tr>
    <tr>
      <td>2</td>
      <td><strong>/playballs/</strong> <span style="font-size: 16px; background: var(--secondary); color: white; padding: 2px 8px; border-radius: 4px; vertical-align: middle; margin-left: 10px;">Runaway Favorite</span></td>
      <td>2,158</td>
    </tr>
    <tr>
      <td>3</td>
      <td><strong>/foam/</strong></td>
      <td>270</td>
    </tr>
    <tr>
      <td>4</td>
      <td><strong>/hoppers/</strong></td>
      <td>253</td>
    </tr>
  </tbody>
</table>

---

<!-- _class: dark-slide -->

<h2>AEO & Schema Audit</h2>

<div class="grid-2">
  <div class="card" style="color: var(--primary);">
    <h3>1. Lack of Product Schema Markup</h3>
    <p>Currently, none of the checked product pages feature structured <code>Product</code> schema markup (JSON-LD). This means Answer Engines (like ChatGPT or Google's AI Overviews) have to guess the page's purpose rather than being fed explicitly structured and standardized details (like price, availability, brand, or SKU).</p>
  </div>
  <div class="card" style="color: var(--primary);">
    <h3>2. Shallow Content Depth</h3>
    <p>The product pages average just under 500 words, and the vast majority of that text comes from boilerplate footer, cookie warning, and navigation menus. The actual product descriptions are typically 3-4 bullet points and roughly 50-70 words long. This is insufficient for AEO, which relies on dense, highly informative context to answer user queries effectively.</p>
  </div>
</div>

<div style="margin-top: 2rem; padding: 1rem; border-left: 4px solid var(--secondary);">
  <strong style="color: var(--secondary);">Why it matters:</strong> Answer Engine Optimization ensures AI tools (ChatGPT, Claude, AI Overviews) can easily read, understand, and cite your products directly in their conversational answers.
</div>

---

## Strategic Recommendations (Q1/Q2 2026)

<div class="grid-2">
  <div class="card highlight">
    <h3>1. Optimize Homepage Engagement</h3>
    <p>Since users venture less deeply, add friction-free CTAs. Place a bold <strong>Playballs</strong> section "above the fold" to channel volume to the top product instantly.</p>
  </div>
  <div class="card">
    <h3>2. Capitalize on Retailer Intent</h3>
    <p>Traffic to <code>/retailers/</code> is climbing. Confirm this page is highly optimized. Maximizing this capture rate leads to outsized B2B and consumer revenue outcomes.</p>
  </div>
  <div class="card">
    <h3>3. Diversify Traffic Sources</h3>
    <p>Experiment with Paid Social (Meta/IG) targeted at playballs demographics. A 10-15% bump could push quarterly traffic consistently over 10k sessions.</p>
  </div>
  <div class="card">
    <h3>4. Content Push for Underperformers</h3>
    <p>Feature <code>/foam/</code> and <code>/hoppers/</code> in buying guides or targeted campaigns to boost discovery from their current ~10% traffic share.</p>
  </div>
</div>

---

<!-- _class: dark-slide -->

<div style="display: flex; flex-direction: column; justify-content: center; height: 100%;">
  <h2 style="color: white; font-size: 60px; line-height: 1.1; border: none;">Strategic Proposal for AEO</h2>
  
  <p style="font-size: 32px; margin-top: 2rem; line-height: 1.5; color: var(--light-teal);">We strongly recommend filling out product page details and upgrading SEO tooling (RankMath/Yoast) to instantly deploy structured data site-wide.</p>
  
  <p style="font-size: 32px; line-height: 1.5;">Along with Schema data, we must test expanding product descriptions with FAQs and detailed specifications to provide the dense context Answer Engines require.</p>
</div>
