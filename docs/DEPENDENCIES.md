
---

## 📁 `docs/DEPENDENCIES.md`

```md
<h2 align="center">🧰 JazzCash Mobile — Dependencies & Libraries</h2>

---

### 🧱 Core Dependencies (Android)

| Category | Library | Description |
|-----------|----------|-------------|
| **Networking** | Retrofit, OkHttp | REST API communication |
| **JSON Parsing** | Gson / Moshi | JSON serialization |
| **Local Database** | Room / Realm | Offline caching and persistence |
| **Dependency Injection** | Dagger / Hilt | Modular, testable architecture |
| **Coroutines / RxJava** | Kotlin Coroutines / RxJava3 | Asynchronous data flow |
| **Image Loading** | Glide / Coil | Efficient image caching |
| **Security** | Android Keystore, EncryptedSharedPrefs | Secure data storage |
| **Logging** | Timber | Debug and error logs |
| **Testing** | JUnit, Espresso | Unit and UI testing |
| **Crash Reporting** | Firebase Crashlytics | App stability monitoring |

---

### 🍎 Core Dependencies (iOS)

| Category | Library | Description |
|-----------|----------|-------------|
| **Networking** | Alamofire | HTTP networking and request management |
| **JSON Parsing** | Codable / SwiftyJSON | JSON decoding |
| **Local Database** | CoreData / RealmSwift | Offline storage |
| **Dependency Injection** | Resolver / Swinject | Inversion of control |
| **Asynchronous Programming** | Combine / RxSwift | Reactive programming |
| **UI Components** | SwiftUI / UIKit Extensions | Custom UI views |
| **Security** | KeychainAccess | Secure credentials storage |
| **Crash Reporting** | Sentry / Firebase Crashlytics | Crash and error analytics |
| **Testing** | XCTest | Unit and integration testing |

---

### 🔒 Security & Compliance Libraries

- **SSL Pinning:** OkHttp CertificatePinner / Alamofire SecurityPolicy  
- **Obfuscation:** ProGuard / R8 for Android, Bitcode & Symbol stripping for iOS  
- **Device Integrity:** SafetyNet / DeviceCheck APIs  
- **Analytics & Monitoring:** Firebase Analytics, AppCenter, Grafana dashboards  

---

### ⚙️ DevOps Tooling

- **CI/CD:** Jenkins, GitHub Actions, Fastlane  
- **Quality:** SonarQube, CodeCov  
- **Build Distribution:** Firebase App Distribution, TestFlight  
- **Profiling:** Android Profiler, Xcode Instruments  
