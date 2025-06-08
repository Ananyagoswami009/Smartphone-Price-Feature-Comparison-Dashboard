# Smartphone Price & Feature Comparison Dashboard

## Overview

The **Smartphone Price & Feature Comparison Dashboard** is an interactive Tableau dashboard designed to help consumers compare essential smartphone features such as 5G, RAM, processor speed, and price. This tool empowers users to make informed purchasing decisions by visualizing various features and their price points. It also aids businesses in identifying market trends, optimizing product offerings, and adjusting pricing strategies based on competitive analysis and consumer feedback. The dashboard also provides insights into customer satisfaction, helping companies improve products and craft targeted marketing strategies.

This project is useful for:
- **Consumers** who want to compare smartphone features and prices.
- **Businesses** looking to optimize their smartphone product offerings and pricing strategies.
- **Market Analysts** who wish to study the competition and identify trends in the smartphone market.

---

## Features

- **Feature Comparison**: Compare various features of smartphones such as 5G compatibility, RAM size, processor speed, and price.
- **Price Analysis**: Visual representation of smartphone prices across different brands and models.
- **Consumer Insights**: Insights into consumer satisfaction based on reviews and ratings.
- **Trends and Market Analysis**: Helps businesses identify trends in the smartphone market and adjust their strategies accordingly.
- **Interactive Filters**: Users can filter data based on brand, model, price range, RAM, processor type, and other features.

---

## Dataset

The dataset used for this dashboard is named **`smartphones.csv`** and contains data related to various smartphones available in the market. The dataset includes the following columns:

- **Brand**: The brand name of the smartphone (e.g., Apple, Samsung, Xiaomi).
- **Model**: The specific model of the smartphone (e.g., iPhone 12, Samsung Galaxy S21).
- **Price**: The price of the smartphone in USD.
- **RAM**: The RAM size of the smartphone in GB.
- **Processor**: The type and speed of the smartphone's processor.
- **5G**: Whether the smartphone supports 5G technology (Yes/No).
- **Rating**: The consumer rating (out of 5 stars).
- **Review Count**: The number of reviews submitted for the smartphone.
- **Launch Year**: The year the smartphone was launched.

**Note:** The dataset is structured in a way that enables easy filtering, sorting, and comparison of smartphone features.

### Example Data:

| Brand   | Model          | Price | RAM (GB) | Processor  | 5G | Rating | Review Count | Launch Year |
|---------|----------------|-------|----------|------------|-----|--------|--------------|-------------|
| Apple   | iPhone 12      | 799   | 4        | A14 Bionic | Yes | 4.5    | 1000         | 2020        |
| Samsung | Galaxy S21     | 799   | 8        | Exynos 2100| Yes | 4.7    | 1500         | 2021        |
| Xiaomi  | Mi 11          | 749   | 8        | Snapdragon 888 | Yes | 4.3  | 1200         | 2021        |

---

## Requirements

To use the **Smartphone Price & Feature Comparison Dashboard**, you'll need the following:

- **Tableau Desktop** or **Tableau Public**: To view and interact with the dashboard.
- **CSV Dataset**: `smartphones.csv` (included in the repository).
- **Web Browser**: To interact with Tableau Public, if shared online.

---

## Installation

### Steps to Set Up the Project Locally:

1. **Download Tableau Desktop**:
   - Visit [Tableau's official website](https://www.tableau.com/products/desktop) to download and install Tableau Desktop.
   
2. **Clone the Repository**:
   - Clone the repository to your local machine by using the following command:
     ```bash
     git clone https://github.com/yourusername/smartphone-price-feature-comparison-dashboard.git
     ```
   
3. **Open the Tableau Workbook**:
   - Open the `.twb` or `.twbx` file in Tableau Desktop to view and interact with the dashboard.
   
4. **Load the Dataset**:
   - Ensure the `smartphones.csv` dataset is loaded correctly into Tableau, or replace the data source if required.

---

## Usage

Once the project is set up, you can:

- **Filter Smartphones**: Use the interactive filters to view smartphones based on criteria like brand, price range, RAM, 5G support, etc.
- **View Comparisons**: Compare features and prices across multiple smartphone models.
- **Analyze Consumer Feedback**: Gain insights into customer ratings and reviews for different models.
- **Identify Trends**: View price trends across different brands and models over time.

---

## Screenshots

![Dashboard Screenshot](https://github.com/Ananyagoswami009/Smartphone-Price-Feature-Comparison-Dashboard/blob/main/Smartphone%20dashboard%20.jpg)  
*Example screenshot of the Smartphone Price & Feature Comparison Dashboard.*

---

## Contribution

We welcome contributions to improve this dashboard and make it even more useful. If you have ideas for new features, improvements, or bug fixes, feel free to fork the repository and submit a pull request.

To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new pull request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Tableau**: For providing the platform to create the dashboard.
- **Dataset**: Smartphone pricing and feature data from various online sources.

