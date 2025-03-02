# Currency Converter

A simple web-based Currency Converter built using **Django**, **HTML**, and **CSS**. This project allows users to convert currency values between different international currencies using real-time exchange rates.

## Features
- Convert between multiple currencies
- Fetch real-time exchange rates via an API
- User-friendly interface
- Responsive design using HTML & CSS

## Technologies Used
- **Backend:** Django
- **Frontend:** HTML, CSS
- **API:** Exchange rate API (e.g., exchangeratesapi.io, Open Exchange Rates, etc.)

## Installation & Setup

### Prerequisites
Make sure you have **Python** and **pip** installed.

### Steps to Run the Project
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/your-username/currency-converter.git
   cd currency-converter
   ```
2. **Create a Virtual Environment:**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Set Up API Key (if required)**
   - Sign up for a currency exchange API and get an API key.
   - Add your API key in Django settings or an environment variable.
   
5. **Run Migrations:**
   ```sh
   python manage.py migrate
   ```
6. **Start the Development Server:**
   ```sh
   python manage.py runserver
   ```
7. Open your browser and visit `http://127.0.0.1:8000/`


## Usage
- Select the currency you want to convert from and to.
- Enter the amount to convert.
- Click on the **Convert** button to get the exchange value.

## Contributing
Feel free to fork this repository and contribute improvements. To contribute:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License
This project is licensed under the MIT License.

---
**Author:** Your Name  
**GitHub:** [Your GitHub Profile](https://github.com/Darshh16)

