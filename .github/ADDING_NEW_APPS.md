# Adding New Apps to the Repository

This guide explains how to properly add new Android applications to this release repository.

## 📂 Folder Structure

Each app should follow this structure:
```
NewAppName/
└── NewAppName-release-v1.0.0.apk  # Release APK files only
```

## 📝 Steps to Add a New App

### 1. Create App Folder
Create a new folder with the app name (use PascalCase, no spaces):
```bash
mkdir YourNewAppName
```

### 2. Update Main README.md
- Add your app to the main repository README.md using the centralized format
- Follow the app section structure shown in step 4 below
- Include all essential app information in the main README

### 3. Add Release APK
- Use naming convention: `AppName-release-vX.Y.Z.apk`
- Place in the app's folder
- Update the README with the correct APK filename

### 4. Update Main README
Add your app to the main repository README.md:

```markdown
### [Your App Name]
Brief description of your app.

**Latest Version**: vX.Y.Z  
**Status**: [Active Development|Stable|Maintenance]  
**Category**: [App Category]

**About**: [Detailed description of your app's functionality and purpose]

**Key Features**:
- **[Feature 1]**: [Description]
- **[Feature 2]**: [Description]
- [Add more features as needed]

**Requirements**: [Android version, RAM, storage, and other requirements]

**Legal**: [Any legal disclaimers, copyright information, or trademark notices]
```

### 5. Verify Structure
Ensure your addition follows the established patterns:
- ✅ App folder exists
- ✅ APK follows naming convention
- ✅ Main README.md updated with comprehensive app information
- ✅ App section includes all required details

## 📋 Checklist for New Apps

Before adding a new app, ensure:

- [ ] App has been thoroughly tested
- [ ] Main README.md is updated with comprehensive app information
- [ ] APK file size is reasonable
- [ ] All required permissions are documented
- [ ] Version numbering follows semantic versioning
- [ ] App description includes all essential details
- [ ] Legal and copyright information is accurate

## 🔄 Updating Existing Apps

When releasing new versions:

1. Add new APK with updated version number
2. Update main README.md with new release information and version number
3. Keep old APK files for version history

## 📝 README Template Values

When using the template, replace these placeholders:

- `[App Name]` - Your application's name
- `[Brief description...]` - One-line app description
- `[Detailed description...]` - Comprehensive app overview
- `vX.Y.Z` - Actual version numbers
- `[Release Date]` - Actual release date
- `[App Category]` - Gaming, Utility, Productivity, etc.
- `[Technology stack]` - Compose, View system, etc.
- `[Permission descriptions]` - Actual permission requirements

## 💡 Best Practices

- Use clear, descriptive app names
- Keep folder names consistent (PascalCase)
- Include comprehensive feature lists in the main README
- Document all permissions with explanations
- Maintain consistent formatting across all app sections
- Ensure all app information is complete and accurate
- Keep legal and copyright information up to date

---

Following this guide ensures consistency and makes it easy for users to find and understand your applications.
