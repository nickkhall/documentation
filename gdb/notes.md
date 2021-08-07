# GDB C++ Debugger

For more information, visit: `https://web.eecs.umich.edu/~sugih/pointers/summary.html`

## Simple Debugger
### Start Debugger
Run executable in debugger (start session):
```
  gdb main
```

### Set Breakpoint (Optional):
You can set a breakpoint on a specific file and line number with the following syntax:
```
break classes/interface.cpp:33
```

### Run the program:
```
run
```

### Step through program:
You can step through, line by line, with the following command:
```
step
```

## Advanced Debugger (gdbserver)
* Start `gdbserver` with host:port and debug executable:
```bash
gdbserver localhost:12345 ./debug/debug
```

* In a separate terminal window, compile application for gdb debugging
```bash
make debug
```

*  Then run `make gdb_debug` in the newly created terminal.

The gdb server and debug executable should be connected now, and you can now proceed to debug.

----

### Notes
#### Common Commands:
  * `layout next` - changes the data / information displayed (hex, assembly, code, etc) 
  * `break src/my_file.c:23` - sets a breakpoint in the file `my_file.c` in the `src` directory on line `23`.
  * `set follow-fork-mode child` - tells `gdb` to follow newly spawned child processes.
  * `continue` - run the debug with all the settings configured
