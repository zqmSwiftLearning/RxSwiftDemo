# RxSwiftDemo
Xcode 7.3 Swift 2.2

####依赖库
#####CocoaPods
Podfile文件内容如下(YOUR_TARGET_NAME/YOUR_TESTING_TARGET替换成你自己的TARGET/TESTING_TARGET,其中TESTING_TARGET部分可以不要)
```
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target 'YOUR_TARGET_NAME' do
    pod 'SwiftyJSON', :git => 'https://github.com/SwiftyJSON/SwiftyJSON.git'
    pod 'Alamofire', '~> 3.3'
    pod 'RxSwift',    '~> 2.0'
    pod 'RxCocoa',    '~> 2.0'
end

target 'YOUR_TESTING_TARGET' do
    pod 'RxBlocking', '~> 2.0'
    pod 'RxTests',    '~> 2.0'
end

```
终端
```
pod install
```
