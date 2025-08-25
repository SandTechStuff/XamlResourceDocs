# XamlResourceDocs
Static/Theme Resource documentation

## Glossary

* __New WinUI:__ Refers to the versions of WinUI2 after 2.6 that follow the Windows 11 design principles.
* __Old WinUI:__ Refers to the versions of WinUI2 before 2.6 that follow the Windows 10 design principles.
* __Theme aware alternative:__ A variant of a brush that is less accurate, but uses pre-defined colors to respond to user Light/Dark mode preferences. The mode listed as "favoring" is the mode that will look the most accurate. Some brushes already use these pre-defined colors, and will not have a theme aware alternative provided.

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

- #### Light Mode

  ```xaml
  <AcrylicBrush x:Key="AcrylicBackgroundFillColorDefaultBrush"
    TintColor="#FCFCFC"
    TintOpacity="0.0"
    TintLuminosityOpacity="0.85"
    FallbackColor="#F9F9F9"
    BackgroundSource="HostBackdrop" />
  ```

- #### Dark Mode

  ```xaml
  <AcrylicBrush x:Key="AcrylicBackgroundFillColorDefaultBrush"
    TintColor="#2C2C2C"
    TintOpacity="0.15"
    TintLuminosityOpacity="0.96"
    FallbackColor="#2C2C2C"
    BackgroundSource="HostBackdrop" />
  ```

### Windows 11 Start/Taskbar/Tray flyout Acrylic

- #### Light Mode

  ```xaml
  <AcrylicBrush x:Key="AcrylicBackgroundFillColorBaseBrush"
    TintColor="#F3F3F3"
    TintOpacity="0.0"
    TintLuminosityOpacity="0.9"
    FallbackColor="#EEEEEE"
    BackgroundSource="HostBackdrop" />
  ```

- #### Dark Mode

  ```xaml
  <AcrylicBrush x:Key="AcrylicBackgroundFillColorBaseBrush"
    TintColor="#202020"
    TintOpacity="0.5"
    TintLuminosityOpacity="0.96"
    FallbackColor="#1C1C1C"
    BackgroundSource="HostBackdrop"/>
  ```
  
- #### Theme aware alternative (favoring Light)

  ```xaml
  <AcrylicBrush x:Key="AcrylicBackgroundFillColorBaseBrush"
    TintColor="{ThemeResource SystemChromeLowColor}"
    TintOpacity="0.0"
    TintLuminosityOpacity="0.9"
    FallbackColor="{ThemeResource SystemChromeLowColor}"
    BackgroundSource="HostBackdrop" />
  ```

- #### Theme aware alternative (favoring Dark)

  ```xaml
  <AcrylicBrush x:Key="AcrylicBackgroundFillColorBaseBrush"
    TintColor="{ThemeResource SystemChromeMediumColor}"
    TintOpacity="0.5"
    TintLuminosityOpacity="0.96"
    FallbackColor="{ThemeResource SystemChromeMediumColor}"
    BackgroundSource="HostBackdrop"/>
  ```
