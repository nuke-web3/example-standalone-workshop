
# Substrate Workshop

...

## Developer Notes on this repo

Using base node template as (squashed) git subtree to track upstream changes.

> how-to https://www.youtube.com/watch?v=sC1sfoCo5qY

```bash
# add the template
git subtree add --prefix=base-node --squash https://github.com/substrate-developer-hub/substrate-node-template

# Update the template
git subtree merge -P --squash <tag, branch, or commit hash>
```

## TODO

- [ ] make a PWA: https://docsify.js.org/#/pwa
- [ ] customize to branded right: https://jhildenbiddle.github.io/docsify-themeable/#/customization?id=theme-styles 
- [ ] md styling and features: https://jhildenbiddle.github.io/docsify-themeable/#/markdown
- [ ] dark & light theme: https://github.com/jhildenbiddle/docsify-themeable/blob/master/docs/assets/js/main.js
- [ ] 
- [ ] 
- [ ] 
- [ ] 


**Acknowledgements:** 
- Based on the [ETHDenver 2022 Workshop](https://github.com/sacha-l/collectables-ethdenver-workshop) {[MIT](https://github.com/sacha-l/collectables-ethdenver-workshop/blob/master/LICENSE)}, inspired by the [crypto zombies tutorial](https://cryptozombies.io/en/lesson/1/chapter/1).
- Source heavily influenced by [the `docsify-themeable` demo](https://github.com/jhildenbiddle/docsify-themeable/tree/master/docs)