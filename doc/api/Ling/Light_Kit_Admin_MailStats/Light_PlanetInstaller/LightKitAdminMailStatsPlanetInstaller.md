[Back to the Ling/Light_Kit_Admin_MailStats api](https://github.com/lingtalfi/Light_Kit_Admin_MailStats/blob/master/doc/api/Ling/Light_Kit_Admin_MailStats.md)



The LightKitAdminMailStatsPlanetInstaller class
================
2021-06-18 --> 2021-06-18






Introduction
============

The LightKitAdminMailStatsPlanetInstaller class.



Class synopsis
==============


class <span class="pl-k">LightKitAdminMailStatsPlanetInstaller</span> extends [LightKitAdminBasePlanetInstaller](https://github.com/lingtalfi/Light_Kit_Admin/blob/master/doc/api/Ling/Light_Kit_Admin/Light_PlanetInstaller/LightKitAdminBasePlanetInstaller.md) implements [LightPlanetInstallerInit3HookInterface](https://github.com/lingtalfi/Light_PlanetInstaller/blob/master/doc/api/Ling/Light_PlanetInstaller/PlanetInstaller/LightPlanetInstallerInit3HookInterface.md), [LightPlanetInstallerInit2HookInterface](https://github.com/lingtalfi/Light_PlanetInstaller/blob/master/doc/api/Ling/Light_PlanetInstaller/PlanetInstaller/LightPlanetInstallerInit2HookInterface.md), [LightServiceContainerAwareInterface](https://github.com/lingtalfi/Light/blob/master/doc/api/Ling/Light/ServiceContainer/LightServiceContainerAwareInterface.md) {

- Inherited properties
    - protected [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) [LightKitAdminBasePlanetInstaller::$_output](#property-_output) ;
    - protected string [LightKitAdminBasePlanetInstaller::$_planetDotName](#property-_planetDotName) ;
    - protected string [LightKitAdminBasePlanetInstaller::$microPermissionProfile](#property-microPermissionProfile) ;
    - protected [Ling\Light\ServiceContainer\LightServiceContainerInterface](https://github.com/lingtalfi/Light/blob/master/doc/api/Ling/Light/ServiceContainer/LightServiceContainerInterface.md) [LightBasePlanetInstaller::$container](#property-container) ;

- Methods
    - public [__construct](https://github.com/lingtalfi/Light_Kit_Admin_MailStats/blob/master/doc/api/Ling/Light_Kit_Admin_MailStats/Light_PlanetInstaller/LightKitAdminMailStatsPlanetInstaller/__construct.md)() : void

- Inherited methods
    - public LightKitAdminBasePlanetInstaller::init2(string $appDir, [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output, ?array $options = []) : void
    - public LightKitAdminBasePlanetInstaller::undoInit2(string $appDir, [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output, ?array $options = []) : void
    - public LightKitAdminBasePlanetInstaller::init3(string $appDir, [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output, ?array $options = []) : void
    - public LightKitAdminBasePlanetInstaller::undoInit3(string $appDir, [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output, ?array $options = []) : void
    - protected LightKitAdminBasePlanetInstaller::message(string $message) : void
    - protected LightKitAdminBasePlanetInstaller::prepareMessage([Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output) : void
    - protected LightKitAdminBasePlanetInstaller::registerOpenMicroPermissionsByProfile(string $appDir, [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output, string $planetDotName, string $relProfile) : void
    - protected LightKitAdminBasePlanetInstaller::unregisterOpenMicroPermissionsByProfile(string $appDir, [Ling\CliTools\Output\OutputInterface](https://github.com/lingtalfi/CliTools/blob/master/doc/api/Ling/CliTools/Output/OutputInterface.md) $output, string $planetDotName, string $relProfile) : void
    - public LightBasePlanetInstaller::setContainer([Ling\Light\ServiceContainer\LightServiceContainerInterface](https://github.com/lingtalfi/Light/blob/master/doc/api/Ling/Light/ServiceContainer/LightServiceContainerInterface.md) $container) : void

}






Methods
==============

- [LightKitAdminMailStatsPlanetInstaller::__construct](https://github.com/lingtalfi/Light_Kit_Admin_MailStats/blob/master/doc/api/Ling/Light_Kit_Admin_MailStats/Light_PlanetInstaller/LightKitAdminMailStatsPlanetInstaller/__construct.md) &ndash; Builds the LightKitAdminMailStatsPlanetInstaller instance.
- LightKitAdminBasePlanetInstaller::init2 &ndash; Executes the init 2 phase of the install command.
- LightKitAdminBasePlanetInstaller::undoInit2 &ndash; Undoes the init 2 phase.
- LightKitAdminBasePlanetInstaller::init3 &ndash; Executes the init 3 phase of the install command.
- LightKitAdminBasePlanetInstaller::undoInit3 &ndash; Undoes the init 3 phase.
- LightKitAdminBasePlanetInstaller::message &ndash; Writes a message to the output, assuming it's set.
- LightKitAdminBasePlanetInstaller::prepareMessage &ndash; Prepares the instance so that it can use the message method properly.
- LightKitAdminBasePlanetInstaller::registerOpenMicroPermissionsByProfile &ndash; Registers micro-permissions using their open system, from a given profile relative path (from the config/data directory).
- LightKitAdminBasePlanetInstaller::unregisterOpenMicroPermissionsByProfile &ndash; Unregisters micro-permissions using their open system, from a given profile relative path (from the config/data directory).
- LightBasePlanetInstaller::setContainer &ndash; Sets the light service container interface.





Location
=============
Ling\Light_Kit_Admin_MailStats\Light_PlanetInstaller\LightKitAdminMailStatsPlanetInstaller<br>
See the source code of [Ling\Light_Kit_Admin_MailStats\Light_PlanetInstaller\LightKitAdminMailStatsPlanetInstaller](https://github.com/lingtalfi/Light_Kit_Admin_MailStats/blob/master/Light_PlanetInstaller/LightKitAdminMailStatsPlanetInstaller.php)



SeeAlso
==============
Previous class: [LightKitAdminMailStatsControllerHubHandler](https://github.com/lingtalfi/Light_Kit_Admin_MailStats/blob/master/doc/api/Ling/Light_Kit_Admin_MailStats/Light_ControllerHub/Generated/LightKitAdminMailStatsControllerHubHandler.md)<br>Next class: [LightKitAdminMailStatsService](https://github.com/lingtalfi/Light_Kit_Admin_MailStats/blob/master/doc/api/Ling/Light_Kit_Admin_MailStats/Service/LightKitAdminMailStatsService.md)<br>
