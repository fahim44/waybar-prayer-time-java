# Muslim Prayer time for waybar

This is my personal script to show prayer time in the waybar. This is an extension of [PrayTimes Java Impl](http://praytimes.org/code/git/?a=viewblob&p=PrayTimes&h=093f77d6cc83b53fb12e9900803d5fa75dacd110&hb=HEAD&f=v1/java/PrayTime.java)

### Waybar config:
```
    "custom/prayerTime": {
        "format": "{}",
        "tooltip": true,
        "interval": 3600,
        "exec": "path-to-java/java /path-to-script/PrayTime.java",
        "return-type": "json"
    },
```
