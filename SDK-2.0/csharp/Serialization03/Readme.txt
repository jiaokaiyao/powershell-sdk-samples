Serialization Sample 03
==========================
     This sample looks at an existing .NET class and shows how to make sure that
     instances of this class and of derived classes are deserialized (rehydrated)
     into live .NET objects.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 


Sample Language Implementations
===============================
     This sample is available in the following language implementations:

     - C#
     - types.ps1xml


To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to ProxyCommand01 under the samples directory.
     2. Double-click the icon for the .sln (solution) file to open the file in Visual Studio.
     3. In the Build menu, select Build Solution.
     The library will be built in the default \bin or \bin\Debug directory.


To run the sample:
=================
     1. Start command prompt.
     2. Navigate to the folder containing the sample binaries.
     3. Run: .\Serialization03.exe

Demonstrates
============
     This sample demonstrates the following:

     1. Setting serialization depth for a given .NET class
     2. Creating a type converter that can rehydrate a deserialized property bag into a live .NET object
     3. Declaring that deserialized property bags of a given .NET class need to be rehydrated using the type converter




