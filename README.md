# Power BI Date Range Slicer

[![Power BI](https://img.shields.io/badge/Power%20BI-Custom%20Visual-F2C811?logo=powerbi)](https://powerbi.microsoft.com/)
[![Version](https://img.shields.io/badge/Version-1.1.0-green.svg)](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz)
[![Release](https://img.shields.io/github/v/release/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz)](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/releases)
[![Downloads](https://img.shields.io/github/downloads/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/total)](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/releases)

A professional date range slicer for Power BI with an intuitive interface, preset date ranges, and customizable styling.

![Date Range Slicer](icon.png)

## ✨ Features

- **Focus Mode Onboarding** - Professional first-time setup experience
- **Date Range Validation** - Prevents invalid date selections
- **Themed Dialog Buttons** - OK/Cancel buttons match your theme color
- **Compact Design** - Matches Power BI's native styling
- **Quick Date Selection** - Click date fields for instant picking
- **Advanced Range Selection** - Dual calendar view with presets
- **Smart Positioning** - Date picker appears below the visual
- **Preset Date Ranges** - Last 7/30/90 days, This Month, and more
- **Customizable Colors** - Match your report theme
- **Professional UI** - Clean interface with month/year dropdowns

## 🆕 What's New in v1.1.0

### Major Enhancements
- **Focus Mode Integration**: Automatically enters focus mode for first-time setup, exits smoothly after completion
- **Date Validation**: Start date cannot be after end date (and vice versa) with visual feedback
- **Custom Themed Buttons**: Dialog buttons now use your selected theme color
- **Improved Layout**: Redesigned date picker footer (Today | Cancel OK)

### Bug Fixes
- Fixed focus mode re-entry loop
- Fixed invalid date range selections
- Removed scrollbars from dialogs
- Theme colors now apply to all dialog buttons

[View Full Changelog](#changelog)

## 📥 Download

**Latest Version: 1.1.0**

**[Download DateRangeSlicer.1.1.0.pbiviz](DateRangeSlicer.1.1.0.pbiviz)** ⬅️ Click to download

Or get previous versions from the [Releases](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/releases) page.

## 🚀 Installation

1. **Download** the `.pbiviz` file from above
2. Open **Power BI Desktop**
3. Go to the **Visualizations** pane
4. Click the **"..."** (three dots) icon
5. Select **"Import a visual from a file"**
6. Browse to the downloaded file
7. Click **Open** and accept the security warning

The visual will now appear in your Visualizations pane!

## 📖 Quick Start

### 1. Add the Visual
Click the Date Range Slicer icon in your Visualizations pane

### 2. Add Your Date Field
Drag a date field from your data to the "Date" field well

### 3. Select Dates

**Quick Selection:**
- Click either date field to open a compact date picker
- Use month/year dropdowns to navigate
- Click any date to select

**Advanced Selection:**
- Click the settings button (⚙️) for full date range options
- Use preset buttons: Last 7 Days, This Month, etc.
- Or select a custom range with dual calendar view

## 🎨 Customization

Open the **Format** pane to customize:
- **Colors** - Highlight, range, text, and background colors
- **Date Fields** - Size, font, and styling
- **Icons** - Calendar icon size and color
- **Presets** - Show/hide specific date range buttons

## 💬 Feedback & Support

Your feedback helps improve this visual!

- **Report Issues**: [Create an issue](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/issues/new)
- **Feature Requests**: [Request a feature](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/issues/new)
- **Questions**: [Ask in Discussions](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/discussions)

When reporting issues, please include:
- Description of the problem
- Steps to reproduce
- Screenshots (if helpful)
- Your Power BI Desktop version

## 🔧 Common Issues

**Visual doesn't appear after import**
- Confirm the security warning during import
- Restart Power BI Desktop

**Filter not working**
- Verify the date field is in the "Date" field well
- Check that other visuals use the same date field
- Ensure proper date format (not text)

**Dialog doesn't open**
- Ensure you're using Power BI Desktop
- Check organization settings allow modal dialogs

## 📊 Usage Tips

- Place the visual at the top of your report for easy access
- Use consistent sizing across report pages
- Test filtering with other visuals on the page
- The end date is included in the filter range

## 👤 Author

**Emmanuel Twum Osafo**
- Email: emmanueltwumosafo@gmail.com
- GitHub: [@EmmanuelTwumOsafo](https://github.com/EmmanuelTwumOsafo)

## 📄 License

Free to use and modify for your Power BI reports.

## 📋 Changelog

### Version 1.1.0 (2026-04-14)

**New Features:**
- Focus mode integration for professional onboarding experience
- Date range validation (start ≤ end)
- Custom themed dialog buttons (OK/Cancel)
- Visual feedback for disabled dates

**Improvements:**
- Redesigned date picker footer layout
- Reduced dialog size (180×240px)
- Removed scrollbars from dialogs
- Added comprehensive documentation (KNOWN_ISSUES.md)

**Bug Fixes:**
- Fixed focus mode re-entry loop
- Fixed invalid date range selections
- Fixed theme color not applying to buttons

### Version 1.0.0 (2026-04-13)
- Initial release
- Dual calendar view
- Preset date ranges
- Custom date picker dialogs
- Theme customization
- Onboarding experience

---

**Made with ❤️ for the Power BI Community**

⭐ If you find this useful, please star the repo!
