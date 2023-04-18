# Syaoul Library

---

## Function

- Button

- Slider

- Textbox

- Toggle

- Label

---

### Setting the Library

```lua
local Library = loadstring(game:HttpGet(("https://raw.githubusercontent.com/Syaoul/Library/main/Syaoul-Gui")))()
```

---

### Creating a Window

```lua
local Window = Library:Create({
    Name = "Syaoul Library",
    StartupSound = {
        Toggle = false,
        SoundID = "rbxassetid://6958727243",
        TimePosition = 1
    }
})
```

### Creating a Tab

```lua
local Tab = Window:Tab('Tab')
```

### Creating a Button

```lua
Tab:Button('Button', function()
    print("button pressed")
end)
```

### Creating a Toggle

```lua
Tab:Toggle('Toggle', function(Value)
    print(Value)
end)
```

### Creating a Textbox

```lua
Tab:Textbox('Textbox', function(Value)
    print(Value)
end)
```

### Creating a Slider

```lua
Tab:Slider('Slider', 30 -- default, 10 -- min, 300 -- max, function(Value)
    print(Value)
end)
```

### Creating a Label
```lua
Tab:Label('This is a label')
```

---
