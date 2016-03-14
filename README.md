# IPB-Downloads-exporter
###Exporter for the exotical Invision Power Downloads (addon for Board) storage method.
####I made this because I cannot find something similar anywhere.

#WARNING: Work in progress, this script is under active development, I take no responsibility if this will rm -rf your entire server, format your local HD, kill your cat, or anything else.

##CHECK EVERYTHING before running it!

Actually if you have to move away your community from Invision Power Board you are in big troubles... There aren't good exporters andyou will find yourself trying to redownload everything.

Invision Power Boards + Downloads store all the files users upload in a single directory based on month/year of uploaded, and change the filename+extension in some blobs+filename+ipbsomethings and this is very unpractical.

Launch this script after configuring it!!

Please be aware:
* Check that you have enough disk space!!
* This script COPY your files, so no damage will occur and you can execute it multiple times (maybe in a cron fashion) to keep in sync with your Invision collection.
* the export will recreate the structure of your Invision collection. so, Eg. `Downloads/Section/subsection1/filename.ext` will created

## TODO

[] Add download of xml of contents
[] Process xml to separate static content from posts
