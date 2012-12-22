# Resave shot
Simple tool to resave multiple bloated mplayer2 screenshots. Requires GIMP and Ruby. Most likely only works on Linux.

## Install
Place resave-image.scm in your GIMP scripts folder for example: ~/.gimp-2.8/scripts/.   
Move rs-shot to a location in your $PATH. 

## Use
Simply run rs-shot in the directory with your bloated files.

## Other
This can easily be modified and used for other wrongfully bloated files.    

You simply change `bloat_size = 2774103` to `bloat_size = bloat_size_in_bytes` and `file_prefix = "shot"` to `file_prefix = "default_prefix"`.     

You may leave the file prefix blank if there is no prefix for example: `file_prefix = ""`.    
**Note: leaving the file prefix blank will resave all files in the directory.**


To be clear, this does not resize the actual image file, it simply corrects wrongfully bloated file sizes by resaving with GIMP.
