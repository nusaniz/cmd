# cmd

## loop syntax
@echo off
set loopcount=5
:loop
echo Hello World!
set /a loopcount=loopcount-1
if %loopcount%==0 goto exitloop
goto loop
:exitloop
pause

https://stackoverflow.com/questions/2591758/batch-script-loop
