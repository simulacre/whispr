0.2.0
- [3](https://github.com/simulacre/whispr/pull/3): fixes update_all setting all values to 0 [ovesh](https://github.com/ovesh)

0.1.0
- [2](https://github.com/simulacre/whispr/pull/2): allows closing the filehandle [ovesh](https://github.com/ovesh)
- IOError caught when reading header will be tagged as Whispr::Error rather than raising Whispr::CorruptWhisprFile
- support testing Whispr from specs using StringIO objects
 
0.0.3
- fixes: branch test and call to #update_one from #update
- [1](https://github.com/simulacre/whispr/pull/1): allows passing array to #update [ovesh](https://github.com/ovesh)

0.0.2
- fixes: Whispr#propogate uses floats when checking xFilesFactor
- fixes: when Archive#fetch is called with a fromTime that is outside of the archive fromTime will be properly adjusted to the oldest available timestamp

0.0.1
- support whispr-create
- support whispr-update
- support whispr-fetch
- support whispr-dump
- support whispr-info
