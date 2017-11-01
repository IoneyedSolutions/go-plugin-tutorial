# Golang Plugin Tutorial

This will be an introduction to the GO plugin capabilities to build modular GO applications. In this tutorial you will learn how to write a basic plugin, load the plugin and use it in an application. As we finish the tutorial we will look at a practical use case for plugins to show how they can be practically used.

# Tutorial

As you see the repository is empty on the `master` branch. This was intentional as each branch shows the steps that will be taken below. You can follow along as each `branch` builds on the previous or you can jump to the `final` branch to see all the steps completed.

* **Tutorial Introduction**
* Basic Plugin - We will build a basic plugin module, load the plugin, and then we will invoke the plugin in our `main` application.
  * Extended - We will expand our basic plugin to dynamically load several plugins by walking the directory and loading each one whilst invoking it to show that each plugin was loaded.
* Intermediate Plugin - We will expand on the basic plugin to dynamically load modules from a configuration file.
  * Extended - We will take this configuration file to load the plugins and configure the plugin module with the same configuration file.
* Advanced Plugin - We will expand on the intermediate plugin to not only load a plugin but we will pull down a remote plugin, compile it, then load it while keeping the application running to demonstrate a daemon with dynamic configurations.