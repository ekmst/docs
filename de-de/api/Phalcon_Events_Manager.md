---
layout: article
language: 'de-de'
version: '4.0'
title: 'Phalcon\Events\Manager'
---
# Class **Phalcon\Events\Manager**

*implements* [Phalcon\Events\ManagerInterface](Phalcon_Events_ManagerInterface)

[Source on GitHub](https://github.com/phalcon/cphalcon/tree/v{{ page.version }}.0/phalcon/events/manager.zep)

Phalcon Events Manager, offers an easy way to intercept and manipulate, if needed, the normal flow of operation. With the EventsManager the developer can create hooks or plugins that will offer monitoring of data, manipulation, conditional execution and much more.

## Methods

public **attach** (*string* $eventType, *object* | *callable* $handler, [*int* $priority])

Attach a listener to the events manager

public **detach** (*string* $eventType, *object* $handler)

Detach the listener from the events manager

public **enablePriorities** (*mixed* $enablePriorities)

Set if priorities are enabled in the EventsManager

public **arePrioritiesEnabled** ()

Returns if priorities are enabled

public **collectResponses** (*mixed* $collect)

Tells the event manager if it needs to collect all the responses returned by every registered listener in a single fire

public **isCollecting** ()

Check if the events manager is collecting all all the responses returned by every registered listener in a single fire

public *array* **getResponses** ()

Returns all the responses returned by every handler executed by the last 'fire' executed

public **detachAll** ([*mixed* $type])

Removes all events from the EventsManager

final public *mixed* **fireQueue** ([SplPriorityQueue](https://php.net/manual/en/class.splpriorityqueue.php) | *array* $queue, [Phalcon\Events\Event](Phalcon_Events_Event) $event)

Internal handler to call a queue of events

public *mixed* **fire** (*string* $eventType, *object* $source, [*mixed* $data], [*boolean* $cancelable])

Fires an event in the events manager causing the active listeners to be notified about it

```php
<?php

$eventsManager->fire("db", $connection);

```

public **hasListeners** (*mixed* $type)

Check whether certain type of event has listeners

public *array* **getListeners** (*string* $type)

Returns all the attached listeners of a certain type