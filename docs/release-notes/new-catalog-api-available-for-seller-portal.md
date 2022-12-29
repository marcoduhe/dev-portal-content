---
title: "New Catalog API available for Seller Portal"
slug: "new-catalog-api-available-for-seller-portal"
type: "added"
createdAt: "2022-10-20T14:45:00.000Z"
hidden: false
---

![Commerce APIs](https://img.shields.io/badge/-Commerce%20APIs-brightgreen)

[block:callout]
{
  "type": "info",
  "body": "The new Catalog API is part of the [Seller Portal Catalog](https://help.vtex.com/en/tutorial/how-the-seller-portal-catalog-works--7pMB6YOt6YQDQQbzFB4Pxp). This functionality is in the Beta stage and can be discontinued at any moment at VTEX's discretion. VTEX will not be responsible for any instabilities caused by its use or discontinuity. If you have any questions, please contact [our Support Center](https://support.vtex.com/hc/en-us/requests)."
}
[/block]
The [Seller Portal](https://help.vtex.com/en/tutorial/how-to-set-up-your-store-on-seller-portal--6w1vBdRH2uuBGmUqgNQjwK) is an edition of the VTEX platform for sellers to connect and sell their products on marketplaces, providing sellers with the essential capabilities for an ecommerce operation.

Previously, sellers were limited to integrating their catalog manually through the Seller Portal interface.

Now, we have released the [Catalog API - Seller Portal](https://developers.vtex.com/vtex-rest-api/reference/catalog-api-seller-portal-overview) to enable sellers using Seller Portal to massively create, fetch and edit information concerning products, SKUs, brands and categories.

The following endpoints are now available:

### Product
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get Product by ID](https://developers.vtex.com/vtex-rest-api/reference/getproduct)
<span class="APIMethod APIMethod_fixedWidth APIMethod_put">put</span> [Update Product](https://developers.vtex.com/vtex-rest-api/reference/putproduct)
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get Product Description by Product ID](https://developers.vtex.com/vtex-rest-api/reference/getproductdescription)
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get Product by external ID, SKU ID, SKU external ID or slug](https://developers.vtex.com/vtex-rest-api/reference/getproductquery)
<span class="APIMethod APIMethod_fixedWidth APIMethod_post">post</span> [Create Product](https://developers.vtex.com/vtex-rest-api/reference/postproduct)


### SKU
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Search for SKU](https://developers.vtex.com/vtex-rest-api/reference/searchsku)
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get List of SKUs](https://developers.vtex.com/vtex-rest-api/reference/listsku)

### Brand
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get List of Brands](https://developers.vtex.com/vtex-rest-api/reference/listbrand)
<span class="APIMethod APIMethod_fixedWidth APIMethod_post">post</span> [Create a Brand](https://developers.vtex.com/vtex-rest-api/reference/postbrand)
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get Brand by ID](https://developers.vtex.com/vtex-rest-api/reference/getbrand)
<span class="APIMethod APIMethod_fixedWidth APIMethod_put">put</span> [Update Brand](https://developers.vtex.com/vtex-rest-api/reference/putbrand)

### Category
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get Category Tree](https://developers.vtex.com/vtex-rest-api/reference/getcategorytree)
<span class="APIMethod APIMethod_fixedWidth APIMethod_put">put</span> [Update Category Tree](https://developers.vtex.com/vtex-rest-api/reference/updatecategorytree)
<span class="APIMethod APIMethod_fixedWidth APIMethod_get">get</span> [Get Category by ID](https://developers.vtex.com/vtex-rest-api/reference/getbyid-1)
<span class="APIMethod APIMethod_fixedWidth APIMethod_post">post</span> [Create a Category](https://developers.vtex.com/vtex-rest-api/reference/createcategory)