# lnav-formats
lnav formats

lnav : is a Log File Analysis navigator which can be found on https://github.com/tstack/lnav by Tim Stack

Statically Linked
OSX       https://github.com/tstack/lnav/releases/download/v0.8.5/lnav-0.8.5-os-x.zip

Linux     https://github.com/tstack/lnav/releases/download/v0.8.5/lnav-0.8.5-linux-64bit.zip

Extra log formats outside of this can be installed using lnav -i extra (see the docs)


------------------------------------------------------------------------------------------------------------------------
This contains some extra formats 

SolidFire

  sf-master.info and sf-master.error    : format is sfmaster
 
  sf-slice.info and sf-slice.error      : format is sfslice
 
  sf-block.info and sf-block.error      : format is sfblock
  
  ------------------------------------------------------------------------------------------------------------------------
  Installation 
    
    Either push this format file locally by lnav -i filename into ~/.lnav/formats/installed
    
    or
    
    Run lnav -i <this git repo>
    You can then use lnav -u to keep the filters current
