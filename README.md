[![Build Status](https://travis-ci.org/wistful/srtmerge.png)](https://travis-ci.org/wistful/srtmerge)
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/wistful/srtmerge/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

### srtmerge

**srtmerge** is a Python library used to merge two Srt files.

## Usage
```
from srtmerge import srtmerge
srtmerge({'filepath1':'enconding', 'filepath2':None, ...}, out_filepath, offset=1000)
```

`srtmerge filepath1:encoding1 filepath2 filepath3:encoding3 out_filepath offset=1000`
