#redis-static
====

Static binaries for `redis`.

Based on <https://github.com/eugeneware/ffmpeg-static>.

Binaries are from <http://download.redis.io/redis-stable.tar.gz>

Usage
----

```js
var redis = require('redis-static');
console.log(redis.path);
```

Version Notes
----

Currently supports Mac OS X (64-bit), Linux (32 and 64-bit) and Windows
(32 and 64-bit).

Currently version `5.0.4` is installed for Mac, Windows and Linux.

I pulled the versions from the redis download pages linked from the
official redis site. Namely:

Acknowledgements
----

Special thanks to [eugeneware](https://github.com/eugeneware) for <https://github.com/eugeneware/ffmpeg-static>, which this is based upon.
