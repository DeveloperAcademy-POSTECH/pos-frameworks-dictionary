# MusicKit

> [MusicKit 공식 문서](https://developer.apple.com/documentation/MusicKit/)

## 개요 및 기능
- SwiftUI를 통해 Apple Music에 있는 대부분의 기능을 사용할 수 있습니다.  
- Apple Music을 구독하고 있는 사용자의 경우 음악을 재생과 개인별 추천 음악을 가져오는 기능 등을 사용할 수 있습니다. 
- Apple Music을 구독하지 않은 사용자의 경우에도 다양한 필터를 사용해 음악 검색을 통한 정보를 가져올 수 있습니다.
- 음악 재생을 위한 플레이어는 SystemMusicPlayer와 ApplicationMusicPlayer가 제공됩니다. 음악 재생이 되는 방식과 제약의 차이가 있으니 구현하기 전에 이해하고 플레이어를 선택해야 합니다.

## 세팅
- MusicKit을 사용하기 위해서는 [Certificates, Identifiers, and Profiles](https://developer.apple.com/account/resources) 에서 프로젝트를 등록해야 합니다. 
  - 프로젝트의 Bundle Identifier를 등록하시면 되고 이 경우의 Apple Developer Program에 가입되어 있어야 합니다. 
- Apple Music을 사용하는 용도에 대해 info에서 NSAppleMusicUsageDescription에 기술해 주셔야 합니다.


## 추천 블로그 & 비디오
- [WWDC 21 MusicKit 한국어 번역](https://nyancoder.tistory.com/27)
- [MusicKit Authorization 공식문서 - 음악권한 허용](https://developer.apple.com/documentation/musickit/musicauthorization)
- [MusicKit Authorization 공식문서 - Request & Response](https://developer.apple.com/documentation/applemusicapi/handling_requests_and_responses)
- [MusicKit Authorization 공식문서 - 구독 확인](https://developer.apple.com/documentation/musickit/musicsubscription)
- [MusicKit Authorization 공식문서 - SystemMusicPlayer](https://developer.apple.com/documentation/musickit/systemmusicplayer)
- [MusicKit Authorization 공식문서 - ApplicationMusicPlayer](https://developer.apple.com/documentation/musickit/applicationmusicplayer)
- [NSAppleMusicUsageDescription 공식문서](https://developer.apple.com/documentation/bundleresources/information_property_list/nsapplemusicusagedescription)