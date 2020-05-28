# PolarDesigner
Our open-source plug-in developed by [Thomas](https://github.com/thomasdeppisch), [IEM](https://iem.kug.ac.at/en/) and [AA](https://austrian.audio/).

PolarDesigner allows you to control the polar pattern of your OC818 microphone in up to five frequency bands.  
Available as VST3, AAX and AU. Get installers for Windows and Mac at [austrian.audio](https://austrian.audio/).

<img width="1102" alt="PolarDesigner Screenshot" src="https://user-images.githubusercontent.com/18114953/83127074-01b25300-a0da-11ea-9e91-8035f2645530.png">

## Building PolarDesigner
PolarDesigner is based on [JUCE](https://juce.com/). To build PolarDesigner, get a recent version of JUCE and open PolarDesigner.jucer in Projucer. Select an exporter of your choice (e.g. Visual Studio or XCode) to create and open a project file in your IDE.

## Requirements
* FFTW: PolarDesigner links FFTW statically. Download [FFTW](http://fftw.org/) and put header and lib files in /resources/fftw_win/ and resources/fftw_osx/.
* For building AAX plugins you need to add the [AAX SDK](http://developer.avid.com/) location to your Projucer paths.

## Related repositories
Parts of the code are based on the [IEM Plugin Suite](https://git.iem.at/audioplugins/IEMPluginSuite) - check it out, it's awesome!
