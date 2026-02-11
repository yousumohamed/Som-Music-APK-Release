# 📝 Changelog

All notable changes to Som Music will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [4.2.4] - 2026-02-11

### ✨ Added
- **User Analytics Dashboard**: Detailed insights for admins including top songs, listening time, and user activity.
- **Optimized ARM64 Build**: Dedicated lightweight APK (~26MB) for modern devices.

### 🔧 Improved
- **User List UI**: Enhanced visual design for user analytics lists in the Admin Panel.
- **Performance**: Faster load times and smoother navigation.

### 🐛 Fixed
- **Event Tracking**: Resolved issues with `user_events` recording and "Recently Played" history.
- **Stability**: General bug fixes and stability improvements.

## [4.1.0] - 2026-02-05

### ✨ Added
- YouTube integration for streaming music directly from YouTube
- Smart playback with optimized YouTube streaming
- Automatic stream optimization for faster loading times
- YouTube thumbnail extraction for cover images
- Background audio support for Android/iOS

### 🔧 Improved
- Enhanced audio quality with automatic bitrate selection
- Improved search functionality with real-time results
- Better offline download management
- Optimized app performance and loading times

### 🐛 Fixed
- Various bug fixes and stability improvements
- Improved error handling for network issues

---

## [4.0.0] - 2026-01-15

### 🎉 Initial Major Release

#### ✨ Core Features
- **Dual Audio Sources**: Stream from uploaded MP3 files or YouTube links
- **Offline Downloads**: Download songs for offline listening
- **Background Audio**: Continue listening while using other apps
- **Play Count Tracking**: Real-time analytics for trending songs

#### 🎨 User Experience
- Spotify-style UI with modern dark theme
- Artist onboarding with favorite artist selection
- Real-time search for songs and artists
- Search history tracking
- Trending songs based on play counts
- New releases section

#### 👤 User Management
- Email/Password authentication
- Google Sign-In integration
- Custom avatars and username customization
- Favorite artists tracking

#### 🔔 Notifications
- In-app announcements for new releases
- Firebase Cloud Messaging support
- Dedicated notification center

#### 📊 Admin Dashboard (Next.js)
- Song management (upload MP3 or YouTube URLs)
- Artist & album management
- Analytics dashboard with play counts
- Announcement system with markdown support

#### 🎧 Social Features
- Follow/unfollow artists
- Like songs
- Create and manage playlists
- Share songs with friends

---

## Version Types Explained

### 📦 Build Variants

- **Universal APK** (`Som-Music-4.1.0.apk`)
  - Works on all Android devices
  - Larger file size (~63 MB)
  - Recommended for maximum compatibility

- **ARM64 APK** (`Som-Music-v4.0.0-arm64.apk`)
  - Optimized for 64-bit ARM processors
  - Smaller file size (~24 MB)
  - Faster performance on compatible devices
  - Recommended for modern Android devices (2019+)

### 🔢 Version Numbering

We follow **Semantic Versioning** (MAJOR.MINOR.PATCH):

- **MAJOR** version (X.0.0) - Incompatible API changes, major redesigns
- **MINOR** version (0.X.0) - New features, backwards-compatible
- **PATCH** version (0.0.X) - Bug fixes and minor improvements

---

## Upcoming Releases

### [4.1.1] - Planned
- 🐛 Fix YouTube playback issues
- 🔧 Performance improvements
- 🐛 Bug fixes for offline mode

### [4.2.0] - Planned
- ✨ Playlist sharing feature
- ✨ Enhanced social features
- ✨ Improved recommendation algorithm

### [5.0.0] - Future
- 🎨 Complete UI redesign
- ✨ New premium features
- 🔄 Breaking changes and modernization

---

## Download Links

For download links and installation instructions, see the [main README](README.md#-download-apk).
