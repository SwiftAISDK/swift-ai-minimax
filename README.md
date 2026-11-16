<!-- Generated distribution; edit the canonical repository. -->
# swift-ai-minimax 1.4.0

Independent Swift-native port of Vercel AI SDK. Source and upstream dispositions are in PROVENANCE.json and Porting/.

## Distribution manifest

Add this package to your SwiftPM dependencies:

```swift
.package(url: "https://github.com/SwiftAISDK/swift-ai-minimax.git", from: "1.4.0")
```

Products: `SwiftAIMiniMax`.
Contribute and report issues in the canonical SwiftAISDK repository.

## Authored usage guide

# MiniMax for Swift

`SwiftAIMiniMax` adds MiniMax to [SwiftAISDK](https://github.com/SwiftAISDK/SwiftAISDK), an independent Swift port of the Vercel AI SDK. It ports `@ai-sdk/minimax` and supports text generation, video generation and image generation.

Provider guide with models, options, streaming and errors:

- [MiniMax](https://swiftaisdk.github.io/SwiftAISDK/providers/minimax/)

## Usage

Add the `SwiftAI` product from `swift-ai-core` and the `SwiftAIMiniMax` product from this package to your target, then create the provider:

```swift
import SwiftAI
import SwiftAIMiniMax

let provider = try AIProviders.miniMax(configuration: MiniMaxProviderSettings())
```

By default the provider reads `MINIMAX_API_KEY` from the environment; values set in `MiniMaxProviderSettings` take precedence.

To use every provider through one dependency, add the complete [SwiftAISDK](https://github.com/SwiftAISDK/SwiftAISDK) package instead; see [Install](https://swiftaisdk.github.io/SwiftAISDK/getting-started/install/).

## Contributing

This package is exported from `Packages/swift-ai-minimax` in the canonical [SwiftAISDK](https://github.com/SwiftAISDK/SwiftAISDK) repository. Open issues and pull requests there.
