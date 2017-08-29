use_frameworks!

workspace 'PinLayout.xcworkspace'

target 'PinLayoutTests' do
  platform :ios
  project 'PinLayout.xcodeproj'

  pod 'Quick'
  pod 'Nimble', :inhibit_warnings => true
end

target 'PinLayoutTestsOSX' do
  platform :osx
  project 'PinLayout.xcodeproj'

  pod 'Quick'
  pod 'Nimble', :inhibit_warnings => true
end

target 'PinLayoutSample' do
  platform :ios
  project 'Example/PinLayoutSample.xcodeproj'

  # Debug only
  pod 'Reveal-SDK', :configurations => ['Debug']
  pod 'SwiftLint'
end
