# Nuclear Option — Türkçe Yama (Localization Patch)

Nuclear Option için Türkçe çeviri modu. BepInEx eklentisi olarak çalışır ve arayüzü, HUD'u, MFD'leri, görevleri, senaryoları, araçları ve silahları çevirir — toplam **2.841 girdi**.

> ⚠️ **Beta sürüm — Google Translate ile otomatik çevrildi.** Topluluk düzeltmeleri PR veya Issue ile bekleniyor. Çevirinin gözden geçirilmesi ve düzeltilmesinde yardımcı olmak için **Hikari [ATOM]** ile iletişime geçildi.

## Gereksinimler

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Erken Erişim 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Kurulum

1. **BepInEx 5.x**'i oyun klasörüne kurun.
   ```
   Örnek: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Oyunu **bir kez** çalıştırıp kapatın. (Bu, BepInEx klasör yapısını oluşturur.)

3. Bu depodaki tüm dosyaları şuraya kopyalayın:
   ```
   [Oyun klasörü]\BepInEx\plugins\LocalizationPatch\
   ```
   > `LocalizationPatch` klasörü yoksa elle oluşturun.

4. `BepInEx\config\com.noms.localizationpatch.cfg` dosyasını düzenleyin:
   ```
   [General]
   Language = tr
   ```

5. Oyunu başlatın — Türkçe çeviri otomatik olarak uygulanır.

### Tek tıkla yükleyici (alternatif)

https://github.com/9138noms/NuclearOption-LocalizationInstaller/releases/latest

## Dahil edilen dosyalar

| Dosya | Açıklama |
|-------|----------|
| `LocalizationPatch.dll` | Çeviri eklentisi |
| `LocalizationPatchDropdown.dll` | Açılır menü eklentisi |
| `tr.json` | Türkçe çeviri verileri (2.841 girdi) |
| `Exo2-Regular.ttf` | Latin Extended desteği için yazı tipi (ç, ğ, ı, ö, ş, ü) |

## Oyun içi kısayollar

| Tuş | İşlev |
|-----|-------|
| `F10` | Hata ayıklama panelini aç/kapat |
| `Ctrl+F10` | Çeviri JSON'unu yeniden yükle (sıcak yeniden yükleme) |

## Notlar

- Fraksiyon adları (PALA, BDF, BOSCALI, PRIMEVA, FFL, LMA) ve uçak/silah kod adları (Compass, Alkyon AB-4, FGA-57 Anvil, IRM-S2 vb.) genellikle özgün halinde tutulmalıdır — bu beta sürümde Google Translate bazılarını çevirmiş olabilir, düzeltme bekleniyor.
- Standart NATO kısaltmaları (AAM, AGM, ARH, APFSDS, IRM, SAM vb.) Türk havacılık camiasında olduğu gibi İngilizce kalmalıdır.
- Sorun yaşarsanız `BepInEx\config\com.noms.localizationpatch.cfg` dosyasında `Language = tr` olarak elle ayarlayabilirsiniz.

## Çeviri katkıları

- İlk taslak: Google Translate ile otomatik oluşturuldu
- Topluluk inceleme/düzeltme: **Hikari [ATOM]** (devam ediyor)
- Eklenti / çerçeve: https://github.com/9138noms/NuclearOption-TranslationToolkit

## Yazı tipi lisansı

Exo 2 — [SIL Open Font License 1.1](https://fonts.google.com/specimen/Exo+2)

## İlgili projeler

🇰🇷 [Korean](https://github.com/9138noms/NuclearOption-KoreanPatch) ·
🇷🇺 [Russian](https://github.com/9138noms/NuclearOption-RussianPatch) ·
🇺🇦 [Ukrainian](https://github.com/9138noms/NuclearOption-UkrainianPatch) ·
🇧🇾 [Belarusian](https://github.com/9138noms/NuclearOption-BelarusianPatch) ·
🇩🇪 [German](https://github.com/9138noms/NuclearOption-GermanPatch) ·
🇪🇸 [Spanish](https://github.com/9138noms/NuclearOption-SpanishPatch) ·
🇫🇷 [French](https://github.com/9138noms/NuclearOption-FrenchPatch) ·
🇧🇷 [Portuguese](https://github.com/9138noms/NuclearOption-PortuguesePatch) ·
🇳🇴 [Norwegian](https://github.com/9138noms/NuclearOption-NorwegianPatch) ·
🇹🇼 [Traditional Chinese](https://github.com/9138noms/NuclearOption-TraditionalChinesePatch) ·
🇮🇹 [Italian](https://github.com/9138noms/NuclearOption-ItalianPatch)

Çeviri araç seti (kendi dil yamanızı oluşturmak için):
https://github.com/9138noms/NuclearOption-TranslationToolkit
