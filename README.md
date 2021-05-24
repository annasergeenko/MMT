# MMT
A simulation environment for multisensor-multitarget problem

## How to use the software

1. For users who do not have MATLAB® installed
 
The folder  ```for_redistribution``` contains the file MyAppInstaller_web.exe that installs the packaged application, MATLAB Runtime, and all the files that enable use of the application on the target platform with the target language in the target folder. It downloads MATLAB Runtime from the Internet if it is not included in the installer at the time of packaging.

2. For users who do have MATLAB Runtime
   
The folder ```for_redistribution_files_only``` contains specific files that enable use of the packaged application on the target platform with the target language.

### Prerequisites for Deployment 

Verify that version 9.10 (R2021a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.

NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2021a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

## Screenshot

An example of the app layout

![Dispersion](https://user-images.githubusercontent.com/61468945/119403957-cd22a880-bce7-11eb-9c95-ed3c5af25816.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)

