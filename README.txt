Guitar tuner
============

A web based guitar tuner.

This is a single web that uses the web audio APIs to provide a simple guitar
tuner interface for a 6 six string guitar in standard tuing.

It listens to audio and tries to idendify the current pitch. This is dispayed
as a moving line against a background showing the frequency.

If it can detect a note id compares it to an internal configuration of the
correct frequencies for the guitar strings and identifies the clost
string. Then it indicates how close it is to that pitch with a promot
indicating if it is too low or too high or close enough.

