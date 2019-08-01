### Fork Goals
These are the goals for this fork. I wont send pull requests for all of them. Each goal will have it's own banch, and all complete goals are in the master branch.
- [ ] detect multiple keyboards separately (Android)
- [X] get gamepad system Id (Ex: Android InputDevice Id)
- [ ] Arial font is proprietary and should be replaced
- [ ] remove jlayer (all my games will use Ogg)
- [X] set mp3 on HTML5 to not required be default (SoundManager2)
- [X] Change Mouse Cursor Image (Android 7+)
- [ ] Capture Mouse Pointer (Android 8+)
- [ ] Ability to get button clicks and precise motion events from separate mice at the same time. (Android)
- [ ] Ability to distinguish between mice and touch events. (Android)
- [ ] Change onPause to onStop to better support multi window mode (Android)
- [X] add check for fullscreen (Android)
- [X] Android gamepad vibrations
- [ ] Maybe change some code to better anticipate hotpluggable touch screens (Android, JavaScript)
- [ ] try out new audio engine for html: https://github.com/libgdx/libgdx/pull/5659
- [ ] documentation for all third party licenses
- [ ] Android be pure Java
- [ ] javascript send Gdx.app.log to console.log()
- [ ] get rid of isMobileDevice, OUYA mapping, xperia play mapping, ...
- [ ] open/save files with Storage Access Framework (Android)

### Canceled Fork Goals
- get gamepad vendor id and product id

![logo](http://libgdx.badlogicgames.com/img/logo.png)

[![Jenkins build status](https://libgdx.badlogicgames.com/jenkins/buildStatus/icon?job=libgdx&.png)](https://libgdx.badlogicgames.com/jenkins/job/libgdx/) (Jenkins)

[![Travis build status](https://travis-ci.org/libgdx/libgdx.svg?branch=master)](https://travis-ci.org/libgdx/libgdx) (Travis)

libGDX is a cross-platform Java game development framework based on 
OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your
WebGL enabled browser and iOS.

### Getting Started
  * [Setup your development environment (Eclipse, Intellij IDEA, NetBeans)](https://github.com/libgdx/libgdx/wiki/Setting-up-your-Development-Environment-%28Eclipse%2C-Intellij-IDEA%2C-NetBeans%29)
  * [Create a libGDX project](https://github.com/libgdx/libgdx/wiki/Project-Setup-Gradle)
    * Import, Run, Debug and Package your project
      * [Eclipse](https://github.com/libgdx/libgdx/wiki/Gradle-and-Eclipse)
      * [Intellij IDEA](https://github.com/libgdx/libgdx/wiki/Gradle-and-Intellij-IDEA)
      * [NetBeans](https://github.com/libgdx/libgdx/wiki/Gradle-and-NetBeans)
      * [Commandline](https://github.com/libgdx/libgdx/wiki/Gradle-on-the-Commandline)
  * [Read the Wiki](https://github.com/libgdx/libgdx/wiki)

### Downloads
As we switched to Gradle, there's no need to download libGDX itself anymore. For those of you who still prefer the old way of doing things, you can get libGDX from the [official download site](http://libgdx.badlogicgames.com/download.html).

### Documentation
The [Wiki](https://github.com/libgdx/libgdx/wiki) contains all the information you'll need to write a 
libGDX game. You can contribute to the Wiki directly here on GitHub!

We also provide [Javadocs](http://libgdx.badlogicgames.com/nightlies/docs/api/) online. The Javadocs are
also bundled as source Jars with every libGDX distribution for consumption in your favorite IDE.

### News & Community
You can follow the latest news about libGDX on the [blog](http://www.badlogicgames.com). Follow
[@badlogicgames](https://twitter.com/badlogicgames) for real-time updates.

You can get help on our [forum](http://badlogicgames.com/forum/) and talk to other libGDX 
users on our IRC channel #libgdx at irc.freenode.net.

Another way of getting help or talking to other libGDX users is the [libgdx discord](https://discord.gg/6pgDK9F).

### Reporting Issues
Use the [issue tracker](https://github.com/libgdx/libgdx/issues?page=1&state=open) here on GitHub to report issues. Make sure you read the 
[Getting Help](https://github.com/libgdx/libgdx/wiki/Getting-help) article that walks you through
the process or properly reporting an issue.

### Contributing & Working from Source
libGDX has a strong developer community constantly improving the code base. We love to
get any and all help we can. The [Contributing](https://github.com/libgdx/libgdx/wiki/Contributing) 
article describes the process of helping libGDX to become even better.

To contribute, you need to work with libGDX' sources directly, something normal users do not
have to go through. The [Working with the Source](https://github.com/libgdx/libgdx/wiki/Running-demos-%26-tests)
article will give you directions.

You can also contribute financially to our infrastructure (build server, web server, test devices) via our [Patreon](http://patreon.com/libgdx)!

### License
libGDX is licensed under the [Apache 2 License](http://www.apache.org/licenses/LICENSE-2.0.html), meaning you
can use it free of charge, without strings attached in commercial and non-commercial projects. We love to
get (non-mandatory) credit in case you release a game or app using libgdx!

### Supported By
libGDX is supported by helpful 3rd parties via code contributions, free licenses, test devices and so forth. Make our supporters happy and visit their sites!

<table>
<tr>
<td style="text-align: center;"><a href="https://github.com/MobiVM/robovm"><img style="margin-right:20px" src="http://libgdx.badlogicgames.com/img/robovm.png" alt="RoboVM" /></a></td>
<td style="text-align: center;"><a href="http://bit.ly/spinegdx"><img src="http://libgdx.badlogicgames.com/img/spine.png"></a></td>
</tr>

<tr>
<td style="text-align: center;"><a href="http://bit.ly/saikoagdx"><img style="margin-right:20px" src="http://libgdx.badlogicgames.com/img/saikoa.png" alt="Saikoa" /></a></td>
<td style="text-align: center;"><a href="http://bit.ly/intelgdx"><img src="http://libgdx.badlogicgames.com/img/intel.png" alt="intel Software Partner" /></a></td>
</tr>

<tr>
<td style="text-align: center;"><a href="http://bit.ly/jetblog"><img src="http://libgdx.badlogicgames.com/img/excelsior.png" alt="Excelsior JET"></a></td>
<td style="text-align: center;"><a href="http://bit.ly/nextpeergdx"><img src="http://libgdx.badlogicgames.com/img/nextpeer.png"></a></td>
</tr>
</table>

Intel and the Intel logo are trademarks of Intel Corporation in the U.S. and/or other countries.
