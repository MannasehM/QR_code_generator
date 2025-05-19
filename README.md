# 🧾 QR Code Generator

A simple Python project to generate QR codes from any URL.

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/qr_code_generator.git
cd qr_code_generator
```

### 2. Create and Activate a Virtual Environment

Windows: 

```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux: 

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install qrcode Pillow
```

### 4. How to Use

Run the program:

```bash
python main.py
```

Then follow the interactive prompts:

```bash
Enter the website URL:
```
➡️ Type a full URL (e.g., https://www.example.com)

```bash
Enter a filename (e.g., qr.png):
```
➡️ Enter a valid image filename (e.g., qr.png, site_qr.jpg, etc.)

Your QR code will be saved in the project directory with the filename you provided.
You can open or scan it using any QR code scanner app.