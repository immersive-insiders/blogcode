# blogcodebuildscript 
{

 repositories 
 {

   google()

   jcenter()

 }

 dependencies 
 {

   // Must be Android Gradle Plugin 3.6.0 or later. For a list of

   // compatible Gradle versions refer to:

   // https://developer.android.com/studio/releases/gradle-plugin

   classpath 'com.android.tools.build:gradle:3.6.0'

 }

}

allprojects 
{

 repositories

 {

   google()

   jcenter()

   flatDir
   
   {

   dirs 'libs'

   }

 }

}
