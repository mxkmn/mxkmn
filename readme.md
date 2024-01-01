<h1 align="center">

hi, it's mxkmn <img src="photos/mxkmn_logo_morse.svg" alt="logo" width="24px" border-radius="4px"/>

<small><small><small>/* pronounced [mʌksikɔma:n] */</small></small></small>

![Someday in 2020](photos/header.jpg)

</h1>

Nowadays and next years I'm an Android developer, also like to play with microcontrollers and bring their benefits to business. Writes lots of useful Android stuff on [StackOverflow](https://stackoverflow.com/users/12544067/mxkmn?tab=answers).

I've worked as an individual and as a team developer in a small outsourcing studios. Currently also working on a personal project for thousands of students.

As a student participated in 9 hackathons, taking 2nd place twice and 3rd place four times. One day I'll get the first, hopefully.

<details><summary><b>My latest&greatest projects</b></summary>

### chronus

![Screenshots](photos/projects/chronus.jpg)

My personal project to automatically add university timetable to the preinstalled system calendar. Under development, not released...

Stack:

* UI: Compose; Material3; Splashscreen API; [Self-written compose permissions handling](https://stackoverflow.com/questions/60608101/how-request-permissions-with-jetpack-compose/77027650#77027650); Notifications.
* Architecture: Multimodule; Single Activity; MVI/UDF/Clean Architecture with Jetpack ViewModel and Kotlin Flows; Coroutines; Dagger Hilt.
* Network and connections: WorkManager; System calendar via ContentResolver/CalendarContract; Ktor Client; Kotlin Serialization; JSoup.
* Local memory: Room; DataStore.
* Tools and testing: Detekt; KtLint; Gradle convention plugins.

Additional info: I struggled for three weeks looking for a solution to the problem of WorkManager not working periodically on Android 10+ (everything is fine on 5.1 and 7.1), hated it and almost migrated to AlarmManager. I had a long laugh when the sync worked 2 weeks after installing the app, even though it should have worked hours later. Tl;dr: NEVER specify flexInterval. It will eat you up.

### Laundry accounting

![Screenshots](photos/projects/laundry.jpg)

An application for linen accounting in laundries. Receives employee data from an RFID scanner via BLE, which was developed in team with me. Offline-first approach. Developed completely by me by order of Irkutsk Oil Company.

Stack:

* UI: Compose; Compose Destinations; Material3; Splashscreen API; [Self-written compose permissions handling](https://stackoverflow.com/questions/60608101/how-request-permissions-with-jetpack-compose/77027650#77027650). 
* Architecture: Multimodule approach in monorepository for all Irkutsk Oil projects; Single Activity; MVI/UDF/Clean Architecture with Jetpack ViewModel and Kotlin Flows; Coroutines; Dagger Hilt.
* Network and connections: Ktor Client; Kotlin Serialization; Bluetooth LE with Kable library.
* Local memory: Room; DataStore; [Storage Access Framework](https://stackoverflow.com/questions/64720379/writing-many-files-on-android-11/77087157#77087157); [.xlsx creation](https://stackoverflow.com/questions/50738119/how-to-create-and-write-to-excel-file-xlsx/77171826#77171826).
* Tools and testing: Detekt; KtLint; Gradle convention plugins.

Additional info: As this was the second project for Irkutsk Oil Company, a monorepository was established for all current and future projects, which increased development speed by times and greatly improved code quality and component reusability.

### Offline tracker

![Screenshots](photos/projects/tracker.jpg)

An application for tracking people in an area without internet coverage. Receives data from trackers via BLE (they get location with GPS and communicates via LoRa), which were developed in team with me. Offline-first approach. Developed completely by me by order of Irkutsk Oil Company.

Stack:

* UI: Compose; Material3; Splashscreen API; [Self-written compose permissions handling](https://stackoverflow.com/questions/60608101/how-request-permissions-with-jetpack-compose/77027650#77027650); OpenStreetMap with Osmdroid library.
* Architecture: Multimodule approach in monorepository for all Irkutsk Oil projects; Single Activity; MVI/UDF/Clean Architecture with Jetpack ViewModel and Kotlin Flows; Coroutines; Dagger Hilt.
* Network and connections: Ktor Client; Kotlin Serialization; Bluetooth LE with Kable library.
* Local memory: Room.
* Tools and testing: Firebase Crashlytics/Analytics; MockK; Compose Tests; Detekt; KtLint; Gradle convention plugins.

Migrations since project start:

* Singlemodule -> Multimodule;
* Default repository -> Monorepo for Irkutsk Oil;
* Google Maps (Maps Compose library) -> Google Maps (Views) -> OpenStreetMap via Osmdroid library (Views);
* BLE via pure Android SDK -> Kable lib;
* Network connections via pure OkHttp -> Ktor Client;
* Accompanist permissions handling -> Self-written permissions handling for Compose;
* Gradle with Groovy -> Gradle with Kotlin and Gradle convention plugins.

Additional info: Thanks to experience, I now know that GMaps for Compose is very unstable and it makes sense to use an implementation of all actions via View and an additional class to abstract the map capabilities. Migrated to OSM at the request of the customer.

### Other stack from older projects

Also worked with:

* UI: XML with Fragments; Navigation Component; Material2; View Binding;
* Architecture: MVVM; LiveData; Dagger 2;
* Network and connections: Retrofit; GSON serialization; WorkManager;
* Tools, testing and other: Mockito; Espresso; iBeacon.

</details>

<details><summary><b>Some fun stuff</b></summary>

### At Summer Schools 2022 by Yandex Academy

![My Yandex team](photos/fun_stuff/yandex_team.jpg)
![Yandex certificate](photos/fun_stuff/yandex_certificate.jpg)

### At MDev Hackathon 2023 by Samsung IT Academy

![My MDev team](photos/fun_stuff/mdev_team.jpg)
![MDev certificate](photos/fun_stuff/mdev_certificate.jpg)
We've got [max rating](https://github.com/mxkmn/HackathonAndroidBlindy?tab=readme-ov-file#result), but 2nd place :/

### My [weather station](https://github.com/mxkmn/Esp8266WeatherStation/blob/main/README_ru.md)

Built almost from scratch in 2021. It's cool, but I want to rebuild it again (to use new MCU and support RTOS features, make it smaller and also rewrite some crappy code).

![Photo](photos/fun_stuff/weatherstation.jpg)

### With [Vlad Savin](https://t.me/VladSavin) at the punk garage "Glotka" (2023)

![Photo](photos/fun_stuff/bestie.jpg)

</details>

## Some interests beyond development

<details><summary><b>Photographing</b></summary>

Check out some pics of nature and travelling on [Instagram](https://instagram.com/mxkmn.inc).

</details>

<details><summary><b>Summer cycling activities</b></summary>

![Photo 1](photos/bicycle/ph1.jpg)

![Photo 2](photos/bicycle/ph2.jpg)

![Statistics in 2023](photos/bicycle/stats_2023.png)

</details>

<details><summary><b>Bottles collection</b></summary>

![Photo](photos/bottles.jpg)

Perhaps I should have shown them from a more attractive angle :/

</details>

<details><summary><b>Music&sound</b></summary>

Because everyone likes it and writes about on personal pages 🥱.

So, if you want to know about my taste in melodic screamo kircore rap: [Deezer profile](http://deezer.com/en/profile/4884764102). Or click on your ultra-random button: [a](https://www.youtube.com/watch?v=bIgBj-G1Vj0) [b](https://www.youtube.com/watch?v=PE3UMiIUaXY) [c](https://www.youtube.com/watch?v=6Gha9xrM10w) [d](https://www.youtube.com/watch?v=JiQHclg_648) [e](https://www.youtube.com/watch?v=wobbf3lb2nk) [f](photos/my_foot.jpg) [g](https://www.youtube.com/watch?v=iVvXB-Vwnco) [h](https://www.youtube.com/watch?v=xuhZtyAwBdE) [i](https://www.youtube.com/watch?v=8dnJpuWuGn8) [j](https://www.youtube.com/watch?v=Yt0kHiRsnHA) [k](https://www.youtube.com/watch?v=t_gRKiXg3Ao) [l](https://www.youtube.com/watch?v=jDcB8FxLFkc) [m](https://www.youtube.com/watch?v=GnvWQVidGS0) [n](https://www.youtube.com/watch?v=d9yJ2WNL-z0) [o](https://www.youtube.com/watch?v=JWVUq-dViWM) [p](https://www.youtube.com/watch?v=lf0d7Dcfcew) [q](https://www.youtube.com/watch?v=0TSuZfQ3ZfI) [r](https://www.youtube.com/watch?v=v9bzFBCMWSw) [s](https://www.youtube.com/watch?v=v2wCvNgvYE0) [t](https://www.youtube.com/watch?v=x7BObbvFPtI) [u](https://www.youtube.com/watch?v=YnGRrWNOZ4E) [v](https://www.youtube.com/watch?v=kqPZltX1dHk) [w](https://www.youtube.com/watch?v=L5dIOnTuRWY) [x](https://www.youtube.com/watch?v=yh3Cy4NuuF8) [y](https://www.youtube.com/watch?v=3UkaCLm__NA) [z](https://www.youtube.com/watch?v=_csj6mA7pOA)

It also requires quality audio equipment, figuring it out was fun and it led to a [set of posts with my conclusions](https://4pda.to/forum/index.php?showtopic=975324) (RU). Comparison of 25+ pairs of TWS included. Right now, my choice is the magnificent Noble FoKus Pro.

</details>

---

Maybe more? Just check [my Telegram blog](https://t.me/c2eef5d9f8a508cbde003c06305b170b) (RU).

## Some nerds statistic

![Profile views](https://komarev.com/ghpvc/?username=mxkmn)

Last days from [my Code::Stats](https://codestats.net/users/mxkmn):

![History graph](https://codestats-readme.wegfan.cn/history-graph/mxkmn?bg_color=111&text_color=aaa&grid_color=333&language_colors=["3e4053","cc4b48","518fbd","ba7a2b","60bd68","f17cb0","b2912f","c71585","b276b2"])

Loving coding since 2015, professionally since 2021.
