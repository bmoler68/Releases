# Adding New Apps to the Repository

This guide explains how to properly add new Android applications to this release repository.

## 📂 Folder Structure

Each app should follow this structure:
```
NewAppName/
├── README.md                    # App-specific documentation
├── NewAppName-release-v1.0.0.apk  # Release APK files
├── NewAppName-release-v1.1.0.apk  # Additional versions
└── [other assets if needed]     # Screenshots, icons, etc.
```

## 📝 Steps to Add a New App

### 1. Create App Folder
Create a new folder with the app name (use PascalCase, no spaces):
```bash
mkdir YourNewAppName
```

### 2. Add README.md
- Copy the template from `.github/APP_README_TEMPLATE.md`
- Fill in all the placeholder values
- Update app-specific information
- Ensure all sections are complete

### 3. Add Release APK
- Use naming convention: `AppName-release-vX.Y.Z.apk`
- Place in the app's folder
- Update the README with the correct APK filename

### 4. Update Main README
Add your app to the main repository README.md:

```markdown
### [Your App Name](./YourNewAppName/README.md)
Brief description of your app.

**Latest Version**: vX.Y.Z  
**Status**: [Active Development|Stable|Maintenance]  
**Category**: [App Category]  
```

### 5. Verify Structure
Ensure your addition follows the established patterns:
- ✅ App folder exists
- ✅ App README.md is complete
- ✅ APK follows naming convention
- ✅ Main README.md updated
- ✅ Links work correctly

## 📋 Checklist for New Apps

Before adding a new app, ensure:

- [ ] App has been thoroughly tested
- [ ] README.md is complete and accurate
- [ ] APK file size is reasonable
- [ ] All required permissions are documented
- [ ] Version numbering follows semantic versioning
- [ ] Release notes are clear and detailed
- [ ] Links between READMEs work correctly

## 🔄 Updating Existing Apps

When releasing new versions:

1. Add new APK with updated version number
2. Update app's README.md with new release information
3. Update main README.md with latest version number
4. Keep old APK files for version history

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
- Include comprehensive feature lists
- Document all permissions with explanations
- Maintain consistent formatting across READMEs
- Test all download links
- Include relevant screenshots in the future if needed

---

Following this guide ensures consistency and makes it easy for users to find and understand your applications.
