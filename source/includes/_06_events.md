# Types of events

## Order Created

Event Name: `order.created`

```json
{
    "event": "order.created",
    "order_id": "172dfbff-ebd9-4c9c-868c-cb79ef7775ed",
    "timestamp": "2018-01-01T00:00:00Z"
}
```

Occurs whenever an order is created.

## Order Updated

Event Name: `order.updated`

```json
{
    "event": "order.updated",
    "order_id": "172dfbff-ebd9-4c9c-868c-cb79ef7775ed",
    "timestamp": "2018-01-01T00:00:00Z"
}
```

Occurs whenever an order is updated.

## Order Deleted

Event Name: `order.deleted`

```json
{
    "event": "order.deleted",
    "order_id": "172dfbff-ebd9-4c9c-868c-cb79ef7775ed",
    "timestamp": "2018-01-01T00:00:00Z"
}
```

Occurs whenever an order is deleted.

## Order Status Updated

Event Name: `order.status_updated`

```json
{
    "event": "order.status_updated",
    "previous_status": "booked",
    "current_status": "dispatched",
    "order_id": "172dfbff-ebd9-4c9c-868c-cb79ef7775ed",
    "timestamp": "2018-01-01T00:00:00Z"
}
```

Occurs whenever an order status changed.