[![Maven metadata URL](https://img.shields.io/maven-metadata/v?color=blue&metadataUrl=https://s01.oss.sonatype.org/service/local/repo_groups/public/content/cafe/adriel/voyager/voyager-core/maven-metadata.xml&style=for-the-badge)](https://repo.maven.apache.org/maven2/cafe/adriel/voyager/)
[![Android API](https://img.shields.io/badge/api-21%2B-brightgreen.svg?style=for-the-badge)](https://android-arsenal.com/api?level=21)
[![kotlin](https://img.shields.io/github/languages/top/adrielcafe/voyager.svg?style=for-the-badge&color=blueviolet)](https://kotlinlang.org/)
[![ktlint](https://img.shields.io/badge/code%20style-%E2%9D%A4-FF4081.svg?style=for-the-badge)](https://ktlint.github.io/)
[![License MIT](https://img.shields.io/github/license/adrielcafe/voyager.svg?style=for-the-badge&color=orange)](https://opensource.org/licenses/MIT)

<h1 align="center">
    <img height="150" src="https://user-images.githubusercontent.com/2512298/127723355-f56b3040-47cb-44fd-8504-a1868721c1a3.png"/>
    <br>
    <a href="https://en.wikipedia.org/wiki/USS_Voyager_(Star_Trek)">Voyager</a>: Compose on Warp Speed
</h1>

A lightweight and pragmatic navigation library built for, and seamlessly integrated with, [Jetpack Compose](https://developer.android.com/jetpack/compose). 

Turn on the Warp Drive and enjoy the trek 🖖

```kotlin
class HomeScreen : Screen {

    @Composable
    override fun Content() {
        // ...
    }
}


class SingleActivity : ComponentActivity() {

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)

        setContent {
            Navigator(HomeScreen())
        }
    }
}
```

### Documentation
See the [project website](https://voyager.adriel.cafe) for documentation and APIs.

### Features
- Create scalable Single-Activity apps powered by a [pragmatic API](https://voyager.adriel.cafe/navigation/fundamentals)
- [Tab navigation](https://voyager.adriel.cafe/navigation/tab-navigation) like [Youtube app](https://play.google.com/store/apps/details?id=com.google.android.youtube)
- [Nested navigation](https://voyager.adriel.cafe/navigation/nested-navigation) if you need to manage multiple stacks
- [State restoration](https://voyager.adriel.cafe/state-restoration) after Activity recreation
- State-aware [Stack API](https://voyager.adriel.cafe/stack-api)
- Built-in [transitions](https://voyager.adriel.cafe/transitions)
- [Lifecycle](https://voyager.adriel.cafe/lifecycle) callbacks
- [Back press](https://voyager.adriel.cafe/back-press) handling
- [Deep linking](https://voyager.adriel.cafe/deep-links) support

### Roadmap
- [Multi-module navigation](https://voyager.adriel.cafe/navigation/multi-module-navigation)
- [Compose for Desktop](https://github.com/JetBrains/compose-jb) support

### Samples
| [Stack API](https://github.com/adrielcafe/voyager/tree/main/sample/src/main/java/cafe/adriel/voyager/sample/stateStack) | [Basic nav.](https://github.com/adrielcafe/voyager/tree/main/sample/src/main/java/cafe/adriel/voyager/sample/basicNavigation) | [Tab nav.](https://github.com/adrielcafe/voyager/tree/main/sample/src/main/java/cafe/adriel/voyager/sample/tabNavigation) | [Nested nav.](https://github.com/adrielcafe/voyager/tree/main/sample/src/main/java/cafe/adriel/voyager/sample/nestedNavigation) |
|-------|------------|----------|-------------|
| ![navigation-stack](https://user-images.githubusercontent.com/2512298/126323192-9b6349fe-7b96-4acf-b62e-c75165d909e1.gif) | ![navigation-basic](https://user-images.githubusercontent.com/2512298/126323165-47760eec-2ba2-48ee-8e3a-841d50098d33.gif) | ![navigation-tab](https://user-images.githubusercontent.com/2512298/126323588-2f970953-0adb-47f8-b2fb-91c5854656bd.gif) | ![navigation-nested](https://user-images.githubusercontent.com/2512298/126323027-a2633aef-9402-4df8-9384-45935d7986cf.gif) |