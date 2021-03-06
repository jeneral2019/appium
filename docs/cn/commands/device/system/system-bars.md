# 获取系统栏

获取状态栏和导航栏的可见度和边界信息
[//]: # (DO NOT EDIT THIS FILE! This is an auto-generated file. Editing for this document happens in /commands-yml/commands/device/system/system-bars.yml)
## 使用样例

```java
// Java
Map<String, String> systemBars = driver.getSystemBars();

```

```python
# Python
self.driver.get_system_bars()

```

```javascript
// Javascript
// webdriver.io example
driver.getSystemBars();

// Not supported
```

```ruby
# Ruby
# ruby_lib example
get_system_bars

# ruby_lib_core example
@driver.get_system_bars

```

```php
# PHP
// TODO

```

```csharp
// C#
// TODO

```


## 支持

### Appium Server

|平台|Driver|平台版本|Appium版本|Driver版本|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | None | None | None |
| Android | [Espresso](/docs/en/drivers/android-espresso.md) | ?+ | 1.9.0+ | All |
|  | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.3+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | None | None | None |


### Appium 客户端

|语言|支持版本|文档|
|--------|-------|-------------|
|[Java](https://github.com/appium/java-client/releases/latest)| All | [appium.github.io](https://appium.github.io/java-client/io/appium/java_client/android/HasAndroidDeviceDetails.html#getSystemBars--) |
|[Python](https://github.com/appium/python-client/releases/latest)| All | [appium.github.io](https://appium.github.io/python-client-sphinx/webdriver.extensions.android.html#webdriver.extensions.android.system_bars.SystemBars.get_system_bars) |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |  |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| None |  |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All | [www.rubydoc.info](https://www.rubydoc.info/github/appium/ruby_lib_core/Appium/Core/Device#get_system_bars-instance_method) |
|[PHP](https://github.com/appium/php-client/releases/latest)| None | [github.com](https://github.com/appium/php-client/) |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| None | [github.com](https://github.com/appium/appium-dotnet-driver/) |


## HTTP API 规范

### 端点

`GET /session/:session_id/appium/device/system_bars`


### URL 参数

|名称|描述|
|----|-----------|
|session_id|用来发送指令的会话id|


### JSON 参数

None

### 响应
状态栏和导航栏可见度和边界信息(`array<object>`)


## 参考

* [JSONWP Specification](https://github.com/appium/appium-base-driver/blob/master/lib/protocol/routes.js#L535)
