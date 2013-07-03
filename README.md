# Fashionable forms example Application

Run these commands to get it running.

```
bundle
rake db:setup
rails s
```

# Explanation

Alright, so currently these forms are just for creating Products & ProductTypes which should demonstrate how to dynamically render Product forms based on the product type selected. The same principle applies for searching and shouldn't be terribly difficult to do.

So first we need a couple of ProductTypes, in our case "Men" and "Women". Do that through product_types/new. You'll also be able to specify which fields you'll have for each particular ProductType.

When you go to products/new you'll be able to select a type from the dropdown to associate with this new product.

