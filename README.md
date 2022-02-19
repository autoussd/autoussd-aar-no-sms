# AutoUssd

[AutoUssd](https://autoussd.com) is a powerful USSD automation SDK for Android which allows you to build Android applications on top of USSD services. Find out more on our [website](https://autoussd.com).

---

> **NOTICE!!!**
>
> Due to Google's new restrictions on SMS permissions being a sensitive permission, we've removed all SMS related features from this version.
>
> This makes it easier for you to release your an using AutoUssd on the Google Play Store.

---

## Installation

1. Add the Maven repository to your **project-level** `build.gradle`

```groovy
allProjects {
  repositories {
    ...
    maven { url 'https://raw.github.com/autoussd/autoussd-aar-no-sms/master' };
  }
}
```

2. Add the SDK dependency to your **app-level** `build.gradle`

```groovy
dependencies {
  ...
  implementation 'com.autoussd:autoussd-sdk:1.2.1';
}
```

3. Sync project with Gradle Files

## Usage

Click [here](https://autoussd.com/docs) to visit our beginner-friendly [guide](https://autoussd.com/docs) to get started with AutoUssd.