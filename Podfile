# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

require 'cocoapods'
# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'
source 'http://localhost:8081/repository/cocoapods-proxy/'


target 'SCA-Demo' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for SCA-Demo
  pod 'Alamofire'
  pod 'libpng'
  pod 'lottie-ios'
  pod 'boost', '~> 1.51.0'
  pod 'Protobuf', '~> 3.21.12'
#  pod 'nanopb', '~> 0.2.4'

  target 'SCA-DemoTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'SCA-DemoUITests' do
    # Pods for testing
  end

end
