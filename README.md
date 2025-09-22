# Drug Calculator Suite

A comprehensive calculator suite for scientific and educational purposes, designed for harm reduction research and pharmacological studies.

## Features

### 💊 Liquid Dosage Calculator
Calculate the exact amount of active substance in a specific volume of liquid preparation.

**Inputs:**
- Total liquid volume (ml)
- Total medication amount (g)
- Drug purity percentage (%)
- Target volume for dosing (ml)

**Output:** Precise dosage in milligrams

### 🧠 Ketamine Tolerance Calculator
Calculate adjusted ketamine dosages based on previous use and tolerance buildup patterns.

**Scientific Basis:**
- Based on NMDA receptor downregulation and recovery patterns
- Uses a tolerance half-life of approximately 4 days
- Accounts for cross-tolerance from previous doses
- Incorporates non-linear effect scaling

**Inputs:**
- Previous dose (mg)
- Days since last dose
- Desired effect intensity (1-10 scale)

**Output:** Recommended dose with tolerance and recovery information

### ⚡ 4-MMC Tolerance Calculator
Calculate adjusted 4-MMC dosages based on previous use and serotonin/dopamine receptor recovery.

**Scientific Basis:**
- Based on serotonergic and dopaminergic receptor tolerance patterns
- Uses a tolerance half-life of approximately 10 days
- More conservative dosing due to neurotoxicity concerns
- Includes extended recovery recommendations

**Inputs:**
- Previous dose (mg)
- Days since last dose
- Desired effect intensity (1-10 scale)

**Output:** Recommended dose with comprehensive safety warnings

## Safety Features

- Built-in dose caps to prevent dangerous recommendations
- Color-coded warnings for high-risk doses
- Recovery rate calculations
- Scientific basis documentation for each calculation
- Educational disclaimers and harm reduction focus

## Usage

Open `index.html` in any modern web browser. No installation or dependencies required.

## Disclaimer

⚠️ **FOR SCIENTIFIC AND EDUCATIONAL PURPOSES ONLY**

This calculator is designed for:
- Harm reduction education
- Scientific research
- Pharmacological studies
- Risk assessment training

**Important Notes:**
- Always consult medical professionals
- Follow all local laws and regulations
- Individual responses vary significantly
- These calculations are theoretical models
- Never use for illegal purposes

## Technical Implementation

- Pure HTML/CSS/JavaScript
- Client-side calculations only
- No data collection or storage
- Responsive design
- Cross-browser compatible

## Contributing

This project is for educational purposes. Contributions should focus on:
- Improving scientific accuracy
- Adding safety features
- Enhancing educational value
- Better harm reduction information