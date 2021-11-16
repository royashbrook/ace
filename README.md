## What is this?

Example of how to install Microsoft ACE drivers in a github action. This allows us to use oledb drivers in the pipeline. This allows us to test Invoke-ExcelQuery in ImportExcel module.

Also shows how to cache a installer file for later use so we can avoid downloading it every time, as well as caching powershell modules. Can cache the modules the same way, but I'm using another action to accomplish that.
