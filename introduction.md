# Inroduction to the Scripting


---

## Why to use Scripting

+ Automate QGIS geoprocessing tasks

+ Perform geoprocessing tasks

+ Access datasets to test for a condition

+ Create tools/plugins to share your python scripts

---

## Creating custom tools

Custom tools become an integral part of geoprocessing, just like system tools.

---

## Why create your own tools?

+ System tools are designed to perform one small but essential operation on geographic data.

+ Using scripting you execute these tools in a sequence, feeding the output of one tool to the input of another.

+ The model or script you create may be an essential part of your workflow—a task you need to repeat again and again

+  You can build your own library of tools that perform small but essential tasks for your organization.

---
# What is script

+ A script can be defined as a set of instructions in plain text, stored in a file and carried out by a software program, specifically a scripting application program.

+ Each scripting application has its own language, and not all scripting languages can be used to write scripts for geoprocessing

---

# Importance of Script

+ Scripts are similar to models in that they allow you to chain processes together to run more efficiently, and to document and share your methodology with others.

+ Scripts can also add functionality that is not available from the standard system tools.

---
# Example use of scripts

+ Batch processing of your data. Scripts can loop through multiple datasets performing the same operation on each dataset, such as projecting all shapefiles in a folder or all feature classes in a geodatabase.

+ You can also write your scripts to process based on certain conditions. For instance, a script can check to see if the input data is a line or a polygon feature class and then process the data accordingly.

---
