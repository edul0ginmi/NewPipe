# How to Unlock RAR Password for Prototype 2 PC Game
 
If you have downloaded Prototype 2 PC game from other sources and it is protected by a RAR password, you may wonder how to unlock it. In this article, we will show you some possible ways to recover or bypass the RAR password for Prototype 2 PC game.
 
## Method 1: Try Frequently-Used Passwords
 
Before you use any third-party tools or online services, you should try some common passwords that you may have used before. For example, you can try your birthday, anniversary, phone number, name, or other frequently-used passwords. Sometimes, you may get lucky and unlock the RAR file without much effort.
 
**Download ⇒ [https://t.co/oJ30pZ6Y3z](https://t.co/oJ30pZ6Y3z)**


 
## Method 2: Use Notepad and Commands
 
This is a free and complicated way to unlock RAR password using Notepad and some commands. You need to create a batch file and run it to crack the RAR password. Here are the steps:
 
1. Create a new Notepad file and copy and paste the following commands:

`@echo off
title Rar Password Cracker
mode con: cols=47 lines=20
copy "C:\Program Files\WinRAR\Unrar.exe"
SET PSWD=0
SET DEST=%TEMP%\%RANDOM%
MD %DEST%
:RAR
cls
echo ----------------------------------------------
echo GET DETAIL
echo ----------------------------------------------
echo.
SET/P "NAME=Enter File Name : "
IF "%NAME%"=="" goto NERROR
goto GPATH
:NERROR
echo ----------------------------------------------
echo ERROR
echo ----------------------------------------------
echo Sorry you can't leave it blank.
pause
goto RAR
:GPATH
SET/P "PATH=Enter Full Path : "
IF "%PATH%"=="" goto PERROR
goto NEXT
:PERROR
echo ----------------------------------------------
echo ERROR
echo ----------------------------------------------
echo Sorry you can't leave it blank.
pause
goto RAR
:NEXT
IF EXIST "%PATH%\%NAME%" GOTO START
goto PATH
:PATH
cls
echo ----------------------------------------------
echo ERROR
echo ----------------------------------------------
echo Opppss File does not Exist..!
pause
goto RAR
:START
SET /A PSWD=%PSWD%+1
echo 0 1 0 1 1 0 0 1 0 0 1 0 0 1 0 1 0 0 1 0 > %DEST%\Matrix.tmp
FOR /F "tokens=1-5 delims= " %%A IN (%DEST%\Matrix.tmp) DO (
SET M1=%%A
SET M2=%%B
SET M3=%%C
SET M4=%%D
SET M5=%%E )
del %DEST%\Matrix.tmp

IF %M5% EQU "0" GOTO ZERO

IF %M5% EQU "1" GOTO ONE

:ZERO

IF %M4% EQU "0" GOTO ZEROZERO

IF %M4% EQU "1" GOTO ZEROONE

:ZEROZERO

IF %M3% EQU "0" GOTO ZEROZEROZERO

IF %M3% EQU "1" GOTO ZEROZEROONE

:ZEROZEROZERO

IF %M2% EQU "0" GOTO ZEROZEROZEROZERO

IF %M2% EQU "1" GOTO ZEROZEROZEROONE

:ZEROZEROZEROZERO

IF %M1% EQU "0" GOTO ZEROZEROZEROZEROZERO

IF %M1% EQU "1" GOTO ZEROZEROZEROZEROONE

:ONE

IF %M4% EQU "0" GOTO ONEZERO

IF %M4% EQU "1" GOTO ONEONE

:ONEONE

IF %M3% EQU "0" GOTO ONEONEZERO

IF %M3% EQU "1" GOTO ONEONEONE

:ONEONEONE

IF %M2% EQU "0" GOTO ONEONEONEZERO

IF %M2% EQU "1" GOTO ONEONEONEONE

:ONEONEONEONE

IF %M1% EQU "0" GOTO ONEONEONEONEZERO

IF %M1% EQU "1" GOTO ONEONEONEONEONE

:GRTGRT

cls

echo.

echo.

echo.

echo.

echo. 8cf37b1e13


`