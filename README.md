# SWOT Analysis Radar Chart

This Streamlit app empowers you to create visually informative radar charts for SWOT (Strengths, Weaknesses, Opportunities, Threats) analysis.

## Features

- **Intuitive Input:** Enter SWOT factors and their importance levels easily using text areas and sliders.
- **Interactive Chart:** Visualize the average importance of each SWOT category on an interactive radar chart.
- **Customizable:** Adjust the importance of each factor individually.
- **Clear Labeling:** See category names and average importance values directly on the chart.

## Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/benjaminjvdm/swot-analysis.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the app:**
   ```bash
   streamlit run app.py 
   ```

2. **Input SWOT Factors:** Enter comma-separated lists of strengths, weaknesses, opportunities, and threats.
3. **Rate Importance:** Use the inputs to assign an importance level (1-3) to each factor.
4. **Generate Chart:** Click the "Generate Radar Chart" button to visualize your analysis.

## Example

```
Strengths: Strong brand, Loyal customer base, Efficient production
Weaknesses: High production costs, Limited distribution network, Lack of innovation
Opportunities: Growing market, New technology, Emerging trends
Threats: Increased competition, Economic downturn, Regulatory changes
```

## Requirements

- `streamlit`
- `pandas`
- `matplotlib`
- `numpy`
- `requests` (for image display in the sidebar)

## About the Author

This app was created by Moon Benjee (문벤지). Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/benjaminjvdm/)!
