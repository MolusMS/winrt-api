---
-api-id: M:Windows.UI.Composition.Compositor.CreateHostBackdropBrush
-api-type: winrt method
---

<!-- Method syntax.
public CompositionBackdropBrush Compositor.CreateHostBackdropBrush()
-->

# Windows.UI.Composition.Compositor.CreateHostBackdropBrush

## -description
Creates an instance of  CompositionBackdropBrush that samples from the area behind the visual, before the window is drawn.

## -returns
Returns the created CompositionBackdropBrush.

## -remarks
The standard backdrop brush samples the area immediately behind the visual where it is used. By default, The host backdrop brush tells the compositor to sample from the area behind the visual, before the window is drawn. By default, the host backdrop brush is translucent and it hit-tests as opaque. The app cannot read the pixel data back.

The transparency of the host backdrop brush is a property which can be controlled by the user from the Settings UI or due power policies.

## -see-also

## -examples

