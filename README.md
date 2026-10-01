# Product Lookup and Real-time Weather Application 🌤️📦

This project is an intuitive web application designed to provide users with the ability to look up product codes and check real-time weather information for cities located all over the globe.

---

## 🌟 Core Features

* **Product Lookup:** Users can enter a product code to search for detailed information. The application reads and parses data from an XML file to display the product's name, category, description, quantity, and unit price.
* **City Weather:** Allows users to enter a city name to view the current weather. This feature connects directly to the OpenWeatherMap API to extract and display the temperature (in °C), weather description, humidity, and wind speed.
* **Easy Navigation:** The homepage provides a straightforward navigation menu linking directly to the product search and weather lookup features.
* **Visual Design:** The interface is fully customized using CSS, utilizing the "Bebas Neue" font to deliver a modern and consistent user experience.

## 💻 Tech Stack

* **Core Languages:** HTML5, CSS3, Vanilla JavaScript.
* **Data Processing:**
  * Uses `DOMParser` in JavaScript to parse XML data (XML Parsing).
  * Uses the `fetch()` method to call the OpenWeatherMap API and process the retrieved data in JSON format.

## 🗂️ File Structure

The system operates based on 5 primary files working together:
* `index.html`: The homepage containing navigation links.
* `products.html`: The product information search page.
* `products.xml`: The file storing all product data in XML format.
* `weather.html`: The weather lookup page integrated with the OpenWeatherMap API.
* `style.css`: Manages the overall visual layout and design of the website.

## 🚀 Installation & Setup

**1. Clone the repository**

```bash
git clone [https://github.com/Ryan271991/Web_Weather_2025_IND](https://github.com/Ryan271991/Web_Weather_2025_IND.git)
```

**2. Run the application**
Because the application uses the fetch() method to load a local XML file and an external API, you need to run the project through a local server rather than opening the HTML files directly to avoid CORS errors.
* You can use the Live Server extension in Visual Studio Code.
* Alternatively, access the application via localhost (e.g., http://localhost:3000/index.html).
