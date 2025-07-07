---
title: MObile KOtlin
---
Mobile Kotlin project aimed at simplifying and accelerating the development of native mobile applications for Android and iOS using Kotlin Multiplatform technology.

## Compose Multiplatform

MOKO libraries supports [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) UI framework. Check badge ![Compose Multiplatform](http://img.shields.io/badge/compose-multiplatform-6EDB8D.svg?style=flat).

Libraries that not have badge also can be used in projects, that use Compose Multiplatform, but just have direct interop with Compose (because it's not UI libraries).

![moko-repo-header](https://user-images.githubusercontent.com/5010169/231642086-8f243134-2c72-4edc-95bb-12979f512c14.png)

## Project template
* [moko-compose-multiplatform-ios-android-template](https://github.com/icerockdev/moko-compose-multiplatform-ios-android-template) is Compose Multiplatform template for Android & iOS with integrated MOKO libraries and sample of common use cases.
* [moko-compose-multiplatform-template](https://github.com/icerockdev/moko-compose-multiplatform-template) is Compose Multiplatform template for Android, Desktop & iOS with integrated MOKO libraries and sample of common use cases.
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
- 🇺🇸 [Sharing Resources on Kotlin Multiplatform with moko-resources](https://www.linkedin.com/pulse/sharing-resources-kotlin-multiplatform-moko-resources-isuru-rajapakse/) (moko-resources);
- 🇺🇸 [How to use Kotlin Multiplatform ViewModel in SwiftUI and Jetpack Compose](https://medium.com/icerock/how-to-use-kotlin-multiplatform-viewmodel-in-swiftui-and-jetpack-compose-8158e98c091d) (moko-mvvm);
- 🇺🇸 [Exposing the separate resources module to iOS target using moko-resources in KMM](https://proandroiddev.com/exposing-the-separate-resources-module-to-ios-target-using-moko-resources-in-kmm-76b9c3d533) (moko-resources);
- 🇺🇸 [Kotlin Multiplatform Mobile: young technology with promising future](https://proandroiddev.com/kotlin-multiplatform-mobile-young-technology-with-promising-future-66b62dd4b723) (moko-resources, moko-mvvm);
- 🇺🇸 [Kotlin Multiplatform Mobile — sharing the UI State management](https://proandroiddev.com/kotlin-multiplatform-mobile-sharing-the-ui-state-management-a67bd9a49882) (moko-mvvm);
- 🇷🇺 [Kotlin Multiplatform Mobile — совместное управление состоянием пользовательского интерфейса](https://habr.com/ru/company/otus/blog/666164/) (moko-mvvm);
- 🇺🇸 [My Kotlin Multiplatform Mobile learning curve](https://proandroiddev.com/my-kotlin-multiplatform-mobile-learning-curve-c024c9fcfe2) (moko-mvvm);
- 🇺🇸 [Kotlin Multiplatform Mobile I18n for Android and iOS Apps](https://phrase.com/blog/posts/kotlin-multiplatform-mobile-i18n-android-ios/) (moko-resources);
- 🇷🇺 [Как сделать удобное взаимодействие с Kotlin из Swift: решение с помощью плагина MOKO KSwift](https://habr.com/ru/post/700030/) (moko-kswift);
- 🇺🇸 [How To Build A Cross Platform Mobile App With Kotlin Multiplatform 1/2 — Shared Code](https://medium.com/tech-takeaways/how-to-build-a-cross-platform-mobile-app-with-kotlin-multiplatform-1-2-shared-code-9dbc6ff681ff) (moko-mvvm);
- 🇺🇸 [We Fast-Tracked Our App Development With Kotlin Multiplatform Mobile](https://medium.com/motive-eng/we-fast-tracked-our-app-development-with-kotlin-multiplatform-mobile-952f2f4afd1) (moko-resources);
- 🇺🇸 [MOKO resources 0.21 with Compose Multiplatform support](https://medium.com/p/462d8b11116b?source=moko-landing) (moko-resources);
- 🇺🇸 [Digging into KMM](https://medium.com/pink-room-club/digging-into-kmm-11be99607cdd) (moko-mvvm);
- 🇺🇸 [Maximizing Mobile Code Reuse with Compose Multiplatform and MOKO Libraries](https://medium.com/icerock/maximizing-mobile-code-reuse-with-compose-multiplatform-and-moko-libraries-140a408b452a);
- 🇺🇸 [From Android to Multiplatform: Real 100% Jetpack Compose App. Part 1 — Resources](https://markonovakovic.medium.com/from-android-to-multiplatform-real-100-jetpack-compose-app-part-1-resources-a5db60f1ed73) (moko-resources);
- 🇺🇸 [Getting Started with Kotlin Multiplatform 2/n: Moko Shared View Model & Koin DI](https://proandroiddev.com/getting-started-with-kotlin-multiplatform-moko-shared-view-model-koin-di-37caf9d67deb) (moko-mvvm);
- 🇺🇸 [Migrating an Android app to iOS with KMP — Part III: UI and Compose Multiplatform](https://proandroiddev.com/migrating-an-android-app-to-ios-with-kmp-part-iii-ui-and-compose-multiplatform-b5e01cc0769a) (moko-resources, moko-mvvm);
- 🇺🇸 [Internationalization (I18n) in Kotlin Multiplatform: Part 1](https://thomaskioko.me/posts/localization/) (moko-resources);
- 🇺🇸 [Alarmee: Schedule Local and Push Notifications in KMP](https://vivienmahe.medium.com/alarmee-schedule-local-and-push-notifications-in-kmp-44ea47972ae7) (moko-permissions);

## Videos
- 🇺🇸 [Kotlin by JetBrains - Build an iOS & Android app in 100% Kotlin with Compose Multiplatform](https://www.youtube.com/watch?v=5_W5YKPShZ4) (moko-mvvm);
- 🇺🇸 [Philipp Lackner - How to Share Resources in KMM (Strings, Images, etc.)](https://youtu.be/xtWzpLtCuY0) (moko-resources);
- 🇺🇸 [Philipp Lackner - Permission Handling in Compose Multiplatform - KMP for Beginners](https://youtu.be/euDQ4zdAfnk) (moko-permissions);
- 🇺🇸 [Oday - Compose Multiplatform iOS @android Android - Fetch Image Results with ViewModel](https://www.youtube.com/watch?v=HoUvMPtUiO8) (moko-mvvm);
- 🇺🇸 [KotlinConf 2019 - Kotlin Multiplatform in action](https://www.youtube.com/watch?v=IKYsX6nBcsw) (moko-widgets);
- 🇷🇺 [Android Broadcast 2021 - MOKO framework for Kotlin Multiplatform Mobile](https://youtu.be/-JjQJG-xkRE) (moko overview);
- 🇷🇺 [IceRock - Kotlin Multiplatform Mobile. MOKO. MVVM #1](https://www.youtube.com/watch?v=qe8FcIQEmyA) (moko-mvvm);
- 🇷🇺 [IceRock - Kotlin Multiplatform Mobile. MOKO. units #1](https://www.youtube.com/watch?v=ES6lHIwp5Jw) (moko-units, moko-kswift);
- 🇷🇺 [IceRock - Kotlin Multiplatform Mobile. MOKO. units #2](https://www.youtube.com/watch?v=aT1i2vN6H6U) (moko-units, moko-utils);
- 🇷🇺 [Kotlin/Everywhere Novosibirsk 2019 - LiveCoding: iOS и Android на Kotlin Multiplatform](https://www.youtube.com/watch?v=r07X_5ICDPk) (moko-widgets);
- 🇷🇺 [Kotlin/Everywhere Minsk 2019 - Опыт работы с Kotlin Multiplatform. Взгляд со стороны iOS-программиста](https://www.youtube.com/watch?v=h9ioWnSlUJc) (moko overview);
- 🇷🇺 [Kotlin/Everywhere Novosibirsk 2019 - Kotlin Multiplatform в production. Реальные примеры, польза и планы на будущее](https://www.youtube.com/watch?v=zzWa_trZvdg) (moko overview);

## Used in projects (by IceRock)
* Campus - [Play Market](https://play.google.com/store/apps/details?id=ru.dewish.campus), [AppStore](https://apps.apple.com/ru/app/кампус-расписание-занятий/id1534975833);
* ClockedIn - [Play Market](https://play.google.com/store/apps/details?id=com.clockedin), [AppStore](https://apps.apple.com/us/app/clocked-in/id1248437112);
* Flipping Book - [Play Market](https://play.google.com/store/apps/details?id=com.flippingbook.online), [AppStore](https://apps.apple.com/ru/app/flippingbook/id1608881415);
* Naked Science - [Play Market](https://play.google.com/store/apps/details?id=ru.ns.nakedscience.magazine), [AppStore](https://apps.apple.com/ru/app/naked-science/id604780121);
* Мойка-Мойка - [Play Market](https://play.google.com/store/apps/details?id=pro.ucar.carwash);
* Recipes - [Play Market](https://play.google.com/store/apps/details?id=ru.nikolife.app), [AppStore](https://apps.apple.com/us/app/nikolife-правильные-рецепты/id1605763336);
* My Fridge - [Play Market](https://play.google.com/store/apps/details?id=com.whitesphere.app);
* Krohne - [Play Market](https://play.google.com/store/apps/details?id=com.krohne.app), [AppStore](https://apps.apple.com/us/app/krohne/id1563728941);
* QR Express - [Play Market](https://play.google.com/store/apps/details?id=com.icerockdev.cft.cashier), [AppStore](https://apps.apple.com/ru/app/уралсиб-qr-для-бизнеса/id1638286686);
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
* AliRadar - [4PDA](https://4pda.to/forum/index.php?showtopic=1011971&st=20), [AppStore](https://apps.apple.com/ru/app/aliradar-для-aliexpress/id1188220508);

## Used in open source apps on GitHub
* tivi - [GitHub](https://github.com/chrisbanes/tivi);
* ToDometerKotlinMultiplatform - [GitHub](https://github.com/serbelga/ToDometerKotlinMultiplatform);
* WeatherApp-Multiplatform - [GitHub](https://github.com/RandhirGupta/WeatherApp-Multiplatform);
* EpisodeTracker - [GitHub](https://github.com/y-polek/EpisodeTracker);
* Reader - [GitHub](https://github.com/msasikanth/reader);
* QuotesApp - [GitHub](https://github.com/mirzemehdi/quotesapp);
* Compose Multiplatform Weatcher App - [GitHub](https://github.com/guerrerorodrigo/compose-multiplatform-weather-app);
* Rhasspy Mobile - [GitHub](https://github.com/Nailik/rhasspy_mobile);
* open-otp - [GitHub](https://github.com/avan1235/open-otp);
* recipies - [GitHub](https://github.com/JunydDEV/kmp-recipes-mobile-app);
* DroidKaigi conference app - [GitHub](https://github.com/DroidKaigi/conference-app-2022);
* Hyperskill mobile app - [GitHub](https://github.com/hyperskill/mobile-app)

## Used in experiments on GitHub
* MyBirdApp - [GitHub](https://github.com/SebastianAigner/my-bird-app);
* SpaceXRockets - [GitHub](https://github.com/AJIEKCX/SpaceXRockets);
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
* ArcsecondKmp - [GitHub](https://github.com/Tetraquark/ArcsecondKmp);
* GitHubUserFinderKMM - [GitHub](https://github.com/apter-tech/GitHubUserFinderKMM).
