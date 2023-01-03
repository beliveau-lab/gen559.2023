# gen559.2023
Support for WI 2023 GEN559

## Conda and Jupyter notebook installation via command-line (OS X only)

1. Open a new terminal window (Applications->Utilities->Terminal) <br/>

2. Type the following command to change your default shell to bash:    <br/>
    ```chsh -s /bin/bash```  <br/>
    
3. Open up a new terminal window. You should see your user name followed by a `$`, e.g. `beliveau$` <br/>

4. Download the appropriate version of miniconda for your system (select the option ending in `bash`: https://docs.conda.io/en/latest/miniconda.html <br/>

5. Move the installer to your home directory by typing:
```mv ~/Downloads/Miniconda3 <tab> .``` <br/>
_Here, when you press the `tab` key, the shell should autocomplete the full filename of the miniconda installer_ <br/>

6. Run the installer by typing:
```bash Miniconda3 <tab>``` <br/>
_Once again, when you press the `tab` key, the shell should autocomplete the full filename of the miniconda installer_ <br/>
_Accept the license, proceed with the install in the default location, and select `Yes` when asked to allow conda to run init_ <br/>

7. Close your terminal and open a new terminal window <br/>

8. Create a new conda enviroment named `gen559` with the necessary packages by entering the following command:
```conda create --name gen559 notebook pandas``` <br/>

9. When asked to proceed, enter `y` <br/>

10. After insallation, activate your enviroment by typing:
```conda activate gen559``` <br/>

11. Activate Jupyter by entering the following command:
```jupyter notebook```  
_After a brief pause, a Jupyter Notebook tab should open in your default web browser._ <br/> 
_You can test it out by selecting `New` from the top right corner._
