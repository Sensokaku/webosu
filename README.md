# Webosu!

A browser rhythm game where players click circles following rhythm of the music.

Powered by [PixiJS](https://www.pixijs.com). Beatmap source: [Sayobot](https://osu.sayobot.cn).

Note: This is an unofficial implementation of [osu!](https://osu.ppy.sh). Scoring and judgement rules differ from official versions. Some music might not be perfectly syncing. Modes other than osu! (std) are unsupported.

## Screenshots

web page:

![webpage](screenshots/page3.png)

game in action:

![webpage](screenshots/clip3.gif)

## Hosting

Set up a web server with root directory located where `index.html` is in.

To host a separate live score, redirect send/fetch api requests to localhost:4000/4001 respectively, and change the api url in `index.html` and `scripts/overlay/score.js` accordingly. Then run:

```bash
nohup node api.js &
```

## Todos/Coming soon

- beatmap hitsounds
- user system 
- some extra fixing/tweaks

## License Notes

Some media files are copyrighted by [ppy](https://github.com/ppy/) and other people. Check their respective license before you use them.
