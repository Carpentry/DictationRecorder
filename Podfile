# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
use_frameworks!

def thirdParty
	pod 'Masonry'
	pod 'MJRefresh'
	pod 'CocoaLumberjack'
	pod 'SDWebImage'
	pod 'AFNetworking'
	pod 'lottie-ios'
	pod 'FMDB/FTS'
end

target 'DictationRecorder' do
	thirdParty

  target 'DictationRecorderTests' do
    inherit! :search_paths
  end

  target 'DictationRecorderUITests' do
  end

end
