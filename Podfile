# Uncomment the next line to define a global platform for your project
platform :ios, '13.0'

target 'ABEO' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for ABEO
  pod 'LGButton'
  pod 'DropDown'
  pod 'Firebase/Core'
  pod 'Firebase/Messaging'
  pod 'MaterialComponents/TextFields'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '12.0'
    end
  end
end
