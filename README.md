# PENeL - Powershell with Embedded .NET Library
Program that prepares a .NET DLL Library to run embedded in Powershell Script

**Created By:** Guilherme Bacellar Moralez (Th3 0bservator)
https://twitter.com/th3_0bservator

## Disclaimer
**This code is created and maintened only for a research proposal. Please do not use for malicious proposes.**

## Objectives
Create a program that prepares every .NET DLL Library and creates a PowerShell Script with that DLL embedded for delivery.

# Features

   * .NET Core and Classic .NET Library Supported
   * Exposes Public Method's Only
   * TBD

# Parameters

* --source
* --class
* --method
* --template
* --destination

### --source
Source file Path (Relative or Absolute)

### --class
Public class name (full qualified namespace) to load

### --method
Public method name inside *class* 

### --template
Template Type

   * V1 - Classic. Classic Direct Public ParameterLess Method Execution
   * V2 - Reflection. Public ParameterLess Method Execution by Reflection
      
### --destination
Destination file Path (Relative or Absolute)


