# TNT Crossbow (Fabric, Minecraft 1.21.11)

No new items. The vanilla crossbow can now be loaded with TNT (from your inventory or offhand).
Fire it and lit TNT flies out with a 4 second fuse. Multishot spreads it: Multishot V = 11 TNT per shot,
1 durability each.

Tune it in TntShooter.java: FUSE_TICKS and SPEED_MULTIPLIER.

Build: run `gradle wrapper` once (or copy gradlew and gradle/ from the Fabric example mod), then `./gradlew build`.
Jar is in build/libs/. Check the versions in gradle.properties against https://fabricmc.net/develop.
