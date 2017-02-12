[![npm version](https://badge.fury.io/js/angular2-debounce.svg)](https://www.npmjs.com/package/angular2-debounce)

# angular2-debounce

***angular2-debounce*** is an Angular2 directive that adds a debounce to your input fields.

It delays the start of a function call after every keyup -event.

## Installation:

```bash
npm install angular2-debounce --save
```

## Use Example:

Add the declaration to your @NgModule:

```typescript
import {Debounce} from 'angular2-debounce';

...

@NgModule({
  declarations: [
    Debounce
  ]
})
```

Use directly inside your HTML templates

```
<input debounce [delay]="700" (func)="myDebouncedFunction()" [(ngModel)]="..." name="Debounce input" class="form-control input-sm">
```

## Author

[Miro Metsänheimo](https://miro.metsanheimo.fi)

## Licence

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
