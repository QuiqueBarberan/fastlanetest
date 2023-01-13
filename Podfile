# Uncomment the next line to define a global platform for your project
platform :ios, '14.0'

# ignore all warnings from all pods
inhibit_all_warnings!
use_frameworks!

def shared_pods
  use_modular_headers!

  pod 'SwiftLint', '0.47.1'
  pod 'Alamofire', '4.8.1'
  pod 'AdvancedPageControl', '0.1.5'
  # add the Firebase pod for Google Analytics
  pod 'Firebase', '7.5.0'
  pod 'Firebase/Analytics', '7.5.0'
  # add pods for any other desired Firebase products
  # https://firebase.google.com/docs/ios/setup#available-pods
  pod 'Firebase/Performance', '7.5.0'
  pod 'Firebase/Crashlytics', '7.5.0'
  pod 'Firebase/Database', '7.5.0'
  pod 'Firebase/Auth', '7.5.0'

  pod 'MaterialComponents/TextFields', '121.0.0'
  pod 'TPKeyboardAvoidingSwift' , '3.2'
  pod 'Koloda', '5.0.1'
  # pod 'Didomi-xcode11.3', '1.16.5'
  # pod 'Didomi-XCFramework', '1.48.2'
  pod 'Didomi-XCFramework', '1.61.0'
  pod 'lottie-ios', '3.1.1'
  pod 'SideMenu', '6.5.0'
  pod "CenteredCollectionView", '2.2.2'
  pod 'PanModal', '1.2.7'
  pod 'Kingfisher', '4.10.1'
  pod 'KeychainSwift', '19.0.0'
  pod 'SwiftyXMLParser', :git => 'https://github.com/yahoojapan/SwiftyXMLParser.git', :tag => '5.2.0'
  pod 'MarqueeLabel', '4.0.2'
  pod "SkeletonView", '1.11.0'
  pod 'YouTubePlayer', '0.7.2'
  pod 'youtube-ios-player-helper', '1.0.3'

  # Google Sign in
  pod 'GoogleSignIn', '5.0.2'

  # Facebook Sign in
  pod 'FacebookCore', '0.9.0'
  pod 'FacebookLogin', '0.9.0'
  pod 'FacebookShare', '0.9.0'

  pod 'GoogleAds-IMA-iOS-SDK', '3.13.0'
  pod 'Google-Mobile-Ads-SDK', '7.69.0'
  pod 'Airship', '16.9.2'

  pod 'TJActivityViewController', '0.0.1'
  pod 'TrueTime', '5.0.3'
  
  #Analytics
  pod 'S2S-SDK', '1.13.0'
  
  # Youbora
  # pod 'YouboraLib', '6.6.4'
  # pod 'YouboraLib', '6.5.47'
  # pod 'YouboraConfigUtils', '1.1.7'
  # pod "YouboraAVPlayerAdapter", '6.6.1'
end

target 'cadenaSer' do
  workspace 'cadenaSer'
  project 'cadenaSer'
  
  shared_pods
end


# target 'cadenaSerMock' do
#   workspace 'cadenaSer'
#   project 'cadenaSer'
  
#   shared_pods
# end

# target 'radioCaracol' do
#   workspace 'cadenaSer'
#   project 'cadenaSer'
  
#   shared_pods
# end


# target 'radioCaracolMock' do
#   workspace 'cadenaSer'
#   project 'cadenaSer'
  
#   shared_pods
# end

# target 'cadenaSerMockExtension' do
#   workspace 'cadenaSer'
  
#   # Airship
#   pod 'AirshipExtensions/NotificationService'
  
# end

# target 'ServiceExtension' do
#   workspace 'cadenaSer'
  
#   # Airship
#   pod 'AirshipExtensions/NotificationService'
  
# end

# target 'cadenaSerTests' do
#   workspace 'cadenaSer'
#   project 'cadenaSer'
    
# end

# post_install do |installer|
#   installer.pods_project.targets.each do |target|
#     target.build_configurations.each do |config|
#       config.build_settings["DEVELOPMENT_TEAM"] = "N2C87TQ9VP"
#     end
#   end
# end
