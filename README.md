# XamlResourceDocs
Static/Theme Resource documentation

## AcrylicBrush

### Windows Calculator background Acrylic

```xaml
<AcrylicBrush x:Key="AppChromeAcrylicHostBackdropMediumLowBrush"
  BackgroundSource="HostBackdrop"
  FallbackColor="{ThemeResource SystemChromeMediumColor}"
  TintColor="{ThemeResource SystemChromeLowColor}"
  TintOpacity="0.7"/>
```

### Windows 10 Settings sidebar Acrylic

```xaml
<AcrylicBrush x:Key="NavBarAcrylicBackgroundBrush"
  BackgroundSource="HostBackdrop"
  FallbackColor="{ThemeResource SystemChromeMediumColor}"
  TintColor="{ThemeResource SystemAltHighColor}"
  TintOpacity="0.6" />
```

### Windows 10 Start/Taskbar/Tray flyout Acrylic

```xaml
<AcrylicBrush x:Key="SystemControlAcrylicWindowBrush"
  BackgroundSource="HostBackdrop"
  TintColor="{StaticResource SystemChromeAltHighColor}"
  TintOpacity="0.8"
  FallbackColor="{StaticResource SystemChromeMediumColor}" />
```
