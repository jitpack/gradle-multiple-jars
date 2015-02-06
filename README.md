# gradle-multiple-jars

Example Gradle project producing two jars from single source directory:
 - *API* from src/api
 - *Impl* from src/impl

Both jars are installed to local maven reactor with:

    gradle install
    
    
To install them use the following syntax:

```gradle 
 compile 'com.github.jitpack:gradle-multiple-jars.api:1.0'
 compile 'com.github.jitpack:gradle-multiple-jars.impl:1.0'
```
