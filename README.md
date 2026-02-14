# Plugin-Roblox-Loader
A Unique idea of Running Your loadstring code with Plugin Format Style

# Code Preview 
```lua
local Plugin = {
  
  Id = "4B45"
  -
  Name = nil,
  --
  Desc = nil,
  ---
  Author = nil,
  ----
  Version = 1,
  ---
  Script = nil,
  --
  Note = nil
  -
}

if Plugin.Version >= 3 then
  print("Version cannot be higher than 3")
  return
end

if Plugin.Version <= 1 then
  print("Version cannot be lower than 3")
  return
end

if Plugin.Id == nil then
  print("Id cannot be nil")
  return
end
```

**Explanation About The Field**

```lua
Id = nil,
```
you can make your own unique Id

```lua
Name = nil, 
```
Plugin Title
<!-- ═══════════════════════════════════════ -->
```lua
Desc = nil, 
```
Plugin Description
<!-- ═══════════════════════════════════════ -->
```lua
Author = nil, 
```
Creator of the plugin
<!-- ═══════════════════════════════════════ -->
```lua
Version = nil, 
```
Version needs to be a number, and you can only pick 1-3, beyond that will cause error
