# Android Login UI - XML Layout

This project provides a clean and simple Android login screen built using XML. The layout is structured using `LinearLayout` and `RelativeLayout`, including fields for email, password, and options for account creation and password recovery.

## 📱 UI Features

- Centered logo and title
- Input fields for Email and Password
- "Forgot Password?" text with clickable link
- Login button
- Prompt and button to create a new account

## 📁 Layout File

The primary layout is defined in `res/layout/activity_main.xml` (or similar) and uses:

- `ImageView` for logo
- `TextView` for labels and prompts
- `EditText` for user inputs
- `Button` for login and new account actions
- `RelativeLayout` for positioning the bottom section

## 🧩 Dependencies & Resources

Make sure the following resources exist in your project:

### 🔤 Strings (`res/values/strings.xml`)
```xml
<string name="title">Your App Title</string>
<string name="email_txt">Email</string>
<string name="password_txt">Password</string>
<string name="forgot_pwd">Forgot Password?</string>
<string name="btn_txt">Login</string>
<string name="noaccount_txt">Don't have an account?</string>
<string name="btn_new">Create Account</string>
