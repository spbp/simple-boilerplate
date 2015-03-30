# Simple Template for Sponge Plugins

This template helps you to get started with Sponge development. It makes use of Gradle, a dependency management and build system (similar to Maven).

*Use one of the advanced boilerplates if you want to create a [multi-platform plugin][4] or a [plugin with a separate API][5].*

## Usage
1. Download this repo and copy it to your project folder
2. Modify to fit your needs:
 1. Change the `settings.gradle` to match your project.
 2. Change the `build.gradle` to match your project.
 3. Modify and rename the `WelcomePlugin` class located in the main project. Remember to change the `@Plugin`-Annotation on line 37.
 4. Change the packet structure to your own. Currently it is `com.github.spbp.welcome` which is simply the domain and user reversed. If you want to find out more about naming conventions go here: [Code Conventions (Oracle.com)][1]. Do this on both the main and the API subprojects.
 5. The template comes with the MIT License, a very simple open-source license. If you want, [choose a different license][2] for your project and modify the `HEADER.TXT` and `LICENSE.TXT` files.
3. Build:
 1. Open a CLI of your choice in the root project folder.
 2. Run `gradlew build` or `./gradlew build` if you're on a *nix system.
 3. You will find the resulting JAR-files in a folder named `build/libs` inside the projects root directory.

For support see the related [thread][3] on the Sponge Forums.

[1]: http://docs.oracle.com/javase/tutorial/java/package/namingpkgs.html
[2]: http://choosealicense.com
[3]: https://forums.spongepowered.org/t/boilerplate-for-plugins-with-api-implementation/6264
[4]: https://github.com/spbp/multiplatform-boilerplate
[5]: https://github.com/spbp/api-plugin-boilerplate
