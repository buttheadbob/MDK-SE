The `Runtime` is another property which exists on your script's base class `MyGridProgram`, alongside [Storage](https://github.com/malware-dev/MDK-SE/wiki/The-Storage-String) and [Me](https://github.com/malware-dev/MDK-SE/wiki/The-Running-Programmable-Block). This property contains information about the running environment of your script. Specifically these members:

* `TimeSinceLastRun`  
    Gets the time elapsed since the last time the Main method of this program was run. This property returns no valid data neither in the constructor nor the Save method. Also keep in mind that the very first time a script is run each session, this property will be empty (`TimeSpan.Zero`) since - obviously - there hasn't _been_ a last run yet.

* `LastRunTimeMs`  
     Gets the time in fractional milliseconds it took to execute the Main method the last time it was run. This method returns no valid data neither in the constructor nor the Save method. You can use this property to profile your script and find out whether it runs fast enough.

* `MaxInstructionCount`  
    In order to help keeping the runtime of scripts down to a reasonable level, the programmable block imposes a maximum number of significant instructions before a script is deemed too complex and forcefully terminated. A "significant instruction" includes conditionals (if/else), switches, method calls and similar. Exactly what a "significant instruction" is is not important, this is just a tool to help you stop the most obvious mistakes. This property Gets the maximum number of significant instructions that can be executed during a single run, including any other programmable blocks invoked immediately. 

* `CurrentInstructionCount`  
    Gets the current number of significant instructions executed so far this run.
