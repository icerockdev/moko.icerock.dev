---
title: MObile KOtlin
---
Mobile Kotlin project aimed at simplifying and accelerating the development of native mobile applications for Android and iOS using Kotlin Multoplatform technology.

## Project template
[COMING SOON] moko-template is mobile multiplatform project template with integrated moko libraries and sample of common use cases (input form, items list, item details).

## Gradle plugins
* [mobile-multiplatform](https://github.com/icerockdev/mobile-multiplatform-gradle-plugin) - Gradle plugin for simplify Kotlin Multiplatform mobile configurations;
* [mobile-multiplatform-resources](https://github.com/icerockdev/moko-resources) - generate resources for android and iOS from common resources - strings, plurals;
* [mobile-multiplatform-network-generator](https://github.com/icerockdev/moko-network) - generate ktor-client network api and entities (with kotlinx.serialization) from OpenAPI (Swagger) specification.

## Libraries
### Architecture
* [moko-mvvm](https://github.com/icerockdev/moko-mvvm) - Model-View-ViewModel architecture components;
* [moko-permissions](https://github.com/icerockdev/moko-permissions) - Runtime permissions controls.

### Device
* [moko-resources](https://github.com/icerockdev/moko-resources) - Resources access;
* [moko-media](https://github.com/icerockdev/moko-media) - Media selection & presenting;
* [COMING SOON] moko-filesystem - filesystem access;
* [COMING SOON] moko-geo - geolocation tracking.

### Network
* [moko-network](https://github.com/icerockdev/moko-network) - http network communications based on [ktor-client](https://github.com/ktorio/ktor);
* [COMING SOON] moko-socketio - websocket communcations.

### Logic
* [moko-fields](https://github.com/icerockdev/moko-fields) - fields with validations for implementing forms;
* [COMING SOON] moko-paging - lists pagination with coroutines and LiveData integrations.

### UI
* [COMING SOON] moko-units - composing units into list and show in RecyclerView/UITableView/UICollectionView. Control your lists from common code;
* [COMING SOON] moko-widgets - declarative UI components;
* [COMING SOON] moko-stylable - styles system for units and widgets;
* [COMING SOON] moko-graphics - graphics types like Color and others.

### Integrations
* [COMING SOON] moko-maps - control content of GoogleMapView from common code;
* [COMING SOON] moko-firebase - interactions with firebase from common code.

### Utils
* [moko-core](https://github.com/icerockdev/moko-core) - Core classes;
* [COMING SOON] moko-parcelize - @Parcelize support in common code;
* [COMING SOON] moko-time - time actions and timers.
