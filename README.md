##Default Apps
Default jumlah method dan besaran file apk ketika dibuild


## Library
- [DexCount - for method counter](https://github.com/KeepSafe/dexcount-gradle-plugin)
- design-support
- cardview
- recyclerview
- [Retrofit 2.0](https://github.com/square/retrofit)
- [Picasso](https://github.com/square/picasso)
- [RxAndroid]()
- [RxJava]
- [RxBinding]
- [Timber]()
- [Butterknife]()
- Retrolambda

### Build using gradle 
```
pratama$box >> ./gradlew assembleDebug

:app:compileDebugJavaWithJavac UP-TO-DATE
:app:compileRetrolambdaDebug UP-TO-DATE
:app:compileDebugNdk UP-TO-DATE
:app:compileDebugSources UP-TO-DATE
:app:preDexDebug
:app:dexDebug
:app:validateDebugSigning
:app:packageDebug
:app:zipalignDebug
:app:assembleDebug
Total methods in app-debug.apk: 28074
Total fields in app-debug.apk:  13554

BUILD SUCCESSFUL

Total time: 33.137 secs

```

```
pratama$box >> gradle clean build
:app:assembleDebug
Total methods in app-debug.apk: 28074
Total fields in app-debug.apk:  13554
:app:checkReleaseManifest
:app:prepareReleaseDependencies
:app:compileReleaseAidl
:app:compileReleaseRenderscript
:app:generateReleaseBuildConfig
:app:generateReleaseAssets UP-TO-DATE
:app:mergeReleaseAssets
:app:generateReleaseResValues UP-TO-DATE
:app:generateReleaseResources
:app:mergeReleaseResources
:app:processReleaseManifest
:app:processReleaseResources
:app:generateReleaseSources
:app:processReleaseJavaRes UP-TO-DATE
:app:compileReleaseJavaWithJavac
:app:compileRetrolambdaRelease
:app:compileReleaseNdk UP-TO-DATE
:app:compileReleaseSources
:app:preDexRelease
:app:dexRelease
:app:packageRelease
:app:assembleRelease
Total methods in app-release-unsigned.apk: 28073
Total fields in app-release-unsigned.apk:  13554
:app:assemble
:app:compileLint
:app:lint
Ran lint on variant debug: 7 issues found
Ran lint on variant release: 7 issues found
Wrote HTML report to file:/Users/pratama/Documents/Workspace/explore/TestingAPKSize/app/build/outputs/lint-results.html
Wrote XML report to /Users/pratama/Documents/Workspace/explore/TestingAPKSize/app/build/outputs/lint-results.xml
:app:preDebugUnitTestBuild UP-TO-DATE
:app:prepareDebugUnitTestDependencies
:app:processDebugUnitTestJavaRes UP-TO-DATE
:app:compileDebugUnitTestJavaWithJavac
:app:compileDebugUnitTestSources
:app:mockableAndroidJar
:app:assembleDebugUnitTest
:app:testDebugUnitTest
:app:preReleaseUnitTestBuild UP-TO-DATE
:app:prepareReleaseUnitTestDependencies
:app:processReleaseUnitTestJavaRes UP-TO-DATE
:app:compileReleaseUnitTestJavaWithJavac
:app:compileReleaseUnitTestSources
:app:assembleReleaseUnitTest
:app:testReleaseUnitTest
:app:test
:app:check
:app:build

BUILD SUCCESSFUL

Total time: 46.442 secs

```

### File Size
- app-release.apk -> 1.9MB
- app-debug.apk -> 1.9MB