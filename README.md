# 🔐 Blockchain-Based QR Code Authentication System

## 🌟 Eliminating Counterfeits, Ensuring Authenticity

### 🎯 Project Overview

This innovative project leverages blockchain technology to authenticate supply chain products and eliminate counterfeits. By converting product details and barcodes into tamper-proof digital signatures stored on a blockchain, we create a robust system that doesn't rely on potentially unreliable third parties.

### 🔑 Key Features

- 🔗 **Blockchain-Powered Security**: Utilizes blockchain's tamper-proof nature for secure data storage.
- 🖋️ **Digital Signature Generation**: Converts product barcodes into unique digital signatures.
- 🌐 **Decentralized Verification**: Eliminates the need for trusted third parties in the authentication process.
- 🖥️ **User-Friendly GUI**: Easy-to-use Tkinter interface for interacting with the system.
- 🕵️ **Counterfeit Detection**: Quickly identifies fake or cloned barcodes.

### 🛠️ Modules

1. **Save Product with Blockchain Entry**: 
   - Enter product details
   - Upload barcode image
   - Generate and store digital signature in the blockchain

2. **Retrieve Product Data**: 
   - Search existing product details using product ID

3. **Authenticate Scan**: 
   - Upload original or potentially fake barcode images
   - Verify digital signatures against blockchain records
   - Display authentication results

### 🚀 Getting Started

1. Ensure you have Python 3.x installed
2. Clone this repository
   ```
   git clone https://github.com/yourusername/blockchain-qr-auth.git
   ```
3. Install required dependencies
   ```
   pip install -r requirements.txt
   ```
4. Run `run.bat` to start the application

### 📊 How It Works

1. **Data Storage**: Each product's details and barcode are converted into a digital signature and stored in a blockchain block.
2. **Verification Process**: The system verifies all previous blocks' hash codes before adding a new transaction.
3. **Authentication**: When scanning a product, the system compares the scanned barcode's signature with stored blockchain data.

### 🎓 Use Case: Academic Certificates

This system can be applied to authenticate academic certificates, preventing forgery of educational credentials. It ensures the integrity and authenticity of important documents.

### 💻 Technical Details

- **Programming Language**: Python 3.x
- **GUI Framework**: Tkinter
- **Blockchain Implementation**: Custom implementation
- **Barcode Processing**: hashlib(SHA-256)


### 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 📞 Contact

For any queries or suggestions, please [open an issue](https://github.com/BinaryBrain45/BreadcrumbsBlockchain-Based-Product-Authentication/issues) or contact [here](mailto:padyala.jayaprakash@gmail.com).

---
