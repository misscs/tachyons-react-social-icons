# tachyons-react-social-icons

A set of beautiful svg social icons.  Easily used in React.  Uses Tacyhons classes for styling. No inline styles.No images. AMP compliant.

 Svg paths provided by Squarespace.

![social network icons](http://i.imgur.com/RoIt9OD.png)

## Install

```
npm install tachyons-react-social-icons --save-dev
```

## Usage

Pass in the `url` prop of your social network, and the icon will be rendered.

```js
import React from 'react';
import ReactDOM from 'react-dom';
import { SocialIcon } from 'react-social-icons';
ReactDOM.render(<SocialIcon url="http://twitter.com/misscs" />, document.body);
```

See more [usage options on the example site](http://misscs.github.io/tachyons-react-social-icons/).

## Rebuild Examples

```
git checkout gh-pages
git rebase master
sh scripts/gen-gh-pages.sh
```
