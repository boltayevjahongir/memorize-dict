# lugat-dict

Lug'at ilovasi uchun ochiq (public) lug'at to'plamlari — Destination CEFR darajalari
bo'yicha. Ilova bu fayllarni ish vaqtida yuklab oladi (on-demand).

| Fayl | Daraja | So'z soni |
|---|---|---|
| `dest_a1.json` | A1 | 862 |
| `dest_a2.json` | A2 | 1152 |
| `dest_b1.json` | B1 | 1160 |
| `dest_b2.json` | B2 | 109 |

Format: JSON massiv — har element bitta so'z (`w`, `uz`, `pos`, `lvl`, `ipa`,
`defEn`, `defUz`, `examples[]`, `topic`, ...). Ilova `[...]` yoki `{"words":[...]}`
ikkalasini ham qabul qiladi.

Raw yuklash manzili (ilovadagi `kDictBaseUrl`):
`https://raw.githubusercontent.com/boltayevjahongir/<repo>/main/`
