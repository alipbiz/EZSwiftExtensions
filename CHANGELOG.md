# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased] 

### Fixed bugs

1. **Array:**
  - `shuffle()` crashing if array contains one or zero elements by *piv199*

2. **EZSwiftExtensions:**
  - Setting image on undefined thread for `imageWithURL` related methods in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/220) by *piv199*
  - `runThisEvery()` now returns `Timer` instead of `CFLoopTimer` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/228) by *lfarah*

### Added extensions

1. **Array:**
  - `shuffled() -> Array` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/212) by *piv199* 
  - `unique() -> Array` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/254) by *Khalian*
  - `get(at range:ClosedRange<Int>) -> Array` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/260) by *Dendim0n*

2. **Date:**
  - `isToday: Bool` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/260)  by *Khalian*
  - `isYesterday: Bool` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/321)  by *Khalian*
  - `isTomorrow: Bool` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/321)  by *Khalian*
  - `year: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/313) by *Khalian*
  - `month: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/313) by *Khalian*
  - `weekday: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/313) by *Khalian*
  - `monthAsString: String` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/313) by *Khalian*
  - `day: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/313) by *Khalian*
  - `hour: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/314) by *Khalian*
  - `minute: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/314) by *Khalian*
  - `second: Int` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/314) by *Khalian*
  - `isThisWeek: Bool` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/321) by *Khalian*
  - `isThisMonth: Bool` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/321) by *Khalian*

3. **CGFloat:**
  - `radiansToDegrees() -> CGFloat` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/258) by *Khalian*
  - `toDegreesInPlace()` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/258) by *Khalian*
  - `static radiansToDegrees(_ angleInDegrees : CGFloat) -> CGFloat` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/258) by *Khalian*
  - `static random() -> CGFloat` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/262) by *Khalian*
  - `static random(within: Range<CGFloat>)` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/262) by *Khalian*
  - `static random(within: ClosedRange<CGFloat>)` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/262) by *Khalian*
  - `static shortestAngleInRadians(from first: CGFloat, to second: CGFloat) -> CGFloat` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/272) by *Khalian*

4. **CGPoint:**
  - `operator +(this: CGPoint, that: CGPoint) -> CGPoint` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/262) by *Khalian*
  - `operator -` by *Khalian*
  - `operator *` by *Khalian*
  - `static distance(from: CGPoint, to: CGPoint) -> CGPoint` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/278) by *Khalian*
  - `normalized()` by *Khalian*
  - `angle: CGFloat` in [[PR]](https://github.com/goktugyil/EZSwiftExtensions/pull/287) by *Khalian*
  - `dotProduct(this: CGPoint, that: CGPoint) -> CGPoint` in [[PR](https://github.com/goktugyil/EZSwiftExtensions/pull/290)] by *Khalian*
  - `linearInterpolation(startPoint: CGPoint, endPoint: CGPoint, interpolationParam: CGFloat)` by *Khalian*

5. **FloatingPoint:**
  - `round(toPlaces places: Int)` by *piv199*
  - `rounded(toPlaces places: Int)` by *piv199*
  - `ceil(toPlaces places: Int)` by *piv199*
  - `ceiled(toPlaces places: Int)` by *piv199*

6. **String:**
  - `urlEncoded()` by *Khalian*
  - `urlEncode()` by *Khalian*
  - `subscript(integerClosedRange: ClosedRange<Int>)` by *lfarah*

7. **UIView**
  - `fadeIn(_ duration: TimeInterval?, delay: TimeInterval?, completion: ((Bool) -> Void)?)` by *vilapuigvila*
  - `fadeOut(_ duration: TimeInterval?, delay: TimeInterval?, completion: ((Bool) -> Void)?)` by *vilapuigvila*
  - `fadeTo(_ value: CGFloat, duration: TimeInterval?, delay: TimeInterval?, completion: ((Bool) -> Void)?)` by *vilapuigvila*

8. **UIViewController:**
  - `hideKeyboardWhenTappedAroundAndCancelsTouchesInView()` by *furuyan*

9. **Dictionary:**
  - `static constructFromJSON(json: String) -> Dictionary` by *Khalian*
  - `formatJSON() -> String?` by *Khalian*

10. **Character:**
  - `lowercased: Character` by *Khalian*
  - `uppercased: Character` by *Khalian*

### Modified extensions

1. **Global:**
  - Updated `M_PI` to `.pi` by *piv199*

2. **Array:**
  - `reverseIndex(_ index: Int)` now returns `Int?` instead of `Int` by *piv199*

### Deprecated/Renamed classes

1. **UIColoredView**

### Deprecated/Renamed extensions

**Array:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
`containsInstanceOf<T>(_ element: T)`  | `containsType<T>(of element: T)` | piv199 
`get(_ index: Int)`  | `get(at index: Int)` | piv199 
`removeObjects(_ objects: Element...)`  | `removeAll(_ elements: Element...)` | piv199 
`removeFirstObject(_ object: Element)`  | `removeFirst(_ element: Element)` | piv199 
`testIfAllIs(_ condition: Bool)`  | `testAll(is condition: Bool)` | piv199 

**CGFloat:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
 `toRadians()` | `degreesToRadians()` | Khalian 

**Double:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
 `ceilByPlaces(_ places: Int)` | `ceil(toPlaces places: Int)` | piv199 
 `getCeiledByPlaces(_ places: Int)` | `ceiled(toPlaces places: Int)` | piv199 
 `getRoundedByPlaces(_ places: Int)` | `rounded(toPlaces places: Int)` | piv199 
 `roundByPlaces(_ places: Int)` | `round(toPlaces places: Int)` | piv199 

**UIColor:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
 `randomColor(_ randomAlpha: Bool)` | `random(randomAlpha: Bool)` | lfarah 

**UIFont:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
`PrintFontFamily(_ font: FontName)` | *deprecated* | lfarah

**UIViewController:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
 `hideKeyboardWhenTappedAround(handler: ((UITapGestureRecognizer) -> Void)?)` | `hideKeyboardWhenTappedAround()` | furuyan 

**NSDictionary:**

Method/property name  | Renamed to | Author 
------------- | ------------- | ------------- 
`init?(json: String)` | *deprecated* | lfarah
`formatJSON() -> String?` | *deprecated* | lfarah 

**UIImageView:**

Method/property name  | Renamed to | Author 
------------- | ------------- | -------------
`imageWithUrl(url: String, placeholderNamed: String)` | `image(url: String, placeholderNamed: String)` | lfarah
`imageWithUrl(url: String, placeholder: UIImage)` | `image(url: String, placeholder: UIImage)` | lfarah
`imageWithUrl(url: String)` | `image(url: String)` | lfarah


[All changes](https://github.com/goktugyil/EZSwiftExtensions/compare/1.7...master)

