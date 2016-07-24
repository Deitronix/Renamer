# Renamer
Rename the files in your folder.

Select one of the files to rename, then create a mask for the program to follow when renaming. 

Example: 
A folder contains 35 files similar to xXx_DokaPSubs_xXx Goro no Rogo-Ep.35 

- Create mask symbols % $ # (it must be the same delimiters, so [ will be the same for the end delim.)
- Put your mask symbols in the example file name: xXx_#DokaPSubs#_xXx $Goro no Rogo$-Ep.%35%
- Set your mask: [ # ] $ % FR

Result: [ DokaPSubs ] Goro no Rogo 35 FR and so on for all the similar files in the folder.

Note that if there are files with different naming style that you still want to rename, just change the example file after 
renaming the first batch.
