

```graphql

query {
  Productaggregation {
    data {
      title
      Shop
      specifications
      images
      price
      disprice
      image
      category
      marketplace
      about
      ShopData {
        title
        user {
          username
        }
        review {
          vfm
          favs
        }
      }
    }
    groupByCategory {
      idw
      count
    }
    groupByBrand {
      idw
      count
    }
  }
}

```