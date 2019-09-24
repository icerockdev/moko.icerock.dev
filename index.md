---
title: MObile KOtlin
---
Mobile Kotlin project aimed at simplifying and accelerating the development of native mobile applications for Android and iOS using Kotlin Multoplatform technology.

## Project template ![coming soon](assets/img/soon.svg)
moko-template is mobile multiplatform project template with integrated moko libraries and sample of common use cases (input form, items list, item details). 

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
* [moko-media](https://github.com/icerockdev/moko-media) - Media selection & presenting.

### Device ![coming soon](assets/img/soon.svg)
* moko-filesystem - filesystem access;
* moko-geo - geolocation tracking.

### Network
* [moko-network](https://github.com/icerockdev/moko-network) - http network communications based on [ktor-client](https://github.com/ktorio/ktor).

### Network ![coming soon](assets/img/soon.svg)
* moko-socketio - websocket communcations.

### Logic
* [moko-fields](https://github.com/icerockdev/moko-fields) - fields with validations for implementing forms.

### Logic ![coming soon](assets/img/soon.svg)
* moko-paging - lists pagination with coroutines and LiveData integrations.

### UI ![coming soon](assets/img/soon.svg)
* moko-units - composing units into list and show in RecyclerView/UITableView/UICollectionView. Control your lists from common code;
* moko-widgets - declarative UI components;
* moko-stylable - styles system for units and widgets;
* moko-graphics - graphics types like Color and others.

### Integrations ![coming soon](assets/img/soon.svg)
* moko-maps - control content of GoogleMapView from common code;
* moko-firebase - interactions with firebase from common code.

### Utils
* [moko-core](https://github.com/icerockdev/moko-core) - Core classes.

### Utils ![coming soon](assets/img/soon.svg)
* moko-parcelize - @Parcelize support in common code;
* moko-time - time actions and timers.
