### Just run `ExampleUnitTest` to see the following stacktrace:

```
android.view.InflateException: XML file build/intermediates/res/merged/debug/layout/abc_screen_toolbar.xml line #-1 (sorry, not yet implemented): Error inflating class android.support.v7.widget.Toolbar

	at android.view.LayoutInflater.createView(LayoutInflater.java:613)
	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:687)
	at android.view.LayoutInflater.rInflate(LayoutInflater.java:746)
	at android.view.LayoutInflater.rInflate(LayoutInflater.java:749)
	at android.view.LayoutInflater.inflate(LayoutInflater.java:489)
	at android.view.LayoutInflater.inflate(LayoutInflater.java:396)
	at android.view.LayoutInflater.inflate(LayoutInflater.java:352)
	at android.support.v7.app.AppCompatDelegateImplV7.createSubDecor(AppCompatDelegateImplV7.java:379)
	at android.support.v7.app.AppCompatDelegateImplV7.ensureSubDecor(AppCompatDelegateImplV7.java:300)
	at android.support.v7.app.AppCompatDelegateImplV7.setContentView(AppCompatDelegateImplV7.java:264)
	at android.support.v7.app.AppCompatActivity.setContentView(AppCompatActivity.java:129)
	at io.sweers.vectordrawablesadness.OtherActivity.onCreate(OtherActivity.java:12)
	at android.app.Activity.performCreate(Activity.java:5008)
	at org.robolectric.util.ReflectionHelpers.callInstanceMethod(ReflectionHelpers.java:195)
	at org.robolectric.util.ActivityController$1.run(ActivityController.java:122)
	at org.robolectric.shadows.ShadowLooper.runPaused(ShadowLooper.java:304)
	at org.robolectric.shadows.CoreShadowsAdapter$2.runPaused(CoreShadowsAdapter.java:45)
	at org.robolectric.util.ActivityController.create(ActivityController.java:118)
	at org.robolectric.util.ActivityController.create(ActivityController.java:129)
	at org.robolectric.util.ActivityController.setup(ActivityController.java:210)
	at org.robolectric.Robolectric.setupActivity(Robolectric.java:46)
	at io.sweers.vectordrawablesadness.ExampleUnitTest.<init>(ExampleUnitTest.java:21)
	at org.junit.runners.BlockJUnit4ClassRunner.createTest(BlockJUnit4ClassRunner.java:217)
	at org.robolectric.RobolectricTestRunner$HelperTestRunner.createTest(RobolectricTestRunner.java:520)
	at org.junit.runners.BlockJUnit4ClassRunner$1.runReflectiveCall(BlockJUnit4ClassRunner.java:266)
	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
	at org.junit.runners.BlockJUnit4ClassRunner.methodBlock(BlockJUnit4ClassRunner.java:263)
	at org.robolectric.RobolectricTestRunner$HelperTestRunner.methodBlock(RobolectricTestRunner.java:530)
	at org.robolectric.RobolectricTestRunner$2.evaluate(RobolectricTestRunner.java:247)
	at org.robolectric.RobolectricTestRunner.runChild(RobolectricTestRunner.java:188)
	at org.robolectric.RobolectricTestRunner.runChild(RobolectricTestRunner.java:54)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.robolectric.RobolectricTestRunner$1.evaluate(RobolectricTestRunner.java:152)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
	at com.intellij.junit4.JUnit4IdeaTestRunner.startRunnerWithArgs(JUnit4IdeaTestRunner.java:69)
	at com.intellij.rt.execution.junit.JUnitStarter.prepareStreamsAndStart(JUnitStarter.java:234)
	at com.intellij.rt.execution.junit.JUnitStarter.main(JUnitStarter.java:74)
	at com.intellij.rt.execution.application.AppMain.main(AppMain.java:144)
Caused by: java.lang.reflect.InvocationTargetException
	at sun.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
	at sun.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
	at java.lang.reflect.Constructor.newInstance(Constructor.java:422)
	at android.view.LayoutInflater.$$robo$$createView(LayoutInflater.java:587)
	at android.view.LayoutInflater.createView(LayoutInflater.java)
	at android.view.LayoutInflater.$$robo$$createViewFromTag(LayoutInflater.java:687)
	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java)
	at android.view.LayoutInflater.$$robo$$rInflate(LayoutInflater.java:746)
	at android.view.LayoutInflater.rInflate(LayoutInflater.java)
	at android.view.LayoutInflater.$$robo$$rInflate(LayoutInflater.java:749)
	at android.view.LayoutInflater.rInflate(LayoutInflater.java)
	at android.view.LayoutInflater.$$robo$$inflate(LayoutInflater.java:489)
	at android.view.LayoutInflater.inflate(LayoutInflater.java)
	at android.view.LayoutInflater.$$robo$$inflate(LayoutInflater.java:396)
	at android.view.LayoutInflater.inflate(LayoutInflater.java)
	at android.view.LayoutInflater.$$robo$$inflate(LayoutInflater.java:352)
	at android.view.LayoutInflater.inflate(LayoutInflater.java)
	at android.support.v7.app.AppCompatDelegateImplV7.$$robo$$createSubDecor(AppCompatDelegateImplV7.java:379)
	at android.support.v7.app.AppCompatDelegateImplV7.createSubDecor(AppCompatDelegateImplV7.java)
	at android.support.v7.app.AppCompatDelegateImplV7.$$robo$$ensureSubDecor(AppCompatDelegateImplV7.java:300)
	at android.support.v7.app.AppCompatDelegateImplV7.ensureSubDecor(AppCompatDelegateImplV7.java)
	at android.support.v7.app.AppCompatDelegateImplV7.$$robo$$setContentView(AppCompatDelegateImplV7.java:264)
	at android.support.v7.app.AppCompatDelegateImplV7.setContentView(AppCompatDelegateImplV7.java)
	at android.support.v7.app.AppCompatActivity.$$robo$$setContentView(AppCompatActivity.java:129)
	at android.support.v7.app.AppCompatActivity.setContentView(AppCompatActivity.java)
	at io.sweers.vectordrawablesadness.OtherActivity.onCreate(OtherActivity.java:12)
	at android.app.Activity.$$robo$$performCreate(Activity.java:5008)
	at android.app.Activity.performCreate(Activity.java)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	at org.robolectric.util.ReflectionHelpers.callInstanceMethod(ReflectionHelpers.java:195)
	at org.robolectric.util.ActivityController$1.run(ActivityController.java:122)
	at org.robolectric.shadows.ShadowLooper.runPaused(ShadowLooper.java:304)
	at org.robolectric.shadows.CoreShadowsAdapter$2.runPaused(CoreShadowsAdapter.java:45)
	at org.robolectric.util.ActivityController.create(ActivityController.java:118)
	at org.robolectric.util.ActivityController.create(ActivityController.java:129)
	at org.robolectric.util.ActivityController.setup(ActivityController.java:210)
	at org.robolectric.Robolectric.setupActivity(Robolectric.java:46)
	at io.sweers.vectordrawablesadness.ExampleUnitTest.<init>(ExampleUnitTest.java:21)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
	at sun.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
	at java.lang.reflect.Constructor.newInstance(Constructor.java:422)
	at org.junit.runners.BlockJUnit4ClassRunner.createTest(BlockJUnit4ClassRunner.java:217)
	at org.robolectric.RobolectricTestRunner$HelperTestRunner.createTest(RobolectricTestRunner.java:520)
	at org.junit.runners.BlockJUnit4ClassRunner$1.runReflectiveCall(BlockJUnit4ClassRunner.java:266)
	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
	at org.junit.runners.BlockJUnit4ClassRunner.methodBlock(BlockJUnit4ClassRunner.java:263)
	at org.robolectric.RobolectricTestRunner$HelperTestRunner.methodBlock(RobolectricTestRunner.java:530)
	at org.robolectric.RobolectricTestRunner$2.evaluate(RobolectricTestRunner.java:247)
	at org.robolectric.RobolectricTestRunner.runChild(RobolectricTestRunner.java:188)
	at org.robolectric.RobolectricTestRunner.runChild(RobolectricTestRunner.java:54)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.robolectric.RobolectricTestRunner$1.evaluate(RobolectricTestRunner.java:152)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
	at com.intellij.junit4.JUnit4IdeaTestRunner.startRunnerWithArgs(JUnit4IdeaTestRunner.java:69)
	at com.intellij.rt.execution.junit.JUnitStarter.prepareStreamsAndStart(JUnitStarter.java:234)
	at com.intellij.rt.execution.junit.JUnitStarter.main(JUnitStarter.java:74)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:497)
	... 1 more
Caused by: android.content.res.Resources$NotFoundException: File build/intermediates/res/merged/debug/drawable/abc_ic_ab_back_material.xml from drawable resource ID #0x7f020016
	at android.content.res.Resources.loadDrawable(Resources.java:1918)
	at org.robolectric.util.ReflectionHelpers.callInstanceMethod(ReflectionHelpers.java:195)
	at org.robolectric.internal.Shadow.directlyOn(Shadow.java:44)
	at org.robolectric.shadows.ShadowResources.loadDrawable(ShadowResources.java:505)
	at android.content.res.Resources.loadDrawable(Resources.java)
	at android.content.res.Resources.getDrawable(Resources.java:659)
	at android.support.v4.content.ContextCompat.getDrawable(ContextCompat.java:323)
	at android.support.v7.widget.AppCompatDrawableManager.getDrawable(AppCompatDrawableManager.java:180)
	at android.support.v7.widget.AppCompatDrawableManager.getDrawable(AppCompatDrawableManager.java:173)
	at android.support.v7.widget.TintTypedArray.getDrawable(TintTypedArray.java:60)
	at android.support.v7.widget.Toolbar.__constructor__(Toolbar.java:254)
	at android.support.v7.widget.Toolbar.<init>(Toolbar.java)
	at android.view.LayoutInflater.createView(LayoutInflater.java:587)
	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:687)
	at android.view.LayoutInflater.rInflate(LayoutInflater.java:746)
	at android.view.LayoutInflater.rInflate(LayoutInflater.java:749)
	at android.view.LayoutInflater.inflate(LayoutInflater.java:489)
	at android.view.LayoutInflater.inflate(LayoutInflater.java:396)
	at android.view.LayoutInflater.inflate(LayoutInflater.java:352)
	at android.support.v7.app.AppCompatDelegateImplV7.createSubDecor(AppCompatDelegateImplV7.java:379)
	at android.support.v7.app.AppCompatDelegateImplV7.ensureSubDecor(AppCompatDelegateImplV7.java:300)
	at android.support.v7.app.AppCompatDelegateImplV7.setContentView(AppCompatDelegateImplV7.java:264)
	at android.support.v7.app.AppCompatActivity.setContentView(AppCompatActivity.java:129)
	at io.sweers.vectordrawablesadness.OtherActivity.onCreate(OtherActivity.java:12)
	at android.app.Activity.performCreate(Activity.java:5008)
	at org.robolectric.util.ReflectionHelpers.callInstanceMethod(ReflectionHelpers.java:195)
	at org.robolectric.util.ActivityController$1.run(ActivityController.java:122)
	at org.robolectric.shadows.ShadowLooper.runPaused(ShadowLooper.java:304)
	at org.robolectric.shadows.CoreShadowsAdapter$2.runPaused(CoreShadowsAdapter.java:45)
	at org.robolectric.util.ActivityController.create(ActivityController.java:118)
	at org.robolectric.util.ActivityController.create(ActivityController.java:129)
	at org.robolectric.util.ActivityController.setup(ActivityController.java:210)
	at org.robolectric.Robolectric.setupActivity(Robolectric.java:46)
	at io.sweers.vectordrawablesadness.ExampleUnitTest.<init>(ExampleUnitTest.java:21)
	at org.junit.runners.BlockJUnit4ClassRunner.createTest(BlockJUnit4ClassRunner.java:217)
	at org.robolectric.RobolectricTestRunner$HelperTestRunner.createTest(RobolectricTestRunner.java:520)
	at org.junit.runners.BlockJUnit4ClassRunner$1.runReflectiveCall(BlockJUnit4ClassRunner.java:266)
	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
	at org.junit.runners.BlockJUnit4ClassRunner.methodBlock(BlockJUnit4ClassRunner.java:263)
	at org.robolectric.RobolectricTestRunner$HelperTestRunner.methodBlock(RobolectricTestRunner.java:530)
	at org.robolectric.RobolectricTestRunner$2.evaluate(RobolectricTestRunner.java:247)
	at org.robolectric.RobolectricTestRunner.runChild(RobolectricTestRunner.java:188)
	at org.robolectric.RobolectricTestRunner.runChild(RobolectricTestRunner.java:54)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.robolectric.RobolectricTestRunner$1.evaluate(RobolectricTestRunner.java:152)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
	at com.intellij.junit4.JUnit4IdeaTestRunner.startRunnerWithArgs(JUnit4IdeaTestRunner.java:69)
	at com.intellij.rt.execution.junit.JUnitStarter.prepareStreamsAndStart(JUnitStarter.java:234)
	at com.intellij.rt.execution.junit.JUnitStarter.main(JUnitStarter.java:74)
	... 1 more
Caused by: org.xmlpull.v1.XmlPullParserException: XML file build/intermediates/res/merged/debug/drawable/abc_ic_ab_back_material.xml line #-1 (sorry, not yet implemented): invalid drawable tag vector
	at android.graphics.drawable.Drawable.createFromXmlInner(Drawable.java:877)
	at android.graphics.drawable.Drawable.createFromXml(Drawable.java:818)
	at android.content.res.Resources.loadDrawable(Resources.java:1915)
	... 54 more
```
