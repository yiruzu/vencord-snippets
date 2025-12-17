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
  --panel-color: var(--background-gradient-highest, var(--background-base-low));

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
| Class | _0d6162a4e6a4b802-mask & _0d6162a4e6a4b802-wrapper | Quest Section
| Class | e0cf275d59896c00-listeningAlong | Spotify Listen Together
| Class | _5dec784a68542d60-panel | Stream Information
| ID | vc-spotify-player | Spotify Player
| Class | e131a99484292a19-wrapper & e131a99484292a19-container | Voice Call Controls
| Class | _37e49614b9f110a9-container | User/Profile Section

## `⭐`丨Credits

- [star_yolk](https://en.pronouns.page/@eggyolk_) - User Area and Activity Panels redesign
- [fripe](https://github.com/Fripe070) - Fancy spotify controls
