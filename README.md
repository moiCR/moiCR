```rust
pub struct MoisesMarencoVives {
    pub role: &'static str,
    pub os: (&'static str, &'static str),
    pub languages: [&'static str; 3],
    pub desktop_and_ui: [&'static str; 5],
}

impl MoisesMarencoVives {
    pub const fn new() -> Self {
        Self {
            role: "Systems Engineer",
            os: ("Linux", "Windows"),
            languages: ["Rust", "Java", "JS/TS"],
            desktop_and_ui: ["GPUI", "Tauri", "Tailwind", "React", "Wayland"],
        }
    }
}
```
