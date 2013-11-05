SkinTerrogate
=============


Hello! You are using SkinTerrogate, a tool designed to help you find pornography easier then ever before!
This is a forensics tool that will crawl a given directory for all images (JPG, PNG).  It will analyze each
picture one by one, checking for an inordinate amount of skin showing in any image.    

Analysis is done via a pixel by pixel basis.  Each pixel is compared to a library of skin tones, if the percentage
of pixels identified as a skin tone is high enough, that Image will be flagged and you will be notified of the suspect
image.  


Usage:
-To begin you must have Python installed! 
-You must then make sure you have the PIL python library installed as well
-Run the SkinTerrogate Python tool
-SkinTerrogate will ask you to enter in the directory you wish to crawl for Images
-Enter in format: /<directory>/<directory>/<targetdirectory>
-For Windows: C:\<directory>\<targetdirectory>
-Sit back and wait for SkinTerrogate to identify possible pornographic images



Future versions entail: 
-Multiple directory crawling (Possibly a smart scan of entire computer?)
