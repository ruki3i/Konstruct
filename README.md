# station/konstruct

<p align="center">
  <img src="https://raw.githubusercontent.com/ruki3i/Konstruct/2e148b21a1f03c61e850ddcd3c4a4999c573e8e7/Images/Konstruct.png" alt="Konstruct Banner">
</p>

> **A clean, modern UI library for Roblox.**

**station/konstruct** is a lightweight Roblox UI library built for developers who want to **construct clean interfaces without the unnecessary complexity.**

### ✦ Features

* Clean & minimal UI
* Lightweight and easy to use
* Flexible components
* Smooth interactions
* Developer-friendly API
* Designed for customization

### Installation

```lua
local Konstruct = loadstring(game:HttpGet("https://raw.githubusercontent.com/ruki3i/Konstruct/refs/heads/main/KonstructMain"))()
```

### Example

```lua
local Window = Konstruct:CreateWindow({
    Title = "Konstruct",
})

local Tab = Window:CreateTab("Main")

Tab:CreateButton({
    Name = "Hello",
    Callback = function()
        print("Hello, Konstruct!")
    end
})
```

---

**station/konstruct**
Developed by **Yera**.

`build clean. construct different.`
