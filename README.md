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
1. Kelas tersebut Itemmemiliki beberapa variabel instan privat: shippingWeight,       description, price, dan taxRate.
   
2. Konstruktor public Item(String shippingWeight, String description, float price,    float taxRate)menginisialisasi properti ini ketika Itemobjek baru dibuat.
4. Metode ini public Item(String shippingWeight, String description, float price,     float taxRate)menetapkan nilai properti shippingWeight, description, price, dan     taxRate.
5. Metode ini public float getPriceForQuantity(int quantity)menghitung harga total untuk jumlah barang tertentu dengan cara mengalikan pricedengan quantity.
6. Metode ini public float getTax()menghitung jumlah pajak untuk barang berdasarkan pricedan taxRate.
7. Metode ini public boolean inStock()mengembalikan boolean yang menunjukkan apakah item tersedia atau tidak.
8. Metode public String getShippingWeight()dan public String getDescription()menyediakan akses ke properti shippingWeightdan description, masing-masing.

# Class Order
![code 2](https://github.com/user-attachments/assets/32c22f8e-6d0d-4c8d-8617-26d729632349)
# Penjelasannya
1. Kelas tersebut Ordermemiliki beberapa variabel instan privat: date, status, customer, dan orderDetails.
2. Konstruktor public Order(String date, String status, Customer customer, OrderDetail[] orderDetails)menginisialisasi properti ini ketika Orderobjek baru dibuat.
3. Metode ini public Order(String date, String status, Customer customer, OrderDetail[] orderDetails)menetapkan nilai properti date, status, customer, dan orderDetails.
4. Metode ini public float calcSubTotal()menghitung subtotal pesanan dengan mengulangi orderDetailsarray dan memanggil calcSubTotal()metode pada setiap OrderDetailobjek.
5. Metode ini public float calcTax()menghitung total pajak untuk pesanan dengan mengulangi orderDetailsarray dan memanggil calcTax()metode pada setiap OrderDetailobjek.
6. Metode ini public float calcTotal()menghitung total biaya pesanan dengan menambahkan subtotal dan jumlah pajak.
7. Metode ini public float calcTotalWeight()menghitung bobot total pesanan dengan mengulangi orderDetailsarray dan memanggil calcWeight()metode pada setiap OrderDetailobjek.
8. Metode public String getDate(), public String getStatus(), public Customer getCustomer(), dan public OrderDetail[] getOrderDetails()menyediakan akses ke properti terkait.
   
# Class OrderDetail
![code 3](https://github.com/user-attachments/assets/1c2cb21b-8c5f-4b3b-b7ad-cd08aef8c505)
# Penjelasannya
1. Kelas tersebut memiliki variabel instan privat quantity, taxStatus, dan item.
2. Konstruktor public OrderDetail(int quantity, String taxStatus, Item item)menginisialisasi properti ini ketika OrderDetailobjek baru dibuat.
3. Metode ini public OrderDetail(int quantity, String taxStatus, Item item)menetapkan nilai properti quantity, taxStatus, dan item.
4. Metode ini public float calcSubTotal()menghitung subtotal untuk detail pesanan dengan memanggil objek getPriceForQuantity()terkait Item.
5. Metode ini public float calcWeight()menghitung bobot untuk detail pesanan dengan memanggil objek getShippingWeight()terkait Itemdan mengalikannya dengan quantity.
6. Metode ini public float calcTax()menghitung pajak untuk detail pesanan dengan memanggil objek getTax()terkait Item.
7. Metode public int getQuantity(), public String getTaxStatus(), dan public Item getItem()menyediakan akses ke properti terkait.
   
# Class Payment
![code 5](https://github.com/user-attachments/assets/d3e37d29-719b-4fa3-b258-cf5e98cbcff0)
# Penjesannya
1. Kelas tersebut Paymentmemiliki protected float amount;deklarasi yang menjadikan amountproperti bersifat privat tetapi dapat diakses oleh subkelas.
2. Konstruktor public Payment(float amount)menginisialisasi amountproperti ketika Paymentobjek baru dibuat.
3. Metode ini public float getAmount()mengembalikan nilai properti amount.

# Class Main
![code 6](https://github.com/user-attachments/assets/74a309ea-9ea0-44fd-81c6-64a691851128)
# Penjelasannya
1. Dua Itemobjek dibuat - satu untuk "Keyboard" dan satu untuk "Mouse".
2. Dua OrderDetailobjek dibuat - satu untuk item "Kena Pajak" (Keyboard) dan satu untuk item "Kena Pajak" lainnya (Mouse).
3. Suatu Customerobjek dibuat dengan nama "Endang Medan".
4. Suatu Orderobjek dibuat dengan tanggal "2024-12-07", status "Sedang diproses", pelanggan, dan kedua OrderDetailobjek tersebut.
5. Nama pelanggan, tanggal pesanan, dan status pesanan dicetak ke konsol.
6. Suatu putaran mengulangi rincian pesanan, mencetak deskripsi item, kuantitas, harga per item, dan subtotal untuk masing-masing item.
7. Subtotal pesanan, pajak, total, dan berat total dicetak ke konsol.

# OUTPUT
![Screenshot 2024-12-05 001740](https://github.com/user-attachments/assets/a4615676-05d5-4aaf-8bcb-16377255ed40)








