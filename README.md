<div align="center">
  <h1>eslint-config-jonathanpalma 🛠️</h1>

  <p>These are my personal ESLint rules that I use in my project. Feel free to use them</p>
</div>

<hr />


[![Version][version-badge]][package]
[![Install Size][size-badge]][package-size]
[![Downloads][downloads-badge]][npmcharts]
[![PRs Welcome][prs-badge]][prs]
[![MIT License][license-badge]][license]

[![Watch on GitHub][github-watch-badge]][github-watch]
[![Star on GitHub][github-star-badge]][github-star]
[![Tweet][twitter-badge]][twitter]



## Usage

Install the conventions by running:

```
npm install --save-dev eslint eslint-config-jonathanpalma
```

Then add the extends to your `.eslintrc`:

```javascript
{
  "extends": "jonathanpalma",
  "rules": {
    // rules you want to override
  },
  "settings": {
    "import/resolver": {
      "node": {
        "paths": ["src"]
      }
    }
  }
}
```


## LICENSE

MIT

[downloads-badge]: https://img.shields.io/npm/dm/eslint-config-jonathanpalma.svg?style=flat-square
[license-badge]: https://img.shields.io/npm/l/eslint-config-jonathanpalma.svg?style=flat-square
[license]: https://github.com/jonathanpalma/eslint-config-jonathanpalma/blob/master/LICENSE
[npmcharts]: http://npmcharts.com/compare/eslint-config-jonathanpalma
[package-size]: https://packagephobia.now.sh/result?p=eslint-config-jonathanpalma
[package]: https://www.npmjs.com/package/eslint-config-jonathanpalma
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[size-badge]: https://flat.badgen.net/packagephobia/install/eslint-config-jonathanpalma
[version-badge]: https://img.shields.io/npm/v/eslint-config-jonathanpalma.svg?style=flat-square

[github-watch-badge]: https://img.shields.io/github/watchers/jonathanpalma/eslint-config-jonathanpalma.svg?style=social
[github-watch]: https://github.com/jonathanpalma/eslint-config-jonathanpalma/watchers
[github-star-badge]: https://img.shields.io/github/stars/jonathanpalma/eslint-config-jonathanpalma.svg?style=social
[github-star]: https://github.com/jonathanpalma/eslint-config-jonathanpalma/stargazers
[twitter]: https://twitter.com/intent/tweet?text=Check%20out%20eslint-config-jonathanpalma!%20https://github.com/jonathanpalma/eslint-config-jonathanpalma
[twitter-badge]: https://img.shields.io/twitter/url/https/github.com/jonathanpalma/eslint-config-jonathanpalma.svg?style=social
