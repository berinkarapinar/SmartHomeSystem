## Sıcaklık ve Fan Kontrolü - Sequential Circuit

### State Diagram



### State Table
| Current State | Input (High Temp) | Next State | Output (Fan) |
|---------------|-------------------|------------|--------------|
| Idle          | 1                | Cool       | 1            |
| Cool          | 0                | Stop       | 0            |
| Stop          | 0                | Idle       | 0            |

### Flip-Flop Türü
- **D Flip-Flop**
- Saat sinyali (Clock) ile kontrol edilir.

### Gerekli Elemanlar
- **Sıcaklık Sensörü (LM35 veya DHT11)**
- **Fan ve Sürücü Devresi**
- Saat sinyali (Clock)

### Ek Bilgi
Bu sistem, ortam sıcaklığı belirli bir eşik değerinin üzerine çıktığında fanı açar. Sıcaklık normal seviyeye düştüğünde fan durur ve "Idle" durumuna döner.
