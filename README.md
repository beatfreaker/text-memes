# text-meme

`<text-meme>` is a polymer element that generate text memes.

<img src="meme.gif" alt="text meme" width="300">

Example:
```html
<text-meme delay="600" text="Don't forget to be Awesome."></text-meme>

<text-meme delay="600" text="Set Goal Reach Repeat." background="#396767"></text-meme>

<text-meme delay="600" text="Make today ridiculously amazing" background="#79fffc" fontcolor="#333e48"></text-meme>

<text-meme delay="600" text="One of the greatest pleasures in life is doing what other say you can't -SindreSorhus" width="300" height="300" fontsize="25"></text-meme>
```

## Options
```
--text          Text for which text-meme to be generated [Default: Don't forget to be Awesome.]
--delay         Frame delay [Default: 400]
--background    Background color in hex [Default: random]
--fontcolor     Text color in hex [Default: #ffffff]
--fontsize      Text size [Default: 30]
--width         Width of the image [Default: 400]
--height        Height of the image [Default: 400]
```

## Usage
Install with bower:
```
mkdir text-meme
cd text-meme
bower install text-meme
```
import it in your page
```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, minimum-scale=1.0, initial-scale=1.0, user-scalable=yes">
    <title>Text Meme</title>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="text-meme.html">
  </head>
  <body>
    <p>An example of <code>&lt;text-meme&gt;</code>:</p>
    <text-meme delay="600" text="Don't forget to be Awesome."></text-meme>
  </body>
</html>
```

## Related

- [text-meme](https://github.com/beatfreaker/text-meme) - node.js API to generate text-meme.
- [text-meme-cli](https://github.com/beatfreaker/text-meme-cli) - CLI utility to generate text-meme.
- [slate](https://github.com/bitshadow/slate) - Inspiration for this module.

## License

MIT © [beatfreaker](https://beatfreaker.github.io)