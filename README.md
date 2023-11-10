# Preprosessing
1. menghapus missing value
2. menghapus duplicate data
3. quantity dijumlah dengan minusnya

total harga = quantity * price (groupby Month-Year) terus di sum
contoh sum: df_surplus.groupby(['Month-Year', "ProductName"])['Quantity'].sum().reset_index()


total penjualan per item per bulan
generate korelasi tiap attribute pake pearson correlation

produk name pake produkno untuk regresi
final bikin model regresi dengan quantity
tren 1 bulan kedepan (regresi linear)


# Link Dataset Kaggle
https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business

# Inspiration

Information is a main asset of businesses nowadays. The success of a business in a competitive environment depends on its ability to acquire, store, and utilize information. Data is one of the main sources of information. Therefore, data analysis is an important activity for acquiring new and useful information. Analyze this dataset and try to answer the following questions.

    1. How was the sales trend over the months?
    2. What are the most frequently purchased products?
    3. How many products does the customer purchase in each transaction?
    4. What are the most profitable segment customers?
    5. Based on your findings, what strategy could you recommend to the business to gain more profit?

