# Gecko

**Discover. Explore. Watch.**

Gecko is a desktop application designed to bring your movies and TV shows together in one place. Discover new content, explore detailed information, organize your personal library and play videos through third-party sources.

## Overview

Gecko provides a unified interface for discovering and organizing movies and TV shows, with integrated video playback and a range of features designed to enhance the viewing experience.

The application combines metadata from TMDB, a customizable personal library, advanced playback controls and integrations with external services.

**Gecko is not a streaming service and does not provide audiovisual content.** It does not host, distribute or operate any movie, TV show, television channel or video stream. Metadata is provided by TMDB, while video playback relies on external sources.

> **Important:** Users must ensure they have the necessary rights to access, watch or download any content. Please read the [Legal Disclaimer](#legal-disclaimer) before using the application.

## Features

### Discovery & Catalog

- Browse movies and TV shows through dedicated catalogs.
- Discover trending and popular content.
- Search for movies and TV shows.
- Explore detailed information, including descriptions, ratings, posters and other metadata.
- Access content information powered by TMDB.

### Video Player

- Desktop video playback powered by libmpv.
- Play, pause, seek and control playback speed.
- Select available audio tracks.
- Manage subtitles and playback preferences.
- Support for external subtitle files.

### Personal Library

- Create and manage multiple user profiles.
- Organize content into custom watchlists.
- Keep track of viewing history.
- Resume playback from where you left off.
- Store personal settings and preferences locally.

### Subtitles

- Support for embedded subtitle tracks.
- Load external subtitle files.
- Search for subtitles online when a compatible service is configured.
- Manage subtitle language and display preferences.

### Live TV

- Access television channels provided by third-party sources.
- Select your preferred language before browsing live channels.
- Browse available channels and start playback.
- Enjoy an integrated live television experience.

### Watch Party

- Synchronize video playback between multiple devices.
- Watch content together remotely.
- Keep playback sessions synchronized.

### Remote Control & Pairing

- Pair compatible devices.
- Control playback on a connected television or device.
- Use another device as a remote control.

### Customization

- Choose your preferred interface language.
- Customize the application accent color.
- Configure playback and subtitle settings.
- Organize and personalize your application experience.

*Feature availability may vary depending on the platform, configuration and third-party services.*

## Platforms

Gecko currently targets desktop environments:

| Platform | Support |
|---|---|
| Windows | Supported |
| macOS | Unsupported |
| Linux | Unsupported |

The interface is designed to adapt to desktop windows.

### Video Playback

Desktop video playback is powered by **libmpv**.

Release packages include the required resources.

## Getting Started

### Requirements

Before building Gecko locally, make sure you have:

- JDK 17.
- An internet connection.
- A TMDB API key.
- The required native libmpv dependencies for your platform.

### Initial Configuration

On the first launch, configure your API key through the installation screen or navigate to:

**Settings → Keys & Access**

| Service | Requirement | Purpose |
|---|---|---|
| TMDB | Required | Movie and TV show metadata |
| TheIntroDB | Optional | Intro and credits-related features |

Once configured, Gecko can retrieve catalog information and use the services required by the enabled features.

## Data & Privacy

Gecko is designed to keep personal application data locally.

- Application settings, profiles, watchlists and playback progress are stored locally.
- Images and some catalog information may be cached on the device.
- Gecko communicates with TMDB and other third-party services required by enabled features.
- Downloads, when supported, are stored locally at the user's request.
- Gecko does not operate a server hosting audiovisual content.

Third-party services have their own terms of service and privacy policies. Their availability and behavior are outside Gecko's control.

## Versioning & Releases

**Current development version: `v0.0.9-beta.1`**

Gecko is currently in beta development. Features, interfaces and internal components may change between releases.

- [View all releases](https://github.com/Guspidor/Gecko/releases)
- [View the latest release](https://github.com/Guspidor/Gecko/releases/latest)
- [View the source code](https://github.com/Guspidor/Gecko)

## Legal Disclaimer

Gecko is a **content discovery and playback client**. It does not provide access to a hosted content catalog and does not host or distribute audiovisual media.

### Third-Party Content

All video streams and external content originate from third-party services selected or configured by the user.

Gecko is not affiliated with these services, TMDB, Discord or the copyright holders of any audiovisual works.

### User Responsibility

Users are solely responsible for their use of the application and the content they access.

You must comply with applicable copyright laws, neighboring rights, third-party terms of service and the legislation in your jurisdiction.

**Only use Gecko with content you are legally authorized to access, watch, copy or retain.**

Any use intended to circumvent technical protection measures, paywalls or access restrictions is prohibited.

### No Warranty

Gecko is provided "as is", without express or implied warranties.

No guarantees are made regarding the legality, availability, quality, security or continued operation of third-party content and services.

To the extent permitted by applicable law, the authors and contributors shall not be held liable for damages resulting from the use of the application, third-party content or unlawful use.

For copyright-related questions or concerns about third-party content, contact the relevant service provider or rights holder. Issues concerning the application itself can be reported through the repository's issue tracker.

### TMDB Attribution

This product uses the TMDB API but is not endorsed or certified by TMDB.

This README does not constitute legal advice. Anyone distributing or making the application available should seek appropriate legal advice for their jurisdiction.

## License

No `LICENSE` file is currently present at the root of this repository.

Unless otherwise specified in a separate license agreement, **all rights are reserved**. The source code is made available for inspection and may not be copied, modified or redistributed without prior written permission from the copyright holder.

---

<p align="center">
  <strong>Gecko</strong>
  <br>
  Discover. Explore. Watch.
  <br><br>
  <a href="https://github.com/Guspidor/Gecko/releases">Releases</a>
  ·
  <a href="https://github.com/Guspidor/Gecko/issues">Issues</a>
  ·
  <a href="RELEASE_NOTES.md">Release Notes</a>
</p>
