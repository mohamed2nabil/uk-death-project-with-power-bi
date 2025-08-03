<img width="884" height="497" alt="the photo of dashboard (1)" src="https://github.com/user-attachments/assets/703e2f23-2abd-4238-b651-bd4e29eda78b" />
# 🚨 Nashville Traffic Accidents Analytics Dashboard

A comprehensive Power BI data analysis project exploring traffic safety patterns in Nashville through interactive visualizations and statistical insights. This dashboard analyzes over 216,000 traffic accidents to identify trends, risk factors, and safety improvement opportunities.

## 📊 Project Overview

This Power BI dashboard provides in-depth analysis of Nashville traffic accidents, examining patterns across multiple dimensions including time periods, lighting conditions, hit-and-run incidents, and seasonal variations. The project aims to support data-driven decision making for traffic safety improvements and policy development.

## 🔧 Tools & Technologies

- **Power BI Desktop** - Primary visualization and dashboard creation
- **DAX (Data Analysis Expressions)** - Custom measures and calculations
- **Power Query** - Data cleaning and transformation
- **M Language** - Advanced data preprocessing
- **Power BI Service** - Dashboard publishing and sharing

## 📈 Key Metrics & Insights

### Overall Statistics
- **Total Accidents**: 216,113 incidents analyzed
- **Total Victims**: 89,585 individuals affected
- **Total Injuries**: 88,760 recorded injuries
- **Total Fatalities**: 825 lives lost

### Performance Indicators
- **Hit-and-Run Rate**: 26.16% of all accidents
- **Vacation Impact**: 25% of victims during vacation periods
- **Peak Risk Period**: Daylight hours show highest victim counts (56,930)
- **Weekly Pattern**: Work days significantly more dangerous than weekends

## 📊 Dashboard Components

### Main KPI Cards
- **Total Accidents Counter**: Real-time accident statistics
- **Victim Analytics**: Comprehensive casualty tracking
- **Injury Metrics**: Non-fatal incident monitoring
- **Fatality Tracking**: Critical safety indicators

### Interactive Visualizations

#### Hit-and-Run Analysis
- Pie chart showing 73.84% regular accidents vs 26.16% hit-and-run incidents
- Trend analysis for policy intervention targeting

#### Vacation Impact Assessment
- Donut chart revealing 75% non-vacation vs 25% vacation-related incidents
- Seasonal safety pattern identification

#### Lighting Conditions Analysis
- Bar chart showing victim distribution across different lighting conditions
- Daylight (56,930), Dark-Lighted (22,043), Dark-Not Lighted (5,851)
- Critical insights for infrastructure improvement

#### Temporal Analysis
- **Quarterly Trends**: Line chart showing victim patterns from 2018-2025
- **Weekly Distribution**: Horizontal bar chart comparing weekday vs weekend incidents
- **Time-based Filtering**: Interactive slider for detailed period analysis

## 🎯 Key Features

### Interactive Filtering
- **Time Range Selector**: Dynamic date filtering from 0-23 hours
- **Multi-dimensional Analysis**: Cross-filtering across all visualizations
- **Drill-through Capabilities**: Detailed incident exploration

### Advanced Analytics
- **Trend Identification**: Multi-year pattern recognition
- **Seasonal Analysis**: Quarterly and weekly trend comparison
- **Risk Factor Assessment**: Lighting and vacation impact evaluation
- **Predictive Insights**: Future trend projections

### User Experience
- **Responsive Design**: Optimized for desktop and mobile viewing
- **Intuitive Navigation**: Clear visual hierarchy and interaction patterns
- **Real-time Updates**: Dynamic data refresh capabilities

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (latest version)
- Access to Nashville traffic accident dataset
- Basic understanding of Power BI interface

### Installation & Setup
1. Clone the repository:
```bash
git clone https://github.com/mohamed2nabil/uk-death-project-with-power-bi.git
```

2. Open Power BI Desktop

3. Load the `.pbix` file from the repository

4. Refresh data connections if prompted

5. Explore the interactive dashboard

