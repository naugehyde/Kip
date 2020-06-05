# Kip 

This is a marine instrumentation package to display signalK data. Display can be split up in any arrangement to show any kind data available on the server.

# Design Goal

The idea is to replicate the functionality of your average MFD such as the B&G Triton, Raymarine i70, or Garmin GMI20.
- Display should be fullscreen and not require any scrolling
- Anything displayed should be as big as possible in the given space
- Touchscreen user experience should be excellent
- Layout and configuration should be both easy to operate and flexible
- Compatibility with Chromium browser and other device form factor important (**HELP WANTED)  

# Features
## User Experience
### Built-in Theme Sample
  Request a theme and send us inspirational/reference material (web sites, picture, etc.). If we fall in love, we will do it. Even better, branch and contribute. We will assist and guide!

  Modern Dark Theme
  ![Modern Dark Theme](./KipSample-1-1024x488.png)
  
  SignalK Inspired Theme
  ![SignalK Inspired Theme](./KipSample-2-1024x488.png)
  
  Light Blue Theme
  ![Light Blue Theme](./KipSample-3-1024x488.png)

### Accessible Night Mode
  Switch to night mode with a quick access button, regardless of the selected theme. Look dark here but at night...perfect!

  ![Light Blue Theme](./KipNightMode-1024x488.png)


## Gauge Layout and Configuration
### Flexible and Easy
Built purposeful screen(s) with however many gauges you want, where you want them. 

  Split page zones, resize and Widgets. Add as many pages as you whish to keep things focused!
  ![Layout Configuration Image](./KipWidgetConfig-layout-1024x488.png)
  
  Easy basic gauge config.
  ![Gauge Configuration Image](./KipConfig-display-1024x488.png) 
  
  See what SignalK has to offer that you can leverage in a gauge.
  ![Path Configuration Image](./KipWidgetConfig-paths-1024x488.png)
  
  Many units are supported. Choose your prefered App defaults and tweak it gauge by gauge. Kip will convert the units for you.
  ![Path Configuration Image](./KipConfig-Units-1024x488.png) 

### Reusable Gauge Library
Get the latest version of Kip to see what's new!
<p align="center">
  <img src="./KipGaugeSample-1-1024x545.png" height="545" width="1024">
  Sample gauge types
  <img src="./KipMonitor-1024x488.png" height="488" width="1024">
  Electrical and Tank monitoring sample 
</p>

# Developing

The app is an Angular-cli app. Install dependencies with `npm install`. Then run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files. Run `ng build` to build the project. The build artifacts will be stored in the `public/` directory. Use the `-prod` flag for a production build. To prepare for npm, run `npm run-script build-npm`.



# Feature Ideas

 * More Customization options for Historical Charts
 * Attitude Indicator
 * Sailing Polars with ChartJS Radar type chart?
 * More Customization options for radial/linear Gauges
 * Gauge Zones
 * Overview page to quickly scroll through known path info.
 * Show alarms on numeric displays based on zones
 * Pre-created widgets for commonly used displays
