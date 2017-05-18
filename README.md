Hosts a 2m5s long test DASH stream at http://localhost:8002/trainstation.mpd

Requires Python 2.

* Execute `run` to start server ("./run").
* Point your DASH player to `http://localhost:8002/trainstation.mpd` (replacing `localhost` with your computer's IP address if playing on a different machine).
* Hit `Ctrl-C` to stop server.

* To test buffering, suspend process with [Ctrl+Z]. And then hit [fg+Enter] to start the process again
* To test streams with `presentationTimeOffset`, use the `http://localhost:8002/trainstation-pto.mpd` manifest.
