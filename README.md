# RxpsG
Processing tool for X-ray Photoelectron Spectroscopy Data

R, RStudio installation: (see also:  https://cloud.r-project.org/ and  https://www.rstudio.com/)
   
    1. Install R and Rstudio on your computer 
    
    2. Run Rstudio and open the Tools menu -> Global Options;
    
    3. Verify all is working by typing:
       version
       you should get something like:
       
         platform       x86_64-pc-linux-gnu         
         arch           x86_64                      
         os             linux-gnu                   
         system         x86_64, linux-gnu           
         status                                     
         major          4                           
         minor          1.2                         
         year           2021                        
         month          11                          
         day            01                          
         svn rev        81115                       
         language       R                           
         version.string R version 4.1.2 (2021-11-01)
         nickname       Bird Hippie   
    
    
RxpsG installation:

    1. Click on the RxpsG_xx.xx.tar.gz package and download. Exit the unzipping procedure if it starts automatically.
     
    2. Control in the Dowloads folder the RxpsG_xx.xx.tar.gz package is present (it could be the .gz extension is lacking do not worry).
    
    3. Run RStudio 
    
    4. Under RStudio -> Tools 
                           -> Install Packages   
                                           
       ==> Verify the destination folder corresponds to that of the installed R version
       
       ==> mark the checkbox INSTALL DEPENDENCIES                                    
           ‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾‾                                
       ==> select option INSTALL FROM PACKAGE ARCHIVE
         
       ==> browse the  RxpsG_xx.xx.tar.gz file. 
     
       ==> Press the  INSTALL  button
       
       Controll that during installation also the additional libraries listed in the dependencies are installed:
       digest, gWidgets2, gWidgets2tcltk, import, latticeExtra, memoise, minpack.lm, signal, rootSolve
       
       If the procedure does not work you must install manually the needed libraries:
       RStudio -> Tools -> Install Packages
       ==> select option INSTALL FROM CRAN 
       ==> enter one by one the names of the following libraries and press install:
           digest, gWidgets2, gWidgets2tcltk, import, latticeExtra, memoise, minpack.lm, signal, rootSolve
    
    5. To run RxpsG, in RStudio select the PACKAGE pain (generally on the right of the RStudio console) and select the RxpsG package 
       then type:
       xps()
    
   

