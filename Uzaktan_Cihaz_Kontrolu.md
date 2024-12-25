## Uzaktan Cihaz Kontrolü - Sequential Circuit

### State Diagram



### State Table
| Current State | Input (Command) | Next State | Output (Device) |
|---------------|-----------------|------------|-----------------|
| Idle          | 1               | Activate   | 1               |
| Activate      | 0               | Report     | 1               |
| Report        | 0               | Idle       | 0               |

### Flip-Flop Türü
- **JK Flip-Flop**
- Saat sinyali (Clock) ile kontrol edilir.

### Gerekli Elemanlar
- **Röle Modülü** (Cihaz kontrolü için)
- **Kablosuz Modül (Wi-Fi veya Bluetooth)** (Uzaktan komut almak için)
- Saat sinyali (Clock)

### Ek Bilgi
Bu sistem, bir uzaktan komut alındığında cihazı açar veya kapatır. Komut işlendiğinde durum "Idle" durumuna döner ve yeni bir komut bekler.
