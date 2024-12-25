## Kapı Kilidi Güvenlik Sistemi - Sequential Circuit

### State Diagram



### State Table
| Current State | Input (Correct Code) | Next State | Output (Lock) |
|---------------|-----------------------|------------|---------------|
| Idle          | 1                    | Check      | 0             |
| Check         | 1                    | Unlock     | 1             |
| Unlock        | 0                    | Idle       | 0             |

### Flip-Flop Türü
- **D Flip-Flop**
- Saat sinyali (Clock) ile kontrol edilir.

### Gerekli Elemanlar
- **Tuş Takımı veya RFID Okuyucu**
- **Elektronik Kilit**
- Clock sinyali (Reset için)

### Ek Bilgi
Bu sistem, doğru bir kod girişi sağlandığında kapı kilidini açar. Yanlış kod durumunda kilit açılmaz ve Idle durumuna geri döner.
