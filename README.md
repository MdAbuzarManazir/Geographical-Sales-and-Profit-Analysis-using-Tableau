# Geographical-Sales-and-Profit-Analysis-using-Tableau

This project visualizes state-wise profit distribution across Asia using the Global Superstore 2016 dataset. The dataset includes detailed information on Orders, Sales, Quantity, Discounts, Categories, and Regions. Using this data, a filled geographical map (choropleth map) was created in Tableau to analyze how profit varies across different countries and states. Tableau automatically recognized the geographic fields (Country and State) and generated Latitude and Longitude to plot each location accurately on the world map.
The map uses SUM(Profit) as the main measure, where blue shades indicate profitable states and orange/red shades highlight states with losses. This allows the viewer to quickly identify which regions contribute positively to business performance and which regions need improvement. For example, in your visualization, several Indian, Chinese, and Southeast Asian states appear in darker blue showing strong profitability, while Punjab and a few surrounding regions appear in orange, indicating negative profit.

# Tools & Tableau Features Used
# Geographic Roles
Country → Geographic role: Country/Region
State → Geographic role: State/Province

# Generated Coordinates
Tableau used Longitude (generated) for Columns
Tableau used Latitude (generated) for Rows

# Marks Card
Color: SUM(Profit)
Detail: Country, State
Tooltip: Profit, Sales, Quantity (auto-generated)

# Filled Map
Map type changed to Filled Map to show color shading per state
Blue (Profit) → Good performance
Orange (Loss) → Poor performance

# Aggregation Used
SUM(Profit)
Only aggregated profit was used—no custom calculations.

# What This Geographical Graph Shows
# 1. Country-wise and State-wise Profit
Each state is shaded based on its total profit value.
Dark blue = High profit
Light blue = Moderate profit
Yellow/orange = Negative profit

# 2. Regional Performance Comparison
You can visually compare:
Which states in India perform best
Profit distribution across Pakistan, China, Japan, Nepal, Bangladesh, etc.

# 3. Identification of Loss-Making Regions
Orange-colored states clearly show where profit is negative.
These regions may need:
Pricing strategy review
Reduced discounts
Supply chain correction
Category-level analysis

# 4. Customer Market Insights
The map shows how customer demand and sales vary by geography, helping in:
Market expansion
Product targeting
Region-specific decision-making
