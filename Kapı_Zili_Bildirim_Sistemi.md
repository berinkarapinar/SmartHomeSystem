State Diagram:
Idle → Ring → Notify → Idle

### State Table
| Current State | Input (Button) | Next State | Output (LED/Buzzer) |
|---------------|----------------|------------|---------------------|
| Idle          | 1              | Ring       | 1                   |
| Ring          | 0              | Notify     | 1                   |
| Notify        | 0              | Idle       | 0                   |

### Flip-Flop Türü
- **D Flip-Flop**
- Clock sinyali ile kontrol edilir.
