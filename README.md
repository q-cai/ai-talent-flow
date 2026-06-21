# AI Talent Flow Analytics Dashboard

👉 **Live Demo: [https://q-cai.github.io/ai-talent-flow/](https://q-cai.github.io/ai-talent-flow/)**

An interactive dashboard mapping the flow of top-tier AI researchers, engineers, and technical leaders among **10 major AI companies** and an **"Other"** category (academia, smaller startups, and other tech sectors) based on normalized LinkedIn and workforce intelligence data (2023 - 2026).

## 🚀 Key Features

- **Sankey Flow Chart**: Visualizes departures (left) moving to arrivals (right).
- **Flow Matrix**: A full crossover grid of exact transition numbers.
- **Net Growth Chart**: Highlights which companies are net talent gainers and which are net donors/feeders.
- **Company Explorer**: Drills down on any specific company to inspect where its departures go and where its hires come from.

## 📊 Covered Companies

1. **Google** (DeepMind, Google Brain, unified Core AI)
2. **OpenAI** (ChatGPT, frontier model teams)
3. **Anthropic** (Claude, safety & alignment focus)
4. **Meta** (FAIR, Llama, Superintelligence labs)
5. **Microsoft** (Microsoft Research, partner AI divisions)
6. **Tesla** (Autopilot, FSD, Optimus robotics)
7. **Nvidia** (CUDA hardware architecture, AI research)
8. **Apple** (Apple Intelligence, ML divisions)
9. **Amazon** (AWS AI, Amazon AGI)
10. **xAI** (Grok, supercomputing teams)
11. **Other** (Startups like Cohere, Mistral, Adept, Character.ai, universities, and general software sectors)

## 📈 Major Insights

- **Google as the Universal Feeder**: Google has a net loss of over **750 professionals** in this normalized cohort. Historically possessing the largest research staff, it serves as the prime incubator. Around **25% of OpenAI's total hires** came directly from Google.
- **Frontier Labs as Vacuums**: OpenAI (+592 net) and Anthropic (+508 net) are the ultimate net talent sinks, attracting professionals with high-velocity product shipping and equity potential.
- **The OpenAI-to-Anthropic safety pipeline**: Anthropic is a major destination for OpenAI departures, specifically for researchers prioritizing safety, alignment, and flat-organizational culture.
- **xAI's Recruitment Mix**: xAI has scaled rapidly by drawing talent from Tesla's autopilot team and targeted poaching from Google DeepMind.
- **Nvidia's Hold**: Nvidia has high employee retention and remains net positive (+33) due to its core hardware positioning and valuable stock options.

## 🌐 How to Showcase on GitHub (GitHub Pages)

To make this interactive dashboard accessible to anyone at any time, you can host it for free using **GitHub Pages** directly from your repository:

1. Go to your repository on GitHub: **[q-cai/ai-talent-flow](https://github.com/q-cai/ai-talent-flow)**.
2. Click on the ⚙️ **Settings** tab.
3. In the left sidebar, click on **Pages** (under the "Code and automation" section).
4. Under **Build and deployment** -> **Source**, ensure it is set to **"Deploy from a branch"**.
5. Under **Branch**, select **`main`** and **`/ (root)`** from the dropdowns, then click **Save**.
6. Wait 1-2 minutes for GitHub to build the page. You will see a live URL at the top of the Pages settings page, which will look like:
   **`https://q-cai.github.io/ai-talent-flow/`**

## 💻 How to Run Locally

You can open the dashboard in your web browser by either:

1. **Double-clicking the file** `index.html` directly in your file manager.
2. **Running a local web server** via Python:
   ```bash
   python3 -m http.server 8000
   ```
   Then navigate to [http://localhost:8000](http://localhost:8000) in your web browser.

## 📚 Data Sources & Methodology

This flow matrix and analysis are synthesized from the following workforce intelligence and research sources:

1. **LiveData Technologies (Workforce Intelligence Reports)**:
   - *Source Type*: Ongoing tracking of LinkedIn professional profiles.
   - *Details*: Analyses of transition patterns for tech companies (e.g., tracking over 1,300 OpenAI employees to trace historic employers), widely cited by business publications like **Business Insider** to map the "AI Talent War" and employee source distribution.
   - *Key Reference*: [LiveData Technologies Workforce Analytics](https://www.livedatatechnologies.com/)
   
2. **MacroPolo (Paulson Institute - Global AI Talent Tracker)**:
   - *Source Type*: Career tracking of elite researchers (authors at NeurIPS, ICML, and ICLR conferences).
   - *Details*: Focuses on international and institutional mobility patterns, assessing how academic and corporate entities attract and retain the top 2% of global AI talent.
   - *Key Reference*: [MacroPolo Global AI Talent Tracker](https://macropolo.org/)

3. **News & Corporate Press Reports (2023 - 2026)**:
   - Media reports from *The Information*, *Business Insider*, and *Fast Company* documenting notable high-profile team transfers (such as Google Gemini leaders moving to OpenAI, and Autopilot program managers transitioning to xAI).

