

## Matrix Table with Bars and Visuals 
***Link *** :[Matrix Table with Bars and Visuals Report](https://app.powerbi.com/view?r=eyJrIjoiZDViYjc5YWEtMzEyZC00NWE1LTkwOTktZmIzODBiYjdmNjgyIiwidCI6IjZhMTgyNzllLTgzMzktNGFhYS1hZDliLTViYjdjMmU4ZDE2YiJ9 "Matrix Table with Bars and Visuals Report")

This Power BI project includes visualizations designed to showcase various metrics using SVG elements.

### Visual Elements

- **Country Sales with Bars**: Visual representation of sales data per country using bar charts.
- **%GT Circles with Percentage**: Circular charts displaying percentages related to Gross Target (GT).
- **Last Period with Negative and Positive Numbers**: Bar graph illustrating changes in performance over the last period with negative (red) and positive (green) bars.
- **Prospect Status**: Visual indicators using SVGs:
  - Master Leader SVG
  - High Growth in Green SVG
  - Declining in Red SVG

### SVG Measures

#### Sales Rank (Square with a Number)

```xml
<svg width="50" height="50" xmlns="http://www.w3.org/2000/svg">
  <rect width="50" height="50" style="fill:#4CAF50;stroke-width:2;stroke:#333333;" />
  <text x="50%" y="50%" text-anchor="middle" dy=".3em" font-size="24px" fill="white">1</text>
</svg>
```

#### Profit Rank (Circle with a Number)

```xml
<svg width="50" height="50" xmlns="http://www.w3.org/2000/svg">
  <circle cx="25" cy="25" r="22" stroke="#333333" stroke-width="2" fill="#2196F3" />
  <text x="50%" y="50%" text-anchor="middle" dy=".3em" font-size="24px" fill="white">2</text>
</svg>
```

#### Change in Profit (Triangle)

```xml
<svg width="50" height="50" xmlns="http://www.w3.org/2000/svg">
  <polygon points="25,5 5,45 45,45" style="fill:#FF9800;stroke:#333333;stroke-width:2" />
  <text x="50%" y="50%" text-anchor="middle" dy=".3em" font-size="24px" fill="white">+10%</text>
</svg>
```

### Simple Table with SVG Donut Example

Below is an example of a simple table demonstrating the use of SVGs, including a donut chart:

| Metric       | Value     |
|--------------|-----------|
| Sales Rank   | ![Sales Rank SVG](sales_rank.svg) |
| Profit Rank  | ![Profit Rank SVG](profit_rank.svg) |
| Change in Profit | ![Change in Profit SVG](change_profit.svg) |
| Donut Chart  | ![Donut Chart SVG](donut_chart.svg) |

#### SVG Donut Example (Embedded in HTML within SVG)

```xml
<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
  <circle cx="50" cy="50" r="40" stroke="#333333" stroke-width="3" fill="transparent" />
  <circle cx="50" cy="50" r="40" stroke="#4CAF50" stroke-width="3" fill="transparent" stroke-dasharray="25, 100" transform="rotate(-90 50 50)" />
</svg>
```

