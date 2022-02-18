### PionFramework_aOS Demo
```
com.example.aos_framework_demo
|__adapter
|   |__CategoryIconAdapter
|   |__CustomAdapter
|   |__MainAdapter
|   |__RecommendAdapter
|
|__data
|   |__TestVO
|   |__UiModel
|
|__dialog
|   |__CustomDialog
|
|__IntroActivity
|__MainActivity
|__ExtensionActivity
|__RecyclerActivity
|__StickyActivity
|__ElandActivity
|__WebviewActivity
```



- IntroActivity : 최초 진입지점
  - MainActivity : `BusinessExtension`, `JsonExtension`, `TextExtension` 구현
  - ExtensionActivity : `ViewExtension`, `AnimationExtension` 구현
  - RecyclerActivity : `SpacingItemDecoration`, `DividerItemDecoration` 구현
  - StickyActivity : `StickyHeaderItemDecoration` 구현
  - ElandActivity : framework util 활용하여 데모 페이지 제작
    - WebviewActivity : 웹뷰
