# Awesome Swift Playgrounds [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)  ![155 playgrounds](https://img.shields.io/badge/Playgrounds:-155-orange.svg)

> A curated list of awesome Swift playgrounds.

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/uraimo/awesome-swift-playgrounds/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/uraimo/awesome-swift-playgrounds/graphs/contributors); you rock!

If you see a playground here that does not work anymore with the current release of Xcode or is not a good fit, please submit a pull request to improve this file or consider updating it, thank you!

### Downloading all the playgrounds

Unless otherwise indicated, all playgrounds are compatible with Swift 3.

All the playgrounds are available as submodules in the `playgrounds/` directory, to download them all in one go, just clone this repository with `git clone --recursive https://github.com/uraimo/Awesome-Swift-Playgrounds.git` or execute `git submodule update --init` after you have cloned the repository the usual way. 

Apple's playgrounds distributed as zip archives have to be downloaded manually.

### Tags

🌟 = My personal favorites

🍁 = Swift 4+ Playground

⏳ = Pre-Swift 3 Playground

### Contents

- [PlaygroundBooks](#playgroundbooks)
- [Learning Swift](#learning-swift)
- [Learning Swift: Advanced Topics](#learning-swift-advanced-topics)
  - [Design Patterns](#design-patterns)
  - [Protocol Oriented Programming](#protocol-oriented-programming)
  - [Functional Reactive Programming](#functional-reactive-programming)
- [Apple's Playgrounds](#apples-playgrounds)
- [WWDC Students Submissions](#wwdc-students-submissions)
- [Playgrounds about Playgrounds](#playgrounds-about-playgrounds)
- [Playgrounds from Playgroundbooks](#playgrounds-from-playgroundbooks)
- [Theoretical Computer Science](#theoretical-computer-science)
    - [Algorithms and Data Structures](#algorithms-and-data-structures)
    - [Languages](#languages)
    - [Machine Learning](#machine-learning)
- [UIKit And Graphics](#uikit-and-graphics)
  - [Core Image](#core-image)
  - [Metal](#metal)
  - [Animations](#animations)
  - [SpriteKit](#spritekit)
- [Audio](#audio)
- [Mathematics](#mathematics)
- [Libraries and APIs](#libraries-and-apis)
- [Playground sets](#playground-sets)
- [Miscellaneous](#miscellaneous)


## PlaygroundBooks
*Playgrounds that can be run on your iPad*

* [Guilloche Pattern Playground Book](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁

   ![](https://img.shields.io/github/stars/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/last-commit/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/issues/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/issues-pr/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/license/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/forks/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/contributors/TheWildHorse/GuillochePlayground)

* [Accessibility](https://github.com/xReee/wwdc2018) - Accessibility for iOS developers. 🍁 

   ![](https://img.shields.io/github/stars/xReee/wwdc2018) ![](https://img.shields.io/github/last-commit/xReee/wwdc2018) ![](https://img.shields.io/github/issues/xReee/wwdc2018) ![](https://img.shields.io/github/issues-pr/xReee/wwdc2018) ![](https://img.shields.io/github/license/xReee/wwdc2018) ![](https://img.shields.io/github/forks/xReee/wwdc2018) ![](https://img.shields.io/github/contributors/xReee/wwdc2018)

* [TJBot Playground](https://github.com/jweisz/tjbot-playground) - Swift Playground for interacting with IBM's TJBot. 🍁

   ![](https://img.shields.io/github/stars/jweisz/tjbot-playground) ![](https://img.shields.io/github/last-commit/jweisz/tjbot-playground) ![](https://img.shields.io/github/issues/jweisz/tjbot-playground) ![](https://img.shields.io/github/issues-pr/jweisz/tjbot-playground) ![](https://img.shields.io/github/license/jweisz/tjbot-playground) ![](https://img.shields.io/github/forks/jweisz/tjbot-playground) ![](https://img.shields.io/github/contributors/jweisz/tjbot-playground)

* [Tree Trouble Playbook](https://github.com/joelrorseth/Tree-Trouble) - An interactive Swift Playground Book about Binary Search Trees.

   ![](https://img.shields.io/github/stars/joelrorseth/Tree-Trouble) ![](https://img.shields.io/github/last-commit/joelrorseth/Tree-Trouble) ![](https://img.shields.io/github/issues/joelrorseth/Tree-Trouble) ![](https://img.shields.io/github/issues-pr/joelrorseth/Tree-Trouble) ![](https://img.shields.io/github/license/joelrorseth/Tree-Trouble) ![](https://img.shields.io/github/forks/joelrorseth/Tree-Trouble) ![](https://img.shields.io/github/contributors/joelrorseth/Tree-Trouble)

* [Auto Pong](https://github.com/cardoso/AutoPong) - A tutorial to implement a pong based on a simple AI.

   ![](https://img.shields.io/github/stars/cardoso/AutoPong) ![](https://img.shields.io/github/last-commit/cardoso/AutoPong) ![](https://img.shields.io/github/issues/cardoso/AutoPong) ![](https://img.shields.io/github/issues-pr/cardoso/AutoPong) ![](https://img.shields.io/github/license/cardoso/AutoPong) ![](https://img.shields.io/github/forks/cardoso/AutoPong) ![](https://img.shields.io/github/contributors/cardoso/AutoPong)

* [Neural Network Playground](https://github.com/hetelek/Neural-Network-Playground) - A neural network Swift playground, with no third party dependencies.

   ![](https://img.shields.io/github/stars/hetelek/Neural-Network-Playground) ![](https://img.shields.io/github/last-commit/hetelek/Neural-Network-Playground) ![](https://img.shields.io/github/issues/hetelek/Neural-Network-Playground) ![](https://img.shields.io/github/issues-pr/hetelek/Neural-Network-Playground) ![](https://img.shields.io/github/license/hetelek/Neural-Network-Playground) ![](https://img.shields.io/github/forks/hetelek/Neural-Network-Playground) ![](https://img.shields.io/github/contributors/hetelek/Neural-Network-Playground)

* [Window Manager Playground](https://github.com/steventroughtonsmith/windowmanager-playgroundbook) - Playground for an experimental window manager.

   ![](https://img.shields.io/github/stars/steventroughtonsmith/windowmanager-playgroundbook) ![](https://img.shields.io/github/last-commit/steventroughtonsmith/windowmanager-playgroundbook) ![](https://img.shields.io/github/issues/steventroughtonsmith/windowmanager-playgroundbook) ![](https://img.shields.io/github/issues-pr/steventroughtonsmith/windowmanager-playgroundbook) ![](https://img.shields.io/github/license/steventroughtonsmith/windowmanager-playgroundbook) ![](https://img.shields.io/github/forks/steventroughtonsmith/windowmanager-playgroundbook) ![](https://img.shields.io/github/contributors/steventroughtonsmith/windowmanager-playgroundbook)

* [AudioKit Playground Book](https://github.com/audiokit/Playgrounds) - A set of playgrounds using AudioKit designed for the iPad Playgrounds app.

   ![](https://img.shields.io/github/stars/audiokit/Playgrounds) ![](https://img.shields.io/github/last-commit/audiokit/Playgrounds) ![](https://img.shields.io/github/issues/audiokit/Playgrounds) ![](https://img.shields.io/github/issues-pr/audiokit/Playgrounds) ![](https://img.shields.io/github/license/audiokit/Playgrounds) ![](https://img.shields.io/github/forks/audiokit/Playgrounds) ![](https://img.shields.io/github/contributors/audiokit/Playgrounds)

* [Numsw](https://github.com/sonsongithub/numsw) - A swift playground book that mimics some of the features of numpy and jupyter notebook.

   ![](https://img.shields.io/github/stars/sonsongithub/numsw) ![](https://img.shields.io/github/last-commit/sonsongithub/numsw) ![](https://img.shields.io/github/issues/sonsongithub/numsw) ![](https://img.shields.io/github/issues-pr/sonsongithub/numsw) ![](https://img.shields.io/github/license/sonsongithub/numsw) ![](https://img.shields.io/github/forks/sonsongithub/numsw) ![](https://img.shields.io/github/contributors/sonsongithub/numsw)

* [File Browser Playground](https://github.com/steventroughtonsmith/files-playgroundbook) - Simple File Browser for Swift Playgrounds on iOS.

   ![](https://img.shields.io/github/stars/steventroughtonsmith/files-playgroundbook) ![](https://img.shields.io/github/last-commit/steventroughtonsmith/files-playgroundbook) ![](https://img.shields.io/github/issues/steventroughtonsmith/files-playgroundbook) ![](https://img.shields.io/github/issues-pr/steventroughtonsmith/files-playgroundbook) ![](https://img.shields.io/github/license/steventroughtonsmith/files-playgroundbook) ![](https://img.shields.io/github/forks/steventroughtonsmith/files-playgroundbook) ![](https://img.shields.io/github/contributors/steventroughtonsmith/files-playgroundbook)

* [Geometry with Swift](https://github.com/dbbudd/Geometry-Swift-PlaygroundBook) - In this course your students will learn the fundamentals of Swift 3 programming, using geometry as their context for learning. 

   ![](https://img.shields.io/github/stars/dbbudd/Geometry-Swift-PlaygroundBook) ![](https://img.shields.io/github/last-commit/dbbudd/Geometry-Swift-PlaygroundBook) ![](https://img.shields.io/github/issues/dbbudd/Geometry-Swift-PlaygroundBook) ![](https://img.shields.io/github/issues-pr/dbbudd/Geometry-Swift-PlaygroundBook) ![](https://img.shields.io/github/license/dbbudd/Geometry-Swift-PlaygroundBook) ![](https://img.shields.io/github/forks/dbbudd/Geometry-Swift-PlaygroundBook) ![](https://img.shields.io/github/contributors/dbbudd/Geometry-Swift-PlaygroundBook)

* [Image Filtering](https://github.com/lennet/image-filtering) - A Swift playgroundbook about Image Filtering. 🍁🌟

   ![](https://img.shields.io/github/stars/lennet/image-filtering) ![](https://img.shields.io/github/last-commit/lennet/image-filtering) ![](https://img.shields.io/github/issues/lennet/image-filtering) ![](https://img.shields.io/github/issues-pr/lennet/image-filtering) ![](https://img.shields.io/github/license/lennet/image-filtering) ![](https://img.shields.io/github/forks/lennet/image-filtering) ![](https://img.shields.io/github/contributors/lennet/image-filtering)

* [Spacetime Rhapsody](https://github.com/hollisliu/Spacetime-Rhapsody) - A Swift Playground visualizing gravity based on Einstein's Theory of General Relativity. 🌟

   ![](https://img.shields.io/github/stars/hollisliu/Spacetime-Rhapsody) ![](https://img.shields.io/github/last-commit/hollisliu/Spacetime-Rhapsody) ![](https://img.shields.io/github/issues/hollisliu/Spacetime-Rhapsody) ![](https://img.shields.io/github/issues-pr/hollisliu/Spacetime-Rhapsody) ![](https://img.shields.io/github/license/hollisliu/Spacetime-Rhapsody) ![](https://img.shields.io/github/forks/hollisliu/Spacetime-Rhapsody) ![](https://img.shields.io/github/contributors/hollisliu/Spacetime-Rhapsody)

* [Neural Network](https://github.com/lennet/neuralnetwork) - A Swift PlaygroundBook about Neural Networks. 🍁

   ![](https://img.shields.io/github/stars/lennet/neuralnetwork) ![](https://img.shields.io/github/last-commit/lennet/neuralnetwork) ![](https://img.shields.io/github/issues/lennet/neuralnetwork) ![](https://img.shields.io/github/issues-pr/lennet/neuralnetwork) ![](https://img.shields.io/github/license/lennet/neuralnetwork) ![](https://img.shields.io/github/forks/lennet/neuralnetwork) ![](https://img.shields.io/github/contributors/lennet/neuralnetwork)

* [coreml-playground](https://github.com/kkk669/coreml-playground) - Core ML examples for Swift Playgrounds. 🍁

   ![](https://img.shields.io/github/stars/kkk669/coreml-playground) ![](https://img.shields.io/github/last-commit/kkk669/coreml-playground) ![](https://img.shields.io/github/issues/kkk669/coreml-playground) ![](https://img.shields.io/github/issues-pr/kkk669/coreml-playground) ![](https://img.shields.io/github/license/kkk669/coreml-playground) ![](https://img.shields.io/github/forks/kkk669/coreml-playground) ![](https://img.shields.io/github/contributors/kkk669/coreml-playground)

* [SF Symbols Viewer](https://github.com/kkk669/SF-Symbols-Viewer) - An SF Symbols Viewer for Swift Playgrounds. 🍁

   ![](https://img.shields.io/github/stars/kkk669/SF-Symbols-Viewer) ![](https://img.shields.io/github/last-commit/kkk669/SF-Symbols-Viewer) ![](https://img.shields.io/github/issues/kkk669/SF-Symbols-Viewer) ![](https://img.shields.io/github/issues-pr/kkk669/SF-Symbols-Viewer) ![](https://img.shields.io/github/license/kkk669/SF-Symbols-Viewer) ![](https://img.shields.io/github/forks/kkk669/SF-Symbols-Viewer) ![](https://img.shields.io/github/contributors/kkk669/SF-Symbols-Viewer)

* [jscore-playground](https://github.com/kkk669/jscore-playground) - A JavaScript REPL using JavaScriptCore. 🍁

   ![](https://img.shields.io/github/stars/kkk669/jscore-playground) ![](https://img.shields.io/github/last-commit/kkk669/jscore-playground) ![](https://img.shields.io/github/issues/kkk669/jscore-playground) ![](https://img.shields.io/github/issues-pr/kkk669/jscore-playground) ![](https://img.shields.io/github/license/kkk669/jscore-playground) ![](https://img.shields.io/github/forks/kkk669/jscore-playground) ![](https://img.shields.io/github/contributors/kkk669/jscore-playground)

* [Accessible Reality](https://github.com/aheze/AccessibleReality) - for learning the basics of ARKit through interactive lessons. 🍁

   ![](https://img.shields.io/github/stars/aheze/AccessibleReality) ![](https://img.shields.io/github/last-commit/aheze/AccessibleReality) ![](https://img.shields.io/github/issues/aheze/AccessibleReality) ![](https://img.shields.io/github/issues-pr/aheze/AccessibleReality) ![](https://img.shields.io/github/license/aheze/AccessibleReality) ![](https://img.shields.io/github/forks/aheze/AccessibleReality) ![](https://img.shields.io/github/contributors/aheze/AccessibleReality)



## Learning Swift
*Some interesting playgrounds to learn Swift*

* [What's new in Swift 4](https://github.com/ole/whats-new-in-swift-4) - An Xcode playground showing off the new features in Swift 4.0. 🍁 🌟 

   ![](https://img.shields.io/github/stars/ole/whats-new-in-swift-4) ![](https://img.shields.io/github/last-commit/ole/whats-new-in-swift-4) ![](https://img.shields.io/github/issues/ole/whats-new-in-swift-4) ![](https://img.shields.io/github/issues-pr/ole/whats-new-in-swift-4) ![](https://img.shields.io/github/license/ole/whats-new-in-swift-4) ![](https://img.shields.io/github/forks/ole/whats-new-in-swift-4) ![](https://img.shields.io/github/contributors/ole/whats-new-in-swift-4)

* [What's new in Swift 4.2](https://github.com/ole/whats-new-in-swift-4-2) - An Xcode playground showing off the new features in Swift 4.2. 🍁 🌟 

   ![](https://img.shields.io/github/stars/ole/whats-new-in-swift-4-2) ![](https://img.shields.io/github/last-commit/ole/whats-new-in-swift-4-2) ![](https://img.shields.io/github/issues/ole/whats-new-in-swift-4-2) ![](https://img.shields.io/github/issues-pr/ole/whats-new-in-swift-4-2) ![](https://img.shields.io/github/license/ole/whats-new-in-swift-4-2) ![](https://img.shields.io/github/forks/ole/whats-new-in-swift-4-2) ![](https://img.shields.io/github/contributors/ole/whats-new-in-swift-4-2)

* [Codable Playground](https://github.com/filip-zielinski/CodablePlayground) - Playground that demonstrates advanced uses of Codable. 🍁

   ![](https://img.shields.io/github/stars/filip-zielinski/CodablePlayground) ![](https://img.shields.io/github/last-commit/filip-zielinski/CodablePlayground) ![](https://img.shields.io/github/issues/filip-zielinski/CodablePlayground) ![](https://img.shields.io/github/issues-pr/filip-zielinski/CodablePlayground) ![](https://img.shields.io/github/license/filip-zielinski/CodablePlayground) ![](https://img.shields.io/github/forks/filip-zielinski/CodablePlayground) ![](https://img.shields.io/github/contributors/filip-zielinski/CodablePlayground)

* [Generics In Swift](https://github.com/LukeSkywalker55/Generics-In-Swift) - Playground that explains generics. 🍁

   ![](https://img.shields.io/github/stars/LukeSkywalker55/Generics-In-Swift) ![](https://img.shields.io/github/last-commit/LukeSkywalker55/Generics-In-Swift) ![](https://img.shields.io/github/issues/LukeSkywalker55/Generics-In-Swift) ![](https://img.shields.io/github/issues-pr/LukeSkywalker55/Generics-In-Swift) ![](https://img.shields.io/github/license/LukeSkywalker55/Generics-In-Swift) ![](https://img.shields.io/github/forks/LukeSkywalker55/Generics-In-Swift) ![](https://img.shields.io/github/contributors/LukeSkywalker55/Generics-In-Swift)

* [Swift String Cheat Sheet](https://github.com/kharrison/Playground-Strings) - A quick guide to using Strings with Swift. 🍁

   ![](https://img.shields.io/github/stars/kharrison/Playground-Strings) ![](https://img.shields.io/github/last-commit/kharrison/Playground-Strings) ![](https://img.shields.io/github/issues/kharrison/Playground-Strings) ![](https://img.shields.io/github/issues-pr/kharrison/Playground-Strings) ![](https://img.shields.io/github/license/kharrison/Playground-Strings) ![](https://img.shields.io/github/forks/kharrison/Playground-Strings) ![](https://img.shields.io/github/contributors/kharrison/Playground-Strings)

* [About Swift](https://github.com/NicolaLancellotti-About/About-Swift) - A playground about Swift language.  🍁

   ![](https://img.shields.io/github/stars/NicolaLancellotti-About/About-Swift) ![](https://img.shields.io/github/last-commit/NicolaLancellotti-About/About-Swift) ![](https://img.shields.io/github/issues/NicolaLancellotti-About/About-Swift) ![](https://img.shields.io/github/issues-pr/NicolaLancellotti-About/About-Swift) ![](https://img.shields.io/github/license/NicolaLancellotti-About/About-Swift) ![](https://img.shields.io/github/forks/NicolaLancellotti-About/About-Swift) ![](https://img.shields.io/github/contributors/NicolaLancellotti-About/About-Swift)

* [The Swift Programming Language Playgrounds](https://github.com/danielpi/Swift-Playgrounds) - 40+ playgrounds, one for each chapter of Apple's Swift book. 🌟

   ![](https://img.shields.io/github/stars/danielpi/Swift-Playgrounds) ![](https://img.shields.io/github/last-commit/danielpi/Swift-Playgrounds) ![](https://img.shields.io/github/issues/danielpi/Swift-Playgrounds) ![](https://img.shields.io/github/issues-pr/danielpi/Swift-Playgrounds) ![](https://img.shields.io/github/license/danielpi/Swift-Playgrounds) ![](https://img.shields.io/github/forks/danielpi/Swift-Playgrounds) ![](https://img.shields.io/github/contributors/danielpi/Swift-Playgrounds)

* [Swift Hack Pack](https://github.com/GuildSA/swift-hack-pack) - Collection of playgrounds that teaches Swift.

   ![](https://img.shields.io/github/stars/GuildSA/swift-hack-pack) ![](https://img.shields.io/github/last-commit/GuildSA/swift-hack-pack) ![](https://img.shields.io/github/issues/GuildSA/swift-hack-pack) ![](https://img.shields.io/github/issues-pr/GuildSA/swift-hack-pack) ![](https://img.shields.io/github/license/GuildSA/swift-hack-pack) ![](https://img.shields.io/github/forks/GuildSA/swift-hack-pack) ![](https://img.shields.io/github/contributors/GuildSA/swift-hack-pack)

* [The Swift Summary Book](https://github.com/jakarmy/swift-summary) - A summary of Apple's Swift language. 🌟

   ![](https://img.shields.io/github/stars/jakarmy/swift-summary) ![](https://img.shields.io/github/last-commit/jakarmy/swift-summary) ![](https://img.shields.io/github/issues/jakarmy/swift-summary) ![](https://img.shields.io/github/issues-pr/jakarmy/swift-summary) ![](https://img.shields.io/github/license/jakarmy/swift-summary) ![](https://img.shields.io/github/forks/jakarmy/swift-summary) ![](https://img.shields.io/github/contributors/jakarmy/swift-summary)

* [Swifter Tips](https://github.com/swifter-tips/Playground) - Examples for every feature of the Swift language.

   ![](https://img.shields.io/github/stars/swifter-tips/Playground) ![](https://img.shields.io/github/last-commit/swifter-tips/Playground) ![](https://img.shields.io/github/issues/swifter-tips/Playground) ![](https://img.shields.io/github/issues-pr/swifter-tips/Playground) ![](https://img.shields.io/github/license/swifter-tips/Playground) ![](https://img.shields.io/github/forks/swifter-tips/Playground) ![](https://img.shields.io/github/contributors/swifter-tips/Playground)

* [MPCS51032 UChicago iOS Course](https://github.com/uchicago-mobi/mcps51032-2017-spring-playground) - Playgrounds from the 2017 Spring iOS course of the University of Chicago.

   ![](https://img.shields.io/github/stars/uchicago-mobi/mcps51032-2017-spring-playground) ![](https://img.shields.io/github/last-commit/uchicago-mobi/mcps51032-2017-spring-playground) ![](https://img.shields.io/github/issues/uchicago-mobi/mcps51032-2017-spring-playground) ![](https://img.shields.io/github/issues-pr/uchicago-mobi/mcps51032-2017-spring-playground) ![](https://img.shields.io/github/license/uchicago-mobi/mcps51032-2017-spring-playground) ![](https://img.shields.io/github/forks/uchicago-mobi/mcps51032-2017-spring-playground) ![](https://img.shields.io/github/contributors/uchicago-mobi/mcps51032-2017-spring-playground)



## Learning Swift: Advanced Topics
*Advanced topics, useful once you have mastered the basics of the language*

* [A Swift Introduction to Core Data](https://github.com/andyshep/CoreDataPlaygrounds) - Learn Core Data experimenting directly in this playground. 🌟

   ![](https://img.shields.io/github/stars/andyshep/CoreDataPlaygrounds) ![](https://img.shields.io/github/last-commit/andyshep/CoreDataPlaygrounds) ![](https://img.shields.io/github/issues/andyshep/CoreDataPlaygrounds) ![](https://img.shields.io/github/issues-pr/andyshep/CoreDataPlaygrounds) ![](https://img.shields.io/github/license/andyshep/CoreDataPlaygrounds) ![](https://img.shields.io/github/forks/andyshep/CoreDataPlaygrounds) ![](https://img.shields.io/github/contributors/andyshep/CoreDataPlaygrounds)

* [TDDSwiftPlayground](https://github.com/sshrpe/TDDSwiftPlayground) - Demonstration of using Swift Playgrounds in Test Driven Development with XCTest.

   ![](https://img.shields.io/github/stars/sshrpe/TDDSwiftPlayground) ![](https://img.shields.io/github/last-commit/sshrpe/TDDSwiftPlayground) ![](https://img.shields.io/github/issues/sshrpe/TDDSwiftPlayground) ![](https://img.shields.io/github/issues-pr/sshrpe/TDDSwiftPlayground) ![](https://img.shields.io/github/license/sshrpe/TDDSwiftPlayground) ![](https://img.shields.io/github/forks/sshrpe/TDDSwiftPlayground) ![](https://img.shields.io/github/contributors/sshrpe/TDDSwiftPlayground)

* [Concurrency on iOS](https://github.com/sammyd/2017AtSwift_Concurrency) - Concurrency and Parallelism in iOS.

   ![](https://img.shields.io/github/stars/sammyd/2017AtSwift_Concurrency) ![](https://img.shields.io/github/last-commit/sammyd/2017AtSwift_Concurrency) ![](https://img.shields.io/github/issues/sammyd/2017AtSwift_Concurrency) ![](https://img.shields.io/github/issues-pr/sammyd/2017AtSwift_Concurrency) ![](https://img.shields.io/github/license/sammyd/2017AtSwift_Concurrency) ![](https://img.shields.io/github/forks/sammyd/2017AtSwift_Concurrency) ![](https://img.shields.io/github/contributors/sammyd/2017AtSwift_Concurrency)

* [Modern Core Data](https://github.com/dfreniche/modern-core-data-playground) - An introduction to Core Data.

   ![](https://img.shields.io/github/stars/dfreniche/modern-core-data-playground) ![](https://img.shields.io/github/last-commit/dfreniche/modern-core-data-playground) ![](https://img.shields.io/github/issues/dfreniche/modern-core-data-playground) ![](https://img.shields.io/github/issues-pr/dfreniche/modern-core-data-playground) ![](https://img.shields.io/github/license/dfreniche/modern-core-data-playground) ![](https://img.shields.io/github/forks/dfreniche/modern-core-data-playground) ![](https://img.shields.io/github/contributors/dfreniche/modern-core-data-playground)

* [Swift DSL Example](https://github.com/cfdrake/swift-dsl-example) - Implementation of a DSL in Swift.

   ![](https://img.shields.io/github/stars/cfdrake/swift-dsl-example) ![](https://img.shields.io/github/last-commit/cfdrake/swift-dsl-example) ![](https://img.shields.io/github/issues/cfdrake/swift-dsl-example) ![](https://img.shields.io/github/issues-pr/cfdrake/swift-dsl-example) ![](https://img.shields.io/github/license/cfdrake/swift-dsl-example) ![](https://img.shields.io/github/forks/cfdrake/swift-dsl-example) ![](https://img.shields.io/github/contributors/cfdrake/swift-dsl-example)

* [Katan](https://github.com/marciok/katan) - A micro web server that replies "Hello world!" to every request, an example of how to use sockets in Swift.

   ![](https://img.shields.io/github/stars/marciok/katan) ![](https://img.shields.io/github/last-commit/marciok/katan) ![](https://img.shields.io/github/issues/marciok/katan) ![](https://img.shields.io/github/issues-pr/marciok/katan) ![](https://img.shields.io/github/license/marciok/katan) ![](https://img.shields.io/github/forks/marciok/katan) ![](https://img.shields.io/github/contributors/marciok/katan)

* [Swift Regular Expressions](https://github.com/ogulcan/SwiftRegEx) - A playground to learn regular expressions with Swift.

   ![](https://img.shields.io/github/stars/ogulcan/SwiftRegEx) ![](https://img.shields.io/github/last-commit/ogulcan/SwiftRegEx) ![](https://img.shields.io/github/issues/ogulcan/SwiftRegEx) ![](https://img.shields.io/github/issues-pr/ogulcan/SwiftRegEx) ![](https://img.shields.io/github/license/ogulcan/SwiftRegEx) ![](https://img.shields.io/github/forks/ogulcan/SwiftRegEx) ![](https://img.shields.io/github/contributors/ogulcan/SwiftRegEx)

* [Network Stack](https://github.com/AndrejKolar/NetworkStack) - Clean & simple Swift networking stack playground.

   ![](https://img.shields.io/github/stars/AndrejKolar/NetworkStack) ![](https://img.shields.io/github/last-commit/AndrejKolar/NetworkStack) ![](https://img.shields.io/github/issues/AndrejKolar/NetworkStack) ![](https://img.shields.io/github/issues-pr/AndrejKolar/NetworkStack) ![](https://img.shields.io/github/license/AndrejKolar/NetworkStack) ![](https://img.shields.io/github/forks/AndrejKolar/NetworkStack) ![](https://img.shields.io/github/contributors/AndrejKolar/NetworkStack)

* [Swiftly Typed Resources](https://github.com/jstart/Swiftly-Typed-Resources) - A playground showing how Swift makes Strings, Colors, Fonts, Images, etc easier to deal with. ⏳

   ![](https://img.shields.io/github/stars/jstart/Swiftly-Typed-Resources) ![](https://img.shields.io/github/last-commit/jstart/Swiftly-Typed-Resources) ![](https://img.shields.io/github/issues/jstart/Swiftly-Typed-Resources) ![](https://img.shields.io/github/issues-pr/jstart/Swiftly-Typed-Resources) ![](https://img.shields.io/github/license/jstart/Swiftly-Typed-Resources) ![](https://img.shields.io/github/forks/jstart/Swiftly-Typed-Resources) ![](https://img.shields.io/github/contributors/jstart/Swiftly-Typed-Resources)

* [Swift KVO Closures](https://github.com/rectalogic/KVOPlayground) - Swift KVO playground. ⏳ 

   ![](https://img.shields.io/github/stars/rectalogic/KVOPlayground) ![](https://img.shields.io/github/last-commit/rectalogic/KVOPlayground) ![](https://img.shields.io/github/issues/rectalogic/KVOPlayground) ![](https://img.shields.io/github/issues-pr/rectalogic/KVOPlayground) ![](https://img.shields.io/github/license/rectalogic/KVOPlayground) ![](https://img.shields.io/github/forks/rectalogic/KVOPlayground) ![](https://img.shields.io/github/contributors/rectalogic/KVOPlayground)

* [Swift Date Tutorial](https://github.com/liuyubobobo/Swift-NSDate-Tutorial) - Learn everythig about NSDate. ⏳ 

   ![](https://img.shields.io/github/stars/liuyubobobo/Swift-NSDate-Tutorial) ![](https://img.shields.io/github/last-commit/liuyubobobo/Swift-NSDate-Tutorial) ![](https://img.shields.io/github/issues/liuyubobobo/Swift-NSDate-Tutorial) ![](https://img.shields.io/github/issues-pr/liuyubobobo/Swift-NSDate-Tutorial) ![](https://img.shields.io/github/license/liuyubobobo/Swift-NSDate-Tutorial) ![](https://img.shields.io/github/forks/liuyubobobo/Swift-NSDate-Tutorial) ![](https://img.shields.io/github/contributors/liuyubobobo/Swift-NSDate-Tutorial)

* [Swift And C](https://github.com/MacMark/SwiftAndC) - Examples about using C with Swift. ⏳ 

   ![](https://img.shields.io/github/stars/MacMark/SwiftAndC) ![](https://img.shields.io/github/last-commit/MacMark/SwiftAndC) ![](https://img.shields.io/github/issues/MacMark/SwiftAndC) ![](https://img.shields.io/github/issues-pr/MacMark/SwiftAndC) ![](https://img.shields.io/github/license/MacMark/SwiftAndC) ![](https://img.shields.io/github/forks/MacMark/SwiftAndC) ![](https://img.shields.io/github/contributors/MacMark/SwiftAndC)

* [Swift Memory Management](https://github.com/ndethore/swift-memory-management) - How to avoid retain cycles, from [this post](http://detho.re/2016/01/21/writing-memory-efficient-swift-code/). ⏳

   ![](https://img.shields.io/github/stars/ndethore/swift-memory-management) ![](https://img.shields.io/github/last-commit/ndethore/swift-memory-management) ![](https://img.shields.io/github/issues/ndethore/swift-memory-management) ![](https://img.shields.io/github/issues-pr/ndethore/swift-memory-management) ![](https://img.shields.io/github/license/ndethore/swift-memory-management) ![](https://img.shields.io/github/forks/ndethore/swift-memory-management) ![](https://img.shields.io/github/contributors/ndethore/swift-memory-management)


### Design Patterns

* [The Principles of OOD in Swift 4](https://github.com/ochococo/OOD-Principles-In-Swift) - The Principles of OOD based on Uncle Bob articles.🍁

   ![](https://img.shields.io/github/stars/ochococo/OOD-Principles-In-Swift) ![](https://img.shields.io/github/last-commit/ochococo/OOD-Principles-In-Swift) ![](https://img.shields.io/github/issues/ochococo/OOD-Principles-In-Swift) ![](https://img.shields.io/github/issues-pr/ochococo/OOD-Principles-In-Swift) ![](https://img.shields.io/github/license/ochococo/OOD-Principles-In-Swift) ![](https://img.shields.io/github/forks/ochococo/OOD-Principles-In-Swift) ![](https://img.shields.io/github/contributors/ochococo/OOD-Principles-In-Swift)

* [Design Patterns Playground](https://github.com/edopelawi/DesignPatternsPlayground) - Learning GoF's Design Patterns in Swift 3.

   ![](https://img.shields.io/github/stars/edopelawi/DesignPatternsPlayground) ![](https://img.shields.io/github/last-commit/edopelawi/DesignPatternsPlayground) ![](https://img.shields.io/github/issues/edopelawi/DesignPatternsPlayground) ![](https://img.shields.io/github/issues-pr/edopelawi/DesignPatternsPlayground) ![](https://img.shields.io/github/license/edopelawi/DesignPatternsPlayground) ![](https://img.shields.io/github/forks/edopelawi/DesignPatternsPlayground) ![](https://img.shields.io/github/contributors/edopelawi/DesignPatternsPlayground)

* [iOS Design Patterns](https://github.com/haxpor/ios-design-patterns) - Sample projects for MVC, MVP, MVVM, and VIPER.

   ![](https://img.shields.io/github/stars/haxpor/ios-design-patterns) ![](https://img.shields.io/github/last-commit/haxpor/ios-design-patterns) ![](https://img.shields.io/github/issues/haxpor/ios-design-patterns) ![](https://img.shields.io/github/issues-pr/haxpor/ios-design-patterns) ![](https://img.shields.io/github/license/haxpor/ios-design-patterns) ![](https://img.shields.io/github/forks/haxpor/ios-design-patterns) ![](https://img.shields.io/github/contributors/haxpor/ios-design-patterns)

* [Design Patterns in Swift](https://github.com/ochococo/Design-Patterns-In-Swift) - Design patterns in Swift 3.

   ![](https://img.shields.io/github/stars/ochococo/Design-Patterns-In-Swift) ![](https://img.shields.io/github/last-commit/ochococo/Design-Patterns-In-Swift) ![](https://img.shields.io/github/issues/ochococo/Design-Patterns-In-Swift) ![](https://img.shields.io/github/issues-pr/ochococo/Design-Patterns-In-Swift) ![](https://img.shields.io/github/license/ochococo/Design-Patterns-In-Swift) ![](https://img.shields.io/github/forks/ochococo/Design-Patterns-In-Swift) ![](https://img.shields.io/github/contributors/ochococo/Design-Patterns-In-Swift)

* [GOF Swift](https://github.com/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) - Learn all 23 Gang of Four patterns using Swift.

   ![](https://img.shields.io/github/stars/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) ![](https://img.shields.io/github/last-commit/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) ![](https://img.shields.io/github/issues/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) ![](https://img.shields.io/github/issues-pr/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) ![](https://img.shields.io/github/license/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) ![](https://img.shields.io/github/forks/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift) ![](https://img.shields.io/github/contributors/SebastianBoldt/Gang-of-Four-and-Solid-Principles-in-Swift)


### Protocol Oriented Programming

* [Swift Diagram Playgrounds](https://github.com/alskipp/Swift-Diagram-Playgrounds) - Adaptation of the Protocol-Oriented Programming in Swift talk from WWDC 2015.

   ![](https://img.shields.io/github/stars/alskipp/Swift-Diagram-Playgrounds) ![](https://img.shields.io/github/last-commit/alskipp/Swift-Diagram-Playgrounds) ![](https://img.shields.io/github/issues/alskipp/Swift-Diagram-Playgrounds) ![](https://img.shields.io/github/issues-pr/alskipp/Swift-Diagram-Playgrounds) ![](https://img.shields.io/github/license/alskipp/Swift-Diagram-Playgrounds) ![](https://img.shields.io/github/forks/alskipp/Swift-Diagram-Playgrounds) ![](https://img.shields.io/github/contributors/alskipp/Swift-Diagram-Playgrounds)

* [Swift Protocol Extensions](https://github.com/davidahouse/SwiftProtocolExtensions) - A playground to explore Protocol Extensions. ⏳ 

   ![](https://img.shields.io/github/stars/davidahouse/SwiftProtocolExtensions) ![](https://img.shields.io/github/last-commit/davidahouse/SwiftProtocolExtensions) ![](https://img.shields.io/github/issues/davidahouse/SwiftProtocolExtensions) ![](https://img.shields.io/github/issues-pr/davidahouse/SwiftProtocolExtensions) ![](https://img.shields.io/github/license/davidahouse/SwiftProtocolExtensions) ![](https://img.shields.io/github/forks/davidahouse/SwiftProtocolExtensions) ![](https://img.shields.io/github/contributors/davidahouse/SwiftProtocolExtensions)

* [Battleship Example](https://github.com/vichudson1/Battleship-POP-Example) - An example of how to use Protocol Oriented Programming with the battleship game. ⏳ 

   ![](https://img.shields.io/github/stars/vichudson1/Battleship-POP-Example) ![](https://img.shields.io/github/last-commit/vichudson1/Battleship-POP-Example) ![](https://img.shields.io/github/issues/vichudson1/Battleship-POP-Example) ![](https://img.shields.io/github/issues-pr/vichudson1/Battleship-POP-Example) ![](https://img.shields.io/github/license/vichudson1/Battleship-POP-Example) ![](https://img.shields.io/github/forks/vichudson1/Battleship-POP-Example) ![](https://img.shields.io/github/contributors/vichudson1/Battleship-POP-Example)


### Functional Reactive Programming

* [ReactiveCocoa Playground](https://github.com/nikita-leonov/ReactiveCocoaPlayground) - The easiest way to get a taste of ReactiveCocoa. ⏳ 

   ![](https://img.shields.io/github/stars/nikita-leonov/ReactiveCocoaPlayground) ![](https://img.shields.io/github/last-commit/nikita-leonov/ReactiveCocoaPlayground) ![](https://img.shields.io/github/issues/nikita-leonov/ReactiveCocoaPlayground) ![](https://img.shields.io/github/issues-pr/nikita-leonov/ReactiveCocoaPlayground) ![](https://img.shields.io/github/license/nikita-leonov/ReactiveCocoaPlayground) ![](https://img.shields.io/github/forks/nikita-leonov/ReactiveCocoaPlayground) ![](https://img.shields.io/github/contributors/nikita-leonov/ReactiveCocoaPlayground)

* [Swift Reactive Playground](https://github.com/ColinEberhardt/SwiftReactivePlayground) - Companion to the article: ReactiveCocoa made Simple With Swift. ⏳ 

   ![](https://img.shields.io/github/stars/ColinEberhardt/SwiftReactivePlayground) ![](https://img.shields.io/github/last-commit/ColinEberhardt/SwiftReactivePlayground) ![](https://img.shields.io/github/issues/ColinEberhardt/SwiftReactivePlayground) ![](https://img.shields.io/github/issues-pr/ColinEberhardt/SwiftReactivePlayground) ![](https://img.shields.io/github/license/ColinEberhardt/SwiftReactivePlayground) ![](https://img.shields.io/github/forks/ColinEberhardt/SwiftReactivePlayground) ![](https://img.shields.io/github/contributors/ColinEberhardt/SwiftReactivePlayground)



## Apple's Playgrounds
*Playgrounds from Apple, usually presented at some WWDC*

* [Apple's Mandelbrot Playground](https://github.com/palmerc/Mandelbrot-Swift-Playground) - A playground with the mandelbrot fractal (updated to Swift 3 by @palmerc, @kemalenver).

   ![](https://img.shields.io/github/stars/palmerc/Mandelbrot-Swift-Playground) ![](https://img.shields.io/github/last-commit/palmerc/Mandelbrot-Swift-Playground) ![](https://img.shields.io/github/issues/palmerc/Mandelbrot-Swift-Playground) ![](https://img.shields.io/github/issues-pr/palmerc/Mandelbrot-Swift-Playground) ![](https://img.shields.io/github/license/palmerc/Mandelbrot-Swift-Playground) ![](https://img.shields.io/github/forks/palmerc/Mandelbrot-Swift-Playground) ![](https://img.shields.io/github/contributors/palmerc/Mandelbrot-Swift-Playground)

* [Interactive Newton's Cradle](https://github.com/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) - Apple's interactive playground of a Newton's Cradle where collisions and gravity are applyed with UIKit dynamics. 🌟 (updated to Swift 3 by @p-sun) 

   ![](https://img.shields.io/github/stars/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) ![](https://img.shields.io/github/last-commit/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) ![](https://img.shields.io/github/issues/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) ![](https://img.shields.io/github/issues-pr/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) ![](https://img.shields.io/github/license/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) ![](https://img.shields.io/github/forks/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle) ![](https://img.shields.io/github/contributors/p-sun/iOS-Effects-and-Animations/tree/master/Newton'sCradle)

* [Apple's Balloons Playground](https://developer.apple.com/swift/blog/downloads/Balloons.zip) - The balloons playground showed at WWDC14. ⏳ 
* [Apple's Crustacean Playground](https://developer.apple.com/sample-code/wwdc/2015/downloads/Crustacean.zip) - Protocol-Oriented Programming with Value Types. ⏳ 
* [Apple's Swift Standard Library Playground](https://developer.apple.com/sample-code/swift/downloads/Standard-Library.zip) - experiment with Swift standard library types and high-level concepts using visualizations and practical examples. ⏳ 

## WWDC Students Submissions
*Playgrounds submitted by students for the WWDC scholarship*

- [2021](https://github.com/wwdc/2021)

   ![](https://img.shields.io/github/stars/wwdc/2021) ![](https://img.shields.io/github/last-commit/wwdc/2021) ![](https://img.shields.io/github/issues/wwdc/2021) ![](https://img.shields.io/github/issues-pr/wwdc/2021) ![](https://img.shields.io/github/license/wwdc/2021) ![](https://img.shields.io/github/forks/wwdc/2021) ![](https://img.shields.io/github/contributors/wwdc/2021)

- [2020](https://github.com/wwdc/2020)

   ![](https://img.shields.io/github/stars/wwdc/2020) ![](https://img.shields.io/github/last-commit/wwdc/2020) ![](https://img.shields.io/github/issues/wwdc/2020) ![](https://img.shields.io/github/issues-pr/wwdc/2020) ![](https://img.shields.io/github/license/wwdc/2020) ![](https://img.shields.io/github/forks/wwdc/2020) ![](https://img.shields.io/github/contributors/wwdc/2020)

- [2019](https://github.com/wwdc/2019)

   ![](https://img.shields.io/github/stars/wwdc/2019) ![](https://img.shields.io/github/last-commit/wwdc/2019) ![](https://img.shields.io/github/issues/wwdc/2019) ![](https://img.shields.io/github/issues-pr/wwdc/2019) ![](https://img.shields.io/github/license/wwdc/2019) ![](https://img.shields.io/github/forks/wwdc/2019) ![](https://img.shields.io/github/contributors/wwdc/2019)

- [2018](https://github.com/wwdc/2018)

   ![](https://img.shields.io/github/stars/wwdc/2018) ![](https://img.shields.io/github/last-commit/wwdc/2018) ![](https://img.shields.io/github/issues/wwdc/2018) ![](https://img.shields.io/github/issues-pr/wwdc/2018) ![](https://img.shields.io/github/license/wwdc/2018) ![](https://img.shields.io/github/forks/wwdc/2018) ![](https://img.shields.io/github/contributors/wwdc/2018)

- [2017](https://github.com/wwdc/2017)

   ![](https://img.shields.io/github/stars/wwdc/2017) ![](https://img.shields.io/github/last-commit/wwdc/2017) ![](https://img.shields.io/github/issues/wwdc/2017) ![](https://img.shields.io/github/issues-pr/wwdc/2017) ![](https://img.shields.io/github/license/wwdc/2017) ![](https://img.shields.io/github/forks/wwdc/2017) ![](https://img.shields.io/github/contributors/wwdc/2017)

- [2016](https://github.com/wwdc/2016)

   ![](https://img.shields.io/github/stars/wwdc/2016) ![](https://img.shields.io/github/last-commit/wwdc/2016) ![](https://img.shields.io/github/issues/wwdc/2016) ![](https://img.shields.io/github/issues-pr/wwdc/2016) ![](https://img.shields.io/github/license/wwdc/2016) ![](https://img.shields.io/github/forks/wwdc/2016) ![](https://img.shields.io/github/contributors/wwdc/2016)

- [2015](https://github.com/wwdc/2015)

   ![](https://img.shields.io/github/stars/wwdc/2015) ![](https://img.shields.io/github/last-commit/wwdc/2015) ![](https://img.shields.io/github/issues/wwdc/2015) ![](https://img.shields.io/github/issues-pr/wwdc/2015) ![](https://img.shields.io/github/license/wwdc/2015) ![](https://img.shields.io/github/forks/wwdc/2015) ![](https://img.shields.io/github/contributors/wwdc/2015)

- [2014](https://github.com/wwdc/2014)

   ![](https://img.shields.io/github/stars/wwdc/2014) ![](https://img.shields.io/github/last-commit/wwdc/2014) ![](https://img.shields.io/github/issues/wwdc/2014) ![](https://img.shields.io/github/issues-pr/wwdc/2014) ![](https://img.shields.io/github/license/wwdc/2014) ![](https://img.shields.io/github/forks/wwdc/2014) ![](https://img.shields.io/github/contributors/wwdc/2014)


## Playgrounds about Playgrounds
*Playgrounds that describe what you can do with playgrounds*

* [XCTest Playground](https://github.com/Liquidsoul/XCTestPlayground) - Better looking tests for playgrounds.

   ![](https://img.shields.io/github/stars/Liquidsoul/XCTestPlayground) ![](https://img.shields.io/github/last-commit/Liquidsoul/XCTestPlayground) ![](https://img.shields.io/github/issues/Liquidsoul/XCTestPlayground) ![](https://img.shields.io/github/issues-pr/Liquidsoul/XCTestPlayground) ![](https://img.shields.io/github/license/Liquidsoul/XCTestPlayground) ![](https://img.shields.io/github/forks/Liquidsoul/XCTestPlayground) ![](https://img.shields.io/github/contributors/Liquidsoul/XCTestPlayground)

* [Interactive Playground](https://github.com/dasdom/InteractivePlayground) - Exploring interactivity in Playgrounds.

   ![](https://img.shields.io/github/stars/dasdom/InteractivePlayground) ![](https://img.shields.io/github/last-commit/dasdom/InteractivePlayground) ![](https://img.shields.io/github/issues/dasdom/InteractivePlayground) ![](https://img.shields.io/github/issues-pr/dasdom/InteractivePlayground) ![](https://img.shields.io/github/license/dasdom/InteractivePlayground) ![](https://img.shields.io/github/forks/dasdom/InteractivePlayground) ![](https://img.shields.io/github/contributors/dasdom/InteractivePlayground)

* [Mondrian](https://github.com/timbellay/Mondrian) - Make iOS app mockups in Swift 2.x playgrounds. ⏳ 

   ![](https://img.shields.io/github/stars/timbellay/Mondrian) ![](https://img.shields.io/github/last-commit/timbellay/Mondrian) ![](https://img.shields.io/github/issues/timbellay/Mondrian) ![](https://img.shields.io/github/issues-pr/timbellay/Mondrian) ![](https://img.shields.io/github/license/timbellay/Mondrian) ![](https://img.shields.io/github/forks/timbellay/Mondrian) ![](https://img.shields.io/github/contributors/timbellay/Mondrian)


## Playgrounds from Playgroundbooks
*Playgrounds derived from iPad Swift Playgroundbooks*

* [iPad Swift Playgrounds](https://github.com/kushtaneja/iPad_Swift_Playgrounds) - The sample playgroundbooks converted to playgrounds.

   ![](https://img.shields.io/github/stars/kushtaneja/iPad_Swift_Playgrounds) ![](https://img.shields.io/github/last-commit/kushtaneja/iPad_Swift_Playgrounds) ![](https://img.shields.io/github/issues/kushtaneja/iPad_Swift_Playgrounds) ![](https://img.shields.io/github/issues-pr/kushtaneja/iPad_Swift_Playgrounds) ![](https://img.shields.io/github/license/kushtaneja/iPad_Swift_Playgrounds) ![](https://img.shields.io/github/forks/kushtaneja/iPad_Swift_Playgrounds) ![](https://img.shields.io/github/contributors/kushtaneja/iPad_Swift_Playgrounds)


## Theoretical Computer Science

* [Functional Debug View](https://github.com/tomquist/DebugView) - Playground to visualize functional programming with graphical sequences. 🍁 🌟

   ![](https://img.shields.io/github/stars/tomquist/DebugView) ![](https://img.shields.io/github/last-commit/tomquist/DebugView) ![](https://img.shields.io/github/issues/tomquist/DebugView) ![](https://img.shields.io/github/issues-pr/tomquist/DebugView) ![](https://img.shields.io/github/license/tomquist/DebugView) ![](https://img.shields.io/github/forks/tomquist/DebugView) ![](https://img.shields.io/github/contributors/tomquist/DebugView)

* [OOP with Functions in Swift](https://github.com/iamleeg/OOPInFPInSwift) - Object-Oriented Programming in Functional Programming in Swift. 🍁

   ![](https://img.shields.io/github/stars/iamleeg/OOPInFPInSwift) ![](https://img.shields.io/github/last-commit/iamleeg/OOPInFPInSwift) ![](https://img.shields.io/github/issues/iamleeg/OOPInFPInSwift) ![](https://img.shields.io/github/issues-pr/iamleeg/OOPInFPInSwift) ![](https://img.shields.io/github/license/iamleeg/OOPInFPInSwift) ![](https://img.shields.io/github/forks/iamleeg/OOPInFPInSwift) ![](https://img.shields.io/github/contributors/iamleeg/OOPInFPInSwift)

* [Logician](https://github.com/mdiep/Logician) - Logic programming in Swift. 🌟

   ![](https://img.shields.io/github/stars/mdiep/Logician) ![](https://img.shields.io/github/last-commit/mdiep/Logician) ![](https://img.shields.io/github/issues/mdiep/Logician) ![](https://img.shields.io/github/issues-pr/mdiep/Logician) ![](https://img.shields.io/github/license/mdiep/Logician) ![](https://img.shields.io/github/forks/mdiep/Logician) ![](https://img.shields.io/github/contributors/mdiep/Logician)

* [Function Composition in Swift](https://github.com/ijoshsmith/function-composition-in-swift) - Exploration of function composition in Swift. 🌟

   ![](https://img.shields.io/github/stars/ijoshsmith/function-composition-in-swift) ![](https://img.shields.io/github/last-commit/ijoshsmith/function-composition-in-swift) ![](https://img.shields.io/github/issues/ijoshsmith/function-composition-in-swift) ![](https://img.shields.io/github/issues-pr/ijoshsmith/function-composition-in-swift) ![](https://img.shields.io/github/license/ijoshsmith/function-composition-in-swift) ![](https://img.shields.io/github/forks/ijoshsmith/function-composition-in-swift) ![](https://img.shields.io/github/contributors/ijoshsmith/function-composition-in-swift)

* [Swift Adventures in Monad Land](https://github.com/alskipp/Swift-Adventures-In-Monad-Land) - Learn about monads.

   ![](https://img.shields.io/github/stars/alskipp/Swift-Adventures-In-Monad-Land) ![](https://img.shields.io/github/last-commit/alskipp/Swift-Adventures-In-Monad-Land) ![](https://img.shields.io/github/issues/alskipp/Swift-Adventures-In-Monad-Land) ![](https://img.shields.io/github/issues-pr/alskipp/Swift-Adventures-In-Monad-Land) ![](https://img.shields.io/github/license/alskipp/Swift-Adventures-In-Monad-Land) ![](https://img.shields.io/github/forks/alskipp/Swift-Adventures-In-Monad-Land) ![](https://img.shields.io/github/contributors/alskipp/Swift-Adventures-In-Monad-Land)

* [Functional Design Patterns](https://github.com/cmvicentehe/FunctionalProgrammingDesignPatterns) - A few functional programming concept and patterns.

   ![](https://img.shields.io/github/stars/cmvicentehe/FunctionalProgrammingDesignPatterns) ![](https://img.shields.io/github/last-commit/cmvicentehe/FunctionalProgrammingDesignPatterns) ![](https://img.shields.io/github/issues/cmvicentehe/FunctionalProgrammingDesignPatterns) ![](https://img.shields.io/github/issues-pr/cmvicentehe/FunctionalProgrammingDesignPatterns) ![](https://img.shields.io/github/license/cmvicentehe/FunctionalProgrammingDesignPatterns) ![](https://img.shields.io/github/forks/cmvicentehe/FunctionalProgrammingDesignPatterns) ![](https://img.shields.io/github/contributors/cmvicentehe/FunctionalProgrammingDesignPatterns)

* [Learn about transducers](https://github.com/mbrandonw/learn-transducers-playground) - A little tutorial that explains transducers. ⏳ 

   ![](https://img.shields.io/github/stars/mbrandonw/learn-transducers-playground) ![](https://img.shields.io/github/last-commit/mbrandonw/learn-transducers-playground) ![](https://img.shields.io/github/issues/mbrandonw/learn-transducers-playground) ![](https://img.shields.io/github/issues-pr/mbrandonw/learn-transducers-playground) ![](https://img.shields.io/github/license/mbrandonw/learn-transducers-playground) ![](https://img.shields.io/github/forks/mbrandonw/learn-transducers-playground) ![](https://img.shields.io/github/contributors/mbrandonw/learn-transducers-playground)

* [Swift Functors, Applicatives, and Monads in Pictures](https://github.com/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) - Companion to the article: Swift Functors, Applicatves, and Monads in Pictures. ⏳ 

   ![](https://img.shields.io/github/stars/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) ![](https://img.shields.io/github/last-commit/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) ![](https://img.shields.io/github/issues/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) ![](https://img.shields.io/github/issues-pr/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) ![](https://img.shields.io/github/license/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) ![](https://img.shields.io/github/forks/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground) ![](https://img.shields.io/github/contributors/mokacoding/Swift-Functors-Applicative-Monads-In-Pictures-Playground)

* [Functors in Swift](https://github.com/mokagio/Swift-Functor-Introduction-Playground) - A playground to introduce Functors in Swift, and their practical usage. ⏳ 

   ![](https://img.shields.io/github/stars/mokagio/Swift-Functor-Introduction-Playground) ![](https://img.shields.io/github/last-commit/mokagio/Swift-Functor-Introduction-Playground) ![](https://img.shields.io/github/issues/mokagio/Swift-Functor-Introduction-Playground) ![](https://img.shields.io/github/issues-pr/mokagio/Swift-Functor-Introduction-Playground) ![](https://img.shields.io/github/license/mokagio/Swift-Functor-Introduction-Playground) ![](https://img.shields.io/github/forks/mokagio/Swift-Functor-Introduction-Playground) ![](https://img.shields.io/github/contributors/mokagio/Swift-Functor-Introduction-Playground)


### Algorithms and Data Structures
*Algorithms and data structures implemented in Swift*

* [Animated Sorting Algorithms](https://github.com/p-sun/Animated-Sorting-Algorithms) - Swift 4 playgrounds to view and manipulate sorting algorithms.🍁

   ![](https://img.shields.io/github/stars/p-sun/Animated-Sorting-Algorithms) ![](https://img.shields.io/github/last-commit/p-sun/Animated-Sorting-Algorithms) ![](https://img.shields.io/github/issues/p-sun/Animated-Sorting-Algorithms) ![](https://img.shields.io/github/issues-pr/p-sun/Animated-Sorting-Algorithms) ![](https://img.shields.io/github/license/p-sun/Animated-Sorting-Algorithms) ![](https://img.shields.io/github/forks/p-sun/Animated-Sorting-Algorithms) ![](https://img.shields.io/github/contributors/p-sun/Animated-Sorting-Algorithms)

* [Expressions](https://github.com/mpangburn/Expressions) - Arithmetic and logical expressions elegantly modeled and visualized using protocol-oriented binary trees.🍁

   ![](https://img.shields.io/github/stars/mpangburn/Expressions) ![](https://img.shields.io/github/last-commit/mpangburn/Expressions) ![](https://img.shields.io/github/issues/mpangburn/Expressions) ![](https://img.shields.io/github/issues-pr/mpangburn/Expressions) ![](https://img.shields.io/github/license/mpangburn/Expressions) ![](https://img.shields.io/github/forks/mpangburn/Expressions) ![](https://img.shields.io/github/contributors/mpangburn/Expressions)

* [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club) - Algorithms and data structures in Swift with explanations. 🌟

   ![](https://img.shields.io/github/stars/raywenderlich/swift-algorithm-club) ![](https://img.shields.io/github/last-commit/raywenderlich/swift-algorithm-club) ![](https://img.shields.io/github/issues/raywenderlich/swift-algorithm-club) ![](https://img.shields.io/github/issues-pr/raywenderlich/swift-algorithm-club) ![](https://img.shields.io/github/license/raywenderlich/swift-algorithm-club) ![](https://img.shields.io/github/forks/raywenderlich/swift-algorithm-club) ![](https://img.shields.io/github/contributors/raywenderlich/swift-algorithm-club)

* [Sorting Experiments](https://github.com/adrfer/Sort) - Alluring experiments with sorting algorithms in Swift, sort of.

   ![](https://img.shields.io/github/stars/adrfer/Sort) ![](https://img.shields.io/github/last-commit/adrfer/Sort) ![](https://img.shields.io/github/issues/adrfer/Sort) ![](https://img.shields.io/github/issues-pr/adrfer/Sort) ![](https://img.shields.io/github/license/adrfer/Sort) ![](https://img.shields.io/github/forks/adrfer/Sort) ![](https://img.shields.io/github/contributors/adrfer/Sort)

* [Visual Binary Trees](https://github.com/akpw/VisualBinaryTrees) - Effortless visualization of arbitrary Binary Trees, along with their pluggable traversal implementations. 🌟

   ![](https://img.shields.io/github/stars/akpw/VisualBinaryTrees) ![](https://img.shields.io/github/last-commit/akpw/VisualBinaryTrees) ![](https://img.shields.io/github/issues/akpw/VisualBinaryTrees) ![](https://img.shields.io/github/issues-pr/akpw/VisualBinaryTrees) ![](https://img.shields.io/github/license/akpw/VisualBinaryTrees) ![](https://img.shields.io/github/forks/akpw/VisualBinaryTrees) ![](https://img.shields.io/github/contributors/akpw/VisualBinaryTrees)

* [Julia Fractal Playground](https://github.com/gongzhang/julia-set-playground#julia-set-playground) - A Swift playground that generates beautiful Julia set fractal images. 

   ![](https://img.shields.io/github/stars/gongzhang/julia-set-playground#julia-set-playground) ![](https://img.shields.io/github/last-commit/gongzhang/julia-set-playground#julia-set-playground) ![](https://img.shields.io/github/issues/gongzhang/julia-set-playground#julia-set-playground) ![](https://img.shields.io/github/issues-pr/gongzhang/julia-set-playground#julia-set-playground) ![](https://img.shields.io/github/license/gongzhang/julia-set-playground#julia-set-playground) ![](https://img.shields.io/github/forks/gongzhang/julia-set-playground#julia-set-playground) ![](https://img.shields.io/github/contributors/gongzhang/julia-set-playground#julia-set-playground)

* [A Star](https://github.com/Dev1an/A-Star) - Protocol oriented A* pathfinding algorithm implementation in Swift 4.🍁

   ![](https://img.shields.io/github/stars/Dev1an/A-Star) ![](https://img.shields.io/github/last-commit/Dev1an/A-Star) ![](https://img.shields.io/github/issues/Dev1an/A-Star) ![](https://img.shields.io/github/issues-pr/Dev1an/A-Star) ![](https://img.shields.io/github/license/Dev1an/A-Star) ![](https://img.shields.io/github/forks/Dev1an/A-Star) ![](https://img.shields.io/github/contributors/Dev1an/A-Star)

* [Sorting Algorithms](https://github.com/bwide/Sorting-Algorithms-Playground) - Live Visualization of some famous sorting algorithms and your experiments.

   ![](https://img.shields.io/github/stars/bwide/Sorting-Algorithms-Playground) ![](https://img.shields.io/github/last-commit/bwide/Sorting-Algorithms-Playground) ![](https://img.shields.io/github/issues/bwide/Sorting-Algorithms-Playground) ![](https://img.shields.io/github/issues-pr/bwide/Sorting-Algorithms-Playground) ![](https://img.shields.io/github/license/bwide/Sorting-Algorithms-Playground) ![](https://img.shields.io/github/forks/bwide/Sorting-Algorithms-Playground) ![](https://img.shields.io/github/contributors/bwide/Sorting-Algorithms-Playground)

* [DataStructures Playground](https://github.com/oliverfoggin/DataStructuresPlayground) - Data Structures and Algorithms in Swift. ⏳

   ![](https://img.shields.io/github/stars/oliverfoggin/DataStructuresPlayground) ![](https://img.shields.io/github/last-commit/oliverfoggin/DataStructuresPlayground) ![](https://img.shields.io/github/issues/oliverfoggin/DataStructuresPlayground) ![](https://img.shields.io/github/issues-pr/oliverfoggin/DataStructuresPlayground) ![](https://img.shields.io/github/license/oliverfoggin/DataStructuresPlayground) ![](https://img.shields.io/github/forks/oliverfoggin/DataStructuresPlayground) ![](https://img.shields.io/github/contributors/oliverfoggin/DataStructuresPlayground)

* [Swiftography](https://github.com/sketchytech/Swiftography) - Standard cryptographic algorithms in a Swift Playground. ⏳

   ![](https://img.shields.io/github/stars/sketchytech/Swiftography) ![](https://img.shields.io/github/last-commit/sketchytech/Swiftography) ![](https://img.shields.io/github/issues/sketchytech/Swiftography) ![](https://img.shields.io/github/issues-pr/sketchytech/Swiftography) ![](https://img.shields.io/github/license/sketchytech/Swiftography) ![](https://img.shields.io/github/forks/sketchytech/Swiftography) ![](https://img.shields.io/github/contributors/sketchytech/Swiftography)

* [Algorithms Playground](https://github.com/ashokgelal/AlgorithmsPlayground) - Various algorithm implementation in Swift. ⏳

   ![](https://img.shields.io/github/stars/ashokgelal/AlgorithmsPlayground) ![](https://img.shields.io/github/last-commit/ashokgelal/AlgorithmsPlayground) ![](https://img.shields.io/github/issues/ashokgelal/AlgorithmsPlayground) ![](https://img.shields.io/github/issues-pr/ashokgelal/AlgorithmsPlayground) ![](https://img.shields.io/github/license/ashokgelal/AlgorithmsPlayground) ![](https://img.shields.io/github/forks/ashokgelal/AlgorithmsPlayground) ![](https://img.shields.io/github/contributors/ashokgelal/AlgorithmsPlayground)

* [The Jelly Bean Problem](https://github.com/kyleweiner/Jelly-Bean-Problem) - The Jelly Bean problem from Wait But Why. ⏳

   ![](https://img.shields.io/github/stars/kyleweiner/Jelly-Bean-Problem) ![](https://img.shields.io/github/last-commit/kyleweiner/Jelly-Bean-Problem) ![](https://img.shields.io/github/issues/kyleweiner/Jelly-Bean-Problem) ![](https://img.shields.io/github/issues-pr/kyleweiner/Jelly-Bean-Problem) ![](https://img.shields.io/github/license/kyleweiner/Jelly-Bean-Problem) ![](https://img.shields.io/github/forks/kyleweiner/Jelly-Bean-Problem) ![](https://img.shields.io/github/contributors/kyleweiner/Jelly-Bean-Problem)

* [Euclidean Strings](https://github.com/modulusMathews/ReEuclid) - A playground leveraging ReSwift to generate Euclidean Strings. ⏳

   ![](https://img.shields.io/github/stars/modulusMathews/ReEuclid) ![](https://img.shields.io/github/last-commit/modulusMathews/ReEuclid) ![](https://img.shields.io/github/issues/modulusMathews/ReEuclid) ![](https://img.shields.io/github/issues-pr/modulusMathews/ReEuclid) ![](https://img.shields.io/github/license/modulusMathews/ReEuclid) ![](https://img.shields.io/github/forks/modulusMathews/ReEuclid) ![](https://img.shields.io/github/contributors/modulusMathews/ReEuclid)


### Languages
*Programming language interpreters implemented in Swift*

* [Introduction to Compilers](https://github.com/ahoppen/introduction-to-compilers) - Great introduction to the inner workings of compilers. 🍁🌟

   ![](https://img.shields.io/github/stars/ahoppen/introduction-to-compilers) ![](https://img.shields.io/github/last-commit/ahoppen/introduction-to-compilers) ![](https://img.shields.io/github/issues/ahoppen/introduction-to-compilers) ![](https://img.shields.io/github/issues-pr/ahoppen/introduction-to-compilers) ![](https://img.shields.io/github/license/ahoppen/introduction-to-compilers) ![](https://img.shields.io/github/forks/ahoppen/introduction-to-compilers) ![](https://img.shields.io/github/contributors/ahoppen/introduction-to-compilers)

* [Pascal Interpreter](https://github.com/igorkulman/SwiftPascalInterpreter) - Simple Swift interpreter for the Pascal language inspired by the Let’s Build A Simple Interpreter article series. 🍁

   ![](https://img.shields.io/github/stars/igorkulman/SwiftPascalInterpreter) ![](https://img.shields.io/github/last-commit/igorkulman/SwiftPascalInterpreter) ![](https://img.shields.io/github/issues/igorkulman/SwiftPascalInterpreter) ![](https://img.shields.io/github/issues-pr/igorkulman/SwiftPascalInterpreter) ![](https://img.shields.io/github/license/igorkulman/SwiftPascalInterpreter) ![](https://img.shields.io/github/forks/igorkulman/SwiftPascalInterpreter) ![](https://img.shields.io/github/contributors/igorkulman/SwiftPascalInterpreter)

* [Write your own language: Mu](https://github.com/marciok/Mu) - A playground explaining how to create a tiny programming language named Mu. 🌟

   ![](https://img.shields.io/github/stars/marciok/Mu) ![](https://img.shields.io/github/last-commit/marciok/Mu) ![](https://img.shields.io/github/issues/marciok/Mu) ![](https://img.shields.io/github/issues-pr/marciok/Mu) ![](https://img.shields.io/github/license/marciok/Mu) ![](https://img.shields.io/github/forks/marciok/Mu) ![](https://img.shields.io/github/contributors/marciok/Mu)

* [ASM Swift](https://github.com/NSExceptional/ASM-Swift) - A playground for learning Assembly language through Swift. 🌟

   ![](https://img.shields.io/github/stars/NSExceptional/ASM-Swift) ![](https://img.shields.io/github/last-commit/NSExceptional/ASM-Swift) ![](https://img.shields.io/github/issues/NSExceptional/ASM-Swift) ![](https://img.shields.io/github/issues-pr/NSExceptional/ASM-Swift) ![](https://img.shields.io/github/license/NSExceptional/ASM-Swift) ![](https://img.shields.io/github/forks/NSExceptional/ASM-Swift) ![](https://img.shields.io/github/contributors/NSExceptional/ASM-Swift)

* [Let's build a compiler in Swift](https://github.com/mkchoi212/LBAC-Swift) - Let's Build a Compiler by Jack Crenshaw translated to Swift Playgrounds. 🌟 

   ![](https://img.shields.io/github/stars/mkchoi212/LBAC-Swift) ![](https://img.shields.io/github/last-commit/mkchoi212/LBAC-Swift) ![](https://img.shields.io/github/issues/mkchoi212/LBAC-Swift) ![](https://img.shields.io/github/issues-pr/mkchoi212/LBAC-Swift) ![](https://img.shields.io/github/license/mkchoi212/LBAC-Swift) ![](https://img.shields.io/github/forks/mkchoi212/LBAC-Swift) ![](https://img.shields.io/github/contributors/mkchoi212/LBAC-Swift)

* [Register VM](https://github.com/brianhill/register-vm-in-swift) - A register-based VM in a Swift playground. 🌟 ⏳

   ![](https://img.shields.io/github/stars/brianhill/register-vm-in-swift) ![](https://img.shields.io/github/last-commit/brianhill/register-vm-in-swift) ![](https://img.shields.io/github/issues/brianhill/register-vm-in-swift) ![](https://img.shields.io/github/issues-pr/brianhill/register-vm-in-swift) ![](https://img.shields.io/github/license/brianhill/register-vm-in-swift) ![](https://img.shields.io/github/forks/brianhill/register-vm-in-swift) ![](https://img.shields.io/github/contributors/brianhill/register-vm-in-swift)

* [Turtle Playground](https://github.com/dimsumthinking/TurtlePlayground) - A playground with Logo-like commands. 🌟 ⏳

   ![](https://img.shields.io/github/stars/dimsumthinking/TurtlePlayground) ![](https://img.shields.io/github/last-commit/dimsumthinking/TurtlePlayground) ![](https://img.shields.io/github/issues/dimsumthinking/TurtlePlayground) ![](https://img.shields.io/github/issues-pr/dimsumthinking/TurtlePlayground) ![](https://img.shields.io/github/license/dimsumthinking/TurtlePlayground) ![](https://img.shields.io/github/forks/dimsumthinking/TurtlePlayground) ![](https://img.shields.io/github/contributors/dimsumthinking/TurtlePlayground)

* [Swift Brainfuck](https://github.com/xavieryao/Swift-Brainfuck) - Brainfuck interpreter written in Swift using Playground. ⏳

   ![](https://img.shields.io/github/stars/xavieryao/Swift-Brainfuck) ![](https://img.shields.io/github/last-commit/xavieryao/Swift-Brainfuck) ![](https://img.shields.io/github/issues/xavieryao/Swift-Brainfuck) ![](https://img.shields.io/github/issues-pr/xavieryao/Swift-Brainfuck) ![](https://img.shields.io/github/license/xavieryao/Swift-Brainfuck) ![](https://img.shields.io/github/forks/xavieryao/Swift-Brainfuck) ![](https://img.shields.io/github/contributors/xavieryao/Swift-Brainfuck)


### Machine Learning

* [Emoji Intelligence](https://github.com/BilalReffas/EmojiIntelligence) - Neural Network built in Apple Playground using Swift. 🌟  

   ![](https://img.shields.io/github/stars/BilalReffas/EmojiIntelligence) ![](https://img.shields.io/github/last-commit/BilalReffas/EmojiIntelligence) ![](https://img.shields.io/github/issues/BilalReffas/EmojiIntelligence) ![](https://img.shields.io/github/issues-pr/BilalReffas/EmojiIntelligence) ![](https://img.shields.io/github/license/BilalReffas/EmojiIntelligence) ![](https://img.shields.io/github/forks/BilalReffas/EmojiIntelligence) ![](https://img.shields.io/github/contributors/BilalReffas/EmojiIntelligence)


## UIKit And Graphics
*A list of playgrounds that demostrate various aspect of UIKit and other graphical frameworks*

* [UIStackView Playground](https://github.com/dasdom/UIStackViewPlayground) - Interesting examples of use of UIStackViews.🌟

   ![](https://img.shields.io/github/stars/dasdom/UIStackViewPlayground) ![](https://img.shields.io/github/last-commit/dasdom/UIStackViewPlayground) ![](https://img.shields.io/github/issues/dasdom/UIStackViewPlayground) ![](https://img.shields.io/github/issues-pr/dasdom/UIStackViewPlayground) ![](https://img.shields.io/github/license/dasdom/UIStackViewPlayground) ![](https://img.shields.io/github/forks/dasdom/UIStackViewPlayground) ![](https://img.shields.io/github/contributors/dasdom/UIStackViewPlayground)

* [Bezier Path Playgrounds](https://github.com/DigitalLeaves/BezierPathPlaygrounds) - Some playgrounds to better understand UIBezierPaths.

   ![](https://img.shields.io/github/stars/DigitalLeaves/BezierPathPlaygrounds) ![](https://img.shields.io/github/last-commit/DigitalLeaves/BezierPathPlaygrounds) ![](https://img.shields.io/github/issues/DigitalLeaves/BezierPathPlaygrounds) ![](https://img.shields.io/github/issues-pr/DigitalLeaves/BezierPathPlaygrounds) ![](https://img.shields.io/github/license/DigitalLeaves/BezierPathPlaygrounds) ![](https://img.shields.io/github/forks/DigitalLeaves/BezierPathPlaygrounds) ![](https://img.shields.io/github/contributors/DigitalLeaves/BezierPathPlaygrounds)

* [UIKit playground](https://github.com/ralfebert/uikit-playground) - Playgrounds to experiment interactively with UIKit views.

   ![](https://img.shields.io/github/stars/ralfebert/uikit-playground) ![](https://img.shields.io/github/last-commit/ralfebert/uikit-playground) ![](https://img.shields.io/github/issues/ralfebert/uikit-playground) ![](https://img.shields.io/github/issues-pr/ralfebert/uikit-playground) ![](https://img.shields.io/github/license/ralfebert/uikit-playground) ![](https://img.shields.io/github/forks/ralfebert/uikit-playground) ![](https://img.shields.io/github/contributors/ralfebert/uikit-playground)

* [UIDynamic Playground](https://github.com/andresbrun/UIDynamicsPlayground) - Multiple Playgrounds using almost every behaviour of UIDynamic.

   ![](https://img.shields.io/github/stars/andresbrun/UIDynamicsPlayground) ![](https://img.shields.io/github/last-commit/andresbrun/UIDynamicsPlayground) ![](https://img.shields.io/github/issues/andresbrun/UIDynamicsPlayground) ![](https://img.shields.io/github/issues-pr/andresbrun/UIDynamicsPlayground) ![](https://img.shields.io/github/license/andresbrun/UIDynamicsPlayground) ![](https://img.shields.io/github/forks/andresbrun/UIDynamicsPlayground) ![](https://img.shields.io/github/contributors/andresbrun/UIDynamicsPlayground)

* [WWDC16 Typography](https://github.com/tototti/wwdc16_typography_playground) 🇯🇵 - Draw a logo or any text with the WWDC16 ASCII texture.  

   ![](https://img.shields.io/github/stars/tototti/wwdc16_typography_playground) ![](https://img.shields.io/github/last-commit/tototti/wwdc16_typography_playground) ![](https://img.shields.io/github/issues/tototti/wwdc16_typography_playground) ![](https://img.shields.io/github/issues-pr/tototti/wwdc16_typography_playground) ![](https://img.shields.io/github/license/tototti/wwdc16_typography_playground) ![](https://img.shields.io/github/forks/tototti/wwdc16_typography_playground) ![](https://img.shields.io/github/contributors/tototti/wwdc16_typography_playground)

* [Animated GIF Playground](https://github.com/danielrhammond/GIF-Playground) - Swift playground for generating animated GIFs.

   ![](https://img.shields.io/github/stars/danielrhammond/GIF-Playground) ![](https://img.shields.io/github/last-commit/danielrhammond/GIF-Playground) ![](https://img.shields.io/github/issues/danielrhammond/GIF-Playground) ![](https://img.shields.io/github/issues-pr/danielrhammond/GIF-Playground) ![](https://img.shields.io/github/license/danielrhammond/GIF-Playground) ![](https://img.shields.io/github/forks/danielrhammond/GIF-Playground) ![](https://img.shields.io/github/contributors/danielrhammond/GIF-Playground)

* [RPClarity](https://github.com/RobotsAndPencils/RPClarity) - Shows a technique for blurring an image behind the characters behind one or more UILabels. ⏳

   ![](https://img.shields.io/github/stars/RobotsAndPencils/RPClarity) ![](https://img.shields.io/github/last-commit/RobotsAndPencils/RPClarity) ![](https://img.shields.io/github/issues/RobotsAndPencils/RPClarity) ![](https://img.shields.io/github/issues-pr/RobotsAndPencils/RPClarity) ![](https://img.shields.io/github/license/RobotsAndPencils/RPClarity) ![](https://img.shields.io/github/forks/RobotsAndPencils/RPClarity) ![](https://img.shields.io/github/contributors/RobotsAndPencils/RPClarity)

* [Swift Clock](https://github.com/nickoneill/swiftclock) - An animated clock in a swift playground. ⏳

   ![](https://img.shields.io/github/stars/nickoneill/swiftclock) ![](https://img.shields.io/github/last-commit/nickoneill/swiftclock) ![](https://img.shields.io/github/issues/nickoneill/swiftclock) ![](https://img.shields.io/github/issues-pr/nickoneill/swiftclock) ![](https://img.shields.io/github/license/nickoneill/swiftclock) ![](https://img.shields.io/github/forks/nickoneill/swiftclock) ![](https://img.shields.io/github/contributors/nickoneill/swiftclock)

* [WatchKit Asset Playground](https://github.com/cwimberger/WatchKitAssetPlayground) - A swift playground for creating awesome animations for your WatchKit Apps. ⏳

   ![](https://img.shields.io/github/stars/cwimberger/WatchKitAssetPlayground) ![](https://img.shields.io/github/last-commit/cwimberger/WatchKitAssetPlayground) ![](https://img.shields.io/github/issues/cwimberger/WatchKitAssetPlayground) ![](https://img.shields.io/github/issues-pr/cwimberger/WatchKitAssetPlayground) ![](https://img.shields.io/github/license/cwimberger/WatchKitAssetPlayground) ![](https://img.shields.io/github/forks/cwimberger/WatchKitAssetPlayground) ![](https://img.shields.io/github/contributors/cwimberger/WatchKitAssetPlayground)

* [Swift 2.0 Protocol Extension Example](https://github.com/jhurray/Swift2-Protocol-Extension-Example) - Showing how to use Swift2 protocol extensions to render errors in UIViews and UIViewControllers without subclassing or creating classes. ⏳

   ![](https://img.shields.io/github/stars/jhurray/Swift2-Protocol-Extension-Example) ![](https://img.shields.io/github/last-commit/jhurray/Swift2-Protocol-Extension-Example) ![](https://img.shields.io/github/issues/jhurray/Swift2-Protocol-Extension-Example) ![](https://img.shields.io/github/issues-pr/jhurray/Swift2-Protocol-Extension-Example) ![](https://img.shields.io/github/license/jhurray/Swift2-Protocol-Extension-Example) ![](https://img.shields.io/github/forks/jhurray/Swift2-Protocol-Extension-Example) ![](https://img.shields.io/github/contributors/jhurray/Swift2-Protocol-Extension-Example)

* [Tinting](https://github.com/Jesse-calkin/tinting) - A small playground to demonstrate image tinting in UIKit. ⏳

   ![](https://img.shields.io/github/stars/Jesse-calkin/tinting) ![](https://img.shields.io/github/last-commit/Jesse-calkin/tinting) ![](https://img.shields.io/github/issues/Jesse-calkin/tinting) ![](https://img.shields.io/github/issues-pr/Jesse-calkin/tinting) ![](https://img.shields.io/github/license/Jesse-calkin/tinting) ![](https://img.shields.io/github/forks/Jesse-calkin/tinting) ![](https://img.shields.io/github/contributors/Jesse-calkin/tinting)

* [Ray tracing Playground](https://github.com/mhorga/Raytracing) - A playground and a series of articles on ray tracing, see also part [2](https://github.com/mhorga/Raytracing2), [3](https://github.com/mhorga/Raytracing3), [4](https://github.com/mhorga/Raytracing4), [5](https://github.com/mhorga/Raytracing5) 🌟 ⏳

   ![](https://img.shields.io/github/stars/mhorga/Raytracing) ![](https://img.shields.io/github/last-commit/mhorga/Raytracing) ![](https://img.shields.io/github/issues/mhorga/Raytracing) ![](https://img.shields.io/github/issues-pr/mhorga/Raytracing) ![](https://img.shields.io/github/license/mhorga/Raytracing) ![](https://img.shields.io/github/forks/mhorga/Raytracing) ![](https://img.shields.io/github/contributors/mhorga/Raytracing)

* [WWDC16 Logo Playground](https://github.com/krutarth/WWDC16Logo) - Drawing the WWDC16 logo in a playground. ⏳

   ![](https://img.shields.io/github/stars/krutarth/WWDC16Logo) ![](https://img.shields.io/github/last-commit/krutarth/WWDC16Logo) ![](https://img.shields.io/github/issues/krutarth/WWDC16Logo) ![](https://img.shields.io/github/issues-pr/krutarth/WWDC16Logo) ![](https://img.shields.io/github/license/krutarth/WWDC16Logo) ![](https://img.shields.io/github/forks/krutarth/WWDC16Logo) ![](https://img.shields.io/github/contributors/krutarth/WWDC16Logo)


### Core Image

* [Interpolation Playground](https://github.com/FlexMonkey/Interpolation-Playground-) - Playground demonstrating lerp, smooth step, Catcall-Rom and others! ⏳

   ![](https://img.shields.io/github/stars/FlexMonkey/Interpolation-Playground-) ![](https://img.shields.io/github/last-commit/FlexMonkey/Interpolation-Playground-) ![](https://img.shields.io/github/issues/FlexMonkey/Interpolation-Playground-) ![](https://img.shields.io/github/issues-pr/FlexMonkey/Interpolation-Playground-) ![](https://img.shields.io/github/license/FlexMonkey/Interpolation-Playground-) ![](https://img.shields.io/github/forks/FlexMonkey/Interpolation-Playground-) ![](https://img.shields.io/github/contributors/FlexMonkey/Interpolation-Playground-)

* [CoreImage for Swift Playgrounds](https://github.com/FlexMonkey/CoreImageForSwiftPlaygrounds) - Growing collection of CoreImage playgrounds from the upcoming book "CoreImage For Swift". 🌟 ⏳

   ![](https://img.shields.io/github/stars/FlexMonkey/CoreImageForSwiftPlaygrounds) ![](https://img.shields.io/github/last-commit/FlexMonkey/CoreImageForSwiftPlaygrounds) ![](https://img.shields.io/github/issues/FlexMonkey/CoreImageForSwiftPlaygrounds) ![](https://img.shields.io/github/issues-pr/FlexMonkey/CoreImageForSwiftPlaygrounds) ![](https://img.shields.io/github/license/FlexMonkey/CoreImageForSwiftPlaygrounds) ![](https://img.shields.io/github/forks/FlexMonkey/CoreImageForSwiftPlaygrounds) ![](https://img.shields.io/github/contributors/FlexMonkey/CoreImageForSwiftPlaygrounds)

* [Image Processor](https://github.com/mortenbrudvik/ImageProcessor) - Implementing different image filter algorithms. ⏳

   ![](https://img.shields.io/github/stars/mortenbrudvik/ImageProcessor) ![](https://img.shields.io/github/last-commit/mortenbrudvik/ImageProcessor) ![](https://img.shields.io/github/issues/mortenbrudvik/ImageProcessor) ![](https://img.shields.io/github/issues-pr/mortenbrudvik/ImageProcessor) ![](https://img.shields.io/github/license/mortenbrudvik/ImageProcessor) ![](https://img.shields.io/github/forks/mortenbrudvik/ImageProcessor) ![](https://img.shields.io/github/contributors/mortenbrudvik/ImageProcessor)


### Metal

* [Metalbrot](https://github.com/jtbandes/metalbrot-playground) - Interactive playground that draws the Mandelbrot fractal with Metal. 🌟

   ![](https://img.shields.io/github/stars/jtbandes/metalbrot-playground) ![](https://img.shields.io/github/last-commit/jtbandes/metalbrot-playground) ![](https://img.shields.io/github/issues/jtbandes/metalbrot-playground) ![](https://img.shields.io/github/issues-pr/jtbandes/metalbrot-playground) ![](https://img.shields.io/github/license/jtbandes/metalbrot-playground) ![](https://img.shields.io/github/forks/jtbandes/metalbrot-playground) ![](https://img.shields.io/github/contributors/jtbandes/metalbrot-playground)

* [METAL Playground](https://github.com/haawa799/METAL_Playground) - Apple Metal framework playground. 🌟 ⏳

   ![](https://img.shields.io/github/stars/haawa799/METAL_Playground) ![](https://img.shields.io/github/last-commit/haawa799/METAL_Playground) ![](https://img.shields.io/github/issues/haawa799/METAL_Playground) ![](https://img.shields.io/github/issues-pr/haawa799/METAL_Playground) ![](https://img.shields.io/github/license/haawa799/METAL_Playground) ![](https://img.shields.io/github/forks/haawa799/METAL_Playground) ![](https://img.shields.io/github/contributors/haawa799/METAL_Playground)


### Animations

* [Core Animation Swift Playgrounds](https://github.com/rmirabelli/CoreAnimationSwiftPlaygrounds) - A set of interesting Core Animation playgounds.

   ![](https://img.shields.io/github/stars/rmirabelli/CoreAnimationSwiftPlaygrounds) ![](https://img.shields.io/github/last-commit/rmirabelli/CoreAnimationSwiftPlaygrounds) ![](https://img.shields.io/github/issues/rmirabelli/CoreAnimationSwiftPlaygrounds) ![](https://img.shields.io/github/issues-pr/rmirabelli/CoreAnimationSwiftPlaygrounds) ![](https://img.shields.io/github/license/rmirabelli/CoreAnimationSwiftPlaygrounds) ![](https://img.shields.io/github/forks/rmirabelli/CoreAnimationSwiftPlaygrounds) ![](https://img.shields.io/github/contributors/rmirabelli/CoreAnimationSwiftPlaygrounds)

* [UIViewPropertyAnimator Playground](https://github.com/mathewsanders/Scrubber) - Playground demonstrating UIViewPropertyAnimator.

   ![](https://img.shields.io/github/stars/mathewsanders/Scrubber) ![](https://img.shields.io/github/last-commit/mathewsanders/Scrubber) ![](https://img.shields.io/github/issues/mathewsanders/Scrubber) ![](https://img.shields.io/github/issues-pr/mathewsanders/Scrubber) ![](https://img.shields.io/github/license/mathewsanders/Scrubber) ![](https://img.shields.io/github/forks/mathewsanders/Scrubber) ![](https://img.shields.io/github/contributors/mathewsanders/Scrubber)

* [WWDC Crowd Simulator 2017](https://github.com/neilsardesai/WWDC-Crowd-Simulator-2017) - A SpriteKit experiment to simulate the WWDC2017 logo crowd.

   ![](https://img.shields.io/github/stars/neilsardesai/WWDC-Crowd-Simulator-2017) ![](https://img.shields.io/github/last-commit/neilsardesai/WWDC-Crowd-Simulator-2017) ![](https://img.shields.io/github/issues/neilsardesai/WWDC-Crowd-Simulator-2017) ![](https://img.shields.io/github/issues-pr/neilsardesai/WWDC-Crowd-Simulator-2017) ![](https://img.shields.io/github/license/neilsardesai/WWDC-Crowd-Simulator-2017) ![](https://img.shields.io/github/forks/neilsardesai/WWDC-Crowd-Simulator-2017) ![](https://img.shields.io/github/contributors/neilsardesai/WWDC-Crowd-Simulator-2017)

* [Duet-Inspired Trail Effect](https://github.com/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) - How to get a Duet style trailing effect in SpriteKit.

   ![](https://img.shields.io/github/stars/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) ![](https://img.shields.io/github/last-commit/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) ![](https://img.shields.io/github/issues/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) ![](https://img.shields.io/github/issues-pr/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) ![](https://img.shields.io/github/license/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) ![](https://img.shields.io/github/forks/dionlarson/Duet-Trail-Effect-SpriteKit-Playground) ![](https://img.shields.io/github/contributors/dionlarson/Duet-Trail-Effect-SpriteKit-Playground)

* [Additive Animations](https://github.com/d-ronnqvist/Additive-Animations-Playground) - Experiment with multiple additive animations in Core Animation. ⏳

   ![](https://img.shields.io/github/stars/d-ronnqvist/Additive-Animations-Playground) ![](https://img.shields.io/github/last-commit/d-ronnqvist/Additive-Animations-Playground) ![](https://img.shields.io/github/issues/d-ronnqvist/Additive-Animations-Playground) ![](https://img.shields.io/github/issues-pr/d-ronnqvist/Additive-Animations-Playground) ![](https://img.shields.io/github/license/d-ronnqvist/Additive-Animations-Playground) ![](https://img.shields.io/github/forks/d-ronnqvist/Additive-Animations-Playground) ![](https://img.shields.io/github/contributors/d-ronnqvist/Additive-Animations-Playground)

* [Core Animation Playground](https://github.com/knightsc/CoreAnimationPlayground) - Companion to Apple's Core Animation Programming Guide. ⏳

   ![](https://img.shields.io/github/stars/knightsc/CoreAnimationPlayground) ![](https://img.shields.io/github/last-commit/knightsc/CoreAnimationPlayground) ![](https://img.shields.io/github/issues/knightsc/CoreAnimationPlayground) ![](https://img.shields.io/github/issues-pr/knightsc/CoreAnimationPlayground) ![](https://img.shields.io/github/license/knightsc/CoreAnimationPlayground) ![](https://img.shields.io/github/forks/knightsc/CoreAnimationPlayground) ![](https://img.shields.io/github/contributors/knightsc/CoreAnimationPlayground)

* [Core Animation Timing](https://github.com/Kentzo/CoreAnimationTiming) - Playground demonstrating effects of CAMediaTiming properties. 🍁

   ![](https://img.shields.io/github/stars/Kentzo/CoreAnimationTiming) ![](https://img.shields.io/github/last-commit/Kentzo/CoreAnimationTiming) ![](https://img.shields.io/github/issues/Kentzo/CoreAnimationTiming) ![](https://img.shields.io/github/issues-pr/Kentzo/CoreAnimationTiming) ![](https://img.shields.io/github/license/Kentzo/CoreAnimationTiming) ![](https://img.shields.io/github/forks/Kentzo/CoreAnimationTiming) ![](https://img.shields.io/github/contributors/Kentzo/CoreAnimationTiming)


### SpriteKit

* [SceneKit ARKit Demo](https://github.com/mhanlon/ARKitDemoPlayground) - The Xcode 9 ARKit SpriteKit demo as a playground.🍁

   ![](https://img.shields.io/github/stars/mhanlon/ARKitDemoPlayground) ![](https://img.shields.io/github/last-commit/mhanlon/ARKitDemoPlayground) ![](https://img.shields.io/github/issues/mhanlon/ARKitDemoPlayground) ![](https://img.shields.io/github/issues-pr/mhanlon/ARKitDemoPlayground) ![](https://img.shields.io/github/license/mhanlon/ARKitDemoPlayground) ![](https://img.shields.io/github/forks/mhanlon/ARKitDemoPlayground) ![](https://img.shields.io/github/contributors/mhanlon/ARKitDemoPlayground)

* [SpriteKit Swift 3](https://github.com/MacMeDan/SpriteKitCollisions) - Playground for exploring Sprite Kit.

   ![](https://img.shields.io/github/stars/MacMeDan/SpriteKitCollisions) ![](https://img.shields.io/github/last-commit/MacMeDan/SpriteKitCollisions) ![](https://img.shields.io/github/issues/MacMeDan/SpriteKitCollisions) ![](https://img.shields.io/github/issues-pr/MacMeDan/SpriteKitCollisions) ![](https://img.shields.io/github/license/MacMeDan/SpriteKitCollisions) ![](https://img.shields.io/github/forks/MacMeDan/SpriteKitCollisions) ![](https://img.shields.io/github/contributors/MacMeDan/SpriteKitCollisions)

* [SpriteKit Collisions](https://github.com/jaredmpayne/SpriteKitCollisionsPlayground) - Demonstrates how to perform physics collision detection using Swift and SpriteKit. ⏳

   ![](https://img.shields.io/github/stars/jaredmpayne/SpriteKitCollisionsPlayground) ![](https://img.shields.io/github/last-commit/jaredmpayne/SpriteKitCollisionsPlayground) ![](https://img.shields.io/github/issues/jaredmpayne/SpriteKitCollisionsPlayground) ![](https://img.shields.io/github/issues-pr/jaredmpayne/SpriteKitCollisionsPlayground) ![](https://img.shields.io/github/license/jaredmpayne/SpriteKitCollisionsPlayground) ![](https://img.shields.io/github/forks/jaredmpayne/SpriteKitCollisionsPlayground) ![](https://img.shields.io/github/contributors/jaredmpayne/SpriteKitCollisionsPlayground)

* [SceneKit Examples](https://github.com/UCh/swift-scene-kit-playgrounds) - Experiment with SceneKit and Swift. ⏳

   ![](https://img.shields.io/github/stars/UCh/swift-scene-kit-playgrounds) ![](https://img.shields.io/github/last-commit/UCh/swift-scene-kit-playgrounds) ![](https://img.shields.io/github/issues/UCh/swift-scene-kit-playgrounds) ![](https://img.shields.io/github/issues-pr/UCh/swift-scene-kit-playgrounds) ![](https://img.shields.io/github/license/UCh/swift-scene-kit-playgrounds) ![](https://img.shields.io/github/forks/UCh/swift-scene-kit-playgrounds) ![](https://img.shields.io/github/contributors/UCh/swift-scene-kit-playgrounds)

* [Astronomy](https://github.com/cl7/Astronomy) - A 3D earth model written in swift playground using SceneKit.

   ![](https://img.shields.io/github/stars/cl7/Astronomy) ![](https://img.shields.io/github/last-commit/cl7/Astronomy) ![](https://img.shields.io/github/issues/cl7/Astronomy) ![](https://img.shields.io/github/issues-pr/cl7/Astronomy) ![](https://img.shields.io/github/license/cl7/Astronomy) ![](https://img.shields.io/github/forks/cl7/Astronomy) ![](https://img.shields.io/github/contributors/cl7/Astronomy)



## Audio
*Sounds and music*

* [Bach Playground](https://github.com/dreamwieber/BachPlayground) - A Simple Swift Playground that plays a brief piece by Bach with AVAudioEngine and AVMIDIPlayer.

   ![](https://img.shields.io/github/stars/dreamwieber/BachPlayground) ![](https://img.shields.io/github/last-commit/dreamwieber/BachPlayground) ![](https://img.shields.io/github/issues/dreamwieber/BachPlayground) ![](https://img.shields.io/github/issues-pr/dreamwieber/BachPlayground) ![](https://img.shields.io/github/license/dreamwieber/BachPlayground) ![](https://img.shields.io/github/forks/dreamwieber/BachPlayground) ![](https://img.shields.io/github/contributors/dreamwieber/BachPlayground)

* [PlayerNode Playground](https://github.com/genedelisa/PlayerNodePlayground) - Playground using AVAudioEngine with a playernode and effects to play an audio file. 🌟

   ![](https://img.shields.io/github/stars/genedelisa/PlayerNodePlayground) ![](https://img.shields.io/github/last-commit/genedelisa/PlayerNodePlayground) ![](https://img.shields.io/github/issues/genedelisa/PlayerNodePlayground) ![](https://img.shields.io/github/issues-pr/genedelisa/PlayerNodePlayground) ![](https://img.shields.io/github/license/genedelisa/PlayerNodePlayground) ![](https://img.shields.io/github/forks/genedelisa/PlayerNodePlayground) ![](https://img.shields.io/github/contributors/genedelisa/PlayerNodePlayground)

* [Miles](https://github.com/lalomts/Miles) - A Swift Playground that creates jazz improvisations in any key using AudioToolbox and AVFoundation. 

   ![](https://img.shields.io/github/stars/lalomts/Miles) ![](https://img.shields.io/github/last-commit/lalomts/Miles) ![](https://img.shields.io/github/issues/lalomts/Miles) ![](https://img.shields.io/github/issues-pr/lalomts/Miles) ![](https://img.shields.io/github/license/lalomts/Miles) ![](https://img.shields.io/github/forks/lalomts/Miles) ![](https://img.shields.io/github/contributors/lalomts/Miles)


## Mathematics
*Live math with playgrounds*

* [Guilloche Pattern Playground Book](https://github.com/TheWildHorse/GuillochePlayground) - Learn more about this pattern you see every day, but probably never knew it was really carefully designed. 🍁

   ![](https://img.shields.io/github/stars/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/last-commit/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/issues/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/issues-pr/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/license/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/forks/TheWildHorse/GuillochePlayground) ![](https://img.shields.io/github/contributors/TheWildHorse/GuillochePlayground)

* [Lindenmayer Systems](https://github.com/henrinormak/lindenmayer) - A Swift playground exploring Lindemayer systems.

   ![](https://img.shields.io/github/stars/henrinormak/lindenmayer) ![](https://img.shields.io/github/last-commit/henrinormak/lindenmayer) ![](https://img.shields.io/github/issues/henrinormak/lindenmayer) ![](https://img.shields.io/github/issues-pr/henrinormak/lindenmayer) ![](https://img.shields.io/github/license/henrinormak/lindenmayer) ![](https://img.shields.io/github/forks/henrinormak/lindenmayer) ![](https://img.shields.io/github/contributors/henrinormak/lindenmayer)

* [Swift Natural Numbers](https://github.com/jakebromberg/Swift-Natural-Numbers) - A playground for implementing the natural numbers and more concepts in number theory.

   ![](https://img.shields.io/github/stars/jakebromberg/Swift-Natural-Numbers) ![](https://img.shields.io/github/last-commit/jakebromberg/Swift-Natural-Numbers) ![](https://img.shields.io/github/issues/jakebromberg/Swift-Natural-Numbers) ![](https://img.shields.io/github/issues-pr/jakebromberg/Swift-Natural-Numbers) ![](https://img.shields.io/github/license/jakebromberg/Swift-Natural-Numbers) ![](https://img.shields.io/github/forks/jakebromberg/Swift-Natural-Numbers) ![](https://img.shields.io/github/contributors/jakebromberg/Swift-Natural-Numbers)

* [Polydoxical](https://github.com/kirkbyo/Polydoxical) - Interactive playground to experiment with roulettes and polygons.

   ![](https://img.shields.io/github/stars/kirkbyo/Polydoxical) ![](https://img.shields.io/github/last-commit/kirkbyo/Polydoxical) ![](https://img.shields.io/github/issues/kirkbyo/Polydoxical) ![](https://img.shields.io/github/issues-pr/kirkbyo/Polydoxical) ![](https://img.shields.io/github/license/kirkbyo/Polydoxical) ![](https://img.shields.io/github/forks/kirkbyo/Polydoxical) ![](https://img.shields.io/github/contributors/kirkbyo/Polydoxical)

* [Abstract Algebra](https://github.com/taketo1024/SwiftyMath) - Abstract algebra concepts implemented in Swift.

   ![](https://img.shields.io/github/stars/taketo1024/SwiftyMath) ![](https://img.shields.io/github/last-commit/taketo1024/SwiftyMath) ![](https://img.shields.io/github/issues/taketo1024/SwiftyMath) ![](https://img.shields.io/github/issues-pr/taketo1024/SwiftyMath) ![](https://img.shields.io/github/license/taketo1024/SwiftyMath) ![](https://img.shields.io/github/forks/taketo1024/SwiftyMath) ![](https://img.shields.io/github/contributors/taketo1024/SwiftyMath)

* [Swift Accelerate](https://github.com/haginile/SwiftAccelerate) - Using the Accelerate framework and Swift for Linear Algebra. ⏳

   ![](https://img.shields.io/github/stars/haginile/SwiftAccelerate) ![](https://img.shields.io/github/last-commit/haginile/SwiftAccelerate) ![](https://img.shields.io/github/issues/haginile/SwiftAccelerate) ![](https://img.shields.io/github/issues-pr/haginile/SwiftAccelerate) ![](https://img.shields.io/github/license/haginile/SwiftAccelerate) ![](https://img.shields.io/github/forks/haginile/SwiftAccelerate) ![](https://img.shields.io/github/contributors/haginile/SwiftAccelerate)

* [Swifty Mathematics](https://github.com/DylanModesitt/swiftyMathematics) - A collection of swift playground about mathematics. ⏳

   ![](https://img.shields.io/github/stars/DylanModesitt/swiftyMathematics) ![](https://img.shields.io/github/last-commit/DylanModesitt/swiftyMathematics) ![](https://img.shields.io/github/issues/DylanModesitt/swiftyMathematics) ![](https://img.shields.io/github/issues-pr/DylanModesitt/swiftyMathematics) ![](https://img.shields.io/github/license/DylanModesitt/swiftyMathematics) ![](https://img.shields.io/github/forks/DylanModesitt/swiftyMathematics) ![](https://img.shields.io/github/contributors/DylanModesitt/swiftyMathematics)

* [Numerical Algorithms](https://www.raywenderlich.com/99559/numeric-algorithms-using-playgrounds) - Numerical argorithms playground from Ray Wenderlich. ⏳

## Libraries and APIs
*Library tutorials, in a playground*

* [AudioKit Playgrounds](https://audiokit.io/playgrounds/) - 130+ Audio synthesis, processing, playback, and analysis playgrounds with AudioKit.
* [AIToolbox](https://github.com/KevinCoble/AIToolbox/tree/master/Playgrounds) - A set of playgrounds showing machine learning algorithms, all implemented with pieces of the AIToolbox framework code.

   ![](https://img.shields.io/github/stars/KevinCoble/AIToolbox/tree/master/Playgrounds) ![](https://img.shields.io/github/last-commit/KevinCoble/AIToolbox/tree/master/Playgrounds) ![](https://img.shields.io/github/issues/KevinCoble/AIToolbox/tree/master/Playgrounds) ![](https://img.shields.io/github/issues-pr/KevinCoble/AIToolbox/tree/master/Playgrounds) ![](https://img.shields.io/github/license/KevinCoble/AIToolbox/tree/master/Playgrounds) ![](https://img.shields.io/github/forks/KevinCoble/AIToolbox/tree/master/Playgrounds) ![](https://img.shields.io/github/contributors/KevinCoble/AIToolbox/tree/master/Playgrounds)

* [Cognitive Service APIs](https://github.com/codePrincess/playgrounds) - Get started with the Microsoft Cognitive Services APIs.

   ![](https://img.shields.io/github/stars/codePrincess/playgrounds) ![](https://img.shields.io/github/last-commit/codePrincess/playgrounds) ![](https://img.shields.io/github/issues/codePrincess/playgrounds) ![](https://img.shields.io/github/issues-pr/codePrincess/playgrounds) ![](https://img.shields.io/github/license/codePrincess/playgrounds) ![](https://img.shields.io/github/forks/codePrincess/playgrounds) ![](https://img.shields.io/github/contributors/codePrincess/playgrounds)

* [Rx Playground](https://github.com/sgr-ksmt/RxPlayground) - A playground with RxSwift examples.

   ![](https://img.shields.io/github/stars/sgr-ksmt/RxPlayground) ![](https://img.shields.io/github/last-commit/sgr-ksmt/RxPlayground) ![](https://img.shields.io/github/issues/sgr-ksmt/RxPlayground) ![](https://img.shields.io/github/issues-pr/sgr-ksmt/RxPlayground) ![](https://img.shields.io/github/license/sgr-ksmt/RxPlayground) ![](https://img.shields.io/github/forks/sgr-ksmt/RxPlayground) ![](https://img.shields.io/github/contributors/sgr-ksmt/RxPlayground)


## Playground Sets
*Sets of playgrounds about various topics*

* [Parks And Recreation](https://github.com/zwaldowski/ParksAndRecreation) - Great collection of interesting playgrounds, for fun and for profit. 🍁🌟

   ![](https://img.shields.io/github/stars/zwaldowski/ParksAndRecreation) ![](https://img.shields.io/github/last-commit/zwaldowski/ParksAndRecreation) ![](https://img.shields.io/github/issues/zwaldowski/ParksAndRecreation) ![](https://img.shields.io/github/issues-pr/zwaldowski/ParksAndRecreation) ![](https://img.shields.io/github/license/zwaldowski/ParksAndRecreation) ![](https://img.shields.io/github/forks/zwaldowski/ParksAndRecreation) ![](https://img.shields.io/github/contributors/zwaldowski/ParksAndRecreation)

* [URaimo's Playgrounds](https://github.com/uraimo/Swift-Playgrounds) - My playgrounds, various topics. 🍁

   ![](https://img.shields.io/github/stars/uraimo/Swift-Playgrounds) ![](https://img.shields.io/github/last-commit/uraimo/Swift-Playgrounds) ![](https://img.shields.io/github/issues/uraimo/Swift-Playgrounds) ![](https://img.shields.io/github/issues-pr/uraimo/Swift-Playgrounds) ![](https://img.shields.io/github/license/uraimo/Swift-Playgrounds) ![](https://img.shields.io/github/forks/uraimo/Swift-Playgrounds) ![](https://img.shields.io/github/contributors/uraimo/Swift-Playgrounds)

* [Public Extensions](https://github.com/Jasdev/Public-Extension) - A set of useful extensions from [@PublicExtension](https://twitter.com/publicextension). 🌟

   ![](https://img.shields.io/github/stars/Jasdev/Public-Extension) ![](https://img.shields.io/github/last-commit/Jasdev/Public-Extension) ![](https://img.shields.io/github/issues/Jasdev/Public-Extension) ![](https://img.shields.io/github/issues-pr/Jasdev/Public-Extension) ![](https://img.shields.io/github/license/Jasdev/Public-Extension) ![](https://img.shields.io/github/forks/Jasdev/Public-Extension) ![](https://img.shields.io/github/contributors/Jasdev/Public-Extension)

* [ManuelCarlos's Playgrouds](https://github.com/manuelCarlos/Swift-Playgrounds) - Various playgrounds.

   ![](https://img.shields.io/github/stars/manuelCarlos/Swift-Playgrounds) ![](https://img.shields.io/github/last-commit/manuelCarlos/Swift-Playgrounds) ![](https://img.shields.io/github/issues/manuelCarlos/Swift-Playgrounds) ![](https://img.shields.io/github/issues-pr/manuelCarlos/Swift-Playgrounds) ![](https://img.shields.io/github/license/manuelCarlos/Swift-Playgrounds) ![](https://img.shields.io/github/forks/manuelCarlos/Swift-Playgrounds) ![](https://img.shields.io/github/contributors/manuelCarlos/Swift-Playgrounds)

* [Mgrebenets's Playgrounds](https://github.com/mgrebenets/playgrounds) - Various playgrounds.c 🌟

   ![](https://img.shields.io/github/stars/mgrebenets/playgrounds) ![](https://img.shields.io/github/last-commit/mgrebenets/playgrounds) ![](https://img.shields.io/github/issues/mgrebenets/playgrounds) ![](https://img.shields.io/github/issues-pr/mgrebenets/playgrounds) ![](https://img.shields.io/github/license/mgrebenets/playgrounds) ![](https://img.shields.io/github/forks/mgrebenets/playgrounds) ![](https://img.shields.io/github/contributors/mgrebenets/playgrounds)

* [Cocoa With Love Playgrounds](https://github.com/mattgallagher/CocoaWithLovePlaygrounds) - Playground versions of select articles from Cocoa with Love.  🌟 

   ![](https://img.shields.io/github/stars/mattgallagher/CocoaWithLovePlaygrounds) ![](https://img.shields.io/github/last-commit/mattgallagher/CocoaWithLovePlaygrounds) ![](https://img.shields.io/github/issues/mattgallagher/CocoaWithLovePlaygrounds) ![](https://img.shields.io/github/issues-pr/mattgallagher/CocoaWithLovePlaygrounds) ![](https://img.shields.io/github/license/mattgallagher/CocoaWithLovePlaygrounds) ![](https://img.shields.io/github/forks/mattgallagher/CocoaWithLovePlaygrounds) ![](https://img.shields.io/github/contributors/mattgallagher/CocoaWithLovePlaygrounds)

* [Sketchytech's Playgrounds](https://github.com/sketchytech/SwiftPlaygrounds) - Various Playgrounds. 🌟 ⏳

   ![](https://img.shields.io/github/stars/sketchytech/SwiftPlaygrounds) ![](https://img.shields.io/github/last-commit/sketchytech/SwiftPlaygrounds) ![](https://img.shields.io/github/issues/sketchytech/SwiftPlaygrounds) ![](https://img.shields.io/github/issues-pr/sketchytech/SwiftPlaygrounds) ![](https://img.shields.io/github/license/sketchytech/SwiftPlaygrounds) ![](https://img.shields.io/github/forks/sketchytech/SwiftPlaygrounds) ![](https://img.shields.io/github/contributors/sketchytech/SwiftPlaygrounds)

* [Swift fun playgrounds](https://github.com/madbat/Swift-fun-playgrounds) - A few playgrounds to showcase Swift peculiar features. ⏳

   ![](https://img.shields.io/github/stars/madbat/Swift-fun-playgrounds) ![](https://img.shields.io/github/last-commit/madbat/Swift-fun-playgrounds) ![](https://img.shields.io/github/issues/madbat/Swift-fun-playgrounds) ![](https://img.shields.io/github/issues-pr/madbat/Swift-fun-playgrounds) ![](https://img.shields.io/github/license/madbat/Swift-fun-playgrounds) ![](https://img.shields.io/github/forks/madbat/Swift-fun-playgrounds) ![](https://img.shields.io/github/contributors/madbat/Swift-fun-playgrounds)

* [BradLarson's Playgrounds](https://github.com/BradLarson/PersonalSwiftPlaygrounds) - Various playgrounds. ⏳

   ![](https://img.shields.io/github/stars/BradLarson/PersonalSwiftPlaygrounds) ![](https://img.shields.io/github/last-commit/BradLarson/PersonalSwiftPlaygrounds) ![](https://img.shields.io/github/issues/BradLarson/PersonalSwiftPlaygrounds) ![](https://img.shields.io/github/issues-pr/BradLarson/PersonalSwiftPlaygrounds) ![](https://img.shields.io/github/license/BradLarson/PersonalSwiftPlaygrounds) ![](https://img.shields.io/github/forks/BradLarson/PersonalSwiftPlaygrounds) ![](https://img.shields.io/github/contributors/BradLarson/PersonalSwiftPlaygrounds)

* [Dmikusa's Playgrounds](https://github.com/dmikusa/swift_playgrounds) - Playgrounds that show basic Swift, JSON parsing, sending HTTP requests and basic file IO. ⏳

   ![](https://img.shields.io/github/stars/dmikusa/swift_playgrounds) ![](https://img.shields.io/github/last-commit/dmikusa/swift_playgrounds) ![](https://img.shields.io/github/issues/dmikusa/swift_playgrounds) ![](https://img.shields.io/github/issues-pr/dmikusa/swift_playgrounds) ![](https://img.shields.io/github/license/dmikusa/swift_playgrounds) ![](https://img.shields.io/github/forks/dmikusa/swift_playgrounds) ![](https://img.shields.io/github/contributors/dmikusa/swift_playgrounds)

* [Cananito's Playgrounds](https://github.com/Cananito/Playgrounds) - Various playgrounds. ⏳

   ![](https://img.shields.io/github/stars/Cananito/Playgrounds) ![](https://img.shields.io/github/last-commit/Cananito/Playgrounds) ![](https://img.shields.io/github/issues/Cananito/Playgrounds) ![](https://img.shields.io/github/issues-pr/Cananito/Playgrounds) ![](https://img.shields.io/github/license/Cananito/Playgrounds) ![](https://img.shields.io/github/forks/Cananito/Playgrounds) ![](https://img.shields.io/github/contributors/Cananito/Playgrounds)

* [Uberbruns's Playgrounds](https://github.com/uberbruns/SwiftPlaygrounds) - Various playgrounds. ⏳

   ![](https://img.shields.io/github/stars/uberbruns/SwiftPlaygrounds) ![](https://img.shields.io/github/last-commit/uberbruns/SwiftPlaygrounds) ![](https://img.shields.io/github/issues/uberbruns/SwiftPlaygrounds) ![](https://img.shields.io/github/issues-pr/uberbruns/SwiftPlaygrounds) ![](https://img.shields.io/github/license/uberbruns/SwiftPlaygrounds) ![](https://img.shields.io/github/forks/uberbruns/SwiftPlaygrounds) ![](https://img.shields.io/github/contributors/uberbruns/SwiftPlaygrounds)


## Miscellaneous
*What doesn't fit anywhere else, but still awesome*

* [Rubik's Cube](https://github.com/codelynx/CoreRubiksCube) - Implementing basic model and behavior of Rubic's Cube in Swift. 🍁

   ![](https://img.shields.io/github/stars/codelynx/CoreRubiksCube) ![](https://img.shields.io/github/last-commit/codelynx/CoreRubiksCube) ![](https://img.shields.io/github/issues/codelynx/CoreRubiksCube) ![](https://img.shields.io/github/issues-pr/codelynx/CoreRubiksCube) ![](https://img.shields.io/github/license/codelynx/CoreRubiksCube) ![](https://img.shields.io/github/forks/codelynx/CoreRubiksCube) ![](https://img.shields.io/github/contributors/codelynx/CoreRubiksCube)

* [Icon Creator](https://github.com/tnantoka/IconCreator) - Create app icons on Swift playground.

   ![](https://img.shields.io/github/stars/tnantoka/IconCreator) ![](https://img.shields.io/github/last-commit/tnantoka/IconCreator) ![](https://img.shields.io/github/issues/tnantoka/IconCreator) ![](https://img.shields.io/github/issues-pr/tnantoka/IconCreator) ![](https://img.shields.io/github/license/tnantoka/IconCreator) ![](https://img.shields.io/github/forks/tnantoka/IconCreator) ![](https://img.shields.io/github/contributors/tnantoka/IconCreator)

* [2048 Playground](https://github.com/robin/2048_Playground) - The 2048 game implemented with a playground.

   ![](https://img.shields.io/github/stars/robin/2048_Playground) ![](https://img.shields.io/github/last-commit/robin/2048_Playground) ![](https://img.shields.io/github/issues/robin/2048_Playground) ![](https://img.shields.io/github/issues-pr/robin/2048_Playground) ![](https://img.shields.io/github/license/robin/2048_Playground) ![](https://img.shields.io/github/forks/robin/2048_Playground) ![](https://img.shields.io/github/contributors/robin/2048_Playground)

* [SwiftShell](https://github.com/JustinJiaDev/SwiftShell) - Bash shell in a playground.

   ![](https://img.shields.io/github/stars/JustinJiaDev/SwiftShell) ![](https://img.shields.io/github/last-commit/JustinJiaDev/SwiftShell) ![](https://img.shields.io/github/issues/JustinJiaDev/SwiftShell) ![](https://img.shields.io/github/issues-pr/JustinJiaDev/SwiftShell) ![](https://img.shields.io/github/license/JustinJiaDev/SwiftShell) ![](https://img.shields.io/github/forks/JustinJiaDev/SwiftShell) ![](https://img.shields.io/github/contributors/JustinJiaDev/SwiftShell)

* [LaunchPad Playground](https://github.com/Juniorlimaivd/LaunchPad-Playground) - A playground that simulates a real LaunchPad for making music.

   ![](https://img.shields.io/github/stars/Juniorlimaivd/LaunchPad-Playground) ![](https://img.shields.io/github/last-commit/Juniorlimaivd/LaunchPad-Playground) ![](https://img.shields.io/github/issues/Juniorlimaivd/LaunchPad-Playground) ![](https://img.shields.io/github/issues-pr/Juniorlimaivd/LaunchPad-Playground) ![](https://img.shields.io/github/license/Juniorlimaivd/LaunchPad-Playground) ![](https://img.shields.io/github/forks/Juniorlimaivd/LaunchPad-Playground) ![](https://img.shields.io/github/contributors/Juniorlimaivd/LaunchPad-Playground)

* [Super Maze](https://github.com/W00dL3cs/Super-Maze) - A programmatic maze generator and solver.

   ![](https://img.shields.io/github/stars/W00dL3cs/Super-Maze) ![](https://img.shields.io/github/last-commit/W00dL3cs/Super-Maze) ![](https://img.shields.io/github/issues/W00dL3cs/Super-Maze) ![](https://img.shields.io/github/issues-pr/W00dL3cs/Super-Maze) ![](https://img.shields.io/github/license/W00dL3cs/Super-Maze) ![](https://img.shields.io/github/forks/W00dL3cs/Super-Maze) ![](https://img.shields.io/github/contributors/W00dL3cs/Super-Maze)

* [Tic Tac Toe](https://github.com/aabosh/Tic-Tac-Toe) - Tic tac toe in a playground.

   ![](https://img.shields.io/github/stars/aabosh/Tic-Tac-Toe) ![](https://img.shields.io/github/last-commit/aabosh/Tic-Tac-Toe) ![](https://img.shields.io/github/issues/aabosh/Tic-Tac-Toe) ![](https://img.shields.io/github/issues-pr/aabosh/Tic-Tac-Toe) ![](https://img.shields.io/github/license/aabosh/Tic-Tac-Toe) ![](https://img.shields.io/github/forks/aabosh/Tic-Tac-Toe) ![](https://img.shields.io/github/contributors/aabosh/Tic-Tac-Toe)

* [Pixel Art Maker](https://github.com/BenEmdon/PixelArtMaker) - A playground where you can make pixel art.

   ![](https://img.shields.io/github/stars/BenEmdon/PixelArtMaker) ![](https://img.shields.io/github/last-commit/BenEmdon/PixelArtMaker) ![](https://img.shields.io/github/issues/BenEmdon/PixelArtMaker) ![](https://img.shields.io/github/issues-pr/BenEmdon/PixelArtMaker) ![](https://img.shields.io/github/license/BenEmdon/PixelArtMaker) ![](https://img.shields.io/github/forks/BenEmdon/PixelArtMaker) ![](https://img.shields.io/github/contributors/BenEmdon/PixelArtMaker)

* [SwiftCoin](https://github.com/Thomvis/Swiftcoin) - A simplistic blockchain & cryptocurrency in a playground.

   ![](https://img.shields.io/github/stars/Thomvis/Swiftcoin) ![](https://img.shields.io/github/last-commit/Thomvis/Swiftcoin) ![](https://img.shields.io/github/issues/Thomvis/Swiftcoin) ![](https://img.shields.io/github/issues-pr/Thomvis/Swiftcoin) ![](https://img.shields.io/github/license/Thomvis/Swiftcoin) ![](https://img.shields.io/github/forks/Thomvis/Swiftcoin) ![](https://img.shields.io/github/contributors/Thomvis/Swiftcoin)

* [SentimentlySwift](https://github.com/benbahrenburg/SentimentlySwift) - Sentiment analysis in Swift. 

   ![](https://img.shields.io/github/stars/benbahrenburg/SentimentlySwift) ![](https://img.shields.io/github/last-commit/benbahrenburg/SentimentlySwift) ![](https://img.shields.io/github/issues/benbahrenburg/SentimentlySwift) ![](https://img.shields.io/github/issues-pr/benbahrenburg/SentimentlySwift) ![](https://img.shields.io/github/license/benbahrenburg/SentimentlySwift) ![](https://img.shields.io/github/forks/benbahrenburg/SentimentlySwift) ![](https://img.shields.io/github/contributors/benbahrenburg/SentimentlySwift)

* [SwiftChain](https://github.com/gg2001/SwiftChain) - Simple Cryptocurrency in a Swift Playground.

   ![](https://img.shields.io/github/stars/gg2001/SwiftChain) ![](https://img.shields.io/github/last-commit/gg2001/SwiftChain) ![](https://img.shields.io/github/issues/gg2001/SwiftChain) ![](https://img.shields.io/github/issues-pr/gg2001/SwiftChain) ![](https://img.shields.io/github/license/gg2001/SwiftChain) ![](https://img.shields.io/github/forks/gg2001/SwiftChain) ![](https://img.shields.io/github/contributors/gg2001/SwiftChain)

* [Game Boards](https://github.com/joalbright/Gameboard) - Chess, checkers, tic-tac-toe, sudoku and many others in playground. 🌟 ⏳

   ![](https://img.shields.io/github/stars/joalbright/Gameboard) ![](https://img.shields.io/github/last-commit/joalbright/Gameboard) ![](https://img.shields.io/github/issues/joalbright/Gameboard) ![](https://img.shields.io/github/issues-pr/joalbright/Gameboard) ![](https://img.shields.io/github/license/joalbright/Gameboard) ![](https://img.shields.io/github/forks/joalbright/Gameboard) ![](https://img.shields.io/github/contributors/joalbright/Gameboard)

* [StarWars Seals](https://github.com/jeremyconkin/StarWarsSeals) - Emblems from Star Wars in Swift playgrounds via CoreGraphics and UIViews. ⏳

   ![](https://img.shields.io/github/stars/jeremyconkin/StarWarsSeals) ![](https://img.shields.io/github/last-commit/jeremyconkin/StarWarsSeals) ![](https://img.shields.io/github/issues/jeremyconkin/StarWarsSeals) ![](https://img.shields.io/github/issues-pr/jeremyconkin/StarWarsSeals) ![](https://img.shields.io/github/license/jeremyconkin/StarWarsSeals) ![](https://img.shields.io/github/forks/jeremyconkin/StarWarsSeals) ![](https://img.shields.io/github/contributors/jeremyconkin/StarWarsSeals)

* [SwiftFiles](https://github.com/sketchytech/SwiftFiles) - Save, Load and Delete files easily from within a Swift playground. ⏳

   ![](https://img.shields.io/github/stars/sketchytech/SwiftFiles) ![](https://img.shields.io/github/last-commit/sketchytech/SwiftFiles) ![](https://img.shields.io/github/issues/sketchytech/SwiftFiles) ![](https://img.shields.io/github/issues-pr/sketchytech/SwiftFiles) ![](https://img.shields.io/github/license/sketchytech/SwiftFiles) ![](https://img.shields.io/github/forks/sketchytech/SwiftFiles) ![](https://img.shields.io/github/contributors/sketchytech/SwiftFiles)

* [Earth photos](https://github.com/jtbandes/DSCOVR.playground) - A slideshow of Earth photos taken by DSCOVR/EPIC. 🌟 ⏳

   ![](https://img.shields.io/github/stars/jtbandes/DSCOVR.playground) ![](https://img.shields.io/github/last-commit/jtbandes/DSCOVR.playground) ![](https://img.shields.io/github/issues/jtbandes/DSCOVR.playground) ![](https://img.shields.io/github/issues-pr/jtbandes/DSCOVR.playground) ![](https://img.shields.io/github/license/jtbandes/DSCOVR.playground) ![](https://img.shields.io/github/forks/jtbandes/DSCOVR.playground) ![](https://img.shields.io/github/contributors/jtbandes/DSCOVR.playground)



