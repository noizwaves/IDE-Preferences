Pivotal Boulder IDE-Preferences
===============

Key mappings and macros for RubyMine, IntelliJ IDEA, and other JetBrains IDEs.

## 1. Clone this repo
```
cd ~/workspace
git clone https://github.com/Pivotal-Boulder/IDE-Preferences.git
```

## 2. Copy the files to your IDE preferences folder

#### IntelliJ

Keymap:

```
mkdir -p ~/.config/JetBrains/IntelliJIdea2020.1/keymaps/
cp ~/workspace/IDE-Preferences/MultiOSImproved.xml ~/.config/JetBrains/IntelliJIdea2020.1/keymaps/
```

Macros:
```
cp ~/workspace/IDE-Preferences/macros.xml ~/.config/JetBrains/IntelliJIdea2020.1/options/
```

(Optional) base keymap for Linux:
```
mkdir -p ~/.config/JetBrains/IntelliJIdea2020.1/keymaps/
wget -O ~/.config/JetBrains/IntelliJIdea2020.1/keymaps/MacOSPlus.xml https://raw.githubusercontent.com/JetBrains/intellij-community/master/platform/platform-resources/src/keymaps/Mac%20OS%20X%2010.5%2B.xml
```

#### RubyMine

Keymap:
```
mkdir -p ~/.config/JetBrains/RubyMine2020.1/keymaps/
cp ~/workspace/IDE-Preferences/MultiOSImproved.xml ~/.config/JetBrains/RubyMine2020.1/keymaps/
```

Macros:
```
cp ~/workspace/IDE-Preferences/macros.xml ~/.config/JetBrains/RubyMine2020.1/options/
```

(Optional) base keymap for Linux:
```
mkdir -p ~/.config/JetBrains/RubyMine2020.1/keymaps/
wget -O ~/.config/JetBrains/RubyMine2020.1/keymaps/MacOSPlus.xml https://raw.githubusercontent.com/JetBrains/intellij-community/master/platform/platform-resources/src/keymaps/Mac%20OS%20X%2010.5%2B.xml
```

#### Rider

Keymap:
```
mkdir -p ~/.config/JetBrains/Rider2020.1/keymaps/
cp ~/workspace/IDE-Preferences/MultiOSImproved.xml ~/.config/JetBrains/Rider2020.1/keymaps/
```

Macros:
```
cp ~/workspace/IDE-Preferences/macros.xml ~/.config/JetBrains/Rider2020.1/options/
```

(Optional) base keymap for Linux:
```
mkdir -p ~/.config/JetBrains/Rider2020.1/keymaps/
wget -O ~/.config/JetBrains/Rider2020.1/keymaps/MacOSPlus.xml https://raw.githubusercontent.com/JetBrains/intellij-community/master/platform/platform-resources/src/keymaps/Mac%20OS%20X%2010.5%2B.xml
```


#### Microsoft Visual Studio Code
These are JetBrains-style key mappings

```
cp ~/workspace/IDE-Preferences/keybindings.json ~/Library/Application\ Support/Code/User/
```

## 3. Restart the IDE

If you have a current IDE instance open you'll need to restart it

## 4. Select the keymap in your IDE
Preferences (⌘,) -> Keymap -> Select "Multi OS Improved+" from the Keymaps dropdown
