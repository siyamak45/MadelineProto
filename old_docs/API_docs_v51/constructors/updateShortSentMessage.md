---
title: updateShortSentMessage
description: updateShortSentMessage attributes, type and example
---
## Constructor: updateShortSentMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|:-------------:|---------:|
|unread|[Bool](../types/Bool.md) | Optional|
|out|[Bool](../types/Bool.md) | Optional|
|id|[int](../types/int.md) | Required|
|pts|[int](../types/int.md) | Required|
|pts\_count|[int](../types/int.md) | Required|
|date|[int](../types/int.md) | Required|
|media|[MessageMedia](../types/MessageMedia.md) | Optional|
|entities|Array of [MessageEntity](../types/MessageEntity.md) | Optional|



### Type: [Updates](../types/Updates.md)


### Example:

```
$updateShortSentMessage = ['_' => 'updateShortSentMessage', 'unread' => true, 'out' => true, 'id' => int, 'pts' => int, 'pts_count' => int, 'date' => int, 'media' => MessageMedia, 'entities' => [Vector t], ];
```  

