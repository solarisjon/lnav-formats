# lnav-formats
lnav formats

lnav : is a Log File Analysis navigator which can be found on https://github.com/tstack/lnav

Extra log formats outside of this can be installed using lnav -i extra (see the docs)

This contains some extra formats 

SolidFire

  sf-master.info and sf-master.error    : format is sfmaster
 
  sf-slice.info and sf-slice.error      : format is sfslice
 
  sf-block.info and sf-block.error      : format is sfblock
  
  Installation 
    
    Either push this format file locally by lnav -i filename into ~/.lnav/formats/installed
    
    or
    
    Run lnav -i <this git repo>
    You can then use lnav -u to keep the filters current
