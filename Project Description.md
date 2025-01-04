### **Simple Documentation for Electronic Shelf Label (ESL) System**

#### **What is an ESL?**

An Electronic Shelf Label (ESL) system is a digital price tag that can be placed on store shelves to show the prices of products. Instead of using paper labels, the prices are displayed on small digital screens and can be updated remotely through the internet.

#### **Components**

* **ESP8266/ESP32:** A small, Wi-Fi-enabled chip that connects to the internet and gets the prices.  
* **Firebase Realtime Database:** An online database where the prices are stored.  
* **20x4 LCD Screen:** A small screen that shows the prices of products like meat, chicken, hotdogs, and burgers.  
* **Wi-Fi Network:** Allows the ESP8266/ESP32 to connect to Firebase and get the latest prices.

#### **How It Works**

1. **Connect to Wi-Fi:**  
   * The ESP8266/ESP32 connects to the store’s Wi-Fi network.  
2. **Get Prices from Firebase:**  
   * The ESP8266/ESP32 fetches the latest prices for each product from Firebase.  
3. **Show Prices on LCD:**  
   * The fetched prices are displayed on the 20x4 LCD screen, with each line showing a different product and its price.

#### **Why Use an ESL?**

* **Quick Updates:** Prices can be changed instantly from a central location without needing to replace paper tags.  
* **Saves Time:** No need for staff to manually update prices on shelves.  
* **Always Accurate:** Ensures customers see the correct price at all times.

#### **Where It Can Be Used**

* **Retail Stores:** For displaying product prices on shelves.  
* **Supermarkets:** To quickly update prices during sales or promotions.

This ESL system makes managing prices in a store much easier and more efficient.

