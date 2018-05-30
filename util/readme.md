# Automatically copying index file

(Windows only)

To automatically copy the index file from `auxil/` to `src/` folder so it can be found, place `copyidx.bat` in your project folder, change directories, and tell IntelliJ to run it by going to the run config - before launch - run external tool - add new - select as program the batch file.

The minted package may also need the `*.pyg` files, this can be fixed in the same way.

Could possibly be generalised using the IntelliJ macros?