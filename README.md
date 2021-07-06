# Detectar-Sistema-Operativo-en-Swift


```swift
#if os(iOS)
return Color(.systemBackground)
#elseif os(tvOS)
return Color(.darkGray)
#elseif os(macOS)
return Color(.windowBackgroundColor)
#endif
```
