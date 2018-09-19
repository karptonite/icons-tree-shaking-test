# IconsTest

## testing webpack bundle analyzer

install with `yarn`.

run `yarn run build:stats`. See the stats with `yarn run bundle-report`.

then edit `icons.ts` as instructed in the comment, and build stats (and look at the report) again.

The main.ts will show an extra nearly 400kb from free-brands-svg-icons, even though, because of tree shaking, the actual built js file will be the same size as before.