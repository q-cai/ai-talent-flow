# AI Talent Flow Analytics Dashboard

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

## 💻 How to Run Locally

You can open the dashboard in your web browser by either:

1. **Double-clicking the file** `index.html` directly in your file manager.
2. **Running a local web server** via python:
   ```bash
   python3 -m http.server 8000
   ```
   Then navigate to [http://localhost:8000](http://localhost:8000) in your web browser.

---
*Data compiled from LinkedIn public workforce updates and LiveData workforce intelligence reports (2023 - 2026).*
