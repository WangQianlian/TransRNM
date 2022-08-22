TransRNM Executable

1. Prerequisites for Deployment 

Verify that version 9.12 (R2022a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2022a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.


2. Files to Deploy and Package

Files to Package for Standalone 
================================
-TransRNM.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 


3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation Center.


4. Operation

Users can either run the exe file directly or run it after installation.
Note that the user must install MATLAB Runtime 9.12, otherwise, the tool TransRNM 
cannot strat up. 
Note that the user must run the tool TransRNM as an administrator, otherwise, 
the tool will report an error because the user lacks folder access rights.

The operation log file is named after the time when the tool TransRNM is running.
The default storage path for operation log files is:
	
	C:\Program Files\TransRNM_Log\ 

And the user cannot change the log file path.


5. Contact us

If you have any question or suggestion, please feel free to contact us. 
We look forward to working with you to improve the TransRNM tool.

Email: wangqianlian@foxmail.com





