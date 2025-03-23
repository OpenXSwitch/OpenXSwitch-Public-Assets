## **OpenXSwitch Public Assets Documentation**  

Welcome to the **OpenXSwitch Assets Repository**! This documentation provides a structured overview of how to access and use OpenXSwitch's **icons, logos, and coin assets** hosted on our CDN.

---

### **📌 Base URL**  
All assets are hosted under:  
```
https://cdn.openxswitch.com/
```

---

## **📁 Directory Structure**  

### **1🔹 Icons (Favicon & General Icons)**
```
/public/icons/
```
- Contains OpenXSwitch-specific **icons** such as favicons and UI icons.  
- Example URL:  
  ```
  https://cdn.openxswitch.com/public/icons/favicon.png
  ```

---

### **2🔹Crypto Logos**
Logos for various coins are available in **multiple sizes** and **SVG format**.

#### **1️⃣ PNG Logos (Sized Assets)**
```
/public/logos/{size}/{coin}.png
```
- Logos are available in the following sizes: **16px, 32px, 64px, 128px**  
- Example URLs:
  ```
  https://cdn.openxswitch.com/public/logos/16/btc.png
  https://cdn.openxswitch.com/public/logos/64/usdt.png
  https://cdn.openxswitch.com/public/logos/128/eth.png
  ```

#### **2️⃣ SVG Logos (Scalable Assets)**
```
/public/logos/svg/{coin}.svg
```
- For scalable vector logos.  
- Example URLs:
  ```
  https://cdn.openxswitch.com/public/logos/svg/btc.svg
  https://cdn.openxswitch.com/public/logos/svg/usdt.svg
  ```

---

## **📜 Supported Sizes**
For PNG logos, the available sizes are:  
✅ `16px`  
✅ `32px`  
✅ `64px`  
✅ `128px`  

For **SVG logos**, the size is **dynamic** and can be used at any resolution.

---

## **📌 Usage Examples**
### **🔹 HTML Example**
```html
<img src="https://cdn.openxswitch.com/public/logos/64/btc.png" alt="Bitcoin Logo" width="64" height="64">
```

### **🔹 CSS Example**
```css
.logo {
    background-image: url('https://cdn.openxswitch.com/public/logos/svg/usdt.svg');
    width: 64px;
    height: 64px;
    background-size: contain;
}
```

### **🔹 JavaScript Example**
```js
const logoUrl = "https://cdn.openxswitch.com/public/logos/128/eth.png";
document.getElementById("crypto-logo").src = logoUrl;
```
---
### **📢 License & Usage**
All assets are **owned by OpenXSwitch** and may be used for **non-commercial and OpenXSwitch-integrated applications**. Redistribution or modification without permission is **prohibited**.

---

💡 **Need help?** Contact us at **support@openxswitch.com**! 🚀
