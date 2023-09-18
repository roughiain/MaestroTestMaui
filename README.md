# com.companyname.mauiapp1

Sample project to test the effectiveness of [Maestro](https://maestro.mobile.dev) with dotnet maui.

Sample test 

```yaml
appId: com.companyname.mauiapp1
---
- launchApp
- assertVisible:
    id: "dotnet_bot.png"
- tapOn: "Click me"
- assertVisible: "Clicked 1 time"
```
