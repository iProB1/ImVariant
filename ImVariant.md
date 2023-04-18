# ImVariant made by ProB1

## Functions

* [Begin](#begin)
* [Destroy](#destroy)
* [PrintVariant](#printvariant)
* [Label](#label)

### PrintVariant

```c++
ImVariant::GetVariantType(int param, variantlist_t& var);
```

Usage:
```c++
variantlist_t variant = { "OnConsoleMessage", "Hello World!" };
ImVariant::PrintVariant(1, variant); //prints param 1 in variant
```

Result:
```
Prints Hello World!
```

### Label

```c++
ImVariant::Label(const std::string& label_text, int itemid, ImVariant_SizeFlags flag, ImVariant_LabelFlags flag2);
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
