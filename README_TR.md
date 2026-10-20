# Stationary Strings Letter 1 — Sodyum-22 Pozitronyum Laboratuvar Testi

> **English:** [README.md](./README.md)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)

**SS-L1: Üç-Foton Pozitronyum Spektrumu — arXiv:2605.21289 Denk. (12)'nin Düzeltmesi ve Bir Saatlik Laboratuvar Testi**

Yazar: Fahri Meral · Tarih: 20 Ekim 2026 · Sürüm: v1 (SS-L1)

> **Durum:** Yayımlanmamış ön-baskı (v1). Hakem denetiminden geçmemiştir. *Zenodo DOI'si yüklemeyi bekliyor.*

## Tek paragrafta iddia
arXiv:2605.21289'un Denk. (12)'nde yayımlanan orto-pozitronyum üç-foton
spektrumu, 1949 Ore–Powell ifadesinin **ln'siz** hâlidir. Normalize
değildir (∫₁⁵¹¹ Ω dE = 2343.47, 1 olmalı) ve düşük enerjide E⁻²
olarak ıraksar — yani yok olması gereken foton sayısından fazlasını
öngörür. Doğru form, asıl 1949 ifadesinin ln(1−x) çarpanlarını taşır,
tam olarak normaldir (∫₀⁵¹¹ Ω dE = 1, 5×10⁻¹³ hassasiyetle) ve
Ω(x) ~ (5/3)x ile sönümlenir. $5$ µCi ²²Na kaynağı, silika aerojel ve
küçük bir HPGe ile yapılacak **tek saatlik** ölçüm, iki formu bant
oranında **7,8×10⁵ standart sapma** ile ayırır
(R = N[10,100] / N[350,490]).

## Ne iddia ediliyor, ne edilmiyor
- **İddia:** yayımlanan denklem yanlıştır; düzeltme 1949 aslıyla terim
  terim kaynak denetimiyle gerekçelendirilir.
- **İddia edilmiyor:** ölçümün yapıldığı. Yapılmamıştır. Makaledeki tablo
  önerilen protokolün **öngörülen** sonucunu verir; testin yürütülüp
  karşılaştırılabilmesi için.
- **Seriden bağımsızdır:** Teoremler I–X'in ya da Stationary Strings XII–XIV'ün hiçbir
  modeli, kilidi ya da ansatz'ı bu mektuba girmez. Bu yüzden ayrı sunulur.

## İçerik

| Dosya | Açıklama |
|---|---|
| `paper/stationary_strings_L1_na22_EN.tex` | Mektup, İngilizce (Tablo 1, 6 bölüm) |
| `paper/stationary_strings_L1_na22_TR.tex` | Türkçe sürüm |
| `CITATION.cff` | Atıf kaydı |
| `LICENSE` | CC BY 4.0 |

Sayısal makine
([`stationary-strings-v`](https://github.com/fahrim/stationary-strings-v)
deposundaki `duran_sicimler_sim/na22_experiment.py`) üç aday spektrumu,
bant integrallerini, dedekte edilen sayımları ve ayrım istatistiklerini
hesaplar.

## Atıf

```bibtex
@misc{meral2026na22,
  author = {Fahri Meral},
  title  = {Üç-Foton Pozitronyum Spektrumu: arXiv:2605.21289 Denk. (12)'nin Düzeltmesi ve Bir Saatlik Laboratuvar Testi},
  year   = {2026},
  url    = {https://github.com/fahrim/stationary-strings-l1}
}
```

Ayrıca bkz. `CITATION.cff`.

## Lisans

CC BY 4.0 — bkz. `LICENSE`. İçerik hakem denetiminden geçmemiştir.
