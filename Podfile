# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'Themoviedb' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Themoviedb



  pod 'Alamofire'
  pod 'Kingfisher'
  pod 'RealmSwift'
  pod 'Localize-Swift', '~> 3.2'
  
  


  post_install do |installer|
    installer.pods_project.targets.each do |target|
    installer.pods_project.build_configurations.each do |config|
      config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
      config.build_settings["ONLY_ACTIVE_ARCH"] = "YES"
    end
  end
  end


end





