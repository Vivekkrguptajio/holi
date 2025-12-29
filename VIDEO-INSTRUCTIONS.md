# Radhe Krishna Video Setup Instructions

## Video File Required

Place your Radhe Krishna video file in the HoliWish folder with the name:
**`radhe-krishna.mp4`**

## How It Works

1. **Curtains Open** → Left and Right curtains slide apart
2. **Video Plays** → Radhe Krishna video plays automatically
3. **After Video** → Holi card appears with countdown timer

## Features

✅ **Auto-play** - Video starts automatically after curtains open
✅ **Skip Button** - "⏭️ Skip Video" button to skip directly to Holi card
✅ **Auto-continue** - Card appears automatically when video ends
✅ **Full-screen ready** - Video is centered and responsive

## Video Specifications

- **Format**: MP4 (recommended)
- **Location**: `c:\Users\Vivek kumar Gupta\Desktop\HoliWish\radhe-krishna.mp4`
- **Controls**: Built-in video controls available

## Alternative Video Formats

If you have a different video format, update line 34 in `index.html`:

```html
<source src="your-video-name.mp4" type="video/mp4">
```

Or add multiple formats:

```html
<source src="radhe-krishna.mp4" type="video/mp4">
<source src="radhe-krishna.webm" type="video/webm">
```

## Testing

1. Place `radhe-krishna.mp4` in the HoliWish folder
2. Open `index.html` in browser
3. Click "पिचकारी चलाओ बाबू"
4. Curtains will slide → Video will play → Card will appear
