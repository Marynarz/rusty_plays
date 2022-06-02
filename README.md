# Rust - nauka!

## Budowanie
* formatowanie: ``` rustfmt <nazwa-pliku> ```
* kompilowanie: ``` rustc <nazwa-pliku> ```

## Struktura
* Funkcja Głowna:
``` fn main() {} ```

## Cargo
Menadżer do tworzenia projektów w RUST. Zarządza wersjami, zależnościami, budowanie itp.

### Tworzenie
``` cargo new <nazwa-projektu> ```
* Z gitem:
``` cargo new <nazwa-projektu> --vsc=git ```

### Budowanie
* W folderze projektu:
``` cargo build ```

* Budowanie i uruchomienie kodu:
``` cargo run ```

* Sprawdzenie czy kod sie kompiluje, bez kompilacji:
``` cargo check ```

* Budowanie releasa. robi ptymalizacje kodu, buduje sie dluzej:
``` cargo build --release ```

* Aktualizacja zaleznosci:
``` cargo update ```