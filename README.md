# RefUp!

Reference up your typescript output to get rid of the pesky Uncaught ReferenceError.

## Open source notice

This project is open to updates by its users, I ensure that PRs are relevant to the community.
In other words, if you find a bug or want a new feature, please help us by becoming one of the
[contributors](#contributors-) ✌️ ! See the [contributing section](#contributing).

## Like this module? ❤

Please consider:

- [Buying me a coffee](https://www.buymeacoffee.com/jeanlescure) ☕
- Supporting me on [Patreon](https://www.patreon.com/jeanlescure) 🏆
- Starring this repo on [Github](https://github.com/jeanlescure/short-unique-id) 🌟

## Install

```
npm install -g refup
```

## Usage

```bash
# if file has export default
refup dist/short-unique-id.js ShortUniqueId

# if file has only named exports
refup dist/multi-replace.js MultiReplace --no-default
```
