# Api_scrapper
This custom build API helps the user to fetch data such as Product details, offers and reviews from Amazon.ca.
> API Key is required

> API is listed on the RAPID API website from where users can request this api and can use it in their applications.
## Technologies used:
Node.js, Express and Javascript.

## ENDPOINTS
### Product Details
- Specific Product details can be fetched by using the endpoint {url}/products/{productID}
### Product Search
- Products can be searched by using the endpoint {url}/search/{productName}
### Product Offers
- Offers related to a specific product can be fetched using the endpoint {url}/products/{productID}/offers
### Product Reviews
- Reviews about the products can be fetched using the endpoint {url}/products/{productID}/reviews
