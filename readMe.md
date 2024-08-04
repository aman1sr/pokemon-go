# NewsApp-MVVM-Architecture
This is a Pokemon application with MVVM Architecture and Jetpack Compose UI

### Feature Implemented
- MVVM Architecture
- Retrofit Network Calling
- Portrait and Landscape feature
- Hilt DI


## Dependency Used:
- Recycler View for listing
```
implementation "androidx.recyclerview:recyclerview:1.2.1"
implementation 'androidx.recyclerview:recyclerview-selection:1.1.0' //multi item selection
```
- Glide for image loading
```
implementation 'com.github.bumptech.glide:glide:4.11.0'
```
- Retrofit for networking
```
implementation 'com.squareup.retrofit2:retrofit:2.9.0'
implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
implementation 'com.squareup.okhttp3:logging-interceptor:4.8.0'
```
- Android Lifecycle aware component
```
implementation 'android.arch.lifecycle:extensions:1.1.1'
implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.5.1'
implementation 'androidx.lifecycle:lifecycle-runtime-ktx:2.5.1'
```
- Dagger for dependency Injection
```
implementation "com.google.dagger:dagger:2.42"
kapt "com.google.dagger:dagger-compiler:2.42"
```

## The Complete Project Folder Structure
```
├── NewsApplication.kt
├── data
│   ├── api
│   ├── local
│   ├── model
│   └── repository
├── di
│   ├── component
│   ├── module
│   ├── qualifiers.kt
│   └── scopes.kt
├── ui
│   ├── MainActivity.kt
│   ├── base
│   ├── country
│   ├── language
│   ├── newsListScreen
│   ├── pagination
│   ├── search
│   ├── sources
│   └── topheadline
└── utils
    ├── AppConstant.kt
    ├── DispatcherProvider.kt
    ├── Extentions.kt
    ├── NetworkHelper.kt
    ├── Resource.kt
    ├── Status.kt
    ├── TypeAliases.kt
    └── network

```

<p align="center">
<img alt="main_screen" src="https://user-images.githubusercontent.com/15169743/221393544-6343e574-c0de-4bab-b421-2ab97202fdba.png" width="360"  height="640"> &nbsp;&nbsp;&nbsp;&nbsp;
<img alt="search_screen" src="https://user-images.githubusercontent.com/15169743/219934168-3a3c7f6e-bd3f-429f-acd3-e6f946454f01.png" width="360"  height="640" marginLeft="20">
</p>

