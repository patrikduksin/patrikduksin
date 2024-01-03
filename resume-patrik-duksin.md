# Patrik Duksin
## Senior software engineer with 4+ years of experience
[GitHub](https://github.com/patrikduksin) | [Email](mailto:patrikduksin@gmail.com) | [Cal](https://cal.com/patrikduksin)

I'm a senior software engineer with 4+ years of experience in mobile development. I love to build financial products, 
being highly interested in DeFi and crypto.
In my work, I like to experiment to better understand the user and improve UX.

Proficient in native iOS and cross-platform react-native development. Have a lot of experience in crypto projects.
Eager to solve research-heavy problems and adopt new technologies in a meaningful way.

Tech Stack
-
- **iOS**: SwiftUI, UIKit, Combine, Structured concurrency, Realm, Alamofire, CoreAnimation, CoreML, XCTest
- **Frontend**: Javascript, Typescript, React Native, Redux, Styled Components, React Navigation
- **CI/CD**: Fastlane, CocoaPods, Swift Package Manager, SwiftLint, Tuist, Git, Make

Experience - 4+ years
-
**Sweat Economy, March 2023 – December 2023<br>
Senior Software Engineer**

https://sweateconomy.com/

Development of the crypto wallet for Sweat Economy friendly to web2 users.

Stack: Javascript, Typescript, React Native, Redux, Styled Components, React Navigation

First react-native project for me. Learned a lot of new things: js, react-native, redux, tools, etc. In a short time I started to contribute to the project using a completely new stack for me.

- Increased speed of processing order book data by splitting up requests and processing them asynchronously to make interface faster.
- Migrated to RTK Query for fetching trading data. It reduced boilerplate code and made work with caching and states easier.
- Worked on the app translation infrastructure. Helped to reach larger audience. Implemented translation to Brazilian Portuguese.
- Proposed definition of done for the design handoff process. It helped to increase layout development speed and reduce miscommunication with designers.

<br>

**Here Wallet Inc, March 2022 – March 2023<br>
iOS Team Lead**

https://herewallet.app/

Development of the first mobile crypto wallet for Near Protocol.

Stack: UIKit, SwiftUI, Structured concurrency, Alamofire, Tuist, Swift package manager, AppClip, GitHub Actions, Fastlane.

- Broke the application into modules using Tuist and SPM, configured code-generation for assets and configs, which allowed iterations on features faster and shortened time2market.
- Proposed and developed AppClip for instant registration in an application, which increased the registration conversion of new users by ~30 percent. The feature has made a huge impact in the Near community. 
- Lead analytics migration from direct use of Mixpanel to proxy events through the backend. Reduced the cost of using analytical services and eliminated duplication of events.
- Integrated Sentry to track release stability and critical functionality. Set up crash alerts, which helped to identify several critical situations at an early stage. 
- Implemented a 100% programmatic UI in Swift using UIKit.
- Used NSCollectionViewCompositionalLayout and UICollectionViewDiffableDataSource for the CollectionView.
- Significantly reduced the number of "classic" asynchronous bugs, improved code readability, and simplified complex synchronization tasks by using a new model for performing asynchronous operations: async/await, Actor, Task, AsyncSequence
- Implemented key generation and transaction signing functionality using an interop between C and Swift.
- Implemented a networking layer allowing RPC nodes to work with blockchain using custom data decoding.
- Speed up prototyping of simple screens using SwiftUI

<br>

**Oops Finance Inc, March 2021 – February 2022 <br>
Senior iOS Engineer**

https://oops.finance/

Development of a financial manager for gen z from scratch, with an audience of tens of thousands of people. Release to the App Store.

Stack: SwiftUI, UIKit, CoreAnimation, Combine, Alamofire, Tuist, Swift package manager, Plaid SDK, GitHub Actions, Fastlane.

- Implemented integration with US and European banks via Plaid
- Had been collaborating with the backend and the product team. We developed a notification system that significantly increases retention.
- Implemented a network layer using Alamofire, with request logging, significantly speeding up debugging with the backend team.
- Developed analytics layer with generic service provider, which helped to easily migrate from Mixpanel to Amplitude SDK.
- Collaborated with backend engineers to develop REST API contracts.
- Reviewed code of 2 fellow engineers.
- Co-authored code standards for the iOS team.
- Increased the speed of checking pull requests by setting up CI / CD to automatically check the code style and the correctness of the pull request.
- Automated application build via GitHub Action + Fastlane. It accelerated the testing of new functionality, shortening the path from a merged pull request to testing
<br>

**Fora Vision, December 2019 – February 2021 <br>
iOS Engineer**

https://fora.vision/

Development of a workout app with real-time on-device exercise recognition.

Stack: SwiftUI, CoreML, MLKit, AVFoundation, GCD.

- Implemented a video stream handler using AVFoundation
- Parallelized the video stream processing into different threads to receive data from two neural networks: Apple CoreML + Google MLKit.
- Eliminated the number of unnecessary repetitions by 36% by implementing a visual notification of successful completion by highlighting the skeleton during the exercise.
- Implemented the ability to pause the training and restore it in case of a disconnection from the backend, increasing the percentage of completed workouts.
- Implemented the transfer of information about the body's position to the backend using a websocket.
<br>

Education
- 
**ITMO, Software engineering**

