# How much should we set the price of a product to get the maximum revenue from it?

![Price Optimization](https://tryolabs.com/assets/blog/price-optimization-machine-learning/price-optimization-opportunities-86e5bf9282.svg)

## 🏨 Background

Price optimization is essential for companies as it maximizes revenue and profit by ensuring products are neither underpriced nor overpriced. It provides a competitive edge, positions products strategically, and allows dynamic responses to market changes. 

Optimized pricing offers insights into customer behavior, aids in market segmentation, and enhances inventory management by balancing supply and demand.

It fosters long-term growth and brand loyalty through fair pricing and ensures financial health for investments in innovation.

## 💾 The Data

We have obtained the informations from six different sources (`customers`, `orders`, `products`, `regions`, `salesteam`, `storelocations`):

### Customers
- "CustomerID"
- "CustomerName"

### Orders
- "OrderNumber"
- "SalesChannel" 
- "WarehouseCode"
- "ProducedDate"
- "OrderDate" 
- "ShipDate" 
- "DeliveryDate"
- "CurrencyCode" 
- "SalesTeamID" 
- "CustomerID"
- "StoreID" 
- "ProductID"
- "OrderQuantity"
- "DiscountApplied"
- "UnitPrice" 
- "UnitCost"

### Products
- "ProductID"
- "ProductName"

### Regions
- "StateCode"
- "State"
- "Region"

### SalesTeam
- "SalesTeamID"
- "SalesTeam"
- "Region"

### StoreLocations
- "StoreID"
- "CityName"
- "Country"
- "StateCode"
- "State"
- "Type"
- "Latitude"
- "Longitude"
- "AreaCode"
- "Population"
- "HouseholdIncome"
- "MedianIncome"
