---
title: MObile KOtlin
---
Mobile Kotlin project aimed at simplifying and accelerating the development of native mobile applications for Android and iOS using Kotlin Multiplatform technology.

## Project template
[moko-template](https://github.com/icerockdev/moko-template) is mobile multiplatform project template with integrated moko libraries and sample of common use cases (input form, items list, item details). 

## Gradle plugins
* [mobile-multiplatform](https://github.com/icerockdev/mobile-multiplatform-gradle-plugin) - Gradle plugin for simplify Kotlin Multiplatform mobile configurations;
* [mobile-multiplatform-resources](https://github.com/icerockdev/moko-resources) - generation resources for android and iOS from common resources - strings, plurals;
* [mobile-multiplatform-network-generator](https://github.com/icerockdev/moko-network) - generation ktor-client network api and entities (with kotlinx.serialization) from OpenAPI (Swagger) specification.

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
* moko-socketio - websocket communications.

### Logic
* [moko-fields](https://github.com/icerockdev/moko-fields) - fields with validations for implementing forms.

### Logic ![coming soon](assets/img/soon.svg)
* moko-paging - lists pagination with coroutines and LiveData integrations.

### UI
* [moko-units](https://github.com/icerockdev/moko-units) - composing units into list and show in RecyclerView/UITableView/UICollectionView. Control your lists from common code;
* [moko-graphics](https://github.com/icerockdev/moko-graphics) - graphics types like Color and others.

### UI ![coming soon](assets/img/soon.svg)
* moko-widgets - declarative UI components;
* moko-stylable - styles system for units and widgets.

### Integrations ![coming soon](assets/img/soon.svg)
* moko-maps - control content of GoogleMapView from common code;
* moko-firebase - interactions with firebase from common code.

### Utils
* [moko-parcelize](https://github.com/icerockdev/moko-parcelize) - @Parcelize support in common code;
* [moko-time](https://github.com/icerockdev/moko-time) - time actions and timers.

## Used in projects
* Apatris Mobile Wallet - [AppStore](https://apps.apple.com/us/app/apatris-mobile-wallet/id1454765749);
* BeGreat - [Play Market](https://play.google.com/store/apps/details?id=ru.begreatapp);
* ENDO Legacy - [Play Market](https://play.google.com/store/apps/details?id=im.endo.legacy) & [AppStore](https://apps.apple.com/us/app/endo-legacy/id1435147480);
* VEKA Measurer 2.0 - [Play Market](https://play.google.com/store/apps/details?id=com.veka.windowmeasurer.new) & [AppStore](https://apps.apple.com/ru/app/%D0%B7%D0%B0%D0%BC%D0%B5%D1%80%D1%89%D0%B8%D0%BA-%D0%BE%D0%BA%D0%BE%D0%BD-2-0/id1455318730);
* BluetoothChatMpp - [GitHub](https://github.com/Tetraquark/BluetoothChatMpp).
