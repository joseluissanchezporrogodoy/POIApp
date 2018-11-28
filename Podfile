# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'


def shared
    pod 'Alamofire', '~> 4.7'
    pod 'SDWebImage/WebP', '~> 4.2'
    pod 'RealmSwift'
end

target 'POIApp' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  
  shared
  # Pods for POIApp

  target 'POIAppTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'POIAppUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
