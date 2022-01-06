# Angular Nx SSR (prerender) Transloco

npm install -g @angular/cli

npm install -g @nrwl/schematics

## Angular

ng new {app}

## Angular Nx

https://jareddesign.medium.com/angular-universal-server-side-rendering-ssr-in-nrwl-nx-fdb94d7953e

npx create-nx-workspace@latest

npx create-nx-workspace@12.10.1

npm i create-nx-workspace@12.10.1

## SSR

ng add @nguniversal/express-engine

~~ng add @nguniversal/express-engine --clientProject=toh~~

~~npx ng add @nguniversal/express-engine~~

~~npx ng add @nguniversal/express-engine --clientProject=toh~~
npx ng add @nguniversal/express-engine --clientProject toh

npm install @nguniversal/express-engine

npx nx g @nguniversal/express-engine:ng-add

## SSR (prerender)

## Transloco

```
@Injectable({ providedIn: 'root' })
export class TranslocoServerHttpLoader implements TranslocoLoader {
  isBrowser: boolean;

  constructor(@Inject(PLATFORM_ID) platformId: Object, private http: HttpClient) {
    this.isBrowser = isPlatformBrowser(platformId);
  }

  getTranslation(lang: string): Observable<Translation> {
    console.log('getTranslation');
    console.log(`this.isBrowser: ${ this.isBrowser }`);

    return of(JSON.parse(readFileSync(`./src/assets/i18n/${ lang }.json`, 'utf8')));
  }
}
```
