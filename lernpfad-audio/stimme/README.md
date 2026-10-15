# Stimme für lernpfad-audio

Piper-Stimme `de_DE-thorsten-high` (Deutsch, Sprecher Thorsten, Qualität high), zerlegt in zwei Teile, weil GitHub keine Einzeldateien über 100 MB annimmt.

| Datei | Größe | SHA-256 |
|---|---|---|
| `de_DE-thorsten-high.onnx.teil0` | 57 000 000 Bytes | `cf3e7ff8d479aabd24e476c6760d629d8701962d2584b125f8668e0db50784f6` |
| `de_DE-thorsten-high.onnx.teil1` | 56 895 201 Bytes | `3990b89d52f949f46a278bcb2ab39ee475e00921cb5b5e80462f9b4d1b40cb6b` |
| zusammengesetzt `de_DE-thorsten-high.onnx` | 113 895 201 Bytes | `9df1c43c61149ef9b39e618e2b861fbe41e1fcea9390b2dac62e8761573ea4f1` |
| `de_DE-thorsten-high.onnx.json` | Konfiguration | |

Zusammensetzen von Hand: `cat de_DE-thorsten-high.onnx.teil0 de_DE-thorsten-high.onnx.teil1 > de_DE-thorsten-high.onnx`

Herkunft: rhasspy/piper-voices auf Hugging Face (`de/de_DE/thorsten/high`), trainiert auf dem Datensatz Thorsten-Voice von Thorsten Müller. Lizenzangaben siehe MODEL_CARD im Original.
