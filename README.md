# praktikum8
Nama : Endang Sirait

NIM : 312310588

![Screenshot 2024-12-04 173658](https://github.com/user-attachments/assets/ef96274e-3e97-43d7-be38-5ee442d06d80)

# Buat code  java dari diagram class berikut :
# INPUT
# Class Customer
![code](https://github.com/user-attachments/assets/0014167f-ff52-499e-88e6-6e8cffccaf3a)
# Penjelasan:
1. Kelas Customer didefinisikan dengan deklarasi private final String name;dan private final String address;, yang berarti properti namedan addressbersifat pribadi dan final (tidak dapat diubah setelah inisialisasi).
2. Konstruktor public Customer(String name, String address)menginisialisasi properti namedan addresssaat objek baru Customerdibuat.
3. Metode ini public String getName()mengembalikan nameproperti objek Customer.
4. Metode ini public String getAddress()mengembalikan addressproperti objek Customer


# Class Item
![code 4](https://github.com/user-attachments/assets/04687d6c-3612-4672-bf80-f7f3becef5e1)
# Penjelasannya
1 Kelas tersebut Itemmemiliki beberapa variabel instan privat: shippingWeight, description, price, dan taxRate.
2. Konstruktor public Item(String shippingWeight, String description, float price, float taxRate)menginisialisasi properti ini ketika Itemobjek baru dibuat.
3. Metode ini public Item(String shippingWeight, String description, float price, float taxRate)menetapkan nilai properti shippingWeight, description, price, dan taxRate.
4. Metode ini public float getPriceForQuantity(int quantity)menghitung harga total untuk jumlah barang tertentu dengan cara mengalikan pricedengan quantity.
5. Metode ini public float getTax()menghitung jumlah pajak untuk barang berdasarkan pricedan taxRate.
6. Metode ini public boolean inStock()mengembalikan boolean yang menunjukkan apakah item tersedia atau tidak.
7. Metode public String getShippingWeight()dan public String getDescription()menyediakan akses ke properti shippingWeightdan description, masing-masing.

# Class Order
![code 2](https://github.com/user-attachments/assets/32c22f8e-6d0d-4c8d-8617-26d729632349)

# Class OrderDetail
![code 3](https://github.com/user-attachments/assets/1c2cb21b-8c5f-4b3b-b7ad-cd08aef8c505)

# Class Payment
![code 5](https://github.com/user-attachments/assets/d3e37d29-719b-4fa3-b258-cf5e98cbcff0)

# Class Main
![code 6](https://github.com/user-attachments/assets/74a309ea-9ea0-44fd-81c6-64a691851128)

# OUTPUT
![Screenshot 2024-12-05 001740](https://github.com/user-attachments/assets/a4615676-05d5-4aaf-8bcb-16377255ed40)








