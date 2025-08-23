# Adding New Apps to the Repository

This guide explains how to properly add new Android applications to this release repository and GitHub Pages site.

## 📂 Folder Structure

Each app should follow this structure:
```
NewAppName/
├── NewAppName-release-v1.0.0.apk  # Release APK files
└── NewAppName_icon.png            # App icon (PNG format, recommended 512x512)
```

**Note**: App icons are now stored alongside their respective applications for better organization and easier maintenance.

## 📝 Steps to Add a New App

### 1. Create App Folder
Create a new folder with the app name (use PascalCase, no spaces):
```bash
mkdir YourNewAppName
```

### 2. Add App Icon
- Create or obtain a high-quality app icon
- Use PNG format for best compatibility
- Recommended size: 512x512 pixels
- Name the file: `YourNewAppName_icon.png`
- Place it in the app's folder

### 3. Add Release APK
- Use naming convention: `AppName-release-vX.Y.Z.apk`
- Place in the app's folder
- Ensure the APK has been thoroughly tested

### 4. Update Main README.md
- Add your app to the main repository README.md using the centralized format
- Follow the app section structure shown in step 5 below
- Include all essential app information in the main README

### 5. Update Main README
Add your app to the main repository README.md:

```markdown
### [Your App Name]

**Latest Version**: vX.Y.Z  
**Status**: [Active Development|Stable|Maintenance]  
**Category**: [App Category]

**About**: [Detailed description of your app's functionality and purpose]

**Requirements**: [Android version, RAM, storage, and other requirements]

**Legal**: [Any legal disclaimers, copyright information, or trademark notices]
```

### 6. Update GitHub Pages Site (index.html)
Add your app to the `index.html` file for the live site:

```html
<!-- Your New App -->
<div class="app-card">
    <div class="app-header">
        <div class="app-icon">
            <img src="YourNewAppName/YourNewAppName_icon.png" alt="Your App Icon">
        </div>
        <div class="app-info">
            <h2>Your App Name</h2>
            <div class="app-version">v1.0.0</div>
        </div>
    </div>
    
    <div class="app-description">
        [Your app description here]
    </div>

    <div class="app-requirements">
        <h4>Requirements</h4>
        <ul>
            <li>Android 7.0 (API 24) or higher</li>
            <li>Minimum 2GB RAM recommended</li>
            <li>Install from Unknown Sources enabled</li>
        </ul>
    </div>

    <div class="download-section">
        <a href="YourNewAppName/YourNewAppName-release-v1.0.0.apk" class="download-btn" download>
            📥 Download APK
        </a>
        <div class="file-info">File size: [X] MB</div>
    </div>
</div>
```

### 7. Verify Structure
Ensure your addition follows the established patterns:
- ✅ App folder exists with proper naming
- ✅ APK follows naming convention
- ✅ App icon is included and properly named
- ✅ Main README.md updated with comprehensive app information
- ✅ GitHub Pages site (index.html) updated with app card
- ✅ App section includes all required details

## 📋 Checklist for New Apps

Before adding a new app, ensure:

- [ ] App has been thoroughly tested
- [ ] App icon is created and added to the app folder
- [ ] Main README.md is updated with comprehensive app information
- [ ] GitHub Pages site (index.html) is updated with app card
- [ ] APK file size is reasonable
- [ ] All required permissions are documented
- [ ] Version numbering follows semantic versioning
- [ ] App description includes all essential details
- [ ] Legal and copyright information is accurate

## 🔄 Updating Existing Apps

When releasing new versions:

1. **Add new APK** with updated version number
2. **Update app icon** if there are visual changes
3. **Update main README.md** with new release information and version number
4. **Update GitHub Pages site** (index.html) with new version number and file size
5. **Keep old APK files** for version history

## 📝 README Template Values

When using the template, replace these placeholders:

- `[App Name]` - Your application's name
- `[Brief description...]` - One-line app description
- `[Detailed description...]` - Comprehensive app overview
- `vX.Y.Z` - Actual version numbers
- `[App Category]` - Gaming, Utility, Productivity, etc.
- `[Technology stack]` - Compose, View system, etc.
- `[Permission descriptions]` - Actual permission requirements

## 🌐 GitHub Pages Integration

The repository now includes a live GitHub Pages site at `https://bmoler68.github.io/Releases/`. When adding new apps:

- **App icons** are automatically displayed on the live site
- **Download buttons** provide direct access to APK files
- **App descriptions** are prominently featured
- **System requirements** are clearly displayed
- **Responsive design** works on all devices

## 💡 Best Practices

- Use clear, descriptive app names
- Keep folder names consistent (PascalCase)
- Include high-quality app icons (512x512 PNG recommended)
- Include comprehensive app descriptions in both README and GitHub Pages
- Document all permissions with explanations
- Maintain consistent formatting across all app sections
- Ensure all app information is complete and accurate
- Keep legal and copyright information up to date
- Test the GitHub Pages site after adding new apps

## 🔧 File Naming Conventions

- **App folders**: `PascalCase` (e.g., `MyNewApp`)
- **APK files**: `AppName-release-vX.Y.Z.apk` (e.g., `MyNewApp-release-v1.0.0.apk`)
- **App icons**: `AppName_icon.png` (e.g., `MyNewApp_icon.png`)
- **Version numbers**: Semantic versioning `vX.Y.Z`

---

Following this guide ensures consistency across the repository and GitHub Pages site, making it easy for users to find, understand, and download your applications.
