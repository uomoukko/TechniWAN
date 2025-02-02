# TechniWAN
<TABLE><TR><TD>
<p align="center"><img src="img/TechniWAN.png" alt="TechniWAN-icon" width="150" height="150"><br></p>

<TABLE BORDER=0>
<TR>
<TD ALIGN=CENTER> <img src="img/win10.png"   alt="w10-icon"     width="100" height="100"><BR>Windows 10<BR></TD>
<TD ALIGN=CENTER> <img src="img/win11.png"   alt="w11-icon"     width="100" height="100"><BR>Windows 11<BR></TD>
</TR>
</TABLE>

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
C:\Users\Myname\Desktop>**TechniWAN** -uuser -ppassword
    *sets user,password to save in register user,password*<BR>
C:\Users\Myname\Desktop>**TechniWAN**  -R192.168.2.1<BR>
    *sets router*<BR>
C:\Users\Myname\Desktop>**TechniWAN** -x0 anything<BR>
    *triggers the IP-change with no countdown*<BR> 

## Uses
SRP modem autentication<BR>

## Built with
tdm-gcc (10.3.0)<BR>

## Bugs
Please contact me for bugs/improvements<BR>
</TD></TR></TD></TABLE>
