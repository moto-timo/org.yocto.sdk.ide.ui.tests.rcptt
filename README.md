# org.yocto.sdk.ide.ui.tests.rcptt

Examples of tests for the [Yocto Project plugins] for [Eclipse] using the Rich
Client Platform Testing Tool ([RCPTT]).

Use this project with the [RCPTT IDE] or the RCPTT plugins in a Eclipse IDE to edit or author new tests. It is highly recommended that you read through the [RCPTT Documentation].

Bind mount this project into the ```crops/eclipse-rcptt-test-runner-container``` to easily execute your tests in a clean, repeatable environment.

```
docker run --rm -t -v /home/$USER/rcpttWorkspace/org.yocto.sdk.ide.ui.tests.rcptt:/org.yocto.sdk.ide.ui.tests.rcptt \
-v /home/$USER/workdir:/workdir crops/eclipse-rcptt-test-runner:neon \
--project=/org.yocto.sdk.ide.ui.tests.rcptt
```

[Yocto Project plugins]: http://git.yoctoproject.org/cgit/cgit.cgi/eclipse-poky/ "Yocto Project plugins"
[Eclipse]: http:/eclipse.org/ "Eclipse"
[RCPTT]: http://eclipse.org/rcptt "RCPTT"
[RCPTT IDE]: https://eclipse.org/rcptt/download "RCPTT IDE'
[RCPTT Documentation]: http://www.eclipse.org/rcptt/documentation/userguide/getstarted "RCPTT Documentation"
