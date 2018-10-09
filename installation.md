# Installation steps

There are many methods to install the SDK. The recommended one is using the `Check out project from Version Control` option in Android Studio. Alternatively you can use git to clone the repo `git clone --depth=1 git@bitbucket.org:phantomrobotics/kit.git`, or download it direclty as a zip from [here](https://bitbucket.org/phantomrobotics/kit/downloads/), extract it and import it.

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

![Git VCS](https://www.github.com/IAmTheVex/phantom/blob/master/resources/images/installation/import1.png?raw=true)

Now you can follow the import procedure described [here](https://iamthevex.github.io/phantom/import) or just follow your intuition and click on next until you can click on finish 😄
