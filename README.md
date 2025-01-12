# **Jabodetabek Property Analysis 🏠💡**

This notebook is used to analyze the prices and features of houses for sale in Jabodetabek based on data scraped from Rumah123.com.
___

Thinking about buying or selling a home in the dynamic Jabodetabek area? 🌆✨ Make informed decisions with this in-depth property analysis! 🧠📊

This research aims to provide a comprehensive analysis of property data in the Jabodetabek region over two weeks, with the goal of building an interactive dashboard that delivers relevant insights for various stakeholders. The analysis includes measuring price distribution, exploring the correlation between home features and price, and identifying price trends across different areas. It also compares property prices based on facilities, property types, and furniture conditions.

💡 Who Can Benefit?
- 🏘️ Real Estate Agents: Set competitive, market-optimized prices by understanding trends and correlations.
- 🏠 Homebuyers: Choose the right property at the right price by knowing what factors truly influence its value.
- 🏗️ Developers: Plan new projects strategically by identifying areas in high demand based on market trends.

This analysis goes beyond surface-level insights, offering valuable data-driven information that empowers stakeholders to make confident and informed property decisions. 🔍✨
___
## **Dashboard 📊**
**[Jabodetabek Property Analysis](https://public.tableau.com/views/JabodetabekPropertyAnalysis/DESCRIPTIVE?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

## **Dataset Overview 📄**
This dataset, extracted from [Rumah123.com](https://www.rumah123.com/?utm_source=Google&utm_medium=cpc&utm_campaign=SEM+V1+-+Secondary+Regular+-+Brand+Keyword&gclsrc=aw.ds&&gclid=Cj0KCQiAyoi8BhDvARIsAO_CDsAdcBqzie1ZKwLvUpED9sRFa9NHZXL5bEbuwUbzm7pkpQRf4kzFagMaAjFeEALw_wcB&gad_source=1), offers a comprehensive collection of property listings specifically within the Jabodetabek area of Indonesia. This dataset provides detailed insights into the Jabodetabek property market, covering a wide range of features to facilitate comprehensive real estate analysis:

| **Column Name**             | **Description**                                                        |
|-----------------------------|-------------------------------------------------------------------------|
| url                         | URL of the property listing.                                           |
| title                       | Title of the property listing.                                         |
| description                 | Detailed description of the property.                                  |
| price                       | Price of the property in Indonesian Rupiah. (Numeric)                 |
| location                    | Location of the property.                                              |
| land_size                   | Land size of the property in square meters.                           |
| building_size               | Building size of the property in square meters.                       |
| bedroom                     | Number of bedrooms in the property. (Numeric)                         |
| bathroom                    | Number of bathrooms in the property. (Numeric)                        |
| garage                      | Number of garages in the property. (Numeric)                          |
| carport                     | Number of carports in the property. (Numeric)                         |
| property_type               | Type of the property (e.g., Rumah, Apartemen).                        |
| certificate                 | Type of property ownership certificate.                               |
| voltage_watt                | Electrical voltage capacity in watts. (Numeric)                       |
| maid_bedroom                | Number of maid's bedrooms. (Numeric)                                  |
| maid_bathroom               | Number of maid's bathrooms. (Numeric)                                 |
| kitchen                     | Number of kitchen in the property. (Numeric)                          |
| dining_room                 | Number of dining room in the property. (Numeric)                      |
| living_room                 | Number of living room in the property. (Numeric)                      |
| furniture                   | Furniture status (e.g., Furnished, Unfurnished, Semi-Furnished).      |
| building_material           | Building materials used for the property.                             |
| floor_material              | Flooring materials used for the property.                             |
| floor_level                 | Number of floors in the property. (Numeric)                           |
| house_facing                | Direction the house faces (e.g., East, West).                         |
| concept_and_style           | Architectural concept or style of the property.                       |
| view                        | Type of view available from the property.                             |
| internet_access             | Presence of internet access (e.g., Wifi).                             |
| road_width                  | Width of the road in front of the property.                           |
| year_built                  | Year the property was built. (Numeric)                                |
| year_renovated              | Year the property was last renovated. (Numeric)                       |
| water_source                | Source of water (e.g., PAM, Air Tanah).                               |
| corner_property             | Indicates if the property is located on a corner. (Binary: True/False)|
| property_condition          | Condition of the property (e.g., Full Renovasi, Rapi Terawat).        |
| ad_type                     | Type of advertisement (e.g., Dijual, Dijual Cepat).                   |
| ad_id                       | Unique identifier for the property listing.                           |


## **Key Findings 🔍**
1. **Price Variation**: Property prices in Jabodetabek exhibit a wide range, with a median price around Rp2,500,000,000. The most popular price range is between Rp1,250,000,000,00 and Rp1,500,000,000,00.
2. **Physical Factors**: Physical attributes such as building area, land size, electrical capacity, number of bedrooms, bathrooms, maid's rooms, carports, property type, property condition, furniture, and city location have a significant correlation with property prices.
3. **Prime Locations**: South Jakarta has the highest property selling prices. Areas with high property prices are generally located in strategic areas in the city center. These locations have extensive access to various facilities and transportation, making the selling price of houses there tend to be more expensive.
4. **Land Size and Price**: In city-center areas, land size has a strong positive correlation with price, indicating that land is a primary determinant of value. However, in suburban areas, the relationship between land size and price is less pronounced, as location and surrounding amenities play a more significant role.
5. **Building Size and Price**: While property prices generally increase with building size, certain city-center areas have higher prices even for properties of the same size, suggesting that other factors like public facilities, area reputation, and accessibility also influence property value.
6. **Standard Layouts**: Most properties in the region have a standard layout with 3 bedrooms and 3 bathrooms. Additional features like maid's rooms or garages are less common.
7. **Property Type and Price**: Property type is significantly correlated with price, larger properties generally command higher prices. However, other factors also influence pricing.

## **Conclusion 💡**
The pricing of properties in Jabodetabek is influenced by a complex interplay of factors, with location and physical characteristics being the primary determinants. While the median price is around Rp2,500,000,000, there is significant variation influenced primarily by proximity to city centers and access to public facilities. Properties in strategic city-center locations show a strong correlation between land size and price, while in suburban areas, location and surrounding amenities play a more dominant role. The standard layout of properties, with 3 bedrooms and 3 bathrooms, reflects a consistent market preference, while larger property types generally command higher prices, though other factors such as location and amenities also influence pricing.

## **Business Recommendations 💼**
Based on the property market analysis in Jabodetabek, the following strategic business recommendations can be made:

1. **Develop Mid-Range Properties**: Focus on building homes with 3 bedrooms and 3 bathrooms, as this is the most popular configuration. Target a price range of Rp1,250,000,000,00 to Rp1,500,000,000,00 to cater to the largest market segment. Prioritize efficient designs while maintaining modern comfort standards.
2. **Location Strategy**: Identify suburban areas with growth potential, especially those that will gain access to new transportation or public facilities. Invest in locations with planned infrastructure developments to anticipate property value increases. Consider mixed-use developments in strategic areas to maximize land value.
3. **Product Differentiation**: Add differentiating features such as smart home systems or eco-friendly designs. Develop cluster concepts with attractive communal facilities. Offer customization options for interiors and layouts to meet buyer needs.

## **Further Improvement 🚀**
1. **Expand Data and Analysis**: Incorporate new variables such as developer name, mortgage options, smart home features, and accessibility to public facilities. Analyze the correlation between these factors and property prices.
2. **Broaden Geographic Scope**: Extend the analysis to other major Indonesian cities like Surabaya, Bandung, or Medan. Compare property prices across cities to identify broader market trends and regional factors influencing prices.
3. **Utilize Multiple Data Sources**: Combine data from various sources to create a richer dataset and conduct more in-depth analyses.

## **Author 👩‍💻**

Yasmin Naila Rachmat
LinkedIn: [Yasmin Naila Rachmat](linkedin.com/in/yasmin-naila)
