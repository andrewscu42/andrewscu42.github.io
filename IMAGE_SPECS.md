# Image Specifications for Salesforce Section

## Overview
You're designing an image for the **Salesforce section** of a portfolio website. This image will appear on the right side of a two-column layout, directly opposite the text content.

## Layout Context

### Container Structure
- **Section**: The image sits in a Bootstrap grid system
- **Column Width**: The image occupies **50% of the container width** on desktop/tablet screens (6 out of 12 columns)
- **Responsive Behavior**: On mobile devices, the image will stack below the text and take up the full width

### Visual Constraints

#### Shape
- **Format**: **Circular** (the image will be displayed as a perfect circle via CSS `rounded-circle` class)
- **Important**: Design your image content with the understanding that it will be cropped into a circle. Keep important visual elements centered and avoid placing critical details near the edges.

#### Sizing
- **Responsive**: The image uses `img-fluid` class, meaning it will scale proportionally with the container
- **Desktop/Tablet**: Approximately **50% of the container width** (which is typically 1140px max-width, so roughly 570px on large screens)
- **Mobile**: Full width of the container (minus padding)
- **Aspect Ratio**: Since it's circular, the effective display will be **1:1** (square), but the image can be any ratio as long as important content is centered

#### Section Context
- **Section Height**: Minimum 60vh (60% of viewport height)
- **Padding**: The section has vertical padding (`py-5`), creating breathing room
- **Background**: Dark background color (#131223)
- **Decorative Element**: There's an animated gradient blob (`shape-3`) in the bottom-left that may partially overlap, so avoid placing important details in that corner

## Design Recommendations

### Content Theme
- **Subject**: "Visual of screen with code" (as indicated by the alt text)
- **Context**: This is a Salesforce development portfolio, so consider:
  - Code editor screenshots
  - Salesforce Lightning interface
  - Development tools
  - Abstract code visualizations

### Technical Considerations
1. **Safe Zone**: Keep important visual elements within the **center 60-70%** of your image to account for circular cropping
2. **Color Palette**: The site uses:
   - Background: #131223 (dark blue-black)
   - Primary gradient: #38C496 (green) to #336AFF (blue)
   - Accent: #7214FF (purple)
   - Text: #FFFFFF (white) and #C5C5C5 (light gray)
3. **Contrast**: Ensure sufficient contrast against the dark background
4. **File Format**: Use PNG or JPG. If transparency is needed, use PNG
5. **Resolution**: Provide at least **1200x1200px** to ensure crisp display on high-DPI screens

### Visual Hierarchy
- The image should complement, not compete with, the text content on the left
- Consider using subtle, muted tones that work with the dark theme
- The circular format creates a modern, focused presentation

## Summary Checklist
- [ ] Design for circular crop (keep important content centered)
- [ ] Minimum 1200x1200px resolution
- [ ] Works at 50% container width (desktop) and full width (mobile)
- [ ] Sufficient contrast against dark background (#131223)
- [ ] Theme: "visual of screen with code" related to Salesforce development
- [ ] Avoid placing critical details in bottom-left corner (decorative blob area)

