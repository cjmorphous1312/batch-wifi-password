# batch-wifi-password
echo off 
color 04
echo ur all password is transfered to ur file manager u can get it by following the steps 
echo u should do this after launching the process 
echo go to the file c:\ directory
echo open the file  echo go to the discription (xml file ) 
echo search for key meterial and that's ur password 
echo note ur all password is loaded in it whic is secured in ur pc 
echo this even includes ur ip. 
echo ======================================================================================= 
echo lets start the process 
echo ======================================================================================= 
pause 
ipconfig 
netsh wlan show profile
netsh wlan export profile folder=. key=clear
echo ======================================================================================= 
echo process completed 
echo ======================================================================================= 
pause
