=== NOOBBUILDS Build Instructions ===

  # Latest AOSP Update
  
    N6 = Nexus 6 =   shamu  = Android 6.0.1_r54 = MTC19Z
    N6P = Nexus 6P = angler = Android 6.0.1_r54 = MTC19Z
    N9 = Nexus 9 = flounder = Android 6.0.1_r54 = MTC19Z

    
  # Get NOOBBUILDS Source

    $ git clone https://github.com/fwhem/build-scripts.git -b mm noobbuilds \
         && cd ~/noobbuilds && chmod a+x N6P_BUILD.sh N6_BUILD.sh N9_BUILD.sh
         
    $ repo init -u https://github.com/fwhem/noobbuilds_manifest -b m25
    
    $ repo sync
    
  # Building
  
    $ cd ~/noobbuilds
    $ ./"build".sh   See README_Build_Scripts.md for "build" options   
    
  # Update Source
  
    $ cd ~/noobbuilds
    $ repo sync
    
  # Cleaning
  
    $ cd ~/noobbuilds
    $ make clobber

  # CREDITS
  
    later
