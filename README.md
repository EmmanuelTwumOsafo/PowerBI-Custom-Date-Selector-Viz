# Power BI Date Range Slicer

[![Power BI](https://img.shields.io/badge/Power%20BI-Custom%20Visual-F2C811?logo=powerbi)](https://powerbi.microsoft.com/)
[![Version](https://img.shields.io/badge/Version-2.1.0-green.svg)](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz)
[![Release](https://img.shields.io/github/v/release/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz)](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/releases)
[![Downloads](https://img.shields.io/github/downloads/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/total)](https://github.com/EmmanuelTwumOsafo/PowerBI-Custom-Date-Selector-Viz/releases)

A professional date range slicer for Power BI with an intuitive interface, preset date ranges, and customizable styling.

![Date Range Slicer](icon.png)

## ✨ Features

- **Multi-Granularity Selection** - Choose dates by Day, Month, Quarter, Half-year, or Year
- **Full Keyboard Accessibility** - Complete keyboard navigation with Tab, Arrow keys, Enter/Space
- **Screen Reader Support** - WCAG 2.1 AA compliant with ARIA labels and live regions
- **Tab-Based Interface** - Easy switching between different time granularities
- **Range Selection** - Select ranges at any granularity (e.g., Q1 2024 - Q3 2024)
- **Business Period Alignment** - Perfect for fiscal quarters and half-year reporting
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
- **High Contrast Support** - Works with Windows High Contrast mode

## 🆕 What's New in v2.1.0

### ♿ Accessibility Features (WCAG 2.1 AA Compliant)

Version 2.1.0 makes the Date Range Slicer fully accessible to all users:

#### **Full Keyboard Navigation** 🎹
- **Tab/Shift+Tab**: Navigate through all controls
- **Enter/Space**: Activate buttons and select items
- **Escape**: Close dialogs
- **Arrow Keys**: Navigate calendar and picker grids
- **Home/End**: Jump to first/last day of month
- **PageUp/PageDown**: Navigate between months

#### **Screen Reader Support** 🔊
- Complete ARIA labels for all elements
- Live regions announce date selections
- Descriptive labels for all controls
- Tested with NVDA screen reader

#### **Focus Management** 🎯
- Visible focus indicators using theme color
- Focus trap in dialogs
- Focus restoration after dialog close
- Logical tab order

#### **High Contrast Support** 🌓
- Works with Windows High Contrast mode
- Sufficient color contrast (4.5:1 ratio)
- Focus indicators always visible

### Benefits
- **Accessible to All**: Keyboard users, screen reader users, low vision users
- **Certification Ready**: Meets Microsoft certification requirements
- **Legal Compliance**: WCAG 2.1 AA compliant (ADA, Section 508)
- **Better UX**: Improved usability for everyone

## 🆕 What's New in v2.0.0

### 🎯 Major Feature: Multi-Granularity Date Selection

Version 2.0.0 introduces a revolutionary tab-based interface for selecting dates at different granularity levels:

#### **Day View** (Original)
- Dual calendar with day-level precision
- Week numbers and date range selection
- Perfect for detailed daily analysis

#### **Month View** 🆕
- Select entire months with one click
- 3-year grid display (12 months per year)
- Range selection: Jan 2024 - Mar 2024

#### **Quarter View** 🆕
- Select fiscal quarters (Q1-Q4)
- Multi-year display
- Range selection: Q1 2024 - Q3 2024

#### **Half-Year View** 🆕
- Select half-year periods (H1-H2)
- Perfect for semi-annual reporting
- Range selection: H1 2024 - H2 2025

#### **Year View** 🆕
- Select full years with one click
- 11-year grid display
- Range selection: 2024 - 2026

### Benefits
- **Faster Selection**: Select entire quarters or years with one click
- **Business Alignment**: Aligns with fiscal reporting periods
- **Flexible Analysis**: Switch between different time granularities
- **Intuitive Interface**: Clear visual representation of time periods

[View Full Changelog](#changelog)

## 📥 Download

**Latest Version: 2.1.0** ♿ Fully Accessible

**[Download DateRangeSlicer.2.1.0.pbiviz](DateRangeSlicer.2.1.0.pbiviz)** ⬅️ Click to download

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

**Advanced Selection with Granularity:**
- Click the settings button (⚙️) for full date range options
- **Choose your granularity**: Day, Month, Quarter, Half-year, or Year tabs
- Use preset buttons: Last 7 Days, This Month, This Quarter, etc.
- Or select a custom range:
  - **Day**: Dual calendar view for precise date selection
  - **Month**: Click months across multiple years
  - **Quarter**: Select Q1-Q4 for fiscal reporting
  - **Half-year**: Choose H1 or H2 for semi-annual periods
  - **Year**: Select full years with one click

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

### Version 2.1.0 (2026-04-15)

**♿ Accessibility Features (WCAG 2.1 AA Compliant)**

**Full Keyboard Navigation:**
- Tab/Shift+Tab navigation through all controls
- Enter/Space to activate buttons and select items
- Escape to close dialogs
- Arrow keys for grid navigation (Calendar, Month, Quarter, Half-year, Year)
- Home/End keys jump to first/last day of month
- PageUp/PageDown keys navigate between months

**ARIA Labels and Roles:**
- Comprehensive ARIA attributes for screen readers
- role="dialog", role="tablist", role="grid", role="gridcell"
- aria-label, aria-selected, aria-expanded for all controls
- Live regions announce date selections

**Focus Management:**
- Visible focus indicators using theme color
- Focus trap in dialogs (Tab cycles within dialog)
- Focus restoration after dialog close
- Logical tab order throughout

**Screen Reader Support:**
- Tested with NVDA screen reader
- All controls have accessible names
- Clear instructions for navigation
- Status announcements for all actions

**High Contrast Support:**
- Works with Windows High Contrast mode
- Sufficient color contrast (4.5:1 ratio)
- Focus indicators always visible

**Benefits:**
- Accessible to keyboard users, screen reader users, low vision users
- Meets Microsoft certification requirements
- WCAG 2.1 AA compliant (ADA, Section 508)
- Better UX for all users

**Documentation:**
- Added ACCESSIBILITY_PHASE1_COMPLETE.md
- Added ACCESSIBILITY_SUMMARY.md
- Added ACCESSIBILITY_TESTING_GUIDE.md

### Version 2.0.0 (2026-04-15)

**🎯 Major Feature: Multi-Granularity Date Selection**
- Tab-based interface for Day/Month/Quarter/Half-year/Year selection
- Month View: 12-month grid per year with 3-year display
- Quarter View: Q1-Q4 selection across multiple years
- Half-Year View: H1-H2 selection for semi-annual reporting
- Year View: Multi-year grid with 11-year range
- Range selection support at all granularity levels
- Automatic date mapping (e.g., Q2 2024 → Apr 1 - Jun 30)

**New Components:**
- MonthPicker: 12-month grid component
- QuarterPicker: 4-quarter grid component
- HalfYearPicker: 2 half-year periods component
- YearPicker: Multi-year grid component
- Date granularity utility functions

**Benefits:**
- Faster selection for business periods
- Fiscal reporting alignment (Q1-Q4, H1-H2)
- Flexible time granularity switching
- Intuitive visual interface

**Technical:**
- Complete refactoring of OptionsDialog
- New dateGranularity.ts utility module
- Theme color integration across all views
- Maintained backward compatibility

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
