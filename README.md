# Tauri wrapper for PenPot

<img width="1200" alt="image" src="https://user-images.githubusercontent.com/134939/219828260-044730b4-0dd2-4bdc-bb37-b4a5c4fe2e21.png">

This app is not signed, follow the directions below to open it:

1. Copy PenPot.app to your Applications folder.
2. Open Terminal and paste the following: 

```zsh
sudo xattr -rd com.apple.quarantine /Applications/PenPot.app

sudo codesign --force --deep --sign - /Applications/PenPot.app
```

3. Double-click the PenPot.app to open it (you may not be able to open it)
4. Right-click the PenPot.app and select "open" (this time it should ask you if you want to open it)
