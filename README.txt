First time setup:
	* Run 'cp setup.in setup'
	* Fill in the missing binary paths in 'setup'

Performance setup:
	* Run 'source setup'
	   This will setup PATH to include project specific scripts

	* Run 'dhcp-server' in its own terminal
	   This will make sure OSC messages will be received

	* Run 'maskin-loop' in its own terminal
	   This is the maskin program, but restarted
	   everytime you change performer

	* Run 'print-poem' to print a poem for the
	   current performer

	* Run 'performer NAME' to change performer

Chords and grammars:
	* Put grammars under grammars/ as NAME.txt
	   where NAME is the name of the performer

	* Put chords under chords/ as NAME.txt
	   where NAME is the name of the performer
