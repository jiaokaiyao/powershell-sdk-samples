Runspace Sample 04
==========================     
     This sample shows how to use the PowerShell class to run commands. 
     The commands generate a terminating exception that the caller should 
     catch and process.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 


Sample Language Implementations
===============================
     This sample is available in the following language implementations:

     - C#

To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to Runspace04 under the samples directory.
     2. Double-click the icon for the .sln (solution) file to open the file in Visual Studio.
     3. In the Build menu, select Build Solution.
     The library will be built in the default \bin or \bin\Debug directory.

To run the sample:
=================
     1. Start a command prompt.
     2. Navigate to the folder containing the sample executable.
     3. Run the executable.

Demonstrates
============
     This sample demonstrates the following:

     1. Creating a PowerShell object.
     2. Using the PowerShell object to run the commands.
     3. Passing input objects to the commands from the calling program.
     4. Using PSObject objects to extract and display properties from the 
        objects returned by the commands.
     5. Retrieving and displaying error records that were generated
        while running the commands.
     6. Catching and displaying terminating exceptions generated
        while running the commands.
