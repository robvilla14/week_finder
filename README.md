# Week Finder

A mobile-friendly ISO 8601 week calculator designed specifically for home inspectors to determine equipment manufacture dates from serial numbers.

## Features

- **ISO 8601 Compliant** - Follows international week numbering standards
- **Mobile Optimized** - Responsive design for field use
- **Dark Mode** - Toggle for various lighting conditions
- **Equipment Focus** - Designed for HVAC and water heater serial number dating
- **Year Range** - Supports years 1950-2030
- **Week Validation** - Automatically handles 52/53 week years
- **Instant Results** - No page reload needed

## Use Case

Home inspectors often need to determine equipment age from serial numbers. Many manufacturers use week-based dating codes (e.g., positions 1-2 for week, 3-4 for year). This tool converts those week numbers into actual calendar dates.

## Usage

1. Open the Week Finder
2. Select year and week number from dropdowns
3. Click "Find Week" to see the date range
4. Use "Clear" to reset for next lookup
5. Toggle dark mode with the 🌙/☀️ button

## Technical Details

- **Standard**: ISO 8601 week date system
- **Week Start**: Monday
- **Week 1 Rule**: First week containing January 4th
- **Cross-year Handling**: Properly manages weeks spanning December/January

## Live Demo

https://robvilla14.github.io/week_finder/

## Contributing

Pull requests welcome! Please open an issue first to discuss changes.

## License

MIT License - see LICENSE file for details.
