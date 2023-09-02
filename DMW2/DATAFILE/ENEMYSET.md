# ENEMYSET.BIN - [Back](https://gledson999.github.io/opendw2/home.html)

File containing the settings and AI of enemies.

## Structure

| Offset | Type | Description |
|--------|------|-------------|
| 0x00   | uint8 | ID
| 0x01   | uint8 | Movement
| 0x02   | uint16 | Overworld Model ID
| 0x04   | uint8 | [Gift Type](#gift-types)
| 0x05   | uint8 | [Encounter Type](#encounter-types)
| 0x06   | uint16 | Gift Rate
| 0x08   | uint16 | [Digimon ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Digimon.html) **Center**
| 0x0A   | uint16 | HP
| 0x0C   | uint16 | MP
| 0x0E   | uint16 | EXP
| 0x10   | uint16 | Bits
| 0x12   | uint8 | Level
| 0x13   | uint8 | Attack
| 0x14   | uint16 | Defense
| 0x16   | uint8 | Speed
| 0x17   | uint8 | [Tech 1 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x18   | uint8 | [Tech 2 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x19   | uint8 | [Tech 3 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x1A   | uint8 | Condition
| 0x1B   | uint8 | Skill
| 0x1C   | uint8 | Target 1
| 0x1D   | uint8 | Condition
| 0x1E   | uint8 | Skill
| 0x1F   | uint8 | Target 2
| 0x20   | uint8 | Condition
| 0x21   | uint8 | Skill
| 0x22   | uint8 | Target 3
| 0x23   | uint8 | Condition
| 0x24   | uint8 | Skill
| 0x25   | uint8 | Target 4
| 0x26   | uint16 | [Digimon ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Digimon.html) **Left**
| 0x28   | uint16 | HP
| 0x2A   | uint16 | MP
| 0x2C   | uint16 | EXP
| 0x2E   | uint16 | Bits
| 0x30   | uint8 | Level
| 0x31   | uint8 | Attack
| 0x32   | uint16 | Defense
| 0x34   | uint8 | Speed
| 0x35   | uint8 | [Tech 1 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x36   | uint8 | [Tech 2 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x37   | uint8 | [Tech 3 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x38   | uint8 | Condition
| 0x39   | uint8 | Skill
| 0x3A   | uint8 | Target 1
| 0x3B   | uint8 | Condition
| 0x3C   | uint8 | Skill
| 0x3D   | uint8 | Target 2
| 0x3E   | uint8 | Condition
| 0x3F   | uint8 | Skill
| 0x40   | uint8 | Target 3
| 0x41   | uint8 | Condition
| 0x42   | uint8 | Skill
| 0x43   | uint8 | Target 4
| 0x44   | uint16 | [Digimon ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Digimon.html) **Right**
| 0x46   | uint16 | HP
| 0x48   | uint16 | MP
| 0x4A   | uint16 | EXP
| 0x4C   | uint16 | Bits
| 0x4E   | uint8 | Level
| 0x4F   | uint8 | Attack
| 0x50   | uint16 | Defense
| 0x52   | uint8 | Speed
| 0x53   | uint8 | [Tech 1 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x54   | uint8 | [Tech 2 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x55   | uint8 | [Tech 3 ID](https://gledson999.github.io/opendw2/DMW2/Dictionary/Tech.html)
| 0x56   | uint8 | Condition
| 0x57   | uint8 | Skill
| 0x58   | uint8 | Target 1
| 0x59   | uint8 | Condition
| 0x5A   | uint8 | Skill
| 0x5B   | uint8 | Target 2
| 0x5C   | uint8 | Condition
| 0x5D   | uint8 | Skill
| 0x5E   | uint8 | Target 3
| 0x5F   | uint8 | Condition
| 0x60   | uint8 | Skill
| 0x61   | uint8 | Target 4
| 0x62   | uint16 | Null

### Gift Types

| Id   | Gift Type |
|------|------------|
| 0x00 | Data Type   
| 0x01 | Vaccine Type
| 0x02 | Virus Type

### Encounter Types

| Id   | Encounter Type |
|------|------------|
| 0x00 | Normal   
| 0x10 | Sub-boss
| 0x11 | Boss
