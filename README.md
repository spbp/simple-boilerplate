# A Simple Template for Sponge Plugins

## How to use this:
1. Download this repo and copy it to your project folder
2. Rename subfolders to whatevery you want. (ex: `myplugin` and `myplugin-api`)
3. Modify to fit your needs:
 1. Change the `settings.gradle` to match your project.
 2. Change the `build.gradle` to match your project.
 3. Modify and rename the `BoilerplatePlugin` class located in the main project. Remember to change the `@Plugin`-Annotation on line 37.
 4. Change the packet structure to your own. Currently it is `com.github.boformer.boilerplate` which is simply the domain and user reversed. If you want to find out more about naming conventions go here: [Code Conventions (Oracle.com)][1]. Do this on both the main and the API subprojects.
 5. Add your own header and license. Information on licenses can be found here: [License Picker][2]
4. Build:
 1. Open a CLI of your choice in the root project folder.
 2. Run `gradlew build` or `./gradlew build` if you're on a *nix system.
 3. You will find the reulting JAR-files in a folder named `build/libs` inside the projects root directory.

For support see the related [thread][3] on the Sponge Forums.

[1]: http://docs.oracle.com/javase/tutorial/java/package/namingpkgs.html
[2]: http://choosealicense.com
[3]: https://forums.spongepowered.org/t/boilerplate-for-plugins-with-api-implementation/6264
