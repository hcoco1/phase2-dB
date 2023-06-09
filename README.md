<div align="center"><h1>Ivan Arias. Full-Stack Engineering Student.</h1></div>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/arias-ivan-hcoco1/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://www.youtube.com/channel/UCban0ilP3jBC9rdmL-fPy_Q">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="https://twitter.com/hcoco1">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>  

## Phase 2 Database Project: "properties".
### Database link:  https://phase2-db.onrender.com/
##### Database repository link: https://github.com/hcoco1/phase2-dB


#### Project Pitch

**"properties"**  is a JSON object representing a list of properties and is used as a data source for the Real State Site (https://phase2app.vercel.app/).

Each property has the following attributes:

* "id": An identifier for the property.
* "address": The street address of the property.
* "city": The city where the property is located.
* "state": The state where the property is located.
* "zip_code": The ZIP code of the property.
* "listing_price": The price at which the property is listed.
* "bedrooms": The number of bedrooms in the property.
* "bathrooms": The number of bathrooms in the property.
* "square_feet": The total area of the property in square feet.
* "listing_date": The date when the property was listed.
* "property_type": The type of property.
* "operation_type": The type of operation (either "Sale" or "Rent").
* "image": The URL of an image representing the property.

### Backend Setup

##### Database Structure


```markdown
{
  "properties": [
    {
      "id": 1,
      "address": "8 Hermina Center",
      "city": "San Jose",
      "state": "California",
      "zip_code": "95138",
      "listing_price": 278185,
      "bedrooms": 8,
      "bathrooms": 2,
      "square_feet": 6427,
      "listing_date": "6/22/2021",
      "property_type": "Farm",
      "operation_type": "Sale",
      "image": "https://images.unsplash.com/photo-rce=unsplash_source&w=640"
    },
    {
      "id": 2,
      "address": "418 Mitchell Trail",
      "city": "Newport News",
      "state": "Virginia",
      "zip_code": "23612",
      "listing_price": 496205,
      "bedrooms": 8,
      "bathrooms": 1,
      "square_feet": 1553,
      "listing_date": "1/9/2020",
      "property_type": "Farm",
      "operation_type": "Rent",
      "image": "https://images.unsplash.com/photo-159h_source&w=640"
    }
  ]
}
```
