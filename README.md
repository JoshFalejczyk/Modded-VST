# Modded-VST

This is a VST Plugin built using the JUCE Framework (which is written in C++).  VST Plugins are an area of huge interest to me, as both a musician and Computer Science student interested in Audio/Digital Signal Processing.  VST's are essentially integrated software interfaces that act as a layer over DAW's (digital audio workstations), that usually work to replicate or emulate some physical studio recording process.  As someone who plays guitar and bass, I've noticed that in the past decade or so, the use of VST Plugins in place of amps and pedals in particular has exploded.  This has piqued my interest in seeing if I can work on a VST myself, to not only gain more knowledge in the development of this type of software, but to also produce something tailored towards my personal wants and needs in musical equipment.  In other words, I think a good bar to set on quality would be if I can use this software as one would use any other VST.  I've quickly become acquainted with JUCE, a VST framework used by multiple key players in the VST industry.  It's surprisingly versatile, and has certainly covered all my needs.  To start off relatively basic, I thought it best to take a preexisting example provided by JUCE, and mod it however I'd like from there.  I selected the DSPModulePluginDemo example in particular, and began working off of it as a base.  Below, I have the changes by version logged:

Versions:
-------------------------------------------------------
V1.0: 

      1. Changed VST title for personal project.
      2. Relabeled "Input Gain" to "Gain" and "Output 
      Gain" to "Volume" to create controls more 
      familiar to a guitar pedal
      3. For Distortion, added custom waveshaping 
      function "Custom function 1" which produces 
      a more traditional distortion effect.
      4. For Distortion, added custom waveshaping 
      function "Custom function 2" which produces a 
      more aggressive distortion effect.
      5. For Distortion, added custom waveshaping 
      function "Custom function 3" which produces a 
      square wave, fuzz-like effect.

Inside the repository, you'll find the the Source folder containing all main source code.  Unfortunately due to GitHub's 100mb file upload limit, I could not include the files related to the JUCE project structure, or all the dependencies from JUCE's header library.  But hypothetically speaking, should one have JUCE downloaded, they can just take the source code from this repository and put it into a blank project of their own.  Additionally, inside the Plugin folder, the latest version of the VST in both a standalone and VST3 format are available to demo.  While I intend on focusing mainly on the distortion effect of the plugin at the moment, the base example provides multiple effects to potentially modify.  Overall though, this project was quite fun to start and I am excited for future mods and updates.

Credit: 
-Any code not listed in the changes log has been written and provided by JUCE.  As seen in the license commented out in the source code, my modifications are within the copyright regulations on the example VST.
-Any code listed in the changes log is of my own work.
