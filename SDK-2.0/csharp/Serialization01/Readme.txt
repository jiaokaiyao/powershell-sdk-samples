Serialization Sample 01
==========================
     This sample looks at an existing .NET class and shows how to make sure that
     information from selected public properties of this class is preserved across
     serialization/deserialization.

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
     3. Run: .\Serialization01.exe

Demonstrates
============
     This sample demonstrates the following:

     1. Setting serialization depth for a given .NET class
     2. Restricting what properties are serialized

