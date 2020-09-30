# Product Schema

```txt
http://example.com/product.schema.json
```

A product from Acme's catalog


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                               |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [product.schema.json](../out/product.schema.json "open original schema") |

## Product Type

`object` ([Product](product.md))

# Product Properties

| Property                    | Type      | Required | Nullable       | Defined by                                                                                                         |
| :-------------------------- | --------- | -------- | -------------- | :----------------------------------------------------------------------------------------------------------------- |
| [productId](#productId)     | `integer` | Required | cannot be null | [Product](product-properties-productid.md "http&#x3A;//example.com/product.schema.json#/properties/productId")     |
| [productName](#productName) | `string`  | Required | cannot be null | [Product](product-properties-productname.md "http&#x3A;//example.com/product.schema.json#/properties/productName") |
| [price](#price)             | `number`  | Required | cannot be null | [Product](product-properties-price.md "http&#x3A;//example.com/product.schema.json#/properties/price")             |
| [tags](#tags)               | `array`   | Optional | cannot be null | [Product](product-properties-tags.md "http&#x3A;//example.com/product.schema.json#/properties/tags")               |
| [dimensions](#dimensions)   | `object`  | Optional | cannot be null | [Product](product-properties-dimensions.md "http&#x3A;//example.com/product.schema.json#/properties/dimensions")   |

## productId

The unique identifier for a product


`productId`

-   is required
-   Type: `integer`
-   cannot be null
-   defined in: [Product](product-properties-productid.md "http&#x3A;//example.com/product.schema.json#/properties/productId")

### productId Type

`integer`

## productName

Name of the product


`productName`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [Product](product-properties-productname.md "http&#x3A;//example.com/product.schema.json#/properties/productName")

### productName Type

`string`

## price

The price of the product


`price`

-   is required
-   Type: `number`
-   cannot be null
-   defined in: [Product](product-properties-price.md "http&#x3A;//example.com/product.schema.json#/properties/price")

### price Type

`number`

### price Constraints

**minimum (exclusive)**: the value of this number must be greater than: `0`

## tags

Tags for the product


`tags`

-   is optional
-   Type: `string[]`
-   cannot be null
-   defined in: [Product](product-properties-tags.md "http&#x3A;//example.com/product.schema.json#/properties/tags")

### tags Type

`string[]`

### tags Constraints

**minimum number of items**: the minimum number of items for this array is: `1`

**unique items**: all items in this array must be unique. Duplicates are not allowed.

## dimensions




`dimensions`

-   is optional
-   Type: `object` ([Details](product-properties-dimensions.md))
-   cannot be null
-   defined in: [Product](product-properties-dimensions.md "http&#x3A;//example.com/product.schema.json#/properties/dimensions")

### dimensions Type

`object` ([Details](product-properties-dimensions.md))