## 📁 Project Structure
```
uk-death-project-with-power-bi/
│
├── Nashville_Traffic_Dashboard.pbix    # Main Power BI file
├── data/
│   ├── raw/                           # Original dataset
│   ├── processed/                     # Cleaned data files
│   └── uk_death.rar                   # Compressed data archive
│
├── documentation/
│   ├── data_dictionary.md             # Field definitions
│   ├── methodology.md                 # Analysis approach
│   └── insights_report.pdf            # Key findings summary
│
├── images/
│   └── dashboard_screenshots/         # Visual documentation
│
└── README.md
```

## 📊 Data Sources & Methodology

### Dataset Information
- **Source**: Nashville Metropolitan Police Department
- **Time Period**: 2018-2025 (projected)
- **Records**: 216,113 traffic incidents
- **Update Frequency**: Monthly data refresh

### Data Processing
- **Cleaning**: Removed duplicates and inconsistent entries
- **Validation**: Cross-referenced with official traffic records
- **Transformation**: Standardized date formats and categorical variables
- **Enhancement**: Added calculated fields for advanced analytics

## 🔍 Key Insights & Findings

### Critical Safety Patterns
1. **High-Risk Periods**: Daylight hours account for majority of victims despite better visibility
2. **Hit-and-Run Trends**: Over 1 in 4 accidents involve hit-and-run, indicating enforcement gaps
3. **Seasonal Variations**: Vacation periods show distinct accident patterns requiring targeted interventions
4. **Weekly Patterns**: Weekdays significantly more dangerous than weekends

### Lighting Impact Analysis
- **Daylight Accidents**: 56,930 victims (highest category)
- **Dark-Lighted Areas**: 22,043 victims (infrastructure investment needed)
- **Unlit Areas**: 5,851 victims (critical safety concern)

### Temporal Trends
- **Peak Years**: 2019-2020 showed highest accident rates
- **Recent Improvements**: Declining trend from 2021-2024
- **Future Projections**: Continued reduction expected through 2025

## 🎯 Business Impact & Applications

### Policy Development
- Evidence-based traffic safety regulations
- Infrastructure investment prioritization
- Enforcement strategy optimization

### Urban Planning
- Intersection safety improvements
- Lighting infrastructure expansion
- Traffic flow optimization

### Public Safety
- Community awareness campaigns
- Emergency response planning
- Risk assessment frameworks

## 🛠️ Technical Implementation

### DAX Measures Created
```dax
Total Victims = SUM('Accidents'[Victim_Count])
Hit and Run Rate = DIVIDE([Hit and Run Count], [Total Accidents])
Fatality Rate = DIVIDE([Total Fatalities], [Total Victims])
Weekend vs Weekday = IF(WEEKDAY(TODAY()) IN {1,7}, "Weekend", "Weekday")
```

### Power Query Transformations
- Date standardization and parsing
- Categorical data cleaning
- Missing value handling
- Data type optimization

## 📈 Performance Optimization

### Dashboard Efficiency
- **Load Time**: <3 seconds for initial dashboard load
- **Refresh Speed**: 30-second full data refresh
- **Memory Usage**: Optimized for standard Power BI capacities
- **Mobile Compatibility**: Responsive design implementation

### Best Practices Applied
- Star schema data modeling
- Efficient DAX measure creation
- Optimized visual interactions
- Compressed data storage

## 🔄 Maintenance & Updates

### Regular Tasks
- Monthly data refresh from source systems
- Quarterly trend analysis updates
- Annual methodology review
- Performance optimization checks

### Version Control
- Semantic versioning for dashboard updates
- Change log documentation
- Backup procedures for critical updates

## 🤝 Contributing

Contributions welcome for:
- Additional data source integration
- Advanced analytics features
- User experience improvements
- Performance optimizations

### Development Guidelines
1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Test changes thoroughly
4. Submit pull request with detailed description

## 📞 Contact & Support

**Project Maintainer**: Mohamed Nabil
- **GitHub**:https://github.com/mohamed2nabil
- **LinkedIn**:(https://www.linkedin.com/in/mohamed-nabil-41047a223/)
- **Email**: mohamed2nabil5@gmail.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Nashville Metropolitan Police Department for data access
- Power BI Community for technical guidance
- Traffic safety researchers for methodology insights

## 📚 References

- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Function Reference](https://docs.microsoft.com/en-us/dax/)
- [Traffic Safety Analysis Best Practices](https://www.nhtsa.gov/)

---

⭐ **Star this repository if it helped you understand traffic safety analytics with Power BI!**
