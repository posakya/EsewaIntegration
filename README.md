# EsewaIntegration

add esewa aar file 
// build.gradle
flatDir {
            dirs 'libs'
        }
        
  as this
allprojects {
    repositories {
        google()
        jcenter()
        flatDir {
            dirs 'libs'
        }
    }
}

/// add dependency
implementation(name: "eSewaSdk", ext: "aar")
