# Rebuild the Plugin
To be able to use those features, you have to rebuild the plugin with your own version of Xcode.

To rebuild the plugin:

1. If the project doesn't contain C++ code, add an empty C++ class from the Editor.
2. Copy the plugin from <UE_ROOT>/Engine/Plugins/Marketplace/AdsPro/ to <PROJECT_ROOT>/Plugins/AdsPro.
3. Delete the Intermediate, Build, and Binaries folder in <PROJECT_ROOT>/Plugins/AdsPro.
4. Open your project and select Yes when asked to build the sources. It will compile the plugin for your current platform.
5. Package your project for iOS.
6. After doing these steps, the plugin's C++ files should be compiled with your version of Xcode during the compilation stage of the packaging.
