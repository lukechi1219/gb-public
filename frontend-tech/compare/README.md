# 評估前端框架

摘要

**Angular** 提供你生活所需的一切，但靈活性比較差，React 最靈活，Vue 則是沒有太大的靈活性。

* Vue 和 React 提供了比 Angular 更好的性能和靈活性。
* Vue 和 React 更適合於**小型的網頁開發**，而 Angular 則**最適合大型 UI 網頁應用**。
* Angular 提供了所有的功能，而這點與 Vue 和 React 不同，Angular 提供的功能從 routing、templates 到測試的工具，一應俱全。
* Vue 目前是最受歡迎和不斷增長的 Javascript 框架。

**參考網址**[**https://terrylee7788.wordpress.com/2019/10/24/angular-vs-react-vs-vue/**](https://terrylee7788.wordpress.com/2019/10/24/angular-vs-react-vs-vue/)

**企業 前端 框架 趨勢 2018**

\*\*\*\*[**https://www.slideshare.net/WillHuangTW/enterprise-frontend-framework-trend-2018**](https://www.slideshare.net/WillHuangTW/enterprise-frontend-framework-trend-2018)\*\*\*\*

= 評估時 所收集的 相關技術文件 =

\*\*\*\*[**https://drive.google.com/drive/folders/1zyITfajRjZcLLRB4F14OOT8-g7sAAKlz?usp=sharing**](https://drive.google.com/drive/folders/1zyITfajRjZcLLRB4F14OOT8-g7sAAKlz?usp=sharing)\*\*\*\*

**.**

**Vue 3**

\*\*\*\*[**https://blog.darkthread.net/blog/vue-3-release/**](https://blog.darkthread.net/blog/vue-3-release/)\*\*\*\*

**乾貨 分层架构**

\*\*\*\*[**https://github.com/mcuking/mobile-web-best-practice\#%E5%88%86%E5%B1%82%E6%9E%B6%E6%9E%84**](https://github.com/mcuking/mobile-web-best-practice#%E5%88%86%E5%B1%82%E6%9E%B6%E6%9E%84)\*\*\*\*

![](../../.gitbook/assets/image%20%2811%29.png)

**----**

**= 前端框架評估 meeting note =**

**\* 主要換 FE 的理由是 未來要做 個人化  
- 換 FE 雖然 Design 跟 PG 用同一套 , 可以減少以前分兩套的問題  
- 但是開發流程要重新 看過 , 用同一套一起開發 , 更容易被彼此的 bug 影響**

**\* 更遠的目標  
用 BI 做到個人化 , 用數據決定 UI 動態載入**

**- 之後可能一個月開一次會討論**

## **技術重點項目** <a id="tech-issues"></a>

* 支援多白牌 開發 -&gt; multiple them based on URL
* mono-repo or sub project?
  * web
  * h5
  * [https://www.sohu.com/a/343217202\_463970](https://www.sohu.com/a/343217202_463970)
  * [https://juejin.cn/post/6844903961896435720](https://juejin.cn/post/6844903961896435720)
* 支援 template 多版本開發
  * /template/v1
  * /template/v2 歐洲版?

![](../../.gitbook/assets/image%20%286%29.png)

* 學習曲線
* 技術成熟度 / 完整度
  * 工具完整度 -&gt; multi-application, shared UI lib, shared data lib, testing
  * 版本穩定度
* 跟其他 JS 整合 ?
  * Angular not easy to integrate with other js libs
  * gasp 設計在用的動態庫 ?
    * [https://dev.to/timvdeijnden/tweening-with-gsap-inside-vue-1lb1](https://dev.to/timvdeijnden/tweening-with-gsap-inside-vue-1lb1)
    * [https://greensock.com/forums/topic/20112-gsap-angular/](https://greensock.com/forums/topic/20112-gsap-angular/)
    * [https://fragland.dev/using-gsap-tweenmax-with-angular/](https://fragland.dev/using-gsap-tweenmax-with-angular/)
* Angular in web view? -&gt; Native App
  * cookie App-name ?
  * Android
  * iOS
* SEO
  * [https://developers.google.com/search/docs/guides/javascript-seo-basics](https://developers.google.com/search/docs/guides/javascript-seo-basics)
* **.**
* **能不能承受 大量的 loading ? 複雜的個人化 ?**
  * server loading ? 上萬個 線上人數
  * BI 數據 出來後 , 先測試 我們前端能不能 承受 ?
  * 壓力測試
  * shadow DOM / virtual DOM
* **.**
* I18N , L10N
* .
* User Agent -&gt; web/ h5
  * [https://material.angular.io/cdk/platform/examples](https://material.angular.io/cdk/platform/examples)
* 404, 505
* IP limit -&gt; block by Country?
  * [https://www.c-sharpcorner.com/article/how-to-get-the-client-ip-address-in-angular-application/](https://www.c-sharpcorner.com/article/how-to-get-the-client-ip-address-in-angular-application/)
* .
* BO 設定 meta tag 如何在 前端框架 做到?
* BO 設定ga , g tag manager 如何在前端框架 做到? -&gt; Angular SEO
* .
* 對 Mobile 的支援與效能
  * touch event
  * RWD - 手機 , 平板
  * [https://betterprogramming.pub/creating-angular-webapp-for-multiple-views-and-screen-sizes-50fe8a83c433](https://betterprogramming.pub/creating-angular-webapp-for-multiple-views-and-screen-sizes-50fe8a83c433)
  * ?
* 設計框架? -&gt; Material ? for Design
* form validation
  * [https://angular.tw/guide/form-validation](https://angular.tw/guide/form-validation)
* data table
* Animation: fade in/out , transition , transform
  * css animation
  * web animation api
* Nested Routes
  * [https://angular.tw/guide/router\#nesting-routes](https://angular.tw/guide/router#nesting-routes)
  * [https://next.router.vuejs.org/zh/guide/essentials/nested-routes.html](https://next.router.vuejs.org/zh/guide/essentials/nested-routes.html)
    * [https://medium.com/unalai/%E8%AA%8D%E8%AD%98-vue-router-%E5%B5%8C%E5%A5%97%E8%B7%AF%E7%94%B1-nested-routes-8168f5395941](https://medium.com/unalai/%E8%AA%8D%E8%AD%98-vue-router-%E5%B5%8C%E5%A5%97%E8%B7%AF%E7%94%B1-nested-routes-8168f5395941)
* .
* .

## **與 Design 合作重點項目** <a id="cowork-issues"></a>

* PG 跟 Designer 怎麼合作
* 開發流程
* 開發工具
  * pug
  * 設計框架?
  * gasp 設計在用的動態庫
* 測試 / debug
* 發佈流程
* dev / prod / hotfix
  * 開 git 分支與 進行 hotfix流程

## **導入重點項目** <a id="introduce-issues"></a>

* **這項技術 是否可以小區塊 抽換舊的網頁?**
  * **Vue.js 漸進式 ?**
  * **微前端 Micro Front-end -&gt; Web Component?**
  * **瀏覽器支援度 ?**

**.**

<table>
  <thead>
    <tr>
      <th style="text-align:left"><b>&#x9805;&#x76EE;</b>
      </th>
      <th style="text-align:left"><b>Angular</b>
      </th>
      <th style="text-align:left"><b>Vue</b>
      </th>
      <th style="text-align:left"><b>React</b>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">intro</td>
      <td style="text-align:left">
        <p></p>
        <p></p>
        <p>Angular &#x5177;&#x6709;&#x4E0D;&#x540C;&#x7684;&#x8868;&#x9054;&#x5F0F;&#x8A9E;&#x6CD5;&#xFF0C;&#x4E3B;&#x8981;&#x662F;&#x7528; <code>&quot;[ ]&quot;</code> &#x4F86;&#x8868;&#x793A;
          <a
          href="https://zh.wikipedia.org/w/index.php?title=Property_(programming)&amp;action=edit&amp;redlink=1">&#x5C6C;&#x6027;</a>&#x7E6B;&#x7D50;&#xFF0C;&#x4EE5;&#x53CA;&#x7528; <code>&quot;( )&quot;</code> &#x4F86;&#x8868;&#x793A;
            <a
            href="https://zh.wikipedia.org/w/index.php?title=Event_(computing)&amp;action=edit&amp;redlink=1">&#x4E8B;&#x4EF6;</a>&#x7E6B;&#x7D50;</p>
        <p>
          <br />&#x8A31;&#x591A;&#x6838;&#x5FC3;&#x529F;&#x80FD;&#x90FD;&#x5DF2;&#x6A21;&#x7D44;&#x5316;</p>
        <p>
          <br />&#x652F;&#x63F4; Angular Universal&#xFF0C;&#x5B83;&#x53EF;&#x4EE5;&#x5728;&#x4F3A;&#x670D;&#x5668;&#x4E0A;&#x57F7;&#x884C;
          Angular &#x61C9;&#x7528;&#x7A0B;&#x5F0F; - &gt; SEO</p>
        <p></p>
        <p>Angular Material &#x662F;&#x4E00;&#x500B; UI &#x7D44;&#x4EF6;&#x5EAB;&#xFF0C;&#x5B83;&#x5728;
          Angular &#x4E2D;&#x5BE6;&#x73FE;&#x4E86; <a href="https://zh.wikipedia.org/wiki/Material_Design">Material Design</a>&#x3002;</p>
      </td>
      <td style="text-align:left">
        <p>Vue&#x6240;&#x95DC;&#x6CE8;&#x7684;&#x6838;&#x5FC3;&#x662F;MVC&#x6A21;&#x5F0F;&#x4E2D;&#x7684;&#x8996;&#x5716;&#x5C64;&#xFF0C;&#x540C;&#x6642;&#xFF0C;&#x5B83;&#x4E5F;&#x80FD;&#x65B9;&#x4FBF;&#x5730;&#x53D6;&#x5F97;&#x8CC7;&#x6599;&#x66F4;&#x65B0;&#xFF0C;&#x4E26;&#x901A;&#x904E;&#x7D44;&#x4EF6;&#x5167;&#x90E8;&#x7279;&#x5B9A;&#x7684;&#x65B9;&#x6CD5;&#x5BE6;&#x73FE;&#x8996;&#x5716;&#x8207;&#x6A21;&#x578B;&#x7684;&#x4E92;&#x52D5;&#x3002;</p>
        <p></p>
        <p>&#x5728;&#x70BA;AngularJS&#x5DE5;&#x4F5C;&#x4E4B;&#x5F8C;&#xFF0C;Vue&#x7684;&#x4F5C;&#x8005;&#x5C24;&#x96E8;&#x6EAA;&#x958B;&#x767C;&#x51FA;&#x4E86;&#x9019;&#x4E00;&#x6846;&#x67B6;&#x3002;&#x4ED6;&#x8072;&#x7A31;&#x81EA;&#x5DF1;&#x7684;&#x601D;&#x8DEF;&#x662F;&#x63D0;&#x53D6;Angular&#x4E2D;&#x70BA;&#x81EA;&#x5DF1;&#x6240;&#x559C;&#x6B61;&#x7684;&#x90E8;&#x5206;&#xFF0C;&#x69CB;&#x5EFA;&#x51FA;&#x4E00;&#x6B3E;&#x76F8;&#x7576;&#x8F15;&#x91CF;&#x7684;&#x6846;&#x67B6;&#x3002;</p>
      </td>
      <td style="text-align:left"> <b>React</b>&#xFF08;&#x6709;&#x6642;&#x53EB;<b>React.js</b>&#x6216;<b>ReactJS</b>&#xFF09;&#xFF0C;&#x662F;&#x4E00;&#x500B;&#x70BA;&#x8CC7;&#x6599;&#x63D0;&#x4F9B;&#x5F69;&#x73FE;&#x70BA;HTML&#x8996;&#x5716;&#x7684;
        <a
        href="https://zh.wikipedia.org/wiki/%E5%BC%80%E6%BA%90%E8%BD%AF%E4%BB%B6">&#x958B;&#x6E90;</a><a href="https://zh.wikipedia.org/wiki/JavaScript%E5%87%BD%E5%BC%8F%E5%BA%93">JavaScript &#x5EAB;</a>&#x3002;
          <br
          />
          <br />React&#x8996;&#x5716;&#x901A;&#x5E38;&#x63A1;&#x7528;&#x5305;&#x542B;&#x4EE5;&#x81EA;&#x8A02;HTML&#x6A19;&#x8A18;&#x898F;&#x5B9A;&#x7684;&#x5176;&#x4ED6;&#x7D44;&#x4EF6;&#x7684;&#x7D44;&#x4EF6;&#x5F69;&#x73FE;&#x3002;
          <br
          />
          <br />React&#x70BA;&#x7A0B;&#x5F0F;&#x8A2D;&#x8A08;&#x5E2B;&#x63D0;&#x4F9B;&#x4E86;&#x4E00;&#x7A2E;&#x5B50;&#x7D44;&#x4EF6;&#x4E0D;&#x80FD;&#x76F4;&#x63A5;&#x5F71;&#x97FF;&#x5916;&#x5C64;&#x7D44;&#x4EF6;&#xFF08;&quot;data
          flows down&quot;&#xFF09;&#x7684;&#x6A21;&#x578B;&#xFF0C;
          <br />
          <br />&#x8CC7;&#x6599;&#x6539;&#x8B8A;&#x6642;&#x5C0D;HTML&#x6587;&#x4EF6;&#x7684;&#x6709;&#x6548;&#x66F4;&#x65B0;&#xFF0C;&#x548C;&#x73FE;&#x4EE3;&#x55AE;&#x9801;&#x61C9;&#x7528;&#x4E2D;&#x7D44;&#x4EF6;&#x4E4B;&#x9593;&#x4E7E;&#x6DE8;&#x7684;&#x5206;&#x96E2;&#x3002;</td>
    </tr>
    <tr>
      <td style="text-align:left">template or js-based</td>
      <td style="text-align:left">template</td>
      <td style="text-align:left">template</td>
      <td style="text-align:left">js</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>&#x7248;&#x672C;&#x66F4;&#x65B0;</b>
      </td>
      <td style="text-align:left">&#x6BCF;&#x4E00;&#x500B;&#x7248;&#x672C;&#x90FD;&#x6703;<b>&#x5411;&#x4E0B;&#x76F8;&#x5BB9;&#x524D;&#x4E00;&#x500B;&#x7248;&#x672C;<br /></b>
        <br
        />Google &#x627F;&#x8AFE;&#x6BCF;&#x5E74;&#x6703;&#x9032;&#x884C;&#x5169;&#x6B21;&#x5347;&#x7D1A;&#x3002;</td>
      <td
      style="text-align:left">2020 &#x525B;&#x63D0;&#x51FA; Vue 3.0 &#x5347;&#x7D1A;</td>
        <td style="text-align:left">?</td>
    </tr>
    <tr>
      <td style="text-align:left">Typescript</td>
      <td style="text-align:left">yes</td>
      <td style="text-align:left">yes</td>
      <td style="text-align:left">yes</td>
    </tr>
    <tr>
      <td style="text-align:left">CLI</td>
      <td style="text-align:left">100%</td>
      <td style="text-align:left">50%</td>
      <td style="text-align:left">25% ?</td>
    </tr>
    <tr>
      <td style="text-align:left">DOM</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>SEO</b>
      </td>
      <td style="text-align:left">yes</td>
      <td style="text-align:left">?</td>
      <td style="text-align:left">?</td>
    </tr>
    <tr>
      <td style="text-align:left">Material or Bootstrip?</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"><b>&#x5C0D; Mobile &#x7684;&#x652F;&#x63F4;&#x8207;&#x6548;&#x80FD;</b>
      </td>
      <td style="text-align:left">&#x6709;</td>
      <td style="text-align:left">?</td>
      <td style="text-align:left">?</td>
    </tr>
    <tr>
      <td style="text-align:left">I18N , L10N</td>
      <td style="text-align:left">yes</td>
      <td style="text-align:left">?</td>
      <td style="text-align:left">?</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <p>&#x652F;&#x63F4;&#x591A;&#x767D;&#x724C; &#x958B;&#x767C;?</p>
        <p></p>
        <p>site folder?</p>
        <p>css &#x5207;&#x63DB;?</p>
        <p>&#x5171;&#x7528;&#x5716;&#x7247;?</p>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>



