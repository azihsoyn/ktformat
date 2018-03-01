# ktformat
kotlin named string format

# Installation
## Gradle

```
repositories {
    jcenter()
}

dependencies {
    compile 'com.github.azihsoyn.ktformat:ktformat:<latest-version>'
}
```

# TL;DR

```kotlin
"Hello, {firstname} {lastname}".format(mapOf("firstname" to "named format", "lastname" to "in kotlin"))
// Hello, named format in kotlin
```

# LICENSE
MIT
