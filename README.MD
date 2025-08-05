# Buy A Coffee For Me

A simple and modern donation/payment page that allows users to support you by sending money via UPI or QR code.

## Features

- Clean, responsive design
- Choose payment method: UPI or QR code (PhonePe, Google Pay, etc.)
- Suggested amount buttons for quick selection
- Contact support form
- Easy to customize

## How It Works

1. **Select Payment Method:**  
   Choose between "Pay with QR" or "UPI Payment".

2. **Enter Amount:**  
   Enter any amount or use the quick-select buttons (₹25, ₹50, ₹100).

3. **Proceed:**  
   - If "Pay with QR" is selected, a QR code will be shown for scanning.
   - If "UPI Payment" is selected, a UPI ID will be displayed for manual payment.

4. **Contact Support:**  
   Users can contact you via the built-in support form.

## Folder Structure

```
buy-a-coffee-for-me-main/
│
├── index.html
├── static/
│   └── QR.jpg
└── README.md
```

## Setup

1. Place your QR code image in the `static` folder as `QR.jpg`.
2. Edit `index.html` to update your UPI ID and any text as needed.
3. Open `index.html` in your browser to use.

## Customization

- **Change UPI ID:**  
  Edit the UPI ID in the HTML file.

- **Change QR Code:**  
  Replace `static/QR.jpg` with your own QR code image.

- **Change Contact Form:**  
  The contact form uses [Formspree](https://formspree.io/) by default. Update the action URL if needed.

## License

MIT License

---

Made with ❤️ for creators who need a simple way to get support!