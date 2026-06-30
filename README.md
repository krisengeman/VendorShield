# VendorShield
Autonomous Vendor Risk &amp; SLA Evaluator

What's inside
Dashboard — KPI cards (total vendors, documents, red lines, critical count), vendor risk rankings with color-coded score bars, and a critical vendor alert banner in the sidebar.

Vendor Detail — Three tabs:

Red Lines — Violations sorted by severity (Critical → High → Medium → Low), each expandable to show vendor position vs. policy requirement, plus the AI-drafted alternative clause with a one-click copy button

Extracted Terms — Clean table of all key metrics pulled from the document (uptime, data retention, liability cap, breach window, etc.)

Documents — Drag-and-drop PDF/TXT upload with doc type selector (MSA / SLA / SOC2), AI model picker, and per-document analyze button

Vendors List — Sortable table with search and status filter tabs, risk score sparklines, and one-click navigation.

Policy Config — Full CRUD for your corporate policy baselines — category, threshold, threshold type (min/max/exact/contains), severity, and active toggle. These drive the AI red-line logic.

To use real AI analysis
Upload a real PDF contract and click Analyze:

Claude (Paid) — uses the built-in llm-api:website credential, no key needed

Gemini Flash (Free) — requires a GEMINI_API_KEY environment variable on the server

The demo data is pre-loaded with 3 vendors and realistic mock analyses to explore immediately.
