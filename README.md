# doublechecker
Double Checking Calculator for NZ Pharmacy Practice
# doublechecker
Double Checking Calculator for NZ Pharmacy Practice


# 🏥 Pharmacy Double Checking Calculator

A comprehensive web-based dosing calculator designed for pharmacists to double-check pediatric medication doses, insulin requirements, and eyedrop/eardrop calculations.

## 📋 Features

### 👶 Children's Medicine Calculator
- **Forward Calculation**: Enter child's weight → get dose (mg) and volume (mL) ranges
- **Reverse Calculation**: Enter volume given → estimate child's weight range
- **Dose Range Display**: Shows clinically relevant min-max ranges instead of arbitrary middle values
- **Complete NZF Dosing Information**: Includes full prescribing guidance with live links
- **Special Dosing Scenarios**: Handles age-specific, indication-specific, and Strep A dosing

### 💉 Insulin Calculator
- Calculate insulin supply requirements based on daily units
- Compare cartridge/pen needs (300 units) vs vial needs (1000 units)
- Customizable supply duration

### 👁️ Eyedrop/Eardrop Calculator
- Calculate total drops and bottles needed
- Supports one or both eyes/ears
- Accounts for frequency and treatment duration
- Uses standard 12 drops = 1mL conversion

## 🧬 Medications Included

### Analgesics
- Paracetamol 120mg/5mL and 250mg/5mL
- Ibuprofen 100mg/5mL

### Antibiotics
- Amoxicillin 125mg/5mL and 250mg/5mL
- Cefaclor 125mg/5mL
- Cefalexin 125mg/5mL and 250mg/5mL
- Co-amoxiclav 125–31.25mg/5mL and 250–62.5mg/5mL
- Cotrimoxazole 240mg/5mL
- Erythromycin 200mg/5mL and 400mg/5mL
- Flucloxacillin 125mg/5mL and 250mg/5mL
- Phenoxymethylpenicillin 125mg/5mL and 250mg/5mL
- Roxithromycin 150mg tablets

### Other Medications
- Prednisolone 5mg/1mL
- Lactulose
- Loratadine 1mg/1mL
- Macrogol 13.12g/sachet
- Ferrous sulphate 30mg/1mL
- Colecalciferol (Vitamin D) 188mcg/mL

## 🚀 How to Use

### Getting Started
1. **Download** the HTML file
2. **Open** in any modern web browser
3. **No installation required** - runs entirely in browser

### Using the Children's Medicine Calculator
1. **Select a category** (Analgesics, Antibiotics, or Other)
2. **Choose specific medication** from dropdown
3. **Enter child's weight** in kg
4. **Click Calculate** to see dose and volume ranges
5. **Optional**: Use reverse calculation by entering volume

### Special Features
- **Dose Ranges**: Shows min-max ranges (e.g., "195.0 - 390.0 mg (15-30 mg/kg)")
- **Weight Estimation**: Reverse calculations show weight ranges
- **Clinical Guidance**: Each medication includes complete NZF dosing information
- **Warning Messages**: Alerts for weight/age mismatches in special dosing scenarios

## 📱 Technical Details

### Browser Compatibility
- **Modern browsers**: Chrome, Firefox, Safari, Edge
- **Mobile responsive**: Works on tablets and smartphones
- **No internet required**: Fully offline after initial load

### Technology Stack
- **HTML5**: Structure and content
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: All calculations and interactions
- **No dependencies**: No external libraries required

### File Structure
```
pharmacy_calculator.html          # Main application file
├── CSS (embedded)               # Styling and responsive design
├── JavaScript (embedded)       # All calculation logic
└── NZF Links                   # External reference links
```

## 🔧 Installation

### For End Users
1. Download the `pharmacy_calculator.html` file
2. Double-click to open in your default browser
3. Bookmark for easy access

### For Developers
1. Clone or download the HTML file
2. Open in any code editor for modifications
3. Test changes by refreshing browser

## ⚡ Key Calculation Examples

### Forward Calculation Example
**13kg child, Amoxicillin 125mg/5mL:**
- **Input**: Weight = 13kg
- **Output**: 
  - Dose range: 195.0 - 390.0 mg (15-30 mg/kg)
  - Volume range: 7.8 - 15.6 mL

### Reverse Calculation Example
**10mL Amoxicillin 125mg/5mL given:**
- **Input**: Volume = 10mL
- **Output**:
  - Dose: 250.0 mg
  - Estimated weight range: 8.3 - 16.7 kg (for 15-30 mg/kg range)

## 📚 Data Sources

All dosing information is sourced from the **New Zealand Formulary for Children (NZF)** with direct links to official references:
- https://nzfchildren.org.nz/
- Each medication includes live NZF reference links
- Dosing guidelines current as of 2025

## ⚠️ Important Notes

### Clinical Use
- **For pharmacy professionals** trained in pediatric dosing
- **Double-checking tool** - not a replacement for clinical judgment
- **Always verify** against current NZF guidelines
- **Maximum doses** are enforced in calculations

### Limitations
- **New Zealand specific** dosing guidelines
- **Pediatric focus** (1 month - 18 years)
- **Does not replace** clinical assessment
- **No drug interaction checking**

## 🛠️ Customization

### Adding New Medications
1. Add option to appropriate dropdown
2. Create calculation form HTML
3. Add calculation function in JavaScript
4. Include NZF dosing information

### Modifying Doses
1. Locate medication function in JavaScript
2. Update mg/kg values as needed
3. Modify maximum dose limits
4. Update dosing information text

## 📞 Support

### For Technical Issues
- Email: suggestions@pharmacy-calculator.com
- Report bugs or request features
- Provide feedback on usability

### For Clinical Questions
- Consult NZF guidelines directly
- Contact prescribing physician
- Seek clinical pharmacist advice

## 🤝 Contributing

### Suggestions Welcome
- New medication requests
- Dose range updates
- UI/UX improvements
- Bug reports

### Development Guidelines
- Maintain NZF compliance
- Test all calculations thoroughly
- Keep mobile responsiveness
- Document any changes

## 📄 License

This calculator is provided for **educational and professional use** by qualified pharmacy professionals. 

### Terms of Use
- **Free for pharmacy use**
- **No warranty provided**
- **Users responsible for accuracy verification**
- **NZF guidelines remain authoritative**

## 🏆 Acknowledgments

- **New Zealand Formulary for Children** for dosing guidelines
- **Claude AI (Anthropic)** for application development
- **Pharmacy professionals** for clinical input and testing

## 📊 Version History

### v1.0 (Current)
- Complete pediatric medication calculator
- Insulin and eyedrop calculators
- Dose range calculations
- Mobile responsive design
- Full NZF integration

---

**Built with ❤️ for pharmacy professionals**

*Always verify dosing with current NZF guidelines and clinical judgment*
