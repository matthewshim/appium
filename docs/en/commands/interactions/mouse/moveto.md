# Move Mouse To

Move the mouse by an offset of the specificed element
## Example Usage

```java
// Java
Actions action = new Actions(driver);
action.moveTo(element, 10, 10);
action.perform()

```

```python
# Python
actions = ActionChains(driver)
actions.move_to(element, 10, 10)
actions.perform()

```

```javascript
// Javascript
// webdriver.io example
driver.moveTo(element, 10, 10);



// wd example
await driver.moveTo(element, 10, 10);

```

```ruby
# Ruby
@driver.mouse.move_to(element)
@driver.mouse.move_to(element, 5, 5)

```

```php
# PHP
// TODO PHP sample

```

```csharp
// C#
// TODO C# sample

```


## Description

If no element is specified, the move is relative to the current mouse cursor. If an element is provided but no offset, the mouse will be moved to the center of the element. If the element is not visible, it will be scrolled into view.


## Client Docs

 * [Java](https://seleniumhq.github.io/selenium/docs/api/java/org/openqa/selenium/interactions/Actions.html#moveToElement-org.openqa.selenium.WebElement-) 
 * [Python](http://selenium-python.readthedocs.io/api.html#selenium.webdriver.common.action_chains.ActionChains.move_to_element) 
 * [Javascript (WebdriverIO)](http://webdriver.io/api/protocol/moveTo.html#description) 
 * [Javascript (WD)](https://github.com/admc/wd/blob/master/lib/commands.js#L1600) 
 * [Ruby](http://www.rubydoc.info/gems/selenium-webdriver/Selenium/WebDriver/Mouse:move_to) 
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

`POST /session/:session_id/moveto`

### URL Parameters

|name|description|
|----|-----------|
|session_id|ID of the session to route the command to|

### JSON Parameters

|name|type|description|
|----|----|-----------|
| element | string | The ID of the element to move to. If not specified, relative to mouse position |
| xoffset | number | X offset to move to, relative to the top-left corner of the element. If not specified, the mouse will move to the middle of the element |
| yoffset | number | Y offset to move to, relative to the top-left corner of the element. If not specified, the mouse will move to the middle of the element |

### Response

null

## See Also

* [W3C Specification](https://drafts.csswg.org/cssom-view/#dom-window-moveto)
* [JSONWP Specification](https://github.com/SeleniumHQ/selenium/wiki/JsonWireProtocol#post-sessionsessionidmoveto)
