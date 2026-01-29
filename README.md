# Install-Telnet-on-macOS
Install Telnet on macOS




## Prerequisites

- macOS
- Internet connection
- Terminal access

---

## Step 1: Install Xcode Command Line License

Open terminal on mac and run :

```bash
sudo xcodebuild -license
```

- The license text will be displayed

- Scroll to the bottom

- Type agree

- Press Enter to accept the license

## Step 2: Install Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- Enter your Mac password if prompted.

## Step 3: Add Homebrew to PATH (Zsh)

  ```
echo >> /Users/atulkumar/.zprofile
  ```
  
 ```
 echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/atulkumar/.zprofile
```

 ```
 eval "$(/opt/homebrew/bin/brew shellenv zsh)"
```

## Step 4: Verify Homebrew
```
brew --version
```

## Step 5: Install Telnet
```
brew install telnet
```
