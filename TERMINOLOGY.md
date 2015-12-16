# Terminology in food infrastructure

As projects tend to develop specific meanings for specific terms, and they may
be slightly different for each system, this document tries to bring a little
clarity on how they relate.

With so many slightly different terms, it is hardly avoidable to create a new
set of terms for describing all of them. Terms in _italics_ refer to those 'defined'
in this document.


### _Product_

_Suppliers_ sell _products_. They may have a name, description, image, and
probably a unit and price (these may also be specified in a _product variant_
instead).

- Foodsoft: **Article**
- Open Food Network: **Product**


### _Product variant_

Some systems may use _product variants_ to describe variations on the same
product. Different classes of apples, for example, or different package sizes.

* Foodsoft: not present (uses different products)
* Open Food Network: **Variant**


### _Supplier_

_Suppliers_ sell _products_. They would typically have profile information like a
name, address, logo, description, web links.

- Foodsoft: **Supplier**
- Open Food Network: **Producer** (who produces something new) and **Hub** (who sells _products_ from other _suppliers_ in the system)


### _Order cycle_

Often _products_ can only be bought during a certain timeframe. _Order cycles_ have a
start date, and end date, and a number of _products_. It is probably only referring
to _products_ from a single _supplier_.

- Foodsoft: **Order**
- Open Food Network: **Order cycle**


### _Order_

Consumers buying _products_ (probably in an _order cycle_) do this by placing
an _order_, which contains a number of products.

* Foodsoft: **Group order** with **Group order articles**
* Open Food Network: **Order** with **Line items**


## Loose ends

Plenty :) including:
* Categories / taxonomies / tags
* Customers / order groups / users / enterprises
* Transporter, processors, storage, (re)packaging, ...

Let's add and expand on the basis of concrete examples. And feel free to edit,
clarify, add terms for another project, etc.

Part of [food-dashboard](https://github.com/ouisharelabs/food-dashboard).
