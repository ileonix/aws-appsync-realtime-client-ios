# Uncomment the next line to define a global platform for your project
platform :tvos, '9.0'

target 'AppSyncRealTimeClient' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for AppSyncRealTimeClient
  pod "Starscream", "~> 3.1.0"
  
  target 'AppSyncRealTimeClientTests' do
    # Pods for testing
  end

end

target "HostApp" do 
  use_frameworks!
  target "AppSyncRealTimeClientIntegrationTests" do 
    inherit! :complete
  end
end
