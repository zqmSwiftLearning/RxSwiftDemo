# RxSwiftDemo
Xcode 7.3  Alamofire 3.3

####依赖库
#####CocoaPods
Podfile文件内容如下
```
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target 'MyApp' do
    pod 'SwiftyJSON', :git => 'https://github.com/SwiftyJSON/SwiftyJSON.git'
    pod 'Alamofire', '~> 3.3'
end
```
终端
```
pod install
```
