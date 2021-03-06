---
title: Sign Hooks
---

# Sign Hooks

## CanUpdateSign

``` csharp
bool CanUpdateSign(BasePlayer player, Signage sign)
{
    Puts("CanUpdateSign works!");
    return true;
}
```

 * Called when the player attempts to change the text on a sign or lock it
 * Returning true or false overrides default behavior

## OnSignLocked

``` csharp
void OnSignLocked(Signage sign, BasePlayer player)
{
    Puts("OnSignLocked works!");
}
```

 * Called after the player has locked a sign
 * No return behavior

## OnSignUpdated

``` csharp
void OnSignUpdated(Signage sign, BasePlayer player, string text)
{
    Puts("OnSignUpdated works!");
}
```

 * Called after the player has changed the text on a sign
 * No return behavior

## OnSpinWheel

``` csharp
void OnSpinWheel(BasePlayer player, SpinnerWheel wheel)
{
    Puts("OnSpinWheel works!");
}
```

 * Called when the player spins a spinner wheel
 * No return behavior
