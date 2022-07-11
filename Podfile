# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'WoWonderiOS' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  inhibit_all_warnings!
  
  # Pods for News_Feed
  
  pod 'Alamofire','~> 4.2'
  pod 'AlamofireImage'
  pod 'Kingfisher'
  pod 'ZKProgressHUD'
  pod 'SDWebImage'
  pod 'MobilePlayer'
  pod 'Player'
  pod 'FBSDKCoreKit'
#  '~> 4.31.1'
  pod 'FBSDKLoginKit'
#  '~> 4.31.1'
  pod 'IQKeyboardManager' #iOS8 and later
  pod 'GoogleSignIn', '5.0.0'
  pod 'GoogleMaps'
  pod 'GooglePlaces'
  pod 'YouTubePlayer'
  pod 'ActiveLabel'
  pod 'PaginatedTableView'
  pod 'Cosmos', '~> 20.0'
  pod 'Toast-Swift'
  pod 'CropViewController'
  pod 'XLPagerTabStrip'

#  pod 'WWCalendarTimeSelector'
  pod 'ImageSlideshow'
  pod 'ImageSlideshow/Kingfisher'
  pod 'NVActivityIndicatorView'
#  pod 'Reactions'
  pod 'TTRangeSlider'
    pod 'MMPlayerView'
    pod 'ActionSheetPicker-3.0'
    pod 'FontAwesome.swift'
    pod 'FittedSheets'
    pod 'VersaPlayer'
#    pod 'PayPal-iOS-SDK'
    pod "LinearProgressBar"
    pod 'Google-Mobile-Ads-SDK'
    pod 'Braintree'
    pod 'BraintreeDropIn'
#    pod 'Giphy'

      pod 'SwiftyBeaver'
      pod 'ReachabilitySwift'
      pod 'AgoraRtcEngine_iOS'
      pod 'TwilioVoice'
      pod 'TwilioVideo', '~> 2.3'
      pod 'DropDown'
      

#    pod 'Giphy'
pod 'AsyncSwift'
pod 'SwiftEventBus', :tag => '3.0.0', :git => 'https://github.com/cesarferreira/SwiftEventBus.git'
pod 'R.swift'
    
  target 'WoWonderiOSTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'WoWonderiOSUITests' do
    # Pods for testing
  end

end

target 'OneSignalNotificationServiceExtension' do
  use_frameworks!
  #pod 'OneSignal', '>= 2.6.2', '< 3.0'
  pod 'OneSignal', '>= 2.11.2', '< 3.0'
end
post_install do |installer|
  installer.pods_project.build_configurations.each do |config|
    config.build_settings.delete('CODE_SIGNING_ALLOWED')
    config.build_settings.delete('CODE_SIGNING_REQUIRED')
  end
end
