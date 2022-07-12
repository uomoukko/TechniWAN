# TechniWAN
![tewan.png](tewan.png)

## A small Windows program to quickly change WAN IP on Technicolor modems
Actually tested on:<BR>
Technicolor DGA4331<BR>
Technicolor DGA4130<BR>
    
## Getting started
Get the last release clicking on the **Releases** button located on the **GitHUB** right panel<BR>
or just click [here](https://github.com/uomoukko/TechniWAN/releases/). It's free for *personal use*<BR>

# Prerequisites
Windows operating system only<BR>  

## Running the executables
 **desktop mode:**<BR>
Double clicking the TechniWAN icon *shows the current IP*<BR>
Dropping any file on TechniWAN icon *triggers the IP-change*<BR>
*(press PAUSE to block countdown to window close)*

 **cmd mode:**<BR>
C:\Users\Myname\Desktop>**TechniWAN**<BR>
    *shows the current IP, doesn't change it*<BR>
C:\Users\Myname\Desktop>**TechniWAN** anything<BR>
    *triggers the IP-change*<BR>

 **other options (cmd mode):**<BR>
C:\Users\Myname\Desktop>**TechniWAN** -uuser -ppassword -R192.168.2.1<BR>
    *sets different user,password,router*<BR>
    *shows the current IP, doesn't change it*<BR>
C:\Users\Myname\Desktop>**TechniWAN** -x0 anything<BR>
    *triggers the IP-change with no delay*<BR> 

## Uses
SRP modem autentication (not easy)<BR>

## Built with
tdm-gcc (10.3.0)<BR>

## Bugs
Please contact me for bugs/improvements<BR>
