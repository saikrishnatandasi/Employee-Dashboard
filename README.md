# Power BI SVG Dashboard - Employee Attendance Tracker


## 📊 Overview

An innovative Power BI dashboard that leverages **SVG (Scalable Vector Graphics)** to create custom visualizations for employee attendance tracking. This project demonstrates advanced Power BI techniques by combining traditional data analysis with modern web technologies to deliver an engaging and interactive user experience.

## 🚀 Key Features

### Custom SVG Employee Cards
- Interactive employee profile cards built entirely with SVG
- Real-time display of employee information including:
  - Profile pictures
  - Employee names and IDs
  - Team assignments
  - Present and remote work percentages

### SVG-Powered Calendar Matrix
- Dynamic calendar visualization using matrix table
- Each date cell contains custom SVG code generated through DAX measures
- Color-coded attendance percentages for visual impact
- Weekly breakdown with attendance rates

### Key Performance Indicators (KPIs)
- **Total Days**: 775
- **Total Working Days**: 500
- **Attendance**: 439 days
- **Present %**: 87.8%
- **Remote %**: 16.8%
- **Overall Attendance**: 88% (January)

## 🛠️ Technical Implementation

### Data Processing
- **Power Query Editor**: Used unpivot operations to transform raw attendance data
- **Data Structure**: Employee status data unpivoted by date for flexible analysis
- **Data Modeling**: Optimized relationships for efficient calculation

### SVG Integration
- **DAX Measures**: Custom measures that return SVG code as strings
- **Matrix Visual**: Leveraged Power BI's matrix table to display SVG content
- **Dynamic Rendering**: SVG elements change based on data values and conditions




## 🎨 What is SVG?

**Scalable Vector Graphics (SVG)** is an XML-based vector image format that offers several advantages for data visualization:

- **Scalability**: Perfect rendering at any size without pixelation
- **Customization**: Full control over styling, colors, and animations
- **Interactivity**: Support for hover effects and click events
- **Performance**: Lightweight and fast-loading
- **Accessibility**: Screen reader compatible with proper markup








### Installation Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/power-bi-svg-dashboard.git
   ```

2. **Open Power BI Desktop**
   - Launch Power BI Desktop
   - Open the `.pbix` file from the `/Dashboard` folder

3. **Data Connection**
   - Update data source connections to point to your local data files
   - Refresh the dataset to load current data

4. **Customize SVG Elements**
   - Modify DAX measures in the model to adjust SVG styling
   - Update color schemes and dimensions as needed

## 📈 Dashboard Components

### Left Panel - KPIs
- Total Days counter
- Working days summary
- Attendance metrics
- Percentage calculations

### Center Panel - Calendar View
- Monthly calendar matrix (January-April tabs)
- Daily attendance percentages
- Color-coded status indicators
- Weekly grouping for better organization

### Right Panel - Employee Cards
- Individual employee profiles
- Team assignments
- Present/Remote work split
- Profile pictures and IDs

## 🎯 Use Cases

- **HR Analytics**: Track employee attendance patterns
- **Team Management**: Monitor remote vs. office presence
- **Workforce Planning**: Identify attendance trends
- **Performance Monitoring**: Evaluate team productivity metrics

## 💡 Advanced Features

### Dynamic Color Coding
- Green: 90%+ attendance
- Orange: 80-89% attendance  
- Red: Below 80% attendance

### Interactive Filtering
- Filter by employee, team, or date range
- Cross-filtering between visuals
- Responsive design for different screen sizes



