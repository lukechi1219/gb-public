# Angular SEO

.

* BO 設定ga , g tag manager 如何在前端框架 做到? -&gt; Angular SEO
  * [https://medium.com/swlh/angular-include-google-tag-manager-with-analytics-bd24fb74b4fc](https://medium.com/swlh/angular-include-google-tag-manager-with-analytics-bd24fb74b4fc)
  * [https://medium.com/quick-code/set-up-analytics-on-an-angular-app-via-google-tag-manager-5c5b31e6f41](https://medium.com/quick-code/set-up-analytics-on-an-angular-app-via-google-tag-manager-5c5b31e6f41)
  * .
  * use environment.prod.ts
  * [https://www.ngdevelop.tech/integrate-google-analytics-with-angular-angular-seo/](https://www.ngdevelop.tech/integrate-google-analytics-with-angular-angular-seo/)
  * [https://medium.com/veyotech/using-angular-environments-to-configure-multiple-segment-sources-3e4ce6897a3](https://medium.com/veyotech/using-angular-environments-to-configure-multiple-segment-sources-3e4ce6897a3)
  * .
  *  If you are using angular with a docker image container and trying to inject _tracking id_ from a config map as an environment variable, this how-to can be suitable for you.
  * [http://www.inferom.com/angular-dynamic-google-analytics-tracking-id-for-every-environment/](http://www.inferom.com/angular-dynamic-google-analytics-tracking-id-for-every-environment/)

```text
<script async src="https://www.googletagmanager.com/gtag/js"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
</script>
app.component.ts

declare const gtag: Function;

constructor() {
  gtag('config', environment.google.analytics.tracking_id, {app_version: environment.appVersion});
}
```

.

