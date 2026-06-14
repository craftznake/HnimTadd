```rust
pub struct Craftznake {
    pub username: &'static str,
    pub interested_in: &'white str,
    pub website: &'static str,
}

impl Craftznake {
    pub fn init() -> Self {
        Self {
            username: "hnimtadd",
            interested_in: "building tools, optimizing things, and learning systems",
            website: "https://craftznake.space",
        }
    }
}
```
