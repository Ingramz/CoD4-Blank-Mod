# Blank mod for Call of Duty 4

This mod will override the main scripts which will invoke other scripts.

Good for testing out code without other scripts affecting it.

## Code execution flow

In _callbacksetup.gsc CodeCallback_StartGameType will be executed in parallel
with gametype and map main functions.

Other callbacks are defined in _callbacksetup.gsc file.
