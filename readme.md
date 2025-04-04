### Bivariate Map of Emergency Medical Services and Fire Fatalities, NC

---
> This map displays EMS building locations in North Carolina as point data. It is categorized by the type of service offered at each location. The map also displays data for fire fatalities as a choropleth map of counties in North Carolina.  It has basic map elements like a legend, scale bar, and north arrow. There is basic interactivity like zooming and panning. There is also click interactivity with the EMS locations, which gives their description using the North American Industry Classification System. 

---

#### Packages, Stylesheets, Data:
- jQuery		(handling DOM manipulation and event handling) 
- leaflet.js 		(Map creation and customization)
- Color Brewer		(color palettes)
- Font Awesome 	(icon library)
- Chroma.js		(color conversions and scales)
  
- Fire Fatality data from ncosfm.gov
- EMS data from nconemap.gov
- North Arrow PNG from  https://www.cleanpng.com/ 

---

- Issue with 25mb limit on github. (~50gb)
- Solved by reducing size of geojson using mapshaper.org

