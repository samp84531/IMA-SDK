# ima-player

React native google ad in video

## Installation

```sh
npm install ima-player
```

## Usage

```js
import { Video } from 'ima-player';
const adTagUrl = "https://pubads.g.doubleclick.net/gampad/ads?sz=640x480&iu=/124319096/external/single_ad_samples&ciu_szs=300x250&impl=s&gdfp_req=1&env=vp&output=vast&unviewed_position_start=1&cust_params=deployment%3Ddevsite%26sample_ct%3Dlinear&correlator="

      <Video
        adTagUrl={adTagUrl}
        source={{
          uri: 'http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4',
          type: 'mp4',
        }}
        style={{ flex: 1 }}
      />

```

## License

MIT
---
