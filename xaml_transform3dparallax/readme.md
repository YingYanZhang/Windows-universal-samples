# Transform3D parallax sample

This sample shows how to implement parallax effects using the new Transform3D API.

Specifically, this sample shows how to:

- **Create a parallax background image:** This sample shows how to add a parallax background to your scrolling experience, and control the magnitude of the parallax effect.
- **Add parallax to a Hub control:** By deriving from the Hub class, we can add a parallax background effect like the one in the Windows 8.1 Hub control. See `generic.xaml` and  the `ParallaxBackgroundHub` class for the implementation of this effect.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Samples

[Transform3D Animations](https://github.com/Microsoft/Windows-universal-samples/tree/master/xaml_transform3danimations/)

### Reference

[UIElement.Transform3D](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.transform3d.aspx)

[PerspectiveTransform3D](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.media.media3d.perspectivetransform3d.aspx)

[CompositeTransform3D](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.media.media3d.compositetransform3d.aspx)

## System requirements

**Client:** Windows 10 Insider Preview

**Server:** Windows 10 Insider Preview

**Phone:**  Windows 10 Insider Preview

## Build the sample

1. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
2. Go to the directory to which you unzipped the sample. Then go to the subdirectory containing the sample in the language you desire - either C++, C#, or JavaScript. Double-click the Visual Studio 2015 Solution (.sln) file. 
3. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**. 

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 
