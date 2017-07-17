# haxe-iso4217

- ISO 4217:2015 data as of 2017-06-09
- all data is available at: https://www.currency-iso.org

# haxe usage
```haxe
import iso4217.CurrencyCode;
import iso4217.Currencies;
import iso4217.UnitConverter;

trace(EUR.minorToMajor(1234));
trace(Currencies.fromCode('EUR').minorToMajor(1234));
```

# js setup
```bash
npm install @psmtec/iso4217
```

# js usage
```js
import { UnitConverter } from '@psmtec/iso4217';

console.log(UnitConverter.minorToMajor('EUR', 123456));
```
