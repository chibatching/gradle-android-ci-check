# Android CI check Gradle

## How to use

Add below line under your build.gradle.

```
apply from: "https://raw.githubusercontent.com/chibatching/gradle-android-ci-check/master/ci.gradle"
```

## Use your own configs

If you want to use your own configs, write local config file path on gradle.properties

```
checkStyleConfigFile=../config/quality/checkstyle/checkstyle.xml
findBugsExcludeFilter=../config/quality/findbugs/findbugs-filter.xml
pmdRuleSetFile=../config/quality/pmd/pmd-ruleset.xml
```
