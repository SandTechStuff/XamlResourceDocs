# XamlResourceDocs
Static/Theme Resource documentation

## Glossary

* New WinUI: Refers to the versions of WinUI2 after 2.6 that follow the Windows 11 design principles.
* Old WinUI: Refers to the versions of WinUI2 before 2.6 that follow the Windows 10 design principles.

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

### Default new WinUI backdrop Acrylic

#### Light Mode

```xaml
<AcrylicBrush x:Key="AcrylicBackgroundFillColorDefaultBrush"
  TintColor="#FCFCFC"
  TintOpacity="0.0"
  TintLuminosityOpacity="0.85"
  FallbackColor="#F9F9F9"
  BackgroundSource="HostBackdrop" />
```

#### Dark Mode

```xaml
<AcrylicBrush x:Key="AcrylicBackgroundFillColorDefaultBrush"
  TintColor="#2C2C2C"
  TintOpacity="0.15"
  TintLuminosityOpacity="0.96"
  FallbackColor="#2C2C2C"
  BackgroundSource="HostBackdrop" />
```
