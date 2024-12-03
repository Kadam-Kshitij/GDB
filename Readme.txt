gdb : Start gdb
file <filename> : Set the executable to run
run arg1 arg2 : Run the executable set above with arguments

break <function> : Set breakpoint at function
break main : Set breakpoint at start of main
break <file>:<lineNumber> : Set breakpoint at <line> in <file>
info breakpoints : Display all breakpoint info
delete breakpoint_number : Delete breakpoint
disable breakpoint_number : Disable breakpoint
enable breakpoint_number : Enable breakpoint

continue : Continue execting the program
step : Step into the function
next : Step over the function
finish : Step out of current function

info threads : Display all thread information
thread <number> : Switch to specified thread

print <var_name> : Print variable value
info locals : Print all local variables in current function
info variables : Print all global variables
print &<varable> : Print address of variable
print *<pointer> : Print pointer contents

backtrace full : Show call stack
info frame : Show current frame
frame frame_num : Switch frame

x/4x address : Examine memory ( 4 units )
