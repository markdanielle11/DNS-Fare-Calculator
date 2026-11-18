# DNS Sukli

Fare at sukli calculator para sa **Diesel n' Steel** (Roblox). Pindutin lang ang route, sakayan, destinasyon, bilang ng pasahero, discount, at binayad. Lalabas agad ang fare at ang sukli.

Hindi ito opisyal na tool. Walang kinalaman ang project na ito sa Roblox o sa gumawa ng Diesel n' Steel.

## Paano gamitin

1. Piliin ang **Route** (Balagtas, Guiguinto, o Malolos).
2. **Sakay**: Terminal kung nakapila sila sa terminal. Kung hindi, piliin ang barangay kung saan sumakay.
3. **Pupunta**: piliin ang destinasyon.
4. **Pasahero**: 1 hanggang 5. **Discount**: Regular o Discount (para sa lahat ng pasahero sa isang bayad).
5. **Binayad**: ₱20, ₱50, ₱100, o i-type ang ibang halaga (hanggang ₱100).
6. Basahin ang **Sukli**. Pindutin ang **Susunod** para sa bagong pasahero.

### Keyboard (PC)

| Susi | Gawa |
| --- | --- |
| 1 hanggang 5 | Bilang ng pasahero |
| Z | Regular o Discount |
| S | Terminal o hindi |
| Q, W, E | ₱20, ₱50, ₱100 |
| Enter | Susunod na pasahero |

## Paano kinukuwenta ang fare

Batay sa [Fare Matrix](https://dieselns.fandom.com/wiki/Fare_Matrix) ng Diesel n' Steel wiki:

- ₱14 ang minimum fare para sa unang apat na barangay.
- Dagdag ₱2 kada barangay pagkatapos.
- ₱2 ang bawas ng Student at Senior.
- Kapag nasa terminal ang pasahero, binibilang mula sa dulo ng route.
- Kapag hindi, binibilang mula sa sakayan hanggang sa bababaan, kasama ang dalawang barangay.

Paalala: ang fare ng mga pasaherong sumakay sa gitna ng route ay hindi nakasulat sa wiki. Ito ay kinuwenta gamit ang parehong rule at hindi pa na-verify sa laro. Kung may nakita kang ibang presyo, mag-open ng issue o ng pull request.

Ang mga fare ng Malolos at Guiguinto ay kinuwenta rin gamit ang rule dahil putol ang nakuhang bersyon ng wiki. I-check sa laro kung may nagbago.

## I-run

Walang build step. Isang `index.html` lang ang buong app.

```
open index.html
```

O i-host sa GitHub Pages: **Settings**, **Pages**, **Deploy from a branch**, branch `main`, folder `/ (root)`.

## Lisensya

MIT. Tingnan ang `LICENSE`.
