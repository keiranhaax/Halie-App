# Changelog

All notable milestones for Halie are documented here.

## [0.5.0] — 2025-11-19
### Added
- Interactive calendar integration with historical health data browsing
- Navigation improvements across all tabs
- Background task scheduling with SwiftUI BackgroundTask API

### Improved
- Major codebase cleanup and HealthKit implementation refactoring
- Calendar header using correct iOS 26 Liquid Glass API
- Build stability and error handling

## [0.4.0] — 2025-09-15
### Added
- CoreML on-device machine learning models: RecoveryPredictor, AnomalyDetector, TrendAnalyzer, SleepOptimizer
- Metal 4 GPU acceleration for CoreML inference
- ML Configuration UI for model management
- Liquid glass morphing transitions for health metric cards
- Recovery Score algorithm (35% HRV, 25% Sleep, 20% Resting HR, 10% Respiratory, 5% Stress, 5% Context)
- Quick actions system and monitoring infrastructure

### Improved
- CoreML async model loading to prevent main thread blocking
- Foundation Models service with cache fixes, token limits, and session management
- Swift 6 concurrency compliance and memory management
- Eliminated main thread bottlenecks in HealthKit operations
- AI Chat stability — fixed message persistence and keyboard lag

## [0.3.0] — 2025-09-02
### Added
- Full HealthKit metrics integration — 40+ health data types
- iOS 26 Liquid Glass UI overhaul with zoom transitions
- Blood pressure, respiratory rate, SpO₂, and advanced cardiac metrics
- App icons with light and dark mode support
- Complete migration from OpenAI GPT-5 to Apple Foundation Models (100% on-device privacy)

### Improved
- Dashboard redesign with in-place card expansion
- 425+ SwiftLint violations fixed (50% reduction)
- iOS 26-only cleanup — removed all legacy version references
- ProMotion optimization for smooth tap gestures
- Swift 6 concurrency and compilation error fixes across 9 files

## [0.2.0] — 2025-08-27
### Added
- OpenAI GPT-5 AI coach integration
- Activity Rings with morphing transitions from tab bar
- Lean architecture refactoring (Phases 1–5)

### Changed
- Renamed from Halie Heart to Halie
- Streamlined app navigation and enhanced performance
- Fixed HealthKit authorization timing in onboarding flow

### Improved
- Major project cleanup and reorganization
- Swift concurrency and compilation error fixes in ViewModels
- Dashboard metric card scrolling fix

## [0.1.0] — 2025-07-28
### Added
- Initial HealthKit integration with health dashboard
- AI Coach with modular service architecture
- iOS 26 tab bar with Chat and Insights views
- Health Metrics tab with activity tracking
- iOS 26 optimization infrastructure with feature flags
- Sleep and Export modal sheets
- Pull-to-refresh and navigation fixes

### Foundation
- SwiftUI app architecture
- HealthKit authorization and data fetching
- Privacy-first design — all data stays on-device
