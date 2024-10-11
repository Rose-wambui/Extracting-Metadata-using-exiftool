# Extracting-Metadata-using-exiftool
Extracting Metadata from a file, video or picture using the exiftool in kali Linux.

ExifTool is developed by Phil Harvey. It is a platform-independent Perl library coupled with a full-featured command-line implementation for reading, writing and manipulating the metadata across a broad range of files, particularly the JPEG images. 

Note: for this study am using kali linux.

How to install
#sudo apt install libimage-exiftool-perl

![image](https://github.com/user-attachments/assets/6598a41e-0c78-4725-9888-95c1575636b6)

We are going to run a few commands using exiftool against an image i downloaded online.

#exiftool <filename> bird.jpeg

![image](https://github.com/user-attachments/assets/2a42c0ae-4795-4de1-9ee7-e0b979a1ce85)


To extract common metadata we can use;
#exiftool -common <filename>
![image](https://github.com/user-attachments/assets/88a277b2-8b2e-47e5-b3b9-10e991f87aaa)


To learn more about the various commands that can be used with exiftool, check in the man pages
#command man exiftool

![image](https://github.com/user-attachments/assets/928a2db5-9b52-40de-8fea-27a2b246b3c8)


