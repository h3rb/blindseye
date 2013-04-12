<pre>
blindseye
=========

Blinds Eye MUD Client - A MU* client written for the seeing impaired that can be used by the non-seeing impaired.

License: MIT


Features:

  * Reads screen content with an open-source Text-To-Speech
  * Provides the ability to create world- and genre- based Triggers that can play audio on disk when triggered.
  * Audio is designed not to play over Text-To-Speech
  * Multiple worlds at one time
  * Strips ANSI and other codes from the session
  * SPAM-control features
 
Keyboard commands:

The numeric keypad is used to interface with client features.
Arrow keys are used to navigate software commands and other options.
TAB is used to switch between Output and Input windows.
Numpad INSERT allows you to create a new connection either from a defined or a new game.
Forward slash / allows you to type verbose commands into the client (see below)

Verbose commands:

/new <name> <ip> <port>      - creates a new world / session and connects to it
/w <name>                    - switches to a session, connecting if it is not connected, if it is defined
/p <name> <file> <search>    - sets a trigger when search phrase is seen which plays a file by name in the Samples directory (see below)
/t <name> <macro> <search>   - triggers trigger of <name> when search phrase is seen and executes command by name
/m <name> <command;list>     - groups a list of commands into a macro which can be triggered by name, cannot override a verbose command
/x <name> X Y                - executes a macro by name X times with an interstitial delay of Y (default 1 second)
</pre>
