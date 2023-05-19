# John Library

## Documentation

#### Getting Loadstring

```lua

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/JohnBardot/JohnLib/main/JohnLib.lua"))()

```

#### Creating Window

```lua

local Window = Library:CreateWindow("Title")

```
#### Creating Tab Sections

```lua

local TabSection = Window:CreateTabSection("Tab Section Text")

```

#### Creating Tabs

```lua

local Tab = TabSection:CreateTab("Tab Text")

```
#### Creating Sections
```lua
local Section = Tab:CreateSection("Section Text")
```
#### Creating Labels

```lua

Section:CreateLabel("Label Text")

```

#### Creating Buttons

```lua

Section:CreateButton("Button Text",function()

end)

```

#### Creating Toggles

```lua

Section:CreateToggle("Toggle Text",function(state)

end)

```

#### Creating Text Boxes

```lua

Section:CreateBox("Text Box Text",function(Value)

end)

```
