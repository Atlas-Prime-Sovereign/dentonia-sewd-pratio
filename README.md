# SEWD P-Ratio: Governance Decay Calibration Dashboard

**Interactive Tool for Quantifying Systemic Retaliation & Institutional Breakdown**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Active-brightgreen)](https://atlas-prime-sovereign.github.io/dentonia-sewd-pratio/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 🎯 Overview

The **SEWD P-Ratio** (Systemic Entropy Weighted Decay - Persecution Ratio) is a mathematical framework for measuring governance dysfunction through the lens of retaliation dynamics. This interactive dashboard provides real-time calibration and visualization of organizational decay patterns.

### Key Metrics

- **P-Ratio (ρ)**: Retaliation-to-Trigger ratio with entropy weighting
- **System Entropy (H)**: Process violations and opacity index
- **Event Horizon**: Threshold of irreversible dysfunction (ρ = 2.0)
- **Systemic Failure**: Complete governance breakdown (ρ = 4.0)

## 📊 Live Dashboard

🔗 **[Launch Interactive Dashboard](https://atlas-prime-sovereign.github.io/dentonia-sewd-pratio/)**

The dashboard features:
- Real-time P-Ratio calculation engine
- Interactive parameter sliders (Triggers, Retaliations, Entropy, Timeline)
- Phase space visualization comparing exponential vs. logarithmic drift
- Verified Dentonia Park case study calibration
- Threshold indicators for Event Horizon and Systemic Failure

## 🧮 Mathematical Model

### Exponential Drift Model (High Entropy Systems)

```
ρ(t) = (R₀/T) × e^(0.08 × H × √t)
```

Where:
- **R₀** = Initial retaliation count
- **T** = Trigger events (legitimate member actions)
- **H** = System entropy (violation ratio)
- **t** = Time elapsed (months)

### Logarithmic Drift Model (Normal Friction)

```
ρ_standard(t) = (R₀/T) × (1 + 0.15 × log(1 + t))
```

Used as baseline for "normal" organizational friction.

### Entropy Calculation

```
H = (Undisclosed Communications + Process Violations) / Total Events
```

## 📋 Verified Case Study: Dentonia Park

| Metric | Value | Source |
|--------|-------|--------|
| Documented Triggers | 4 | Oct 2023 Member Actions |
| Observed Retaliations | 11 | Board Responses |
| Process Violations | 12 | Documented Infractions |
| Total Events Logged | 43 | Full Timeline |
| **Calculated Entropy** | **2.79** | 12/43 = 0.279 |
| **Base Ratio (R/T)** | **2.75** | 11/4 = 2.75 |

### Current Status
At 14 months with H=2.8:
- **ρ = 8.24** (Systemic Failure Zone)
- **206% above Event Horizon**
- **Exponential divergence from normal governance friction**

## 🎨 Features

### Interactive Controls
- **Trigger Events Slider**: Adjust initial member actions (1-20)
- **Retaliation Slider**: Modify board response count (1-50)
- **Entropy Slider**: Set system opacity level (0-5)
- **Timeline Slider**: Change duration analysis (1-24 months)

### Visualizations
- **Phase Space Trajectory**: Dual-line chart showing actual vs. standard decay
- **Real-time P-Ratio Display**: Color-coded status indicator
- **Threshold Reference Lines**: Visual markers at ρ=2.0 and ρ=4.0
- **Dynamic Analysis**: Contextual interpretation updates with parameters

## 🔬 Use Cases

1. **Early Warning System**: Monitor P-Ratio for governance health
2. **Governance Audits**: Identify high-entropy boards before collapse
3. **Intervention Timing**: Determine optimal points for mediation
4. **Comparative Analysis**: Benchmark multiple organizations
5. **Litigation Support**: Quantitative evidence of systemic dysfunction
6. **Policy Design**: Test "what-if" scenarios for governance reforms

## 🚀 Quick Start

### Option 1: Direct Access
Visit the live dashboard: [https://atlas-prime-sovereign.github.io/dentonia-sewd-pratio/](https://atlas-prime-sovereign.github.io/dentonia-sewd-pratio/)

### Option 2: Local Installation
```bash
# Clone the repository
git clone https://github.com/Atlas-Prime-Sovereign/dentonia-sewd-pratio.git

# Navigate to directory
cd dentonia-sewd-pratio

# Open in browser
open index.html
```

No build process required! The dashboard uses CDN-hosted libraries.

## 🛠️ Technology Stack

- **React 18.2.0**: UI framework
- **Recharts 2.12.0**: Data visualization
- **TailwindCSS**: Styling
- **Babel Standalone**: In-browser JSX compilation

## 📖 Methodology

### Threshold Definitions

**Event Horizon (ρ = 2.0)**
- Point where normal resolution becomes impossible
- Retaliation exceeds triggers by 2:1 ratio
- System enters self-reinforcing dysfunction loop

**Systemic Failure (ρ = 4.0)**
- Complete governance breakdown
- 4:1 retaliation-to-trigger ratio
- Irreversible institutional decay

### Entropy Impact

The entropy coefficient (H) measures:
- **Undisclosed communications** that violate transparency
- **Process violations** circumventing proper procedures
- **Opacity index** as ratio of violations to total events

Higher entropy accelerates exponential drift away from normal friction patterns.

## 📈 Interpretation Guide

| P-Ratio Range | Status | Color | Interpretation |
|---------------|--------|-------|----------------|
| ρ < 2.0 | Stable / Manageable | Green | Normal friction range |
| 2.0 ≤ ρ < 4.0 | Event Horizon | Amber | Serious dysfunction, intervention needed |
| ρ ≥ 4.0 | Systemic Failure | Red | Complete breakdown, runaway decay |

### Gap Analysis

The **purple-gray gap** in the phase space chart quantifies the **cost of opacity**:
- Gray line = Standard logarithmic friction
- Purple line = Actual exponential decay
- Gap width = Excess dysfunction attributable to high entropy

## 🤝 Contributing

Contributions welcome! Areas of interest:
- Alternative decay models
- Additional case study calibrations
- Enhanced visualization options
- Statistical validation methods

## 📄 License

MIT License - See [LICENSE](LICENSE) for details

## 📚 Related Work

- [Supernova Model Framework](https://github.com/Atlas-Prime-Sovereign/dentonia-supernova)
- Dentonia Park Case Documentation
- Governance Decay Theory

## 🙏 Acknowledgments

Built on verified event data from the Dentonia Park Condominium governance crisis (Oct 2023 - Dec 2024).

## 📧 Contact

Questions, feedback, or collaboration inquiries: Open an issue in this repository.

---

**Last Updated**: November 2025  
**Version**: 2.1 (Exponential Model)
