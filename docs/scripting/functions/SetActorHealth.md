---
id: SetActorHealth
title: SetActorHealth
description: Set the health of an actor.
tags: []
---

:::warning

This function was added in SA-MP 0.3.7 and will not work in earlier versions!

:::

## Description

Set the health of an actor.


| Name | Description |
|------|-------------|
|actorid | The ID of the actor to set the health of.|
|Float:health | The value to set the actors's health to.|


## Returns

 1 - success

 0 - failure (i.e. actor is not created).


## Examples


```c
new MyActor;

public OnGameModeInit()
{
    MyActor = CreateActor(179, 316.1, -134.0, 999.6, 90.0); // Actor as salesperson in Ammunation
    SetActorHealth(MyActor, 100);
    return 1;
}
```


## Related Functions


