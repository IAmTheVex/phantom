# Installation steps

There are many methods to install the SDK. The recommended one is using the `Check out project from Version Control` option in Android Studio. Alternatively you can use git to clone the repo `git clone --depth=1 git@bitbucket.org:phantomrobotics/kit.git`, or download it direclty as a zip from [here](https://bitbucket.org/phantomrobotics/kit/downloads/), extract it and import it (you can learn how to do that [here](https://iamthevex.github.io/phantom/import)).

![Bitbucket Download](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/download.png?raw=true)

Before you install the SDK make sure your Android Studio version supports Kotlin out of the box or install the Kotlin plugin for Intellij IDEA/Android Studio.

## Check out project from Version Control

Is a good practice to use VCS because you can easily upgrade your local SDK if a new version is published. The new versions will NOT bring breaking changes. The VCS is also a nice tool for collaborative coding (features like branching).

When you open up Android Studio, one of the options is to check out a project from Version Control. Click on that.

![Android Studio Option](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/clone1.png?raw=true)

You will be prompted to choose what type of VCS you have. Phantom is using Git (and so does a huge number of people), so click on the Git option.

![Git VCS](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/clone2.png?raw=true)

In the next popup you need to choose the directory where you want the project to be stored and also where to clone it from. The url is `git@bitbucket.org:phantomrobotics/kit.git`. You can also click the test button to check if it's working. After that you may hit the clone button.

![Git VCS](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/clone3.png?raw=true)

Now wait for the clone procedure to finish.

![Git VCS](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/clone4.png?raw=true)

After the clone procedure is finished you will be surprised with a nice dialog that asks you if you would like to import the cloned project. Click yes.

![Import](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/import1.png?raw=true)

Now you can follow the import procedure described [here](https://iamthevex.github.io/phantom/import) or just follow your intuition and click on next until you can click on finish 😄

After the import is done you are basically ready to go! The first thing you need to do is to rename your package to match your team name (not mandatory but pretty important). You can find it in the Android view on the left.

![Android](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/android.png?raw=true)

If you don't see the view, just double tap on the module name, in this case `main`.

![Show](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/show.png?raw=true)

Navigate in the package tree until you see `com.yourteam`. Right click on that, then go to `Refactor > Rename` in the contextual menu.

![Rename](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/rename1.png?raw=true)

Choose a good name (you can change it later) and click on refactor.

![Rename](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/rename2.png?raw=true)

After the IDE finishes it's jobs, you are ready to Rock! Click on `SimpleGameUnit` to get a taste of how your code will look like.

![Code](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/code.png?raw=true)

Now you're ready to run your Phantom SDK based app on your phone! Give it a spin! (You may also want to follow FIRST's instructions on this)

![Run](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/run.png?raw=true)

Good work, champ! You installed the Phantom SDK! Now you are ready to develop modular apps! You might want to install the plugin, for easyer and faster development. You can learn how to do that [here](https://iamthevex.github.io/phantom/plugin).