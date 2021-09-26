# Angular + Pug

.

final 

[https://www.npmjs.com/package/ng-cli-pug-loader](https://www.npmjs.com/package/ng-cli-pug-loader)

[https://www.npmjs.com/package/pug-plugin-ng](https://www.npmjs.com/package/pug-plugin-ng)

[https://github.com/danguilherme/ng-cli-pug-loader/issues/38](https://github.com/danguilherme/ng-cli-pug-loader/issues/38)

1. Instead of using `ng add ng-cli-pug-loader`, you will have to install project dependency and script for pug manually.

* First, install dependency with this command `npm install apply-loader@~2.0.0 pug-loader@~2.4.0 pug@~2.0.3 --save-dev`
* Create new script file `ng-add-pug-loader.js` in your project. You can find the initial for the file content [here](https://github.com/danguilherme/ng-cli-pug-loader/blob/master/src/files/ng-add-pug-loader.js).
* Open the file, find and replace the content for some variables as below:

```text
const commonCliConfig = 'node_modules/@angular-devkit/build-angular/src/webpack/configs/common.js';
const pugRules = '{test:/\\.(pug|jade)$/,exclude:/\\.(include|partial)\\.(pug|jade)$/,use:[{loader:"apply-loader" },{loader:"pug-loader"}]},{test:/\\.(include|partial)\\.(pug|jade)$/,loader:"pug-loader"},';
const typescriptCliConfig = 'node_modules/@angular-devkit/build-angular/src/webpack/configs/typescript.js';
```

* Open your `package.json`, add `"postinstall": "node ./ng-add-pug-loader.js"` in the `scripts` section.

1. Run `npm i` command.

{% embed url="https://www.smashingmagazine.com/2020/05/angular-templates-pug/" %}

.

[https://www.smashingmagazine.com/2020/05/angular-templates-pug/](https://www.smashingmagazine.com/2020/05/angular-templates-pug/)

[https://hackernoon.com/using-pug-jade-with-angular-with-cli-5592b7ee24e6](https://hackernoon.com/using-pug-jade-with-angular-with-cli-5592b7ee24e6)

[https://www.hebergementwebs.com/news/using-docker-docker-compose-angular-cli-6-sass-and-pug-jade](https://www.hebergementwebs.com/news/using-docker-docker-compose-angular-cli-6-sass-and-pug-jade)

[https://www.npmjs.com/package/ng-cli-pug-loader](https://www.npmjs.com/package/ng-cli-pug-loader)

[https://github.com/danguilherme/ng-cli-pug-loader/issues/38](https://github.com/danguilherme/ng-cli-pug-loader/issues/38)

.

