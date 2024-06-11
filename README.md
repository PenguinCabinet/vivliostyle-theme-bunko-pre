# Bunko-pre

A theme that support pre text.     
Forked by the [bunko theme for Vivliostyle](https://github.com/PenguinCabinet/vivliostyle-themes/tree/main/packages/@vivliostyle/theme-bunko).

[文庫用のテーマ](https://github.com/PenguinCabinet/vivliostyle-themes/tree/main/packages/@vivliostyle/theme-bunko)を、preテキストに対応したテーマ。

## Use

In `vivliostyle.config.js`:

```js
module.exports = {
  theme: '@penguincabinet/vivliostyle-theme-bunko-pre',
};
```

## Differences from the original
For more details, please see [the example](https://raw.githubusercontent.com/PenguinCabinet/vivliostyle-theme-bunko-pre/main/example/bunko.md).
### A samples of the original bunko theme
```markdown
「ではみなさんは、そういうふうに川だと{云|い}われたり、乳の流れたあとだと云われたりしていたこのぼんやりと白いものがほんとうは何かご承知ですか。」先生は、黒板に{吊|つる}した大きな黒い星座の図の、上から下へ白くけぶった銀河帯のようなところを{指|さ}しながら、みんなに{問|とい}をかけました。

カムパネルラが手をあげました。それから四五人手をあげました。ジョバンニも手をあげようとして、急いでそのままやめました。たしかにあれがみんな星だと、いつか雑誌で読んだのでしたが、このごろはジョバンニはまるで毎日教室でもねむく、本を読むひまも読む本もないので、なんだかどんなこともよくわからないという気持ちがするのでした。

ところが先生は早くもそれを{見附|みつ}けたのでした。
```
### Equivalent
```
「ではみなさんは、そういうふうに川だと{云|い}われたり、乳の流れたあとだと云われたりしていたこのぼんやりと白いものがほんとうは何かご承知ですか。」先生は、黒板に{吊|つる}した大きな黒い星座の図の、上から下へ白くけぶった銀河帯のようなところを{指|さ}しながら、みんなに{問|とい}をかけました。
　カムパネルラが手をあげました。それから四五人手をあげました。ジョバンニも手をあげようとして、急いでそのままやめました。たしかにあれがみんな星だと、いつか雑誌で読んだのでしたが、このごろはジョバンニはまるで毎日教室でもねむく、本を読むひまも読む本もないので、なんだかどんなこともよくわからないという気持ちがするのでした。
　ところが先生は早くもそれを{見附|みつ}けたのでした。
```

## Available theme CSS variables

```css
:root {
  /**
   *  Number of lines per page/Number of characters per line
   */
  --vs-theme--num-of-line: 15;
  --vs-theme--num-of-character: 39;
  /**
   *  Content to be displayed in the upper left/upper right corner of the page spread
   */
  --vs-theme--page-top-left-content: counter(page) '　' env(doc-title);
  --vs-theme--page-top-right-content: counter(page);
  /**
   *  Indent size of subsection
   */
  --vs-theme--subsection-text-indent: 3rem;
  /**
   *  Color of anchor texts on screen media
   */
  --vs-theme--anchor-color-body: darkblue;
}
```

## License

> author: PenguinCabinet
