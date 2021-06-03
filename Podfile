platform :ios, '10.0'

workspace 'ACPPlacesMonitor'
project 'ACPPlacesMonitor.xcodeproj'

target 'ACPPlacesMonitor_iOS' do
  use_frameworks!
  
  pod 'ACPCore', :git => 'https://github.com/adobe/aep-sdk-compatibility-ios.git', :branch => 'main'
  pod 'AEPPlaces', :path => '/Users/stevebenedick/code/git/forks/adobe/ios/aepsdk-places-ios/'
end

target 'ACPPlacesMonitor-iOS-unit-tests' do
  use_frameworks!
  
  pod 'ACPCore', :git => 'https://github.com/adobe/aep-sdk-compatibility-ios.git', :branch => 'main'
  pod 'AEPPlaces', :path => '/Users/stevebenedick/code/git/forks/adobe/ios/aepsdk-places-ios/'
  pod 'OCMock', '3.4.3'
end
