# How to Download

```
1. get yt-dlp (I'm using version 2025.12.08).
2. get secretstorage (from pip).
3. In your browser get an extension called "Get cookies.txt LOCALLY".
4. Open a YouTube movie that you want to download.
5. Start watching, approve the age restriction/captcha and keep it playing in the background.
6. Click on the plugin and and "Export As" and save as a file name (in our example cookies.txt).
7. Open CLI
8. yt-dlp + cookie file + browser type + link.

Example:
yt-dlp --cookies-from-browser chrome --cookies ./dotan_cookies.txt https://www.youtube.com/watch?v=kOpoi4ILbKg
```

## Some git

'''
echo "# yt-dlt-download" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/dotd/yt-dlt-download.git
git push -u origin main
'''