# User & Activity Panels Redesign

| Before | After |
| -------- | -------- |
| <img valign='middle' alt='UserActivityRedesign' src='../../docs/media/UserActivityRedesign_before.png'/> | <img valign='middle' alt='UserActivityRedesign' src='../../docs/media/UserActivityRedesign_after.png'/> |

## `⚙️`丨Configuration

After importing the snippet, copy and paste the code below into your QuickCSS file to configure it.

```css
:root {
  --bg-color: var(--background-gradient-high, var(--background-base-lowest));

  --panel-gap: 8px;
  --panel-radius: 10px;
  --panel-color: var(--bg-overlay-floating, var(--background-base-low, var(--background-secondary-alt)));

  --spotify-image-blur: 4px;
  --spotify-image-opacity: 0.45;
  --spotify-image-hover-opacity: 0.7;

  --order-quests: 0;
  --order-listening: 1;
  --order-stream: 2;
  --order-spotify-player: 3;
  --order-voice: 4;
  --order-profile: 5;
}
```

## `🧩`丨Classes & IDs

| Type | Name | Purpose |
| -------- | -------- | ------- |
| Class | mask__0d616 & mask__0d616 | Quest Section
| Class | listeningAlong_e0cf27 | Spotify Listen Together
| Class | panel__5dec7 | Stream Information
| ID | vc-spotify-player | Spotify Player
| Class | wrapper_e131a9 & container_e131a9 | Voice Call Controls
| Class | container__37e49 | User/Profile Section

## `⭐`丨Credits

- [star_yolk](https://en.pronouns.page/@eggyolk_) - User Area and Activity Panels redesign
- [fripe](https://github.com/Fripe070) - Fancy spotify controls
