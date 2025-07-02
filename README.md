# Android XML Layout – Simple Intro Screen

This project demonstrates a basic Android UI screen created using XML. It features a vertical layout with an image, heading, input field, and a styled button.

## 📄 Layout Overview

**File**: `activity_main.xml`

This layout includes the following components:

- 🖼 **ImageView**: Displays a scenic placeholder image (`fitXY` scaled).
- 📝 **TextView**: A heading with bold, colored text saying "Hello! How are you".
- ✍ **EditText**: A user input field prompting to "Enter Name".
- 🔘 **Button**: A button labeled "Click Here" with custom styling.

### Layout Structure (Simplified)
LinearLayout (Vertical)
├── ImageView (scenic sample)
├── TextView ("Hello! How are you")
├── EditText (Hint: "Enter Name")
└── Button ("Click Here")


## 🎯 Purpose

This layout serves as a simple entry screen or a UI prototype for practicing:

- LinearLayout orientation and alignment
- Basic widgets (ImageView, TextView, EditText, Button)
- Using `strings.xml` for clean string management
- Styling UI components (text size, color, background)

## 🧰 Tools Used

- **Language**: XML
- **IDE**: Android Studio
- **Target SDK**: (adjust in your `build.gradle`)
- **Min SDK**: 21+

## 📦 How to Use

1. Clone or download this repo.
2. Open in Android Studio.
3. Replace placeholder image with your own in `ImageView` (or use an online URL via Glide/Picasso in Java code).
4. Run the project on an emulator or device.

## 🖼 Preview

> *(Optional)* Add a screenshot of the app layout here once run in the emulator.

## 🗂 Strings Used (from `strings.xml`)

```xml
<string name="app_name">My Application</string>
<string name="About">Hello!How are you</string>
<string name="enter_name">Enter Name</string>
<string name="click_here">Click Here</string>
<string name="todo">TODO</string>


