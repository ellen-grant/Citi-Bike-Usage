1. Table of Contents
2. Project Overview
3. Goals and Objectives
4. Dataset Information
5. Project Structure
6. Key Insights
7. Visualizations and Story Points
8. Recommendations
9. Business Opportunities
10. Future Enhancements
11. Conclusion
12. Getting Started

## Project Overview
The Citi Bike Usage Analysis project explores patterns in Citi Bike usage across New York City in the month of September 2024 to inform service improvement and expansion strategies. Through detailed visualizations, the project aims to uncover insights on ridership trends, user behavior, and geographic hotspots for bike rentals. This project leverages Tableau for visualizations and storytelling, highlighting trends in daily usage, trip duration, peak hours, popular routes, and station density.

## Goals and Objectives
### The main objectives of this analysis are:
- Understand User Behavior: Identify differences in usage patterns between member and casual riders.
- Optimize Service During Peak Times: Analyze usage patterns to determine high-demand hours for better resource allocation.
- Identify High-Demand Routes and Locations: Locate popular routes and high-density areas to support targeted infrastructure improvements.
- Guide Expansion and Service Improvement: Use findings to propose recommendations for service expansion and optimization, catering to both regular commuters and tourists.

## Dataset Information
### The project utilizes Citi Bike trip data, which includes:
- Ride ID: Unique identifier for each trip.
- Start and End Timestamps: Times at which each trip began and ended.
- Start and End Stations: Locations for each trip's starting and ending points.
- User Type: Classification of users into Member and Casual.
- Trip Duration: Length of each trip in minutes.
- Geographic Coordinates: Latitude and longitude of start and end locations.

## Data Preprocessing
## Data cleaning steps include:
- Removing null values.
- Filtering out data with erroneous trip durations (e.g., excessively long or negative times).
- Binning trip durations to simplify distribution analysis.
- Adding fields for analysis, such as day of the week, hour of the day, and trip type.

## Project Structure
### The project is structured as follows:
- Data Cleaning: A script for cleaning and preparing the raw data.
- Tableau Workbook: Contains all visualizations, dashboards, and story points.
- README: Provides a detailed overview of the project, objectives, and insights.

## Key Insights
- User Behavior: Members primarily use Citi Bike during weekdays for commuting, with peak usage during rush hours. Casual riders show increased activity on weekends and around midday, likely indicating tourism and leisure usage.
- Trip Duration: Casual users typically have longer trips than members, especially around popular locations, suggesting that tourists use bikes for exploration while members use them for quick commutes.
- Peak Usage Times: Member usage spikes on weekday mornings and evenings, while casual usage peaks on weekend afternoons.
- Popular Routes: Routes in tourist-heavy areas such as Central Park and Roosevelt Island Tramway are highly frequented, showcasing the significance of tourist locations for casual users.
- Geographic Clustering: Dense clusters of usage around Manhattan's business districts and tourist spots indicate high demand in these areas, suggesting opportunities for infrastructure expansion.

## Visualizations and Story Points
### The analysis is broken down into the following Tableau story points:
1. When are riders most active? 
- Insight: Our analysis of ridership patterns reveals a distinct difference in usage behavior between casual riders and members. Casual riders show a strong preference for weekend rides, likely reflecting leisure and tourism activities. In contrast, members maintain steady ridership during weekdays, aligning with typical commuting hours and routines.
- Peak Usage Observation: Peak usage hours for members are concentrated during the early morning (commuting hours) and late afternoon, indicating a work-related pattern. Casual riders, however, have more consistent usage throughout the day on weekends, showing a significant preference for afternoons.
- Takeaway: These insights present a clear opportunity for Citi Bike to tailor its offerings to each rider type. For instance, increasing bike availability on weekends and in high-tourist areas could better serve casual riders. Additionally, promoting membership benefits during weekends might encourage casual riders to become members, while enhancing service availability around commuting hours would cater to member needs effectively.
2. Trip patterns of Citi Bike users
- Commuting Patterns: Rides peak during weekday commuting hours (8-9 AM, 5-6 PM), indicating significant usage for work commutes. High bike availability in residential areas in the morning and business districts in the evening is essential.
- Recreational and Casual Use: Casual riders have higher usage midday and afternoons, especially on weekends, suggesting leisure or tourist-related activities. Increasing bike availability around parks and tourist areas during these times could improve service for casual riders.
- Strategic Recommendations: Tailoring bike distribution to align with both weekday commuting and weekend recreational demand can enhance user satisfaction. A dynamic redistribution strategy will ensure bikes are available when and where they’re most needed.
3. Where do riders god? Popular Stations and Routes
- This analysis highlights Citi Bike's most popular start and end locations, with a strong concentration in areas frequented by tourists and near transit hubs. Notable locations include Central Park, the Roosevelt Island Tramway, and Governor’s Island. These areas serve both recreational riders, often visiting iconic sites, and commuters utilizing convenient transit connections.
- The high frequency of rides at these locations underscores the dual appeal of Citi Bike for sightseeing and practical transportation. The concentration of rides around Central Park indicates its appeal for scenic routes, while the Roosevelt Island Tramway and Governor’s Island routes attract both tourists and local commuters.
- Key Takeaway: To meet the demand in these high-traffic areas, Citi Bike may consider increasing station density, ensuring bike availability, and rebalancing efforts. This can enhance the user experience by minimizing bike shortages and maximizing accessibility, particularly in popular tourist and transit-adjacent locations.
4. Trip Duration Distribution
- Insights:
    - Members primarily use Citi Bike for short, frequent trips, typically around 5–10 minutes. This suggests a heavy use case for commuting or quick errands.
    - Casual users tend to have longer ride durations, indicating that they are more likely using Citi Bike for leisurely or exploratory trips rather than routine travel.
