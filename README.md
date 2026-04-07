# rangeiq
Physics-based EV range optimizer using real-time riding factors and optimization logic
 RangeIQ — EV Range Optimizer

RangeIQ is a physics-informed EV range optimization tool that models energy consumption and suggests optimal riding strategies to maximize range.

How it works:
The system estimates battery consumption using:

Wh/km = (15 + 0.008 × v²) × A × T × S

Where:
v → speed
A → acceleration factor
T → traffic density
S → road slope
Features:
Real-time range optimization engine
Riding strategy recommendations
Interactive dashboard with live visualizations
Efficiency scoring and insights
Responsive across mobile, desktop, and EV dashboards
Example Insight:
“Aggressive acceleration can reduce range by ~12%”
Tech Stack:
JavaScript
Chart.js
Physics-based modeling
Live Demo:
https://batteryoptimisationtech.netlify.app

Goal:
To simulate real-world riding conditions and support data-driven decision-making for EV efficiency.
