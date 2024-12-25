## Nem ve Sulama Sistemi - Sequential Circuit

### State Diagram


### State Table
| Current State | Input (Moisture Low) | Next State | Output (Water Pump) |
|---------------|-----------------------|------------|---------------------|
| Idle          | 1                    | Water      | 1                   |
| Water         | 0                    | Stop       | 0                   |
| Stop          | 0                    | Idle       | 0                   |

### Flip-Flop Türü
- **JK Flip-Flop**
- Clock sinyali ile kontrol edilir.
