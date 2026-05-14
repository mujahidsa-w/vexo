# Vexo — Mobile App Design Plan

## Brand Identity
- **Name:** Vexo
- **Tagline:** "See Beyond"
- **Personality:** Dark, futuristic, premium, cinematic
- **Logo:** Hexagonal camera-aperture icon with violet-to-cyan gradient

## Color Palette (Dark-First)
| Token | Dark Value | Light Value | Usage |
|-------|-----------|-------------|-------|
| `background` | `#0A0A0F` | `#F5F5FA` | Screen backgrounds |
| `surface` | `#13131A` | `#FFFFFF` | Cards, sheets |
| `surface2` | `#1C1C28` | `#F0F0F8` | Elevated surfaces |
| `foreground` | `#F0F0FF` | `#0A0A1A` | Primary text |
| `muted` | `#7878A0` | `#6060A0` | Secondary text |
| `primary` | `#7C3AED` | `#6D28D9` | Violet accent (brand) |
| `secondary` | `#00D4FF` | `#0099CC` | Cyan accent |
| `border` | `#2A2A3A` | `#E0E0F0` | Borders/dividers |
| `gradient1` | `#7C3AED` | — | Gradient start |
| `gradient2` | `#00D4FF` | — | Gradient end |

## Screen List
1. **Home Feed** — Vertical scrollable feed of posts with stories row at top
2. **Explore** — Grid of trending posts + search bar + category filters
3. **New Post** — Image/video picker with caption, tags, location
4. **Notifications** — Activity feed (likes, comments, follows)
5. **Profile** — User profile with grid of posts, stats, bio

## Primary Content & Functionality

### Home Feed
- Stories row (horizontal scroll, circular avatars with gradient ring)
- Post cards: full-width image/video, user avatar, username, caption, action bar (like, comment, share, save)
- Gradient like button animation
- Double-tap to like with heart burst animation

### Explore
- Search bar with frosted glass effect
- Category chips (All, Photos, Videos, Art, Travel, Food)
- Masonry/staggered grid of posts
- Trending section with rank badges

### New Post
- Gallery picker with multi-select
- Caption input with hashtag/mention detection
- Location tag
- Post button with gradient

### Notifications
- Grouped by type (likes, comments, follows, mentions)
- Avatar + action description + time
- Unread indicator dot

### Profile
- Cover gradient header
- Circular avatar with gradient ring
- Stats row (Posts, Followers, Following)
- Bio text + website link
- 3-column post grid
- Edit Profile button

## Key User Flows
1. **Browse Feed:** Open app → Home Feed → Scroll posts → Double-tap to like → Tap comment icon → View comments
2. **Explore Content:** Tap Explore tab → Search or browse categories → Tap post → View full post
3. **Create Post:** Tap + tab → Select image → Add caption → Tap Post
4. **View Profile:** Tap avatar → Profile screen → Tap post → View full post

## Typography
- **Headers:** SF Pro Display Bold / System Bold
- **Body:** SF Pro Text / System Regular
- **Captions:** SF Pro Text Light / System Light
- **Accent:** Monospace for counts/numbers

## Navigation
- Bottom tab bar: Home, Explore, New Post (+), Notifications, Profile
- Tab bar: dark background, gradient active indicator, minimal icons
- No header bars on main screens (full-bleed content)

## Design Principles
- **Dark-first:** All screens optimized for dark mode
- **Gradient accents:** Violet → Cyan gradient used for interactive elements
- **Glass morphism:** Frosted glass cards and overlays
- **Minimal chrome:** Content takes priority, UI elements fade into background
- **Micro-interactions:** Subtle animations on like, follow, and navigation
