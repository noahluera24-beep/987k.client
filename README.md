[README.txt](https://github.com/user-attachments/files/34409132/README.txt)
987k Client - setup
1) Get a Gradle wrapper: download the official Fabric template from https://fabricmc.net/develop/template (MC 1.21.11),
   then copy the files from this folder over it (build.gradle, gradle.properties, settings.gradle, src/).
   (Or just run "gradle wrapper" if you have Gradle installed.)
2) Open in IntelliJ IDEA (JDK 21), let Gradle import.
3) Test: run the "Minecraft Client" run config (or ./gradlew runClient).
4) Join/create a world, press RIGHT SHIFT.
5) Build jar: ./gradlew build  -> build/libs/k987-client-1.0.0.jar (needs Fabric API in your mods folder).
