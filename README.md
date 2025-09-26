# Global Energy Dashboard (2020–2022)

This project is the result of a complete data modeling and visualization process in Power BI, using global energy consumption and generation data from 2020 to 2022. The goal was to build a set of dashboards focused on analyzing energy trends by country and energy source (renewable and non-renewable), following best practices in data cleaning, transformation, and dashboard design.  

### Data Preparation
- Applied advanced cleaning techniques in Power Query.  
- Normalized energy categories and removed redundancies.  
- Split compound fields to create a scalable and usable indicator dimension.  
- Built a star-schema model centered on the **fact table `fctEnergy`**, linked to dimensions: country, year, energy type, and energy indicators.  

### Dashboards
- **Dashboard 1** – Comparative analysis of energy consumption and generation by country.  
- **Dashboard 2** – Aggregated and per-country KPIs (top energy types, emissions, population).  
- **Dashboard 3** – Storytelling summary: global energy impact, basic projections, and key takeaways on the energy transition.

### Notes
- The `.pbix` file and related components are available for reuse or adaptation in other data-driven projects.  
