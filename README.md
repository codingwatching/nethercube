

## Please note that php7 support is in beta!

# <a name="ENG"></a>English  
# We present you: nthercube-darklava ~ A [PM](https://github.com/PocketMine/PocketMine-MP) fork (PHP7+5) 
ClearSky is an ultra fast Minecraft: Pocket Edition server software with clean code and stable features. It was initially designed for production servers

 - official Test Server : Creative IP: nethercube.ga Port: **19132**
 - 
## [CRITICAL]: Please REMOVE xdebug in production server
 - You can comment out zend_extension=php_xdebug in your php.ini or recompile PHP without xdebug.
 - There is also a switch under debug in pocketmine.yml to force enable xdebug.

## Advanced Features
All features can be configed in pocketmine.yml.<br>
 - About 20 times faster than offical PM repo
 - Universal Client version join (e.g. 0.14.0 and builds for 0.14.0 can join together)(note¹)
 - Unlimited player join (set max-players to -1 in server.properties)(note²)
 - Modified Version color and string freely (set network.protocol,version in pocketmine.yml)
 - You can increase acceptable packetlost and disable anti-cheat when your server in a bad network (network section in pocketmine.yml) 
 - UltraFast Redstone Calculation with almost no bugs
 - Fully working Experience System, include block/player/entity/bottle/furnace hook.
 - Fully working Food & Hunger System, include game-difficulty hook.
 - Fully working Weather System
 - Fully working boats
 - Fast Chunk loading and sending
 - Fast Logger, includes a switch to turn log on/off
 - Almost perfect translations
 - Potions (Working, Creative Only)
 - Enchanting (Command)
 - Variations of Mobs (Rabbits, Villagers etc.)
 - Bug Fixes

Note¹ - Please set 'Outdated Server' message to 'false' in the CustomAlert plugin or any related plugin if you encounter *Outdated server*

Note² - Please set 'Full server' message to 'false' in the CustomAlert plugin or any related plugin if you encounter *Full server*

## For Developers
This is a clean, high quality code base, because we are trying to keep PocketMine's great code quality.
Developing/modifying this project is easy.<br>
We are still rewriting the base to make sure ClearSky has the best developing feel.<br>
ClearSky is not just for a CLEAN feel for users - it's also for developers!<br>
