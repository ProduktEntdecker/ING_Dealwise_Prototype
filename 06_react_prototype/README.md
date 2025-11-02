# ING DealWise Interactive Prototype

An iOS-styled web prototype of the ING Banking app's DealWise cashback service integration.

## 📱 What's Included

### 4 Interactive Screens:

1. **Account Overview** - Girokonto Future with balance, transactions, and action buttons
2. **Cashback Service** - Partner logos grid and service information
3. **DealWise Landing** - Category navigation and deal discovery
4. **Offer Detail** - Individual cashback offer with CTA

### Features:

- ✅ iOS-inspired design with smooth animations
- ✅ Bottom sheet menu interaction
- ✅ Screen navigation
- ✅ Responsive layout (mobile-optimized, max-width 430px)
- ✅ Scrollable content
- ✅ ING brand colors and styling

## 🎨 Design System

### Colors:
- **ING Orange**: `#FF6200` (primary brand, CTAs, icons)
- **ING Green**: `#4CAF50` (sustainability icons)
- **ING Blue**: `#006` (logo)
- **Purple**: `#5E5A9D` (buttons, interactive elements)
- **Background**: `#F5F5F5` (light gray), `#FFFFFF` (white)
- **Text**: `#333333` (primary), `#666666` (secondary)

### Typography:
- System font stack: `-apple-system, BlinkMacSystemFont, 'Segoe UI'`
- Weights: 400 (regular), 500 (medium), 600 (semibold), 700 (bold)

## 🚀 How to Use

### Option 1: Local Preview
1. Open `index.html` in any modern web browser
2. Click the **"Mehr"** (More) button to open the bottom sheet
3. Navigate through screens by clicking on menu items and buttons

### Option 2: Import to Lovable.dev
1. Copy the entire contents of `index.html`
2. In Lovable, create a new project
3. Paste the HTML code
4. The prototype will work immediately - all styles and scripts are inline

### Option 3: Import to Bolt.new
1. Upload `index.html` to Bolt.new
2. Or copy/paste the code into the editor
3. Run the preview

## 📐 Screen Flow

```
Account Overview (Screen 1)
    ↓ Click "Mehr" button
Bottom Sheet Menu
    ↓ Click "Cashback Service"
Cashback Service (Screen 2)
    ↓ Click "Zu DealWise"
DealWise Landing (Screen 3)
    ↓ Click on offer card
Offer Detail (Screen 4)
```

## 🎯 Interactive Elements

- **Mehr Button** (⋯) - Opens bottom sheet menu
- **Cashback Service** - Navigate to partner grid
- **Zu DealWise** - Navigate to DealWise platform
- **Offer Cards** - View deal details
- **Back Buttons** (‹) - Navigate backwards
- **Zum Shop** - Primary CTA button

## 🛠️ Customization

### Partner Logos:
✅ **Real logos are now included!** The partner grid uses 20 actual merchant logos from:
- Amazon, ABOUT YOU, AliExpress, OTTO
- bonprix, ASOS, Expedia, DECATHLON
- Notino, Trip.com, LEGO, Agoda
- Lieferando, weg.de, Wolt, Disneyland
- REWE, TUI, L'Occitane, zooplus

Logos are referenced from: `../01_reference/merchant_logos/`

### Changing Colors:
Update CSS variables in `:root` (lines 10-30):
```css
:root {
    --ing-orange: #FF6200;
    --ing-green: #4CAF50;
    /* etc. */
}
```

### Adding More Screens:
1. Create a new `<div id="screen-name" class="screen">`
2. Add navigation with `onclick="showScreen('screen-name')"`

## 📦 File Structure

```
06_react_prototype/
├── index.html          # Complete standalone prototype
└── README.md          # This file
```

## 🎨 Brand Assets Used

- ING Logo SVG (blue lion + "ING" wordmark)
- DealWise Logo SVG (black wordmark)
- Partner logos: Placeholder emojis and text (replace with real logos)

## 🔧 Technical Details

- **No build process required** - Pure HTML/CSS/JavaScript
- **No dependencies** - Works offline
- **Mobile-optimized** - 430px max width (iPhone 14 Pro size)
- **Smooth animations** - CSS transitions for bottom sheet, cards
- **Accessible** - Semantic HTML, ARIA labels

## 📱 Tested On

- Chrome/Safari (Desktop)
- Safari (iOS)
- Chrome (Android)
- Lovable.dev
- Bolt.new

## 🚧 Next Steps / Enhancements

1. **Add Real Assets**:
   - Replace emoji partner logos with actual SVG/PNG files
   - Add real account icons
   - Include product images for offers

2. **Enhanced Interactions**:
   - Swipe gestures for bottom sheet
   - Card flip animations
   - Loading states
   - Success messages

3. **More Screens**:
   - Partner detail pages
   - Search functionality
   - Category filters
   - User profile/settings

4. **Data Integration**:
   - Connect to real API
   - Dynamic offers
   - User-specific cashback tracking

## 📄 License

Prototype for ING Dealwise concept. Design based on ING Banking app screenshots.

## 🤝 Credits

- Design: Based on ING Mobile Banking App
- DealWise: Integration concept
- Built with: Plain HTML/CSS/JavaScript
- Created for: Lovable/Bolt prototyping

---

**Questions or Issues?** Open the HTML file and use browser dev tools to inspect/modify elements.
