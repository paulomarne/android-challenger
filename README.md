<h1 align="center">Aplicativo Marvel Challenger</h1>


<p align="center">  
Herois da Marvel é baseado em uma arquitetura moderna usando a plataforma android e como padrão de desenvolvimento MVVM.<br>
</p>
</br>

## Tech stack & Open-source libraries
- Minimum SDK level 21
- [Kotlin](https://kotlinlang.org/) based + [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) for asynchronous.
- JetPack
  - Lifecycle - dispose of observing data when lifecycle state changes.
  - ViewModel - UI related data holder, lifecycle aware.å
  - Room Persistence - construct a database using the abstract layer.
- Architecture
  - MVVM Architecture (View - DataBinding - ViewModel - Model)
  - Repository pattern
  - [Koin](https://github.com/InsertKoinIO/koin) - dependency injection.
- [Retrofit2 & Gson](https://github.com/square/retrofit) - construct the REST APIs.
- [OkHttp3](https://github.com/square/okhttp) - implementing interceptor, logging and mocking web server.
- [Sandwich](https://github.com/skydoves/Sandwich) - construct lightweight http API response and handling error responses.
- [Glide](https://github.com/bumptech/glide) - loading images.
- [TransformationLayout](https://github.com/skydoves/transformationlayout) - implementing transformation motion animations.
- [WhatIf](https://github.com/skydoves/whatif) - checking nullable object and empty collections more fluently.
- [AndroidVeil](https://github.com/skydoves/androidveil) - easy way to implement veil skeletons and shimmering effect.
- [DiscreteScrollView](https://github.com/yarolegovich/DiscreteScrollView) - implementing a scrollable list of items.
- [Timber](https://github.com/JakeWharton/timber) - logging.
- [Material-Components](https://github.com/material-components/material-components-android) - Material design components like ripple animation, cardView.

## Unit Testing Frameworks
Unit Tests verify the interactions of viewmodels between repositories and dao & REST api requests.
- [Robolectric](https://github.com/robolectric/robolectric) - Robolectric is the industry-standard unit testing framework for Android.
- [Mockito-Kotlin](https://github.com/nhaarman/mockito-kotlin) - a small library that provides helper functions to work with Mockito in Kotlin.

## Architecture
MarvelHeroes is based on MVVM architecture and a repository pattern.
