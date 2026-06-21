# Changelog

All notable changes to Erect Banana will be documented here.
This project follows [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Added
- Generative Fill, Outpaint, and Harmonize (light matching) modules
- BYOK support for Google AI Studio, Google Vertex AI, and OpenRouter
- Automatic platform detection from API key format
- Multi-language UI (English, Simplified & Traditional Chinese, Japanese, Korean, Spanish, French, German)
- Feathered mask compositing for seamless result blending
- Reference image support for guided generation

### Changed
- OpenRouter added as a unified-key alternative for Gemini models
- Distribution moved to Adobe Exchange — no local license server or HWID activation required

### Known issues
- Windows only — macOS is not supported in this release
- OpenRouter image-generation model availability varies by provider; check OpenRouter's model list if a model returns no image
