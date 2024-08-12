# LiteYTEmbed - Lightweight YouTube Embed Custom Element

LiteYTEmbed is a custom web component designed to optimize the performance of embedded YouTube videos by loading the video iframe only when it's needed. This approach significantly improves the initial load time of web pages.

## 🎯 Features

- 🚀 **Lazy Loading**: Iframes are only loaded on interaction, reducing initial page load.
- ⚙️ **Customizable Attributes**:
  - `videoid`: The ID of the YouTube video to embed.
  - `playlistid`: The ID of the YouTube playlist to embed.
  - `videotitle`: The title of the video, used for accessibility and metadata.
  - `videoPlay`: The text label for the play button.
  - `videoStartAt`: Start the video at a specific time.
  - `autoload`: Automatically load the video when it comes into view.
  - `nocookie`: Load the video using YouTube's privacy-enhanced mode.
  - `posterquality`: Control the quality of the video poster image.

- 📱 **Responsive Design**: The component adapts to different screen sizes, with support for YouTube Shorts.
- 🔗 **Preconnection**: Establishes preconnect hints for YouTube and related services to speed up video loading.
- 🎨 **Custom Styling**: Encapsulated styles with Shadow DOM, allowing you to customize the look without affecting other elements on your page.
- 👁️ **Intersection Observer**: Automatically loads the iframe when the video comes into view, enhancing the user experience.

## 📦 Installation

To include `LiteYTEmbed` in your project, copy the `LiteYTEmbed` class into your JavaScript file or include it as a module.
