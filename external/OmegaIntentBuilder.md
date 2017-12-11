# OmegaIntentBuilder [![](https://jitpack.io/v/Omega-R/OmegaIntentBuilder.svg)](https://jitpack.io/#Omega-R/OmegaIntentBuilder)

An android library that makes it really easy for sharing data between activities. OmegaIntentBuilder provides helper functions for constructing a sharing intent, call intent, email intent.

Example:
```
new OmegaIntentBuilder().call()
                        .phoneNumber("Your phone number")
                        .handler(context)
                        .startActivity();
```

### Including into project

**Step 1.** Add the JitPack repository to your build file
```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

**Step 2.** Add the dependency
```
dependencies {
    compile 'com.github.Omega-R:OmegaIntentBuilder:0.0.1'
}
```
