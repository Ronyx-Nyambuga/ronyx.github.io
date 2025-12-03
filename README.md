# ronyx.github.io
Currency Converter

A simple, lightweight web-based currency converter that provides real-time exchange rates for over 160 world currencies.

Features

- Real-time Exchange Rates: Fetches live currency data from the Fixer.io API
- Extensive Currency Support: Convert between 160+ global currencies including major currencies (USD, EUR, GBP) and regional currencies
- Live Conversion: Automatic conversion as you type - no button clicks required
- Clean Interface: Simple, user-friendly design with dropdown menus for easy currency selection
- Instant Results: Real-time calculation with two decimal precision

 How to Use

1. Open `index.html` in any web browser
2. Enter the amount you want to convert in the top input field (default is 1)
3. Select your source currency from the first dropdown (default is USD)
4. Select your target currency from the second dropdown (default is KES - Kenyan Shilling)
5. The converted amount appears automatically in the bottom field

 Technical Details

- Built with: HTML, CSS, and vanilla JavaScript
- API: Fixer.io Currency Data API
- Method: XMLHttpRequest for API calls
- Calculation: Accurate conversion using real-time exchange rates

 Default Configuration

- Source currency: USD (US Dollar)
- Target currency: KES (Kenyan Shilling)
- Default amount: 1

 Supported Currencies

The converter supports all major world currencies including but not limited to:
- USD, EUR, GBP, JPY, CNY, INR, CAD, AUD
- African currencies: KES, ZAR, NGN, EGP, MAD
- Asian currencies: JPY, CNY, INR, KRW, THB
- And 150+ more...

 Note

This application requires an active internet connection to fetch real-time exchange rates from the Fixer.io API.
