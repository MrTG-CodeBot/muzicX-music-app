# Changelog

All notable changes to MuzicX will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [4.2.8] - 2024-12-23

### Added
- Active Downloads screen with real-time progress tracking
- Download pause/resume functionality
- Clear completed downloads button
- Playlist batch download support
- Download progress notifications
- Offline mode detection and navigation
- Home screen widget for Android (with playback controls)
- Spotify playlist import functionality
- YouTube Music playlist import
- Cloud sync for favorites and playlists via Firestore
- Cross-device synchronization
- Firebase authentication (Google & Email)
- Force update system
- Visitor ID tracking
- Multi-language support
- Dynamic color theming
- Sleep timer functionality
- Audio equalizer
- Lyrics display support
- Share song functionality
- Queue reordering with drag-and-drop

### Fixed
- Widget data display issues on Android home screen
- RenderFlex overflow in album UI
- Download dialog state management
- MediaPlayer service method calls
- Player screen rendering with null artwork
- Duplicate download prevention
- JVM target compatibility across Gradle projects
- Search functionality in saved screens
- Queue management with proper GlobalKey handling
- Bottom player artwork display

### Changed
- Refactored download screen to read from file system
- Improved download manager with better state handling
- Enhanced notification system for downloads
- Updated UI with glassmorphic effects
- Optimized playlist thumbnail loading
- Improved performance for large libraries

### Removed
- Deprecated search functionality from certain screens
- Legacy home widget implementation
- Unused import dialogs

## [4.0.0] - 2024-11-01

### Added
- Initial stable release
- YouTube Music integration
- Basic audio player
- Download functionality
- Local playlist management
- Search functionality

### Changed
- Complete UI overhaul with modern design
- Migration to Flutter 3.4.1+

## [3.0.0] - 2024-09-15

### Added
- Beta release with core features
- Audio streaming
- Basic download support
- Playlist creation

---

**Legend:**
- `Added` - New features
- `Changed` - Changes in existing functionality
- `Deprecated` - Soon-to-be removed features
- `Removed` - Removed features
- `Fixed` - Bug fixes
- `Security` - Security improvements
