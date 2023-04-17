# ImVariant Remade

## Functions

* [Begin](#begin)
* [Destroy](#destroy)
* [GetVariantType](#getvarianttype)
* [Label](#label)

### Label

```c++
ImVariant::Label(remaking...);
```

Usage:
```c++
variantlist_t variant = { "OnDialogRequest" };
ImVariant::Label("Hello!", variant, 1, true, ImVariant_SpacerFlagSmall);
ImVariant::Send(variant);
```
Result:
```
Sends a variantlist that contains a label with "Hello!" text.
```
