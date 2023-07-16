## Namaste React Course by Akshay Saini
# _Chapter 02 - Igniting our App_

# what is module-bundler
- A bundler is a development tool that combines many JavaScript code files into a single one that is production-ready loadable in the browser. A fantastic feature of a bundler is that it generates a dependency graph


# we have multiple module-bundlers like parcel, webpack,browserify,esbuild, rollup etc

# parcel
- Dev build
- Local server
- HMR = Hot module reload
- File watching algorithrm  - written in c++
- caching - building faster
- Image optimization
- minification
- bundling
- compressing
- Consistent hashing
- code splitting
- Diffrential bundling - to support older browsers
- Tree shaking algo - remove unused functions
- Diffrent dev and prod bundles



## Coding Assignment:
- In your `existing project`
    - initialize `npm` into your repo
    - install `react` and `react-dom`
    - `remove CDN links` of `react`
    - `install parcel`
    - `ignite your app` with `parcel`
    - `add scripts` for `“start”` and `“build”` with `parcel commands`
    - add `.gitignore` file
    - add `browserlists`
    - build a production version of your code using `parcel build`


## References:
- [Creating your own create-react-app](https://medium.com/@JedaiSaboteur/creating-a-react-app-from-scratch-f3c693b84658)
- [Parcel Documentation](https://parceljs.org/getting-started/webapp/)
- [Parcel on Production](https://parceljs.org/features/production/)
- [BrowsersList](https://browserslist.dev/)