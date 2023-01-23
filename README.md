# undergrad_research
For my undergrad students

HELLO, WELCOME TO MY FIRST ATTEMPT AT TEACHING PEOPLE - I'M SURE WE'LL ALL HAVE A GOOD TIME. 

First things first, the necessaries of what you need to do this research:

--> access to a linux workspace - I believe in Ubuntu supremacy, so that's preferred. You can find it here: https://ubuntu.com/download/desktop
    i) Jammy Jellyfish is preferred, as it is the most stable of the newer releases I believe. 
    ii) if you're having issues getting Ubuntu up and running, or simply don't want to not have Windows on your personal PC, there is a spare computer in my
        lab that you can use.
        
--> once you have Ubuntu, please download several packages to the computer. You can do this via sudo apt install (make sure you are the root user on your PC)
     perl: sudo apt install perl
     
     build-essential: sudo apt install build-essential
     
     gcc: sudo apt-get install manpages-dev
     
     libsdl2-dev: sudo apt-get install libsdl2-dev
     
     gzip: sudo apt -y install gzip
     
     coreutils: sudo apt -y install coreutils
     
     bedtools: https://bedtools.readthedocs.io/en/latest/content/installation.html
     
     VCFtools: https://vcftools.github.io/examples.html
     
  To verify that these are all installed do: 
  
     [package] --version
  
  if they are installed correctly, your PC should spit out the package name plus a version number. 
     
--> then download the .bed files for your specific Neanderthal from http://ftp.eva.mpg.de/neandertal/
    
    Maya: Chagyrskaya 8 (http://ftp.eva.mpg.de/neandertal/Chagyrskaya/FilterBed/)
    
    Megan: Vindija 33.19 (http://ftp.eva.mpg.de/neandertal/Vindija/FilterBed/Vindija33.19/)
    
    Jonathan: Altai (http://ftp.eva.mpg.de/neandertal/Vindija/FilterBed/Altai/)
      
  make sure these are accessible to your ubuntu workspace. 
  download all the chr .bed files, as it'll probably save time later. 
    
--> if you don't already, make sure you have a github account. it's super useful (and free!) it'll also allow you to copy (fork) my respositories easily.
    
--> the first three genes we'll be looking at are: GMBE1, TRAIP, RPN1.
    
  This is as I've found that these are DIFFERENT from the human versions of the genes in the Chagyrskaya Neanderthal, so I want to replicate research and then see if other Neas show the same differentiation.
    
    Look them up on https://www.genecards.org/ for a rough idea of what they do. What do they all have in common, for instance?
    
--> look at the file working_pipeline in this repository and have a go! 


If you're having difficulties with this - no problems! But what I'd like you to do is to try and solve the issue on your own. Searching the error in google is an absolutely excellent way to find out how to get around them (but be careful with chmod commands, they can destroy your file structure, and there's no way to get it back). Stackoverflow, stackexchange, and BioStars are full of people who will just give you the solutions at the drop of a hat. If this doesn't work, don't hesitate to get in contact with me! 
