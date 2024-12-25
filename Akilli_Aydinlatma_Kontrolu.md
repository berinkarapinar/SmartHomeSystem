## Akıllı Aydınlatma Kontrolü - Sequential Circuit

### State Diagram



### State Table
| Current State | Input (Motion) | Next State | Output (Light) |
|---------------|----------------|------------|----------------|
| Idle          | 1              | On         | 1              |
| On            | 0              | Off        | 0              |
| Off           | 0              | Idle       | 0              |

### Flip-Flop Türü
- **T Flip-Flop**
- Saat sinyali (Clock) ile kontrol edilir.

### Gerekli Elemanlar
- **PIR Hareket Sensörü**
- **LED veya Lamba**
- Clock sinyali (Saat Sinyali)

### Ek Bilgi
Bu sistem, bir hareket algılandığında ışığı açar ve belirli bir süre sonra kapatır. Sistem, enerji tasarrufu sağlamak için otomatik olarak "Idle" durumuna geri döner.
