Since rendering folium maps is not possible in Github the unrendered code of this repository can be found at
[(here)](http://nbviewer.org/github/Vishnu-Kota/Foursquare/blob/main/Foursquare.ipynb)

When you look for nearby restaurants or plan an errand in an unknown area, you expect relevant, accurate information. To maintain quality data worldwide is a challenge, and one with implications beyond navigation. Businesses make decisions on new sites for market expansion, analyze the competitive landscape, and show relevant ads informed by location data. For these, and many other uses, reliable data is critical.

Large-scale datasets on commercial points-of-interest (POI) can be rich with real-world information. To maintain the highest level of accuracy, the data must be matched and de-duplicated with timely updates from multiple sources. De-duplication involves many challenges, as the raw data can contain noise, unstructured information, and incomplete or inaccurate attributes. A combination of machine-learning algorithms and rigorous human validation methods are optimal to de-dupe datasets.

With 12+ years of experience perfecting such methods, Foursquare is the #1 independent provider of global POI data. The leading independent location technology and data cloud platform, Foursquare is dedicated to building meaningful bridges between digital spaces and physical places. Trusted by leading enterprises like Apple, Microsoft, Samsung, and Uber, Foursquare’s tech stack harnesses the power of places and movement to improve customer experiences and drive better business outcomes.

In this competition, you’ll match POIs together. Using a dataset of over one-and-a-half million Places entries heavily altered to include noise, duplications, extraneous, or incorrect information, you'll produce an algorithm that predicts which Place entries represent the same point-of-interest. Each Place entry includes attributes like the name, street address, and coordinates. Successful submissions will identify matches with the greatest accuracy.

By efficiently and successfully matching POIs, you'll make it easier to identify where new stores or businesses would benefit people the most.


# Foursquare
![image](https://user-images.githubusercontent.com/65905342/169336470-6e1c98a9-1c1f-412f-b861-4067fc0215a6.png)

## Table Of Contents:
- Libraries Used
- Data Cleaning
- Data Visualization
- Location Analysis
- Map Out the Lat / Long by Category
- Heatmap
- Point Of Interest[POI]
- LightGBM baseline model
# Libraries Used:
- [(Numpy)](https://numpy.org/install/)
- [(Pandas)](https://pandas.pydata.org/)
- [(Geolocation)](https://pypi.org/project/geolocation-python/)
- [(Folium)](https://pypi.org/project/folium/)
