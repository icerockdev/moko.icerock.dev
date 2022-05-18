---
title: MObile KOtlin
---
Mobile Kotlin project aimed at simplifying and accelerating the development of native mobile applications for Android and iOS using Kotlin Multiplatform technology.

## Project template
* [moko-template](https://github.com/icerockdev/moko-template) is mobile multiplatform project template with integrated MOKO libraries and sample of common use cases (input form, items list, item details).

## Gradle plugins
{% for plugin in site.data.plugins %}
* {% include plugin-item data=plugin %}
{% endfor %}

## Libraries
{% for group in site.data.repositories %}
### {{ group.name }}

{% for repository in group.repositories %}
* {% include moko-item data=repository %}
{% endfor %}

{% endfor %}

## Links
- 🇺🇸 [Kotlin Multiplatform — MVVM & Clean Architecture](https://proandroiddev.com/kotlin-multiplatform-mvvm-clean-architecture-f20b99f90b95) (moko-mvvm);
- 🇺🇸 [Kotlin Multiplatform — Firebase + MVVM](https://proandroiddev.com/kotlin-multiplatform-firebase-mvvm-4cdcddd98893) (moko-mvvm);
- 🇷🇺 [Kotlin Multiplatform — библиотека moko](https://tetraquark.ru/archives/511) (moko overview);
- 🇺🇸 [Creating a simple Kotlin Multiplatform project based on moko-template](https://medium.com/icerock/creating-a-simple-kotlin-multiplatform-project-based-on-moko-template-2dd87d020bbd) (moko-template and libs);
- 🇺🇸 [How to implement Swift-friendly API using Kotlin Multiplatform Mobile](https://icerockdev.com/blog/kotlin-multiplatform/2021-08-09-swift-friendly-API/) (moko-kswift);
- 🇺🇸 [KotlinConf 2019 - Kotlin Multiplatform in action](https://www.youtube.com/watch?v=IKYsX6nBcsw) (moko-widgets);
- 🇷🇺 [Kotlin/Everywhere Novosibirsk 2019 - LiveCoding: iOS и Android на Kotlin Multiplatform](https://www.youtube.com/watch?v=r07X_5ICDPk) (moko-widgets);
- 🇷🇺 [Kotlin/Everywhere Minsk 2019 - Опыт работы с Kotlin Multiplatform. Взгляд со стороны iOS-программиста](https://www.youtube.com/watch?v=h9ioWnSlUJc) (moko overview);
- 🇷🇺 [Kotlin/Everywhere Novosibirsk 2019 - Kotlin Multiplatform в production. Реальные примеры, польза и планы на будущее](https://www.youtube.com/watch?v=zzWa_trZvdg) (moko overview);
- 🇷🇺 [Android Broadcast 2021 - MOKO framework for Kotlin Multiplatform Mobile](https://youtu.be/-JjQJG-xkRE) (moko overview);
- 🇷🇺 [Kotlin Multiplatform Mobile. MOKO. MVVM #1](https://www.youtube.com/watch?v=qe8FcIQEmyA) (moko-mvvm);
- 🇷🇺 [Kotlin Multiplatform Mobile. MOKO. units #1](https://www.youtube.com/watch?v=ES6lHIwp5Jw) (moko-units, moko-kswift);
- 🇷🇺 [Kotlin Multiplatform Mobile. MOKO. units #2](https://www.youtube.com/watch?v=aT1i2vN6H6U) (moko-units, moko-utils);
- 🇺🇸 [Sharing Resources on Kotlin Multiplatform with moko-resources](https://www.linkedin.com/pulse/sharing-resources-kotlin-multiplatform-moko-resources-isuru-rajapakse/) (moko-resources);
- 🇺🇸 [How to use Kotlin Multiplatform ViewModel in SwiftUI and Jetpack Compose](https://medium.com/icerock/how-to-use-kotlin-multiplatform-viewmodel-in-swiftui-and-jetpack-compose-8158e98c091d) (moko-mvvm);
- 🇺🇸 [Exposing the separate resources module to iOS target using moko-resources in KMM](https://proandroiddev.com/exposing-the-separate-resources-module-to-ios-target-using-moko-resources-in-kmm-76b9c3d533) (moko-resources);
- 🇺🇸 [Kotlin Multiplatform Mobile: young technology with promising future](https://proandroiddev.com/kotlin-multiplatform-mobile-young-technology-with-promising-future-66b62dd4b723) (moko-resources, moko-mvvm);
- 🇺🇸 [Kotlin Multiplatform Mobile — sharing the UI State management](https://proandroiddev.com/kotlin-multiplatform-mobile-sharing-the-ui-state-management-a67bd9a49882) (moko-mvvm);
- 🇷🇺 [Kotlin Multiplatform Mobile — совместное управление состоянием пользовательского интерфейса](https://habr.com/ru/company/otus/blog/666164/) (moko-mvvm);

## Used in projects (by IceRock)
* ![moko-widgets](https://img.shields.io/badge/-moko--widgets-green) Alliance Trucks - [Play Market](https://play.google.com/store/apps/details?id=com.alliancetrucks.app), [AppStore](https://apps.apple.com/ru/app/alliancetrucks/id1500907708);
* ![moko-widgets](https://img.shields.io/badge/-moko--widgets-green) Virtual Vibe - [Play Market](https://play.google.com/store/apps/details?id=be.virtualvi);
* BMW Motorrad - [Play Market](https://play.google.com/store/apps/details?id=io.smartdriving.bmwmoto), [AppStore](https://apps.apple.com/us/app/id1492857555);
* Delivery Club - Picker App - [Play Market](https://play.google.com/store/apps/details?id=com.deliveryclub.stock);
* НЕВОТОН - [Play Market](https://play.google.com/store/apps/details?id=com.nevoton.app), [AppStore](https://apps.apple.com/ru/app/%D0%BD%D0%B5%D0%B2%D0%BE%D1%82%D0%BE%D0%BD-%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%BA%D0%B0/id1409537985#?platform=iphone);
* Snow4u - [Play Market](https://play.google.com/store/apps/details?id=com.snow4unet.snowtinder), [AppStore](https://apps.apple.com/ru/app/snow4u/id1546814178);
* PRIMETIME - [Play Market](https://play.google.com/store/apps/details?id=ru.primetime), [AppStore](https://apps.apple.com/us/app/primetime-delivery/id1471500882?l=ru&ls=1);
* Apatris Mobile Wallet - [AppStore](https://apps.apple.com/us/app/apatris-mobile-wallet/id1454765749);
* BeGreat - [Play Market](https://play.google.com/store/apps/details?id=ru.begreatapp);
* ENDO Legacy - [Play Market](https://play.google.com/store/apps/details?id=im.endo.legacy), [AppStore](https://apps.apple.com/us/app/endo-legacy/id1435147480);
* VEKA Measurer 2.0 - [Play Market](https://play.google.com/store/apps/details?id=com.veka.windowmeasurer.new), [AppStore](https://apps.apple.com/ru/app/%D0%B7%D0%B0%D0%BC%D0%B5%D1%80%D1%89%D0%B8%D0%BA-%D0%BE%D0%BA%D0%BE%D0%BD-2-0/id1455318730);
* KotlinConf Locator - [Play Market](https://play.google.com/store/apps/details?id=org.jetbrains.kotlin.locator), [AppStore](https://apps.apple.com/us/app/kotlinconf-locator/id1487944666), [GitHub](https://github.com/JetBrains/KotlinFinder);

## Used in projects (not by IceRock)
* PokeRaid - [Play Market](https://play.google.com/store/apps/details?id=me.pokeraid), [AppStore](https://apps.apple.com/us/app/pokeraid-raid-from-home/id1507659524);
* YouCan - [Play Market](https://play.google.com/store/apps/details?id=mksm.youcan), [AppStore](https://apps.apple.com/ru/app/%D0%BC%D0%B5%D0%B4%D0%B8%D1%82%D0%B0%D1%86%D0%B8%D1%8F-%D1%81%D0%BD%D0%B0-youcan/id1499982716);
* BarnTalk - [Play Market](https://play.google.com/store/apps/details?id=com.barntalk), [AppStore](https://apps.apple.com/us/app/barntalk/id1520342639);
* Currency Converter Calculator - [Play Market](https://play.google.com/store/apps/details?id=mustafaozhan.github.com.mycurrencies), [GitHub](https://github.com/CurrencyConverterCalculator/CCC);

## Used in experiments on GitHub
* BluetoothChatMpp - [GitHub](https://github.com/Tetraquark/BluetoothChatMpp);
* WordTeacher - [GitHub](https://github.com/soniccat/WordTeacher);
* LikeAStarMpp - [GitHub](https://github.com/Jaime97/LikeAStarMpp);
* compoza.lite2.moko - [GitHub](https://github.com/Diy2210/compoza.lite2.moko);
* IDScanner - [GitHub](https://github.com/Diy2210/IDScanner);
* Pl_io - [GitHub](https://github.com/alekseevvv/Pl_io);
* VpnApp - [GitHub](https://github.com/Merseyside/VpnApp);
* konet - [GitHub](https://github.com/eduayuso/konet);
* TodoList - [GitHub](https://github.com/TinNova/TodoList);
* open-banking-app - [GitHub](https://github.com/openMF/open-banking-app);
* LiquidMultiplatform - [GitHub](https://github.com/tSquaredd/LiquidMultiplatform);
* dukecon_mobile - [GitHub](https://github.com/dukecon/dukecon_mobile);
* WeatherApp-Multiplatform - [GitHub](https://github.com/RandhirGupta/WeatherApp-Multiplatform);
* EpisodeTracker - [GitHub](https://github.com/y-polek/EpisodeTracker);
* gtcompanion - [GitHub](https://github.com/thumbcat-io/gtcompanion);
* paris-respire-app - [GitHub](https://github.com/alan-camilo/paris-respire-app);
* portfolio_android - [GitHub](https://github.com/MrTheGood/portfolio_android);
* herdr - [GitHub](https://github.com/f8full/herdr);
* android-template - [GitHub](https://github.com/Merseyside/android-template);
* com.rompos.activator.kmm - [GitHub](https://github.com/Diy2210/com.rompos.activator.kmm);
* Lynx - [GitHub](https://github.com/DoubleSymmetry/lynx);
* corona-multiplatform - [GitHub](https://github.com/egeniq/corona-multiplatform);
* com.rompos.deactivator - [GitHub](https://github.com/Diy2210/com.rompos.deactivator);
* CameraSample - [GitHub](https://github.com/Jaime97/CameraSample);
* GithubKmp2 - [GitHub](https://github.com/EmanEraky/GithubKmp2);
* zakupy - [GitHub](https://github.com/YokiToki/zakupy);
* ArcsecondKmp - [GitHub](https://github.com/Tetraquark/ArcsecondKmp).
