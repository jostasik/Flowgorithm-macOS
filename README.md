# Flowgorithm for MacOS

Flowgorithm is a beginner-friendly programming language based on simple graphical flowcharts. It supports a variety of programming languages, including AppleScript, Bash, C#, C++, Java, JavaScript, PHP, Powershell, Python, Ruby, Swift, SQL, TypeScript, Visual Basic .NET, and more! Flowgorithm provides an easy-to-understand output and a graphical variable watch window. You can even convert your flowcharts to real live code!

## Installation

There are two ways to install Flowgorithm on your MacOS device.

#### Option 1: Use Homebrew

1.  Install the package manager [brew](https://www.brew.sh) if you haven't already.
2.  Run the following commands in the Terminal:

```bash
brew tap jostasik/homebrew-tap
brew update
brew install --no-quarantine jostasik-flowgorithm
```

#### Option 2: Download the Latest Release

1.  Go to the [Flowgorithm-MacOS release page](https://github.com/jostasik/Flowgorithm-MacOS/releases).
2.  Download the latest release.
3.  Run the Flowgorithm installer.
4.  Flowgorithm will be installed in your Applications folder.

## Troubleshooting

#### Issue: "Unidentified Developer" Warning

If you see a message that says "Flowgorithm.app can't be opened because it is from an unidentified developer", it means that your security settings on your MacOS device are preventing the app from opening.

Here's what you can do to resolve this issue:

1.  Right-click Flowgorithm.app from Finder.
2.  Click "Open".

You should now see a new dialog box that asks if you're sure you want to open the app. Click "Open" to proceed.

#### Issue: "Apple cannot check it for malicious software" Warning

If you see a message that says "Apple cannot check it for malicious software", it means that your MacOS device is blocking the installation of the app because it is not from a verified developer.

Here's what you can do to resolve this issue:

1.  Hold down the Control key and click on the Flowgorithm.app file in Finder.
2.  Choose "Open" from the context menu.
3.  A new dialog box will appear asking if you want to open the app. Click "Open" to proceed.

Note that you might have to repeat this process every time you open the app.

#### Issue: "App is Damaged and Can't Be Opened" Error

If you see a message that says "Flowgorithm.app is damaged and can't be opened", it means that the app has been corrupted during the installation process.

Here are two ways you can try to resolve this issue:

1.  Move the Flowgorithm.app file to the Trash.
2.  Download the app again from the source you used originally to install the app.
3.  Install the app again.

If the issue persists, try the following additional troubleshooting step:

1.  Open Terminal from the Applications folder.
2.  Type in the following command and hit Enter:

```bash
xattr -d com.apple.quarantine /Applications/Flowgorithm.app
```

If you still encounter issues after trying these troubleshooting steps, please contact me and I'll gladly help get you up and running!
