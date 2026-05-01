# 🌍 TerraHealth

**A global decision engine for climate-sensitive disease forecasting.**

TerraHealth is the **flagship climate-health AI platform** of the [Oxford Planetary Health Informatics Lab (PHI Lab)](https://www.ndorms.ox.ac.uk/research/research-groups/planetary-health-informatics-1) at the University of Oxford. It learns a shared spatiotemporal representation across multiple geospatial and predictive models, fusing **Earth Observation**, **electronic health records**, and **federated analytics** to support anticipatory decision-making for infectious and selected non-communicable diseases — with a focus on equitable health in low- and middle-income countries (LMICs).

🔗 **Live platform:** [www.terrahealth.net](https://www.terrahealth.net/)
🏛️ **Hosted by:** [Planetary Health Informatics Lab](https://www.ndorms.ox.ac.uk/research/research-groups/planetary-health-informatics-1), NDORMS, University of Oxford
👩‍🔬 **Head of Lab:** [Dr Sara Khalid](https://www.ndorms.ox.ac.uk/team/sara-khalid)

---

## 🧭 The Three-Pillar Framework

TerraHealth's mission is structured around three interconnected dimensions of health:

| Pillar | Focus |
|--------|-------|
| 🧬 **Personalised Health** | Individual-level modelling and precision intervention |
| 👥 **Population Health** | Scalable analytics for communities and health systems |
| 🌐 **Planetary Health** | Integrated Earth–human system intelligence |

Together these pillars frame how the platform connects individual patient outcomes to population-scale signals and to the environmental drivers that shape them.

---

## 🛠️ Operational Tools

TerraHealth ships a suite of tools that turn raw Earth-observation and health data into actionable products. Code for each tool — where open-sourced — lives in our [dashboards](https://github.com/phi-research/dashboards) and [models](https://github.com/phi-research/models) repositories.

| Tool | Purpose | Status | Repo link |
|------|---------|--------|-----------|
| 🌀 **Cyclone** | Cyclone pattern + population health-impact analysis (web + Tauri desktop) | Released | [`dashboards/cyclonedata`](https://github.com/phi-research/dashboards/tree/main/cyclonedata) |
| 🛰️ **GeoInsight AI** | Satellite × health data integration platform | Active | _coming soon_ |
| 💧 **Aabpashi** | South Asian water security + drought monitoring | Active | _coming soon_ |
| 🏭 **Emission × ARI** | Industrial-emissions ↔ acute respiratory infection mapping | Active | _coming soon_ |
| 🌊 **Flood Lens** | High-resolution flood monitoring from satellite imagery | Active | _coming soon_ |
| 🌧️ **Flood Analyzer** | Multi-hazard watershed-scale forecasting | Launching 2026 | _coming soon_ |

---

## 📊 Open Datasets

TerraHealth curates and releases open datasets that pair environmental exposures with health outcomes, primarily across South Asia, Sub-Saharan Africa, West Africa, and Southeast Asia.

| Dataset | Coverage |
|---------|----------|
| Brick-kiln emissions ↔ respiratory infection exposure | South Asia |
| Malaria climate risk | Sub-Saharan Africa |
| Brick-kiln locations (>100,000 identified) | Pakistan, India, Bangladesh |
| Flood inundation linked to health outcomes (2015–2023) | South & Southeast Asia |
| Heat stress ↔ non-communicable disease risk | LMIC focus |
| Dengue vector habitat + surveillance (2010–2024) | 12 countries |

> Dataset documentation, schemas, and download links are published on the [TerraHealth website](https://www.terrahealth.net/).

---

## 🔬 Active Research Themes

- AI fairness across demographics
- Clinical NLP in low-resource settings
- Women's health and menstrual equity
- Climate–disease linkages (malaria, dengue, ARIs, NCDs)
- Digital public infrastructure for health
- Malaria outbreak prediction
- West Africa climate-and-health initiatives

Code accompanying each peer-reviewed output is released in [`phi-research/models`](https://github.com/phi-research/models) — see the index there for the latest list.

---

## 🧪 Technology Stack

- **Earth Observation:** Sentinel-2, Sentinel-1 SAR, MODIS, CHIRPS — orchestrated through Google Earth Engine
- **Modelling:** Deep learning (CNNs, transformers), spatial-temporal models, multivariate LSTMs, sequential chaining
- **Clinical NLP:** Large language models for low-resource clinical text
- **Architecture:** Federated analytics for privacy-preserving multi-site modelling
- **Delivery:** Open-source code (this org), interactive dashboards (Next.js / Tauri), and the public TerraHealth platform

---

## 👥 Target Users

- Clinicians and clinical students
- Public-health professionals
- Health-system stakeholders in LMICs
- Researchers working on equitable global health

---

## 🌐 Global AI Health Equity Hub *(forthcoming)*

A planned open collaborative platform — described as **"a global commons for equitable health AI"** — bringing together datasets, code, and decision tools across partner institutions. Updates will be posted here and on [terrahealth.net](https://www.terrahealth.net/) as the Hub launches.

---

## 🗂️ Repository Layout

This repository will track TerraHealth-specific platform code, integration glue, and documentation. The lab's broader codebase is organised across four sibling repos:

| Repo | Purpose |
|------|---------|
| [`terrahealth`](https://github.com/phi-research/terrahealth) | **You are here** — flagship platform docs, integration code |
| [`dashboards`](https://github.com/phi-research/dashboards) | Interactive dashboards (Cyclone, future Flood Analyzer, etc.) |
| [`models`](https://github.com/phi-research/models) | Code accompanying publications (M-LSTM, kiln detection, …) |
| [`shared`](https://github.com/phi-research/shared) | Reusable utilities, data loaders, geospatial helpers |

---

## 🚀 Getting Involved

- **Researchers:** explore the [open datasets](https://www.terrahealth.net/) and [publications](https://github.com/phi-research/models)
- **Developers:** browse the [dashboards repo](https://github.com/phi-research/dashboards) and open issues / PRs
- **Partners & Collaborators:** contact the lab to discuss data sharing, federated deployments, or joint projects

---

## 📚 Citation

When referencing TerraHealth in academic work, please cite the platform alongside the relevant tool / paper. A `CITATION.cff` will be added once the first platform-level publication is released.

```bibtex
@misc{terrahealth_2026,
  title  = {TerraHealth: A Global Decision Engine for Climate-Sensitive Disease Forecasting},
  author = {{Planetary Health Informatics Lab, University of Oxford}},
  year   = {2026},
  url    = {https://www.terrahealth.net/},
  note   = {Code repositories: https://github.com/phi-research}
}
```

---

## 📞 Contact

- **Lab website:** [ndorms.ox.ac.uk/.../planetary-health-informatics-1](https://www.ndorms.ox.ac.uk/research/research-groups/planetary-health-informatics-1)
- **Platform:** [www.terrahealth.net](https://www.terrahealth.net/)
- **Head of Lab:** [Dr Sara Khalid](https://www.ndorms.ox.ac.uk/team/sara-khalid)
- **GitHub:** [@phi-research](https://github.com/phi-research)
- **Email:** orms1036@ox.ac.uk

For data-access requests, partnership enquiries, or media please reach out via email or open an issue on this repository.

---

## 📄 License

Code in this repository is released under the **MIT License** — see [LICENSE](LICENSE). Datasets, imagery, and platform branding may be subject to separate terms — see the [TerraHealth website](https://www.terrahealth.net/) and individual dataset documentation for details.

---

<div align="center">

**Open science · Earth observation · AI · Equitable health**

🌍 Built by the Oxford Planetary Health Informatics Lab

</div>
