# Power-BI-
Data visualization and storytelling 

# 🛍️ Retail Store Inventory Dashboard – Power BI Template

This Power BI Template (Power Bi retail.pbit) delivers a robust dashboard for retail inventory and sales analysis. It provides data-driven insights across store locations, product categories, sales performance, and external influencers like weather and promotions.

Built for inventory managers, retail analysts, and operations teams, this dashboard enables quick decision-making around stocking, forecasting, and promotional planning.

## 📊 Dashboard Overview

### Page 1: **Executive Overview – Product Performance**
- **KPI Tiles**: Total Units Sold, Sales Goal, and Revenue
- **Region & Store Analysis**: Bar charts showing unit sales by region and store ID
- **Category Performance**: Top-performing categories like Clothing and Electronics
- **Product-Level Trends**: Visuals for Units Sold, Inventory, and Pricing by Product ID
- **Insights**:
  - West and South regions lead in sales
  - High-selling, low-inventory products show price sensitivity
  - Inventory levels can guide restocking priorities

### Page 2: **Impact of External Factors**
- **Top Products**: Highlighting high-volume items
- **Weather Effect**: Sunny and Cloudy days see the highest sales
- **Holiday Promotions**: Promotions drive noticeable sales spikes
- **Insights**:
  - External conditions like weather & holidays influence buying behavior
  - Supports timing of seasonal campaigns and inventory stock-up

### Page 3: **Forecast vs Actual**
- **Sales vs Forecast Scatter**: Compares actual sales with demand forecasts
- **Category Forecast Accuracy**: Electronics shows lower forecast accuracy, especially in winter
- **Insights**:
  - Need for refined, category-specific forecasting models
  - Emphasizes seasonal adjustments in demand planning

## 🗂️ Dataset Requirements

The dashboard works with CSV data. Recommended structure:

### `products.csv`
| ProductID | ProductName | Category | Supplier | UnitPrice | ReorderLevel |

### `inventory.csv`
| ProductID | StoreID | QuantityOnHand | LastRestocked |

### `sales.csv`
| SaleID | ProductID | StoreID | QuantitySold | SaleDate | Discount |

### `stores.csv`
| StoreID | StoreName | Region | Location |

### `weather.csv` *(Optional but recommended)*
| Date | WeatherCondition |

### `promotions.csv`
| Date | Event | DiscountRate |

## 🚀 How to Use

1. **Download and open** 'Power Bi retail.pbit' in Power BI Desktop.
2. **Load your CSV files** when prompted.
3. **Refresh** to apply the data and view the visuals.
4. **Explore the visuals** to analyze sales and inventory patterns.

## 🔧 Customization Ideas

- Add forecasting algorithms or AI models via DAX or Power Query.
- Include return and refund data for more accurate product performance.
- Customize visuals or slicers to match your store hierarchy or product taxonomy.

## 📌 Requirements

- Power BI Desktop (latest)
- Structured CSV files as shown above

## 📞 Support

For help or feedback, feel free to open an issue or contact the dashboard author.


