---
title: v0.3.0 of touch_targets
url: https://pub.dev/packages/touch_targets
date: '2026-05-26'
author: ''
feed_url: https://pub.dev/feed.atom
---
Create overflowing touch targets to make accessible design-sized components.

Changelog excerpt:
-  Performed element renames:

   - `TouchClient.childSize`→ `TouchClient.innerSize`;
  - `TouchClient.hitTestFrom()`→ `TouchClient.hitTestInnerFrom()`;
  - `TouchTargetBehavior`→ `TouchTargetFit`(`behavior`→ `fit`).
 
-  Refactored `RenderTouchTargetMixin`into three mixins: base `TouchClientRenderObjectBaseMixin`, optional `TouchClientRenderObjectOptionalMixin`and required `TouchClientRenderObjectRequiredMixin`.


-  Added documentation comments to some elements.


-  Minor internal changes.
