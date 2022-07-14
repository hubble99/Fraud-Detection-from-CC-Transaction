Dalam kehidupan sehari-hari, Kartu Kredit digunakan untuk membeli jasa dan barang dalam transaksi online atau transaksi offline. Mendeteksi fraud, dimana transaksi kartu kredit tidak sah atau terindikasi penipuan merupakan suatu tantangan bagi lembaga perbankan agar dapat mengurangi kerugian. Pada dataset ini akan dilakukan analisa dan modeling data dari transaksi kartu kredit, khususnya terhadap fraud transaction.
Keterangan dataset:
accountNumber : nomor akun
customerId : id customer
creditLimit : maksimum limit kredit
availableMoney : limit available yang dapat dipakai
transactionDateTime : tanggal dan waktu terjadinya transaksi
transactionAmount : nilai transaksi
merchantName : nama merchant transaksi
acqCountry : negara asal tempat dikeluarkannya kartu kredit
merchantCountryCode : negara asal tempat merchant
posEntryMode : mode entry point of sales (baca ini sbg referensi : https://help.globalmerchantportal.com/en/code-glossary/pos-entry-modes (Links to an external site.))
posConditionCode : kondisi pada saat entry transaksi terjadi di point of sales (baca ini sbg referensi : https://www.mreports.com/documentation/ac/nonmerchant/80449.htm (Links to an external site.) )
merchantCategoryCode : kode kategori merchant transaksi
currentExpDate : Expiry date atau tanggal kadaluarsa kartu
accountOpenDate : tanggal dibukanya akun 
dateOfLastAddressChange : tanggal terakhir pergantian alamat 
cardCVV  : CVV yg ada pada kartu
enteredCVV : CVV yang dimasukkan pada saat transaksi
cardLast4Digits  : 4 digit terakhir pada kartu
transactionType : tipe transaksi 
isFraud : transaksi fraud/tidak fraud (target variable)
echoBuffer : - 
currentBalance : tagihan / jumlah limit yang terpakai
merchantCity : kota dari merchant
merchantState : state dari merchant
merchantZip : zipcode dari merchant
cardPresent : ada tidak nya kartu pada saat transaksi terjadi
posOnPremises : -
recurringAuthInd : -
expirationDateKeyInMatch : False -> Match, True -> Not Match
