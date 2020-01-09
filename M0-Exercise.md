## M0 - Setup and Preparation

1. Download and install the [Java Development Kit (JDK)](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html). Make sure to download JDK 8 (the latest update for JDK 8 is JDK 8u231).
2. Download and install [Intellij IDEA IDE](https://www.jetbrains.com/idea/download/).
3. Clone the [Demo project](https://github.com/jin-guo/COMP303_CodeDemos) project into your Eclipse workspace. In the Intellij IDE, click `File -> New -> Project from Version Control -> Git` and under URI enter `https://github.com/jin-guo/COMP303_CodeDemos.git`, then click-through. Once imported, the project should compile without errors.
4. Just like you did for step 3, clone the [JetUML](https://github.com/jin-guo/JetUML) project into your workspace. For convenience, you can also download the [executable file](https://github.com/prmr/JetUML/releases) and place it somewhere convenient.
5. Just like you did for steps 3 and 4, clone the [Solitaire](https://github.com/jin-guo/Solitaire) project into your workspace.

To ensure that everything works:

1. In the Demo project, in package `...m0.demo`, right-click on the file `Welcome.java` and select `Run 'Welcome.main()'`. You should see a small GUI application appear. Try the different buttons which should do the obvious thing.
2. Right-click on the file `TestAlternatingLabelProvider.java` and select ``Run 'TestAlternatingLabelProvider'``. You should see the message with tests passed.
3. Right-click again on the file `TestAlternatingLabelProvider.java` and select `Run 'TestAlternatingLabelProvider' with Coverage`. You should see a report showing coverage information.
4. Once everything works as described above, change line 37 of file `AlternatingLabelProvider.java` to return `aLabel1` instead of `aLabel2`, and re-run the test. The test should fail.

---
Note: some content is updated from previous exercises [here](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-00.md) by Martin P. Robillard
