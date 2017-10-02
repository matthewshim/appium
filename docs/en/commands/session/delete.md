# Delete Session

Delete the session
## Example Usage

```java
// Java
driver.quit();

```

```python
# Python
self.driver.quit()

```

```javascript
// Javascript
// webdriver.io example
driver.end();


// wd example
await driver.quit();

```

```ruby
# Ruby
@driver.quit();

```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
// TODO C# sample

```



## Client Docs

 * [Java](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/remote/RemoteWebDriver.html#quit--) 
 * [Python](http://selenium-python.readthedocs.io/api.html#selenium.webdriver.remote.webdriver.WebDriver.quit) 
 * [Javascript (WebdriverIO)](http://webdriver.io/api/utility/end.html) 
 * [Javascript (WD)](https://github.com/admc/wd/blob/master/lib/commands.js#L470) 
 * [Ruby](http://www.rubydoc.info/gems/selenium-webdriver/Selenium/WebDriver/Driver:quit) 
 * [PHP](https://github.com/appium/php-client/) 
 * [C#](https://github.com/appium/appium-dotnet-driver/) 

## Support

### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | 9.3+ | 1.6.0+ | All |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | 8.0 to 9.3 | All | All |
| Android | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | ?+ | 1.6.0+ | All |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | 4.2+ | All | All |
| Mac | [Mac](/docs/en/drivers/mac.md) | ?+ | 1.6.4+ | All |
| Windows | [Windows](/docs/en/drivers/windows.md) | 10+ | 1.6.0+ | All |

### Appium Clients 

|Language|Support|
|--------|-------|
|[Java](https://github.com/appium/java-client/releases/latest)| All |
|[Python](https://github.com/appium/python-client/releases/latest)| All |
|[Javascript (WebdriverIO)](http://webdriver.io/index.html)| All |
|[Javascript (WD)](https://github.com/admc/wd/releases/latest)| All |
|[Ruby](https://github.com/appium/ruby_lib/releases/latest)| All |
|[PHP](https://github.com/appium/php-client/releases/latest)| All |
|[C#](https://github.com/appium/appium-dotnet-driver/releases/latest)| All |

## HTTP API Specifications

### Endpoint

`DELETE /session/:session_id`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to delete|

### JSON Parameters

None

### Response

null

## See Also

* [W3C Specification](https://www.w3.org/TR/webdriver/#dfn-delete-session)
* [JSONWP Specification](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol#sessionsessionid)
