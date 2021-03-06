Runspace Sample 05
==========================
     This sample shows how to create an initial session state and 
     then how to use the initial session state when creating the 
     runspace.

     This sample assumes that user has the GetProcessSample01.dll that is 
     produced by the GetProcessSample01 sample copied to the current directory.

     For Windows PowerShell information on MSDN, 
     see http://go.microsoft.com/fwlink/?LinkID=178145 
 

Sample Language Implementations
===============================
     This sample is available in the following language implementations:
     - C#

To build the sample using Visual Studio:
=======================================
     1. Open Windows Explorer and navigate to Runspace05 under the samples directory.
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
     
     1. Creating a default initial session state.
     2. Creating a runspace using the default initial session state.
     3. Creating a PowerShell object that uses the runspace.
     4. Adding the get-proc cmdlet to the PowerShell object from a 
        snap-in.
     5. Using PSObject objects to extract and display properties from 
        the objects returned by the cmdlet.
