# RxpsG
Processing tool for X-ray Photoelectron Spectroscopy Data

R, RStudio installation: (see also:  https://cloud.r-project.org/ and  https://www.rstudio.com/)
   
    1. Install R and Rstudio on your computer 
    
    2. Run Rstudio and open the Tools menu -> Global Options;
    
    3. Verify all is working: open RStudio and type:
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
    
    2. Dowload the macro  instPkgs.r
    
    3. Control in the Dowloads folder the RxpsG_xx.xx.tar.gz and instPkgs.r packages are present (it could be the .gz extension is lacking do not worry).
    
    4. Run RStudio 
    
    5. Under RStudio -> Code -> Source File   browse the  instPckgs.r file. Then install all the needed libraries typing:
       instPckgs() 
       the installation will take one or two minutes.
    
    5. Under RStudio open the Tools menu -> Install Packages -> Package Archive File ( *.tar.gz ) 
       browse the Rxpsg.xx.xx.tar.gz  file and install it
    
   

