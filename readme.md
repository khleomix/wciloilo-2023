# WordCamp Iloilo 2023 Style Guide
WordCamp Iloilo is using the TwentyTwentyThree theme's site editor with custom styles.

## Connecting style guide

----------

If you are hosting your style guide repository on GitHub, you can use the power of GitHub to share compiled CSS with your WordCamp website. After CSS is updated on GitHub, you can update it on WordPress By using Hooks, you can make your WordCamp website update every time the CSS file is updated. Here are steps on how to setup that.

* Make sure your style guide is available on GitHub and that you have Administrator access to your WordCamp website wp-admin
* Go to your repository **settings** on GitHub and find **Hooks**.
* Paste the hook URL: **year.wordcamp-name**.wordcamp.org/wp-admin/admin-ajax.php?action=wcrcss_webhook
* Go to your WordCamp admin and find **Remote CSS** **under Appearance**.
* Paste the link to your compiled CSS on GitHub. Example: [https://raw.githubusercontent.com/khleomix/wordcamp-style-guide/master/build/assets/stylesheets/style.css](https://raw.githubusercontent.com/khleomix/wordcamp-style-guide/master/build/assets/stylesheets/style.css)

If you need more help, check the Help screen on Remote CSS page on your WordCamp website admin.
