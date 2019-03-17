# YouTubeHelper
Play videos from youtube url in AVPlayer iOS. Xcode 10.1 swift 4.2

**Usage**

1. This helper class works with `pod 'XCDYouTubeKit', '~> 2.7'`. Install this pod file and then use this helper class.

            let playerClass = YoutubePlayerHelper()
            playerClass.playVideo(url: "youtube url string here", vc: self)
