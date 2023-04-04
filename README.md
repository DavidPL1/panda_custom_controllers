# UBI Custom Panda Controllers

### This is a collection of custom controllers for the Franka Emika Panda robot

If you want to contribute your controller, simply add the controller package as subdirectory and add it as dependency of the meta package:

To do that simply add the following line to `ubi_panda_custom_controllers/package.xml`
```xml
    <exec_depend>YOUR_CONTROLLER_PACKAGE_NAME</exec_depend>
```