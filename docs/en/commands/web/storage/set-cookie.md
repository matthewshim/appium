# Set Cookie

Set a cookie (Web context only)
## Example Usage

```java
// Java
driver.manage().addCookie(new Cookie("foo", "bar"));

```

```python
# Python
self.driver.add_cookie({name: 'foo', value: 'bar'})

```

```javascript
// Javascript
// webdriver.io example
driver.cookie('post', {
  name: 'myCookie',
  value: 'some content'
});



// wd example
let cookies = await driver.setCookie({name: 'foo', value: 'bar'});

```

```ruby
# Ruby
@driver.add_cookie(:name => 'foo', :value => 'bar')

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

 * [Java](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/remote/RemoteWebDriver.RemoteWebDriverOptions.html#addCookie-org.openqa.selenium.Cookie-) 
 * [Python](http://selenium-python.readthedocs.io/api.html#selenium.webdriver.remote.webdriver.WebDriver.add_cookie) 
 * [Javascript (WebdriverIO)](http://webdriver.io/api/protocol/cookie.html) 
 * [Javascript (WD)](https://github.com/admc/wd/blob/master/lib/commands.js#L1971) 
 * [Ruby](http://www.rubydoc.info/gems/selenium-webdriver/Selenium/WebDriver/Options:add_cookie) 
 * [PHP](https://github.com/appium/php-client/) 
 * [C#](https://github.com/appium/appium-dotnet-driver/) 

## Support

### Appium Server

|Platform|Driver|Platform Versions|Appium Version|Driver Version|
|--------|----------------|------|--------------|--------------|
| iOS | [XCUITest](/docs/en/drivers/ios-xcuitest.md) | None | None | None |
|  | [UIAutomation](/docs/en/drivers/ios-uiautomation.md) | None | None | None |
| Android | [UiAutomator2](/docs/en/drivers/android-uiautomator2.md) | None | None | None |
|  | [UiAutomator](/docs/en/drivers/android-uiautomator.md) | None | None | None |
| Mac | [Mac](/docs/en/drivers/mac.md) | None | None | None |
| Windows | [Windows](/docs/en/drivers/windows.md) | None | None | None |

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

`POST /wd/hub/session/:sessionId/cookie`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to route the command to|

### JSON Parameters

|name|type|description|
|----|----|-----------|
| cookie | object | The cookie to add |

### Response

null

## See Also

* [W3C Specification](https://www.w3.org/TR/webdriver/#dfn-delete-cookie)
* [JSONWP Specification](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol#sessionsessionidcookie)
