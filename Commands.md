## .ss 

take screenshot at any time 
 
![img](https://user-images.githubusercontent.com/44233157/203397679-78bf53de-0a66-4ee2-811e-5b8cf10377dc.png)

## .join 

join voice-channel and stream live microphone input

![img](https://user-images.githubusercontent.com/44233157/203397968-79001712-5fd1-43cd-a898-774c57c0c1e6.png)

## .show [what-to-show] 

Options are:

- processes

get list of running processes or available commands

![img](https://user-images.githubusercontent.com/44233157/203438468-43aed4e3-8d21-41a9-87a0-3630b58979b8.jpg)

## .kill [process-id] 

kill any running process

![img](https://user-images.githubusercontent.com/44233157/203439640-f7754516-be78-4e06-81f8-b22f08eeebd1.jpg)

## .grab [what-to-grab] 

Options are:

- passwords
- history
- cookies
- wifi
- discord

grab for example saved passwords in web browsers

![img](https://user-images.githubusercontent.com/44233157/205966715-a753397c-df0c-4515-bc88-f44513e5b1e0.png)

## .clear 

clear messages from file-related channel  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/203398296-c73b79e8-9f70-45ec-9607-586cd54767a6.png)

## .pwd 

show working directory  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204939055-3bc4da31-b72e-4eea-a153-7b5d712e40ff.png)

## .tree 

show tree of working directory  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204939884-a44fb244-f837-4018-b64e-a12ebde2bbcb.jpg)

## .ls 

list content of working directory  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204940025-5d1f145f-ebf3-463c-b5f0-48099897fbda.png)

## .download [file-or-dir] 

download any file or zipped directory (also greater than 8MB ones) from target PC  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204940123-454bd16b-bcfd-460f-98bd-0455e0fae984.png)

## .upload [type] [name] 

Options for type are:

- single
- multiple

Options for type multiple is name:

- name of the file which is uploaded on the victims pc (uses our splitter)

upload any file or zipped directory (also greater than 8MB ones) onto target PC  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204941488-ba19a2b7-98aa-42fb-a70f-fd26fb93c2dc.jpg)

## .execute [file] 

run any file on target PC  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204941945-33ddcf04-9825-400b-8111-8c1540c0208a.jpg)

## .remove [file-or-dir] 

remove file or directory on target PC  
(command only available on file-related channel)

![img](https://user-images.githubusercontent.com/44233157/204947262-7aca6073-2f2e-4af8-b96b-171a52738da0.png)

## .implode 

remove PySilon from target PC and clean the "evidence"

![img](https://user-images.githubusercontent.com/44233157/204947559-2960d3a6-d259-4592-8b32-7e5193c4cae7.jpg)

## .webcam photo

capture a photo of the victim's webcam and send it to the channel

## .screenrec

record the victim's screen for 15 seconds and send it to the channel.

## .block-input / .unblock-input

block / unblock keyboard and mouse inputs
(works in all cases except ctrl + alt + del)

## .start-clipper / .stop-clipper

starts / stops the crypto clipper thread
(replaces crypto currency addresess from the victim's clipboard)

## .blacklist / .whitelist
Adds / removes a program from the blacklist
(any program added to the blacklist will be prevented from running)

## .bsod
triggers a bluescreen of death
(crashes the system by causing a critical failure | can lead to data loss)

## .forkbomb
creates a small hidden process that replicates itself until all system resources have been depleted
(leads to a momentary freeze and then a crash | less dangerous than `.bsod`)

## .tts
Plays text-to-speech voice messages

## .msg
Displays highly customisable message boxes

## .cmd [command]

execute a command on the victim's pc
(command only available on file-related channel)

## .cd [dir] 

change working directory  
(command only available on file-related channel)

To disable the 2 minute voice recordings, just type 'disable' into the channel with the voice recordings. To resume / restart the voice recordings delete the 'disable' text. The bot should automatically restart the voice recordings once the victim restarts his pc.