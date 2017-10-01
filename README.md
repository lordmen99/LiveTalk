

### Installation
- ```git clone``` the code

- Import Module from Android Studio with [vitamio](https://github.com/yixia/VitamioBundle/vitamio) and name as ```vitamio```

- Import Module from [ossrs](https://github.com/begeekmyfriend/yasea) and name as ```ors.yasea```

### Screenshots
<div>
<img width=256 src="https://dl2.pushbulletusercontent.com/WolTqTEF6nak2SmTrAI35xOcifZotdnm/Screenshot_2017-10-01-15-43-10-419_fudreamer.com.livetalk.png" />
<img width=256 src="https://i.imgur.com/qUldsDx.jpg" />
</div>

### How to use

- Choose your role (Publisher or Subscriber)

- Input your RTMP Server's location

```rtmp://10.0.3.2/live/stream //if inside genymotion```

- Click ```Publish``` Button if you are publisher

- Subscriber can See the RTMP stream content came from Publisher


### Use Opensources 

[vitamio](https://github.com/yixia/VitamioBundle)

[ossrs](https://github.com/begeekmyfriend/yasea)


Test
-----
Subscriber: GenyMotion Google Nexus 5X API Level 23 Android 6.0.1

Publisher: Xiaomi Note 2 Android 6.0.0

Others
---
```java
mVideoView.setBufferSize(1024); // reduce the buffer size can shorten the RTMP latency
```

Know Issues
---
https://github.com/yixia/VitamioBundle/issues/321
> ...maybe replace vitamio

TODO
---
- [ ] Replace Vitamio, because of continus playing make cause accumulated buffer and lead to latency issue  
- [ ] Add Chat came from subscriber
- [ ] Check Streaming Audio is fine