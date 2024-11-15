---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# The basics

### Creating a shipment

Begin by clicking the _Shipment ID_ button.

Either enter the Shipment ID manually or enable the camera to scan a barcode.

<div align="left">

<figure><img src=".gitbook/assets/www.supership.is_shipments (1).png" alt=""><figcaption><p>By pressing the camera button you can scan a barcode as the Shipment ID</p></figcaption></figure>

</div>

This will create a `PENDING` shipment in the system and take you to the shipment details page.

You can now enable the _camera_ using the corresponding button.

We suggest taking at least 2-3 images of the delivered items before confirming the shipment.

You can add attachments either by barcode scanning or manual entry.

Comments can be useful for future references and internal communication.



### Confirming a shipment

Once you're happy with the shipment data, attachments, images etc. you can confirm the shipment.

By clicking the _Complete_ button on the shipment you move on to the confirmation stage.

You now have two options, _authentication_ or _delivery without authentication_.

{% hint style="info" %}
It is strongly suggested to go with _authentication_ whenever possible.
{% endhint %}

Authentication is done using [_electronic IDs_](https://island.is/en/electronic-id).

The operator inserts the recipients phone number or SSN to prompt the recipients phone.

Once the request is confirmed by the recipient, then operator receives the information related to the authentication request. The operator can then validate that the recipient is indeed who he says he is, and is permitted to receive the shipment.

The operator can either approve or deny the recipient during this process. See [features](features.md) for further information regarding available options.

Once the shipment is confirmed by both the recipient and the operator, the shipment is marked as `COMPLETE` and it's data locked. The location of the delivery is marked, along with validated information on the recipient.

Delivering authentication simply skips these steps and marks the shipment as `DELIVERED` and locks it's data.

### Finding and monitoring shipments

The shipments table updates itself on an interval, so there is no need to refresh the page manually.

Searching can be done by IDs, recipients, attachments and comments.

Filtering by shipment status and dates is supported.

Sorting can be done by IDs, status, creation date and modification date.

