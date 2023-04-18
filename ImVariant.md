# ImVariant made by ProB1

## Functions

* [Begin](#begin)
* [Destroy](#destroy)
* [GetVariantType](#getvarianttype)
* [Label](#label)

### Label

```c++
ImVariant::Label(const std::string& label_text, int itemid, ImVariant_SizeFlags flag, ImVariant_LabelFlags flag2)
```

Usage:
```c++
variantlist_t variant = { "OnDialogRequest" }; // dialog type
ImVariant::Label("Hello!", NULL, ImVariant_SizeFlags::Small, ImVariantLabelFlags::Normal); // adds normal label without icon
ImVariant::Send(variant); // sends variant list
ImVariant::Reset(); // resets saved variant
```
Result:
```
Sends a variantlist that contains a label with "Hello!" text.
```
