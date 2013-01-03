# Bad Metronome

This application shows how NOT to write audio timing code.  It directly uses setTimeout to schedule and play notes, which is a great way to let layout and other tasks mess up your audio timing in audio applications.

Check it out, feel free to submit issues or requests, fork, submit pull requests, etc.

The live app is at http://webaudiodemos.appspot.com/badmetronome/index.html.

-Chris