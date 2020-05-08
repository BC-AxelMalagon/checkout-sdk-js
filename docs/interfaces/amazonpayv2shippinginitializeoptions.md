[@bigcommerce/checkout-sdk](../README.md) > [AmazonPayv2ShippingInitializeOptions](../interfaces/amazonpayv2shippinginitializeoptions.md)

# AmazonPayv2ShippingInitializeOptions

A set of options that are required to initialize the shipping step of checkout in order to support Amazon Pay.

When Amazon Pay is initialized, a widget will be inserted into the DOM. The widget has a list of shipping addresses for the customer to choose from.

## Hierarchy

**AmazonPayv2ShippingInitializeOptions**

## Index

### Properties

* [container](amazonpayv2shippinginitializeoptions.md#container)

### Methods

* [onError](amazonpayv2shippinginitializeoptions.md#onerror)

---

## Properties

<a id="container"></a>

### `<Optional>` container

**● container**: * `undefined` &#124; `string`
*

The ID of a container which the address widget should insert into.

___

## Methods

<a id="onerror"></a>

### `<Optional>` onError

▸ **onError**(error: *[StandardError](../classes/standarderror.md)*): `void`

**Parameters:**

| Param | Type |
| ------ | ------ |
| error | [StandardError](../classes/standarderror.md) |

**Returns:** `void`

___