- Key Takeaway: The contrasting trip durations highlight Citi Bike's dual role in serving both commuting and recreational needs. This segmentation allows for targeted strategies: improving service and bike availability during peak commuting hours for members, and enhancing access to high-demand tourist and scenic areas to accommodate casual users’ longer trips.
5. Geographic Patterns of Usage: Density
- Insight: The heat map indicates zones of intense usage, primarily centered around Midtown Manhattan, Central Park, and Downtown. These areas serve as hubs for commuters, tourists, and local residents, leading to significant demand for bikes and docking stations. Ensuring bike availability in these high-demand locations is crucial to meet user needs.
- Key Takeaway: Identifying these dense areas allows Citi Bike to strategically increase bike availability and docking options in key locations. This approach can improve accessibility, especially during peak hours, while also alleviating issues of overcrowding at popular stations.
6. Geographic Patterns of Usage: Clusters
- Insight: The cluster map identifies groups of stations with shared characteristics such as high ridership, geographic proximity, or similar peak usage hours. This clustering helps pinpoint both established demand hubs and areas that may be underserved by the current station network, allowing for a deeper understanding of usage patterns across the city.
- Key Takeaway: Through cluster analysis, Citi Bike can make informed decisions to optimize its network. High-usage clusters could benefit from expanded bike availability or additional stations to better meet demand, while clusters outside these zones present opportunities for targeted promotions to boost ridership. By aligning station locations and bike availability with demand patterns, Citi Bike can enhance service and improve user experience across both high-traffic and less-utilized areas.

## Recommendations
- Expand High-Demand Stations: Add more bikes and docking stations in Manhattan’s high-density areas, particularly near Central Park, Midtown, and transit hubs, to accommodate both commuter and tourist demand.
- Seasonal Adjustments for Tourists: Increase bike availability in tourist-heavy areas during peak travel seasons, such as summer, to accommodate casual riders.
- Improve Member Experience During Commute Hours: Prioritize bike redistribution to high-demand commuter areas in the early mornings and evenings.
- Increase Marketing to Casual Riders: Since casual riders frequent tourist spots, Citi Bike could introduce promotional packages targeting tourists to boost casual rider engagement.


## Business Opportunities
### Businesses can leverage these insights by offering tailored promotions based on user type:
- Commuter-Friendly Businesses: Companies near popular start and end locations can partner with Citi Bike to provide discounts or promotions for members who ride during peak commuting hours, driving traffic from daily commuters.
- Leisure-Oriented Businesses: Cafes or tourist attractions near popular casual routes can offer deals for longer-duration riders, encouraging casual users to extend their trips and explore more local attractions.

This targeted approach can enhance the user experience for Citi Bike riders and drive more foot traffic to nearby businesses, creating mutual benefits for Citi Bike and local businesses alike.

## Future Enhancements
- Seasonal and Weather Impact Analysis: Analyze how different seasons and weather patterns impact ridership to improve bike availability forecasting.
- Enhanced Predictive Models: Utilize machine learning to predict peak times and locations for future expansions.
- User Experience Surveys: Collect direct feedback from users, especially casual riders, to further tailor the service for tourists and infrequent users.
- Integration with Public Transit: Explore opportunities for more seamless integration with NYC transit options for smoother transitions between biking and other transportation modes.

## Conclusion
This analysis provides Citi Bike with detailed insights into usage patterns, helping the company tailor its services to meet the needs of different user groups and areas. By adjusting bike availability to align with commuting and recreational patterns, Citi Bike can improve user satisfaction, reduce bike shortages, and promote membership growth. Additionally, partnering with local businesses for tailored promotions based on user behavior presents an opportunity for community engagement and shared value.

This README file summarizes key insights from the Tableau story points, providing actionable recommendations for enhancing the Citi Bike service. For a detailed visualization and exploration of these insights, please refer to the associated Tableau workbook.

## Getting Started
1. Download the Tableau Workbook: Download the .twbx file included with the project.
2. Open in Tableau: Use Tableau to explore each dashboard and story point.
3. Navigate Through Story Points: Follow the story points to get a comprehensive view of Citi Bike usage trends and insights.
4. Explore Recommendations: Each insight is accompanied by actionable recommendations for Citi Bike service improvement.
