# AndroidRepo

Declare next in gradle's repository settings
```kotlin
        maven {
            url = uri("https://raw.githubusercontent.com/difftim/AndroidRepo/main/")
        }
```

and then add implementation, for example:

```kotlin
    api("org.difft.android.libraries:rust-encryption-sdk:0.1.0")
```
