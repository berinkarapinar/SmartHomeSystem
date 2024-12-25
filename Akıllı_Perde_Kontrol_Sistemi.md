## Akıllı Perde Kontrol Sistemi - Sequential Circuit

### State Diagram



### State Table
| Current State | Input (Light Level) | Next State | Output (Motor) |
|---------------|---------------------|------------|----------------|
| Idle          | 1 (Bright)         | Open       | 1              |
| Open          | 0 (Dark)           | Close      | 1              |
| Close         | 0                  | Idle       | 0              |

### Flip-Flop Türü
- **T Flip-Flop**
- Clock sinyali ile kontrol edilir.

### Gerekli Elemanlar
- **Motor ve Motor Sürücü Devresi**
- **LDR (Işık Sensörü)**
- Saat sinyali (Clock)
