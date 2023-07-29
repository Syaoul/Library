# Syaoul Library

---

## Function

- Tab

- Button

- Slider

- Textbox

- Toggle

- Dropdown

- Label

---

### Setting the Library

```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Syaoul/Library/main/Syaoul"))()
```

### Creating a Window

```lua
local Window = Library:Window()
```

---

### Creating a Tab

```lua
local Tab = Window:Tab("Tab")
```

### Creating a Button

```lua
Tab:Button("Button", function()
    print("button pressed")
end)
```

### Creating a Toggle

```lua
Tab:Toggle("Toggle", function()
    print(Value)
end)
```

### Creating a Textbox

```lua
Tab:Textbox("Text Box", "disapper", function()
    print(Value)
end)
```

### Creating a Slider

```lua
Tab:Slider("Slider", 0, 50, function()
    print(Value)
end)
```

### Creating a Dropdown

```lua
Tab:Dropdown("DropDown", list, callback)
```

### Creating a Label
```lua
Tab:Label("Label")
```

---
