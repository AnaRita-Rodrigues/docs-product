---
summary:
locale: en-us
guid: 22c50ae1-0e53-45c1-a60e-417311bca7ba
app_type: traditional web apps, mobile apps, reactive web apps
platform-version: o11
figma: https://www.figma.com/design/daglmSUESdKw9J3HdT87a8/O11-to-ODC-migration?node-id=2350-7652
helpids: 30527
tags: code migration, architecture review, dependency management, asset management, platform version upgrade
audience:
  - mobile developers
  - frontend developers
  - full stack developers
  - architects
outsystems-tools:
  - service studio
coverage-type:
  - unblock
  - understand
---

# Asset consuming a Resource

In ODC, Assets can't have dependencies to Resources from other Assets.

## How to solve

You must solve this pattern in O11, before proceeding with the code migration to ODC.

### Solve in O11

Depending on your scenario, solve this pattern in one of the following ways:

* If several ODC assets consume the Resource, replicate the Resource in each of the ODC consumer assets.

* If only one ODC asset consumes the Resource, review the O11 to ODC architecture mapping and consider moving the image to an app mapped to the ODC asset.

    ![Diagram showing the architecture review process before and after. Before: O11 Apps with strong dependencies to ODC Apps. After: O11 Apps consolidated within ODC Apps.](images/review-arch-consolidate-diag.png "Architecture Review Before and After")
