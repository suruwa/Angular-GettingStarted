
## Eksport typu, na podstawie modułów ES 2015:
```
export class Product {

}
```

## Import tego samego typu
```
import { Product } from './product'
```

product.ts jest transpilowany do product.js, stąd `import { Product } from './product'`, bez podania rozszerzenia

## Moduły Angular (modularna aplikacja) != Moduły ES 2015 (modu ł per plik)
 
## Komponenty składaja się importów, dekoratora @Component (metadata) oraz klasy (export class ...)

ES 2015 backticks ` - tekst w wielu liniach

dyrektywy strukturalne posiadają gwiazdkę z przodu

ES 2015 for ... of vs for ... in - for of iteruje po elementach tabeli itd, for in iteruje po propercjach obiektu

property binding < img [src]="costa">

interpolation < img src="{{costa}}"> 

event binding < img (click)="costam" >

two way binding: < input [(ngModel)]='costam'>

komponent rodzic przekazuje dane do komponentu dziecka za pomocą properties
komponent dziecko przekazuje informacje do rodzica za pomocą eventów
WIĘCEJ O KOMUNIKACJI MIĘDZY KOMPONENTAMI!!! (Pluralsight - Angular Component Communication?)