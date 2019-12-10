# Euphony.js

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![](https://data.jsdelivr.com/v1/package/gh/designe/euphony.js/badge?style=rounded)](https://www.jsdelivr.com/package/gh/designe/euphony.js) 

Acoustic Data Telecommunication Library. This repository is for Javascript.

## Prerequisite

``` html
<script src='https://cdn.jsdelivr.net/gh/designe/euphony.js/dist/euphony.min.js'></script>

<!-- if you want to use module version of euphony, import this like below.
<script type='module'>
    import {Euphony} from "https://cdn.jsdelivr.net/gh/designe/euphony.js/dist/euphony.m.min.js";
</script>
-->

```

## Usage
```javascript
var euphony = new Euphony();
euphony.setCode("hello, euphony");
euphony.play();

// if you want to stop sound
euphony.stop();
```

## Contributing
Changes are improvements are more than welcome! Feel Free to fork and open a pull request. Please make your changes in a specific branch and request to pull into `master`.

## License
Euphony is licensed under the Apache 2.0 license. (https://github.com/designe/euphony.js/blob/master/LICENSE)
