##Default Apps
Default jumlah method dan besaran file apk ketika dibuild


## Library
- [DexCount - for method counter](https://github.com/KeepSafe/dexcount-gradle-plugin)

### Build using gradle 
```
pratama$box >> ./gradlew assembleDebug

:app:compileDebugJavaWithJavac UP-TO-DATE
:app:compileDebugNdk UP-TO-DATE
:app:compileDebugSources UP-TO-DATE
:app:preDexDebug
:app:dexDebug
:app:validateDebugSigning
:app:packageDebug
:app:zipalignDebug
:app:assembleDebug
Total methods in app-debug.apk: 16610
Total fields in app-debug.apk:  8654

BUILD SUCCESSFUL

Total time: 16.466 secs

```

```
pratama$box >> gradle clean build

Parallel execution is an incubating feature.
:app:clean
:clean
:app:assembleDebug
Total methods in app-debug.apk: 16610
Total fields in app-debug.apk:  8654
:app:checkReleaseManifest
:app:prepareReleaseDependencies
:app:compileReleaseAidl
:app:compileReleaseRenderscript
:app:packageRelease
:app:assembleRelease
Total methods in app-release-unsigned.apk: 16608
Total fields in app-release-unsigned.apk:  8654
:app:assemble
:app:compileLint
:app:lint
Ran lint on variant release: 5 issues found
Ran lint on variant debug: 5 issues found
Wrote HTML report to file:/Users/pratama/Documents/Workspace/explore/TestingAPKSize/app/build/outputs/lint-results.html
Wrote XML report to /Users/pratama/Documents/Workspace/explore/TestingAPKSize/app/build/outputs/lint-results.xml
:app:preDebugUnitTestBuild UP-TO-DATE
:app:prepareDebugUnitTestDependencies
:app:processDebugUnitTestJavaRes UP-TO-DATE

:app:testReleaseUnitTest
:app:test
:app:check
:app:build

BUILD SUCCESSFUL

Total time: 34.145 secs

```

### File Size