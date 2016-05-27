# mvn-repo
###如何使用
* 在项目的build.gradle repositories中加上

> maven { url 'https://raw.githubusercontent.com/lingyfh/mvn-repo/master/' }

* 在dependencies中加上需要依赖的库

> compile 'org.generalutil:generalutil:0.0.1-alpha@aar'



##EX##

> build.gradle

> ......

> repositories {

>    maven { url 'https://raw.githubusercontent.com/lingyfh/mvn-repo/master/' }

>    jcenter()

> }

> dependencies {

>    compile 'org.generalutil:generalutil:0.0.1-alpha@aar'

> }
