
# GeoEdge Google Ads Package

A fork of the official [google_mobile_ads](https://pub.dev/packages/google_mobile_ads) package, customised to integrate the GeoEdge AppHarbr SDK for iOS and Android.

This fork adds support for monitoring Google Ad Manager (GAM) Banner Ads with GeoEdge. Note that it does not implement full AppHarbr SDK functionality, focusing specifically on banner ads to maintain compatibility with our mobile apps.

## Key Features

- Integrates GeoEdge's ad quality monitoring with GAM Banner Ads.
- Supports both iOS and Android platforms.

## Usage

To use this package, follow the steps below:

1. **Initialise MobileAds with GeoEdge API Key**:  
   Provide your GeoEdge API key when initialising Google ads `MobileAds.instance.initialize(geoEdgeApiKey: "XXXXXX")`.

2. **Create a banner ad**:
   Follow the [official docs](https://developers.google.com/admob/flutter/quick-start) to create yuor banner ad. No other setup needed.

## Versioning

This fork adheres to semantic versioning, closely following the versioning of the upstream `google_mobile_ads` package. Versioning conventions are as follows:

- **Base Version**: Matches the upstream `google_mobile_ads` version.
- **Build Number**: Appended to indicate changes specific to this fork.

### Example:
If the upstream version is `1.2.3` and changes are made within this fork:
- Initial tag: `1.2.3`  
- First fork-specific update: `1.2.3+1`  
- Second fork-specific update: `1.2.3+2`, and so on.

To update this package:
1. Merge the latest changes from the official `google_mobile_ads` repository. Latest versions to be merged to `main`.
2. Test thoroughly.
3. Tag the release following the versioning scheme outlined above.

## License

[Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0)
