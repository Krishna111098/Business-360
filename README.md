🎯 Project Overview
   * Business Insight 360 is an enterprise-grade, multi-page Power BI dashboard designed to provide comprehensive business intelligence across six critical     operational domains. Built for AtliQ (a technology products company), this analytical platform transforms raw business data into actionable insights, enabling data-driven decision-making across all organizational levels.

  *  The dashboard serves as a centralized intelligence hub, offering stakeholders—from C-suite executives to department managers—instant visibility into financial performance, sales trends, marketing effectiveness, supply chain efficiency, and overall business health.


🔍 Problem Statement
Modern businesses face several critical analytical challenges:

  * Data Fragmentation: Key performance metrics scattered across multiple systems and departments, making holistic analysis difficult
  * Delayed Insights: Traditional reporting methods create lag between data generation and actionable insights
  * Limited Visibility: Stakeholders lack real-time access to critical business metrics affecting their decision-making capability
  * Complex Data Relationships: Understanding the interconnections between sales, finance, marketing, and supply chain requires sophisticated analytical tools
  * Performance Monitoring Gaps: Difficulty in tracking performance against benchmarks and identifying trends across time periods and business segments

💡 Objectives
This dashboard was developed to achieve the following strategic goals:

  * Unified Analytics Platform: Create a single source of truth for business performance metrics across all departments
  * Real-Time Monitoring: Enable stakeholders to track KPIs, trends, and anomalies as they occur
  * Comparative Analysis: Facilitate benchmarking against last year's performance and predefined targets
  * Granular Insights: Provide drill-down capabilities from high-level summaries to detailed segment/product/customer analysis
  * Predictive Intelligence: Incorporate forecast accuracy metrics to improve demand planning and inventory management
  * Executive Decision Support: Deliver consolidated insights for strategic planning and resource allocation

📁 Dataset Details
Data Sources
The dashboard integrates data from AtliQ's enterprise systems covering:

  * Sales transactions across multiple regions (NA, EU, APAC, LATAM)
  * Financial statements and P&L data
  * Customer and segment information
  * Product catalog and categories (Networking, Desktop, Accessories, Storage, Peripherals, Notebook)
  * Supply chain and inventory records
  * Marketing campaign data
    
Key Data Dimensions
  * Time Period: 2018 - 2022 (with YTD and quarterly breakdowns)
  * Geographic Coverage: Multiple sub-zones including USA, Canada, Mexico, Colombia, Chile, India, ANZ, ROA, SE, NE, NA
  * Business Segments: 6 product segments across multiple customer channels
  * Customer Base: Major retailers including Amazon, AtliQ Exclusive, AtliQ e-Store, Flipkart, Neptune, Walmart, and others
  * Sales Channels: Retailer, Direct, Distributor
  * Business Divisions: PC (Personal Computers), P & A (Peripherals & Accessories), N & S (Networking & Storage)

    
Data Volume
  * Currency: INR (Indian Rupees) in Millions
  * Last updated: December 21, 2025
  * Comprehensive records spanning multiple fiscal years with quarterly granularity

🧹 Data Cleaning & Transformations
Power Query Operations
  * Data Import: Connected to multiple data sources and consolidated into a unified data model
  * Column Standardization: Renamed columns for consistency and clarity across all tables
  * Data Type Optimization: Ensured proper data types for dates, currencies, and categorical variables
  * Null Handling: Addressed missing values using appropriate imputation strategies
  * Duplicate Removal: Eliminated redundant records to maintain data integrity
    
Data Modeling
  * Star Schema Design: Implemented dimension and fact table relationships for optimal query performance
  * Relationships: Established proper cardinality between tables (one-to-many, many-to-one)
  * Calendar Table: Created a comprehensive date dimension for time intelligence calculations
  * Hierarchies: Built region, product, and customer hierarchies for intuitive drill-down analysis
    
DAX Calculations
  * Developed 40+ custom measures including:

