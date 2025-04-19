# Simple Storage Smart Contract (Solidity)

Ini adalah proyek smart contract pertama saya menggunakan bahasa Solidity. Kontrak ini sangat sederhana dan bertujuan untuk menjadi dasar pertama saya di dunia blockchain.

## Deskripsi

Kontrak `SimpleStorage.sol` digunakan untuk:
1. Menyimpan sebuah angka bulat positif (`uint`) di blockchain.
2. Mengambil kembali angka yang telah disimpan.

## Fungsi Utama

* `store(uint _newValue)`: Fungsi publik untuk menyimpan atau memperbarui nilai. Membutuhkan satu argumen berupa angka (`uint`).
* `retrieve() public view returns (uint)`: Fungsi publik untuk membaca nilai yang tersimpan saat ini. Tidak memerlukan argumen dan tidak mengubah state (view).
* `storedData (public variable)`: Variabel state publik yang menyimpan nilai `uint`. Nilainya bisa langsung dibaca karena bersifat `public`.

## Cara Menjalankan/Menguji

Kontrak ini dapat dikompilasi dan diuji dengan mudah menggunakan [Remix IDE](https://remix.ethereum.org/):
1. Buka Remix IDE di browser masing-masing
2. Buat file baru `SimpleStorage.sol` dan salin kode dari repository berikut
3. Buka tab "Solidity Compiler", pilih versi compiler yang sesuai (misal `0.8.20` atau lebih tinggi), dan klik "Compile"
4. Buka tab "Deploy & Run Transactions", pilih environment "Remix VM"
5. Klik "Deploy"
6. Interaksi dengan kontrak yang sudah di-deploy menggunakan tombol-tombol yang muncul (`store`, `retrieve`, `storedData`).

## Tujuan Proyek

Proyek ini dibuat sebagai bagian dari dasar Solidity dan smart contract development, serta menjadi langkah awal saya di Web3.
