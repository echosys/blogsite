---
title: sysTool_log
date: 2025-01-10T17:33:42.565Z
---
-------------------------//
-------------------------//25
---------------//15
-----//5




---------------//
-----//
-----//
-----//

-----//


---------------//
-----//
-----//
-----//

-----//

//
brew install p7zip
zip -P password -r output.zip inputfolder

zip -P qwer -r zL1_vid.7z zL1_vid
7z x zL1_vid.7z -P qwer 

7z -Pqwer a zZip.7z zZip
7z x zZip.7z zZip2 -pqwer 
7z a test.7z test.log -pqwer
7z x test.7z -pqwer 


//FFmpeg
brew install ffmpeg

ffmpeg -i input.mp4 -vcodec libx265 -crf 28 output.mp4
push the compression lever further by increasing the CRF value — add, say, 4 or 6, since a reasonable range for H.265 may be 24 to 30. Note that lower CRF values correspond to higher bitrates, and hence produce higher quality videos.


ffmpeg -i 2023-06-23_1-1.mov -vcodec libx265 -crf 36 2023-06-23_1-1.mp4
ffmpeg -i GMT20210525.mp4 -vcodec libx265 -crf 36 GMT20210525.mp4
too slow 

-y -i $sourceFile -s ${width}x${height} -r 5 -c:v libx264 -b:v 600k -b:a 44100 -ac 2 -ar 22050 -tune fastdecode -preset ultrafast $destPath
ffmpeg -y -i 2024-03-20_orch.mov -r 5 -c:v libx264 -b:v 600k -b:a 44100 -ac 2 -ar 22050 -tune fastdecode -preset ultrafast 2024-03-20_orch.mp4

ffmpeg -y -i 2023-05-25_Anuscheduler.mov -r 5 -c:v h264_videotoolbox -b:v 100k -b:a 44100 -ac 2 -ar 22050 -tune fastdecode -preset ultrafast 2023-05-25_Anuscheduler.mp4

ffmpeg -y -i GMT20210525.mp4 -r 5 -c:v h264_videotoolbox -b:v 60k -b:a 44100 -ac 2 -ar 22050 -tune fastdecode -preset ultrafast GMT202105251.mp4

gpu support 
https://stackoverflow.com/questions/52591553
ffmpeg -i input.mov -c:v h264_videotoolbox output.mp4


//JDiskReport
/Users/lge11/z1Dr1
java -jar jdiskreport-2beta5.jar 
java -Dpath=/Users/lge11/z1DrLg -jar jdiskreport-2beta5.jar 


//Correct typing errors in Terminal on Mac
Erase the line: Press Control-U.
Erase from cursor position to the end of the line: Press Control-K.


//multi use diff version dl from browser
IJ, goland  
vscode 
chrome can not dl from web

//sublime text turn off update check
Modify /etc/hosts to include entries:

127.0.0.1 www.sublimetext.com
127.0.0.1 sublimetext.com
127.0.0.1 sublimehq.com
127.0.0.1 license.sublimehq.com
127.0.0.1 45.55.255.55
127.0.0.1 45.55.41.223
0.0.0.0 license.sublimehq.com
0.0.0.0 45.55.255.55
0.0.0.0 45.55.41.223


//osx control c not killing vscdoe terminal python script 
ps aux | grep python
kill -9 pid 


//
vector database





-------------------------//
-------------------------//