Financial Metrics
  * Net Sales with benchmark comparisons
  * Gross Margin and Gross Margin % with variance analysis
  * Net Profit and Net Profit % calculations
  * Total COGS (Cost of Goods Sold)
  * Operating expenses breakdown
    
Performance Indicators
  * YoY (Year-over-Year) growth calculations
  * vs LY (Last Year) comparative metrics
  * vs Target performance tracking
  * Benchmark calculations for competitive analysis
    
Supply Chain Metrics
  * Net Error (forecast vs actual variance)
  * Forecast Accuracy percentage
  * Absolute Error calculations
  * Risk classification (OOS - Out of Stock, EI - Excess Inventory)
    
Advanced Calculations

  * Time intelligence functions (YTD, QTD)
  * Dynamic segmentation and ranking
  * Conditional formatting logic
  * Market share percentage calculations

📈 Key Insights
  * Financial Performance
  * Net Sales: ₹3.74 billion with +353.5% benchmark outperformance
  * Gross Margin: 38.08% (+4.37% vs benchmark)
  * Net Profit: Showing -13.98% indicating operational challenges requiring cost optimization
  * Seasonal Trends: Peak performance observed in November 2021, followed by stabilization in 2022
  * Top Performers
  * High-Value Customers

  * Amazon leads with ₹496.9M in net sales (36.78% GM)
  * AtliQ Exclusive: ₹307.2M (47.22% GM - highest margin)
  * AtliQ e-Store: ₹304.1M (36.88% GM)
    
Product Segments
  * Notebook segment dominates with ₹1,580.4M in sales
  * Storage segment shows lowest performance at ₹54.6M
  * Networking and Desktop segments demonstrate stable profitability
Geographic Strength
  * USA leads regional sales at ₹770.3M
  * Strong APAC presence with high margins
  * LATAM showing growth potential with positive metrics
    
Operational Concerns
Profitability Challenges

  * All major segments showing negative net profit percentages
  * Notebook segment: -14.06% despite highest sales volume
  * Peripherals showing -14.03% net profit margin
    
Supply Chain Issues
  * Net Error: -3472.7K indicating forecast inaccuracies
  * Forecast Accuracy: 81.17% - room for improvement
  * Multiple customers flagged as OOS (Out of Stock) risk
  * Zone customer with highest forecast discrepancy (-19035 net error)
    
Regional Disparities
  * NA region shows negative profitability (-11.82% net profit)
  * India sub-zone significantly underperforming (-23.0% net profit)
Market Position
  * Strong market share in 2022EST at 22.3%
  * AtliQ brand maintaining leadership position (25.7% share in 2018, 22.3% in 2022EST)
  * Competition from bp, dale, innovo, and pacer brands showing steady presence

Key Skills Demonstrated
✅ Advanced DAX programming
✅ Complex data modeling and relationship management
✅ Interactive dashboard design with UX best practices
✅ Business intelligence storytelling
✅ Performance optimization techniques
✅ Financial analysis and reporting
✅ Supply chain analytics

Screenshot Link : -https://github.com/Krishna111098/Business-360/blob/main/BI360%20screenshot.png

📝 Lessons Learned
Throughout this project, I gained valuable insights into:

Designing user-centric dashboards that balance complexity with usability
Optimizing DAX calculations for performance with large datasets
Creating reusable measure patterns for scalability
Implementing consistent design language across multiple report pages
Translating business requirements into analytical visualizations
Handling complex data relationships in star schema models

🤝 Contributing
Contributions are welcome! If you have suggestions for improvements or find any issues:

🙏 Acknowledgments
AtliQ for the business context and dataset structure
Power BI community for inspiration and best practices
Data Analytics mentors and colleagues for valuable feedback

⭐ If you found this project helpful, please consider giving it a star!
Made with ❤️ and Power BI


Tags
#PowerBI #DataAnalytics #BusinessIntelligence #DAX #DataVisualization #Dashboard #Finance #Sales #Marketing #SupplyChain #ExecutiveDashboard
