<p align="center">
  <img alt="style-it-themes-logo" src="https://cdn.rawgit.com/style-it-themes/style-it-themes-logos/864bb0c047a612c2c07089901e33d33199c81ef9/style-it-themes-logo-full.svg" width="580">
</p>
<br>
<h2 align="center"><strong>Gitter Inspired Dark</strong></h2>
<p align="center">
  <a href="https://discord.gg/MhwZjV">
    <img src="https://img.shields.io/badge/style--it--themes-discord%20channel-blue.svg?style=for-the-badge" alt="Style-it-themes Discord Channel">
  </a>
</p>

## About

The *Gitter Inspired Dark* theme is a Gitter instant messaging service dark style,
that refines styling throughout all elements and areas.

## Sites Covered

| Site Name                      | Partial            | Full               |
| ------------------------------ | ------------------ | ------------------ |
| [Gitter IM](https://gitter.im) |                    | :heavy_check_mark: |

:asterisk: Full coverage entails styled while using a free open source account,
its not bug free, there possible are elements that were likely missed.

## Installing

#### Using a browser extension:

* Stylus - get the addon for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) and [Opera](https://addons.opera.com/en-gb/extensions/details/stylus/).

#### Then install this style using:  
:arrow_right: [userstyles.org](https://userstyles.org/styles/160316)  
:arrow_right: [![INSTALL DIRECTLY WITH - STYLUS Stylus](https://img.shields.io/badge/Install_directly_with-Stylus-21d1d0.svg?longCache=true&style=for-the-badge)](https://github.com/style-it-themes/gitter-inspired-dark/raw/master/gitter-inspired-dark.user.css)
  >This is only available using Stylus (see the [documentation](https://github.com/openstyles/stylus/wiki/Usercss)). :tada:

:arrow_right: [Manually](https://raw.githubusercontent.com/style-it-themes/gitter-inspired-dark/master/gitter-inspired-dark.css) into the editor.  
  >Please refer to the [installation documentation](https://github.com/style-it-themes/gitter-inspired-dark/wiki/Install) for more details.

## I Found a Bug

At the first instance of finding a bug, have a look if there is already an open issue, if so add the required information as described in the [issue template](.github/ISSUE_TEMPLATE.md).

If your issue is new, please [open an issue](https://github.com/style-it-themes/gitter-inspired-dark/issues/new) and report your problem.

## Contributing

At this time any help is appreciated, so if you can help fix a bug or improve the *Gitter Inspired Dark theme*, just open a pull request to start the ball rolling.

You will need to ideally:

* [Fork](https://github.com/style-it-themes/gitter-inspired-dark/fork) the project.

* Limit to the [K&R (KNF variation style)](https://en.wikipedia.org/wiki/Indentation_style#Variant:_BSD_KNF), and **2 SPACE INDENTATION** (no tabs, and no less than 2 spaces).

* K&R - KNF Variation Example:
  ```css
  element[attr='value'] {
  ··property: value;
  }
  ```

* **Not Allman**
  ```css
  element[property='value']
  {
  ··property: value;
  }
  ```

* Strict space between the `selector` and the `{`:
  ```css
  /* good */
  element[attr='value'] { }

  /* bad */
  element[attr='value']{ }
  ```

* 2 Space indentation
  ```css
  /* good */
  ··property: value;

  /* bad */
  ····property: value;
  ----property: value;
  ·property: value;
  ```

:asterisk: Try to wrap lines at around 80 characters.

### Development Scripts

* `npm run clean`: Runs the Perfectionist script, cleans up after it and fixes some CSS via Stylelint.
* `npm run eslint`: Lint the JavaScript code in the `tools` directory.
* `npm run lint`: Run ESlint & Stylelint scripts.
* `npm run major`: Creates a semantic major release.
* `npm run minor`: Creates a semantic minor release.
* `npm run patch`: Creates a semantic patch release.
* `npm run perfectionist`: Runs Perfectionist only. The CSS is not cleaned/fixed!
* `npm run stylelint`: Run stylelint on the CSS file.
* `npm run lintfix`: Run stylelint with `--fix` on the CSS file.
* `npm run test`: Same as `npm run lint`.
* `npm run update`: Update development dependencies.

## Screens

![gitter home](/screens/Home-Gitter.png)

![gitter explore](/screens/Explore-Gitter.png)

![gitter explore](/screens/gitterHQ-Chat.png)

:asterisk: More screenshots available in [screens directory](/screens) for your perusal.

[![CC-BY-SA-4.0](https://img.shields.io/badge/License-CC--BY--SA--4.0-blue.svg?longCache=true&style=for-the-badge)](LICENSE)
