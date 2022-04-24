# ToTable-ToInstance
Module that allows instances to tables and tables to instances.

## Introduction

Hello!

I've created this module to allow individuals to easily convert their tables to instances, and convert those instances back to tables. I created it for my own personal use but decided I may be helping individuals who need it if I provided it for everyone to use.

In terms of customizability, unfortunately there is none that I made readily available but since it's open-sourced, you can feel free to edit it to your own liking.

## Questions you may have

> Does it support nested folders and tables?

It does! This module relies heavily on recursion which is one thing I had a hard time with when I first started. I'm hoping this module aids users with datastores and recursion.

> What datatypes does it support?

The basic version supports boolean, table, number and string. The advanced version supports boolean, table, number, string, BrickColor, Vector3, CFrame, Color3 and Ray.

## Functions:
`Module:ToInstance(table, parent)`
Converts table variable to instances and parents it to the parent variable assigned above.

`Module:ToTable(parent)`
Parent of the instances which you want to compile into a table.

You can get the module here:
https://www.roblox.com/library/6281148847/ToTable-ToInstance

Second, more advanced option that includes more datatypes:

## Advanced Functions:

`Module:ToInstance(table, parent)`
Converts the `table` variable to instances which are parented to the `parent` argument.

`Module:ToTableForDataStore(folder)`
Converts the instances from the children of the provided `folder` argument.

https://www.roblox.com/library/6925157422/Advanced-ToTable-ToInstance
