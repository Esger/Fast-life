# `bugs-life`

This project is bootstrapped by [aurelia-cli](https://github.com/aurelia/cli).

For more information, go to https://aurelia.io/docs/cli/cli-bundler

## Run dev app

Run `au run`, then open `http://localhost:9000`

To open browser automatically, do `au run --open`.

To change dev server port, do `au run --port 8888`.

To change dev server host, do `au run --host 127.0.0.1`

To install new npm packages automatically, do `au run --auto-install`

**PS:** You could mix all the flags as well, `au run --host 127.0.0.1 --port 7070 --open`

## Build for production

Run `au build --env prod`.

<h1>Fast Life</h1>
<h2>Pushing Aurelia JS to speed</h2>
<p>Conway's Game Of Life has been a vehicle to learn new things to me for many years; here I&rsquo;m experimenting to see if Aurelia can match a <a href="https://www.ashware.nl/graylife" target="_blank">Vanilla js version</a> &mdash; It does. Take look at <a href="https://nl.wikipedia.org/wiki/Game_of_Life" target="_blank">this wikipedia page for a description of GOL</a></p>
<p>The modular nature of Aurelia invited me to enhance the UI / layout as well.</p>
<h2>Features</h2>
<ul>
  <li>Easy buttons to experiment with the rules</li>
  <li>Rule presets that sync with your own settings - if there&rsquo;s a match</li>
  <li>Adjustable cell size</li>
  <li>Draw cells yourself</li>
  <li>Optional &lsquo;trails&rsquo; to smooth things out</li>
  <li>Slow life with slider or hover over the canvas</li>
  <li>Grid for drawing life cells more precisely</li>
  <li>Web-worker for computing of life generations</li>
  <li>Optionally stop heavy computing automatically when Life get's stable</li>
</ul>
<p>Don't hesitate to check out my other games and projects at <a href="https://www.ashware.nl" target="_blank">ashWare.nl</a></p>
