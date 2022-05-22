# Numbers

## Integer

There are two types of numbers as base number types:

| Type |      Description       | Range          |
| ---: | :--------------------: | :------------- |
|   u8 | Unsinged 8-byte number | `0` - `255`    |
|   i8 |  Singed 8-byte number  | `-128` - `127` |

To save more data, write the length in brackets(`[]`).
For example `u8[4]` is an unsigned 32-byte number.
To simplify this, the standard library defines following types:

| Type | Alias   |
| ---: | :------ |
|  i16 | i8[2]   |
|  i32 | i8[4]   |
|  i64 | i8[8]   |
| i128 | i8[128] |
|  u16 | u8[2]   |
|  u32 | u8[4]   |
|  u64 | u8[8]   |
| u128 | u8[128] |

