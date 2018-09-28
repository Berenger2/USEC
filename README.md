# USEC - Project description

## Introduction

Date security is an important topics nowaday. With the increasing usage of flash 
disk (which are amovible), it is more likely good to find a good and right way 
to lock data against copy. Python is a cripting language that could be used to 
do such task. As, python is cross plaform scripting language. The aim of this 
project is to build a pythoon based application to secure the data on a USB key 
against reproduction.

The idea is to block the copy of the data on the USB key, so the data will be 
available by default in read mode and only after activation from the application 
they will go into edit mode and execution.

## Language and requirement

This application will be based on `python3`. And should be tested on `Linux` and 
`windows` environments. A unit test should also be added to the project in 
order to validate the results.

## Structure

To achieve the results we're expecting, the project will be break down into more 
simple sub-program (`functions`).

1. a function to read folders
2. a function to read files
3. a function to modify files attributes
4. a function to lock the USB disk
5. bluid  pipeline to use those functions

Those simple task will be created as issues on the `github` environment and then 
solved linearly.

## Timing




