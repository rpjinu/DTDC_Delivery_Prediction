# DTDC_Delivery_Prediction
visualization and modeling!  ---  **Happy Analyzing! 🚀**

<img src="https://github.com/rpjinu/DTDC_Delivery_Prediction/blob/main/download.jpeg" width=500>

# 📦 DTDC Courier Dataset

A real-world courier shipment dataset from **DTDC** operations across 🇮🇳 **India**. This dataset captures the **end-to-end journey** of parcels — from booking to delivery — making it a valuable resource for **analytics, machine learning**, and **logistics research**.

---

## 📄 Dataset Overview

Each row represents a **courier consignment** booked via DTDC, including:

- 📍 Pickup & Delivery Details (City, Pincode, State)  
- ⚖️ Shipment Weights (Actual, Volumetric, Chargeable)  
- 🚚 Delivery Mode & Tariff Breakdown  
- ✍️ Signatures, 📅 Timestamps, and 🧾 GST Details  
- 📃 Nature of Parcel (Documents or Non-Documents)

---

## 🔍 Sample Use Cases

- 🗺️ **Route Optimization**  
- ⏳ **Delivery Time Prediction**  
- 💰 **Tariff Modeling**  
- 🏘️ **Last-Mile Delivery Analytics**  
- 🗾 **Geospatial Heatmaps of Courier Demand**

---

## 🧾 Column-Wise Schema

| Column Name              | Description |
|--------------------------|-------------|
| 🏙️ **Origin** | City from which the parcel was dispatched |
| 🏙️ **Destination** | City where the parcel is to be delivered |
| 🆔 **Pouch No** | Internal unique shipment group ID |
| 📆 **Date** | Booking date (Excel serial format) |
| 👤 **Sender's Name** | Name of sender |
| ☎️ **Sender Phone** | Sender's contact number |
| 📬 **Sender Address** | Full sender address |
| 🏙️ **Sender City** | City of the sender |
| 🏞️ **Sender State** | State of the sender |
| 🔢 **Sender Pincode** | 6-digit postal code |
| 🧾 **Sender GSTIN** | GST ID of sender (if any) |
| 📦 **Total Pieces** | Number of parcels in the shipment |
| ⚖️ **Actual Wt** | Actual weight in kg |
| 📐 **Volumetric Wt** | Volume-based weight |
| 💳 **Chargeable Wt** | Billed weight (max of actual/volumetric) |
| 📄 **Paperwork** | Whether paperwork was submitted (Yes/No) |
| ✍️ **Sender Signature** | Dispatch signature by sender (Yes/No) |
| 📅 **Sender Date** | Date sender signed (Excel format) |
| 👤 **Recipient Name** | Name of recipient |
| ☎️ **Recipient Phone** | Contact of recipient |
| 📬 **Recipient Address** | Full delivery address |
| 🏙️ **Recipient City** | City of recipient |
| 🏞️ **Receiver State** | State of recipient |
| 🔢 **Receiver Pincode** | ZIP code of recipient |
| 🧾 **Description** | Description of contents |
| 🚀 **Value Added Services** | Optional services (insurance, fragile, express) |
| 🔍 **Consignment No** | Official tracking number |
| ⌛ **Expiry Date** | Last valid delivery date (Excel format) |
| 🏢 **Booking Code** | Branch/Counter booking code |
| 🧾 **Recipient GSTIN** | GST ID of the recipient |
| 🧍 **Receiver Name** | Duplicate or alternate recipient field |
| 🤝 **Relationship** | Receiver's relation to recipient (e.g., Self, Staff) |
| 🏢 **Company Stamp** | Whether a stamp was used (Yes/No) |
| ✍️ **Receiver Signature** | Recipient's delivery signature (Yes/No) |
| 📅 **Receive Date** | Parcel received date (Excel format) |
| 💵 **Tariff** | Base delivery charge (₹) |
| ➕ **VAS Charges** | Extra fees for add-on services |
| 💰 **Total Amount** | Total billing amount (Tariff + Add-ons) |
| 🚚 **Mode** | Shipment mode (Surface / Air / Express) |
| ⚠️ **Risk Surcharge** | Liability bearer (Owner/Carrier) |
| 💳 **Mode of Payment** | Payment method (Cash, UPI, Card, etc.) |
| 📦 **Nature of Consignment** | "Dox" (Documents) or "Non-Dox" (Goods) |

---

## 📊 Ideal For

- Data Science Projects 🔬  
- Logistics & Supply Chain Research 🚛  
- ML Model Training 📈  
- EDA, Visualization & Dashboards 📉  

---

## 📝 License

For educational and research use only. 📚 Please cite the dataset source (if applicable) and DTDC for original logistics data format inspiration.

---

## 🤝 Contributing

Feel free to open issues or pull requests to improve documentation, suggest use cases, or extend support for visualization and modeling!

---

**Happy Analyzing! 🚀**
