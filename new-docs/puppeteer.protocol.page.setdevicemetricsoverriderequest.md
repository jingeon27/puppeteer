<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Page](./puppeteer.protocol.page.md) &gt; [SetDeviceMetricsOverrideRequest](./puppeteer.protocol.page.setdevicemetricsoverriderequest.md)

## Protocol.Page.SetDeviceMetricsOverrideRequest interface

<b>Signature:</b>

```typescript
export interface SetDeviceMetricsOverrideRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [deviceScaleFactor](./puppeteer.protocol.page.setdevicemetricsoverriderequest.devicescalefactor.md) | number | Overriding device scale factor value. 0 disables the override. |
|  [dontSetVisibleSize](./puppeteer.protocol.page.setdevicemetricsoverriderequest.dontsetvisiblesize.md) | boolean | Do not set visible view size, rely upon explicit setVisibleSize call. |
|  [height](./puppeteer.protocol.page.setdevicemetricsoverriderequest.height.md) | [integer](./puppeteer.protocol.integer.md) | Overriding height value in pixels (minimum 0, maximum 10000000). 0 disables the override. |
|  [mobile](./puppeteer.protocol.page.setdevicemetricsoverriderequest.mobile.md) | boolean | Whether to emulate mobile device. This includes viewport meta tag, overlay scrollbars, text autosizing and more. |
|  [positionX](./puppeteer.protocol.page.setdevicemetricsoverriderequest.positionx.md) | [integer](./puppeteer.protocol.integer.md) | Overriding view X position on screen in pixels (minimum 0, maximum 10000000). |
|  [positionY](./puppeteer.protocol.page.setdevicemetricsoverriderequest.positiony.md) | [integer](./puppeteer.protocol.integer.md) | Overriding view Y position on screen in pixels (minimum 0, maximum 10000000). |
|  [scale](./puppeteer.protocol.page.setdevicemetricsoverriderequest.scale.md) | number | Scale to apply to resulting view image. |
|  [screenHeight](./puppeteer.protocol.page.setdevicemetricsoverriderequest.screenheight.md) | [integer](./puppeteer.protocol.integer.md) | Overriding screen height value in pixels (minimum 0, maximum 10000000). |
|  [screenOrientation](./puppeteer.protocol.page.setdevicemetricsoverriderequest.screenorientation.md) | [Emulation.ScreenOrientation](./puppeteer.protocol.emulation.screenorientation.md) | Screen orientation override. |
|  [screenWidth](./puppeteer.protocol.page.setdevicemetricsoverriderequest.screenwidth.md) | [integer](./puppeteer.protocol.integer.md) | Overriding screen width value in pixels (minimum 0, maximum 10000000). |
|  [viewport](./puppeteer.protocol.page.setdevicemetricsoverriderequest.viewport.md) | [Viewport](./puppeteer.protocol.page.viewport.md) | The viewport dimensions and scale. If not set, the override is cleared. |
|  [width](./puppeteer.protocol.page.setdevicemetricsoverriderequest.width.md) | [integer](./puppeteer.protocol.integer.md) | Overriding width value in pixels (minimum 0, maximum 10000000). 0 disables the override. |
