# 🚀 GitHub Actions Setup Guide

## Step-by-Step Instructions to Build APK on GitHub

### Step 1: Create GitHub Account (if you don't have one)
1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process
4. Verify your email

### Step 2: Create New Repository
1. Click the **+** icon (top right) → "New repository"
2. Repository name: `vlc-pro-translator`
3. Description: `VLC with auto language detection and translation`
4. Make it **Public** (required for free GitHub Actions)
5. Check **"Add a README file"**
6. Click **"Create repository"**

### Step 3: Upload Files
1. In your new repo, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL files from this folder:
   - `.github/` folder
   - `www/` folder
   - `config.xml`
   - `icon.png`
   - `.gitignore`
3. OR use the GitHub Desktop app for easier upload
4. Click **"Commit changes"**

### Step 4: Trigger Build
The build starts automatically when you push files!

**To manually trigger:**
1. Go to **"Actions"** tab
2. Click **"Build VLC Pro APK"**
3. Click **"Run workflow"** dropdown
4. Click **"Run workflow"** button
5. Wait 3-5 minutes

### Step 5: Download APK
1. Go to **"Actions"** tab
2. Click the latest successful run (green checkmark ✅)
3. Scroll down to **"Artifacts"**
4. Download **"VLC-Pro-Debug-APK"**
5. Unzip the downloaded file
6. Install `app-debug.apk` on your phone!

---

## 📱 Installing on Android

1. Transfer APK to phone (USB, email, cloud)
2. Tap the APK file
3. Allow "Install from unknown sources"
4. Install and open!

---

## 🔧 Troubleshooting

### Build fails?
- Check that all files are uploaded correctly
- Ensure `config.xml` is in root directory
- Check Actions log for specific errors

### APK won't install?
- Enable "Unknown Sources" in Settings → Security
- Make sure APK downloaded completely
- Try the debug version instead of release

### App crashes?
- Ensure you're using Android 5.0+
- Grant microphone permission when prompted
- Check that video file is valid

---

## 🔄 Updating the App

To make changes:
1. Edit files in your GitHub repo
2. Commit the changes
3. GitHub automatically rebuilds the APK
4. Download new version from Actions tab

---

## 💡 Tips

- **Bookmark the Actions page** for quick access to downloads
- **Enable notifications** to get alerted when build completes
- **Use GitHub Mobile app** to monitor builds from your phone
- **Star the repository** to find it easily later

---

## 📧 Need Help?

If you get stuck:
1. Check the Actions log for error messages
2. Make sure you uploaded all files from this package
3. Try creating a new repository and uploading again
