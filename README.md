# First Spark Project

Setup Scala and Spark in Intellij in Mac
  1. Open Intellij and go to Intellij IDEA in the toolbar and click on Preference
  2. Select Plugins
  3. Install Scala, sbt, lambok and Save Actions
  4. Restart your Intellij IDE
  5. Go to New ==> Project ==> Select Scala ==> select sbt ==> Select Scala Version(when I'm writing this, current version is 2.13.0 but spark 2.3.0 is not compiled with this version, so please use suitable version)
  6. Click on Finish
  7. You are able to configure scala project, to enable spark go to build.sbt file
  8.ADD below lines at the end of the file
    a. libraryDependencies += "org.apache.spark" %% "spark-core" % "<Your desired spark version>"
  9. Import RatingCounter File in IDE and execute it
