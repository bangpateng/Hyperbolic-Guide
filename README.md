# Hyperbolic Guide on How to Buy a Hyperbolic GPU and Use It

Hyperbolic menyediakan akses ke penyewaan GPU yang terjangkau dan on-demand, dengan potensi memotong biaya komputasi AI hingga 75%. Instans GPU tersedia dalam waktu kurang dari satu menit.

### 1. Buat Account
![h1](https://github.com/user-attachments/assets/93d7ec82-20bf-41d9-b278-8e5fd2496fd1)

- Buat Akun Hyperbolic : https://app.hyperbolic.xyz/invite/7o4gdedCm
- Daftar Menggunakan Email > Verifikasi Email
- Login

**Noted :** Jika Kamu Melakukan $5 Deposit Pertamamu, Kamu Mendapatkan Credit $6

### 2. Cara Isi Balance Dengan Crypto

![h2](https://github.com/user-attachments/assets/0d73ba02-f486-4214-ad04-7f380ce03ef4)

- Click Billing dan Bergulir kebawah
- Click Wallet Address > Masukan Address Metamask Kamu (EVM) > Add
- Kamu Bisa Melakukan Deposit Dari Address Kamu Yang Sudah Terdaftar ke Alamat Deposit Hyperbolic Yang Tersedia di Website
- Deposit Hanya Bisa Menggunakan USDC, USDT, or DAI
- Tunggu 1-3 Menit, Tunggu Saldo Anda Bertambah di Akun
- Selesai

### 3. Cara Sewa GPU di Hyperbolic

![h3](https://github.com/user-attachments/assets/0e2eeab9-2f4c-45a0-b0cc-8589de2f529c)

- Click Home
- Cari GPU Yang Ingin Kamu Sewa
- Click `Rent`

![h4](https://github.com/user-attachments/assets/aa9e8e25-bf66-4c74-bd5a-c7c3ce90116c)

- Confirm Rental

![h5](https://github.com/user-attachments/assets/3a2d89cf-3f22-4be9-a6f0-76e0f8e6278d)
![h6](https://github.com/user-attachments/assets/38574c17-3192-41ca-a011-a99dcf53ae39)

- Click GPU Anda Yang Sudah Aktif
- Kamu Akan Melihat SSH Yang Kamu Dapatkan
- Simpan

**Noted :** Untuk Berhenti Sewa GPU Kamu Bisa Click `Terminted Instanced`

## Cara Menggunakan GPU di Powershell Windows dan VPS

### 1. Cara Menggunakan GPU di Powershell Windows/CMD

![h7](https://github.com/user-attachments/assets/92224a25-1d23-43d3-83ab-71bf913a0917)

```
ssh-keygen -t rsa -b 4096
```

- Arahakan Tempat Penyimpannya Contoh Saya Arahkan ke Folder saya di C:\Users\Bang Pateng/.ssh/id_rsa
- Masukan Password 2x
- Kamu Akan Melihat Tampilan Seperti di Atas
- Perhatikan Arah Folder Pubkey Kamu

![h8](https://github.com/user-attachments/assets/188efa9c-e011-4a8a-9e5f-8865b9de21f6)

```
Get-Content "C:\Users\Bang Pateng\.ssh\id_rsa.pub"
```

![h9](https://github.com/user-attachments/assets/41f95a5c-f76d-47bc-a54e-e70c8c48b677)

- Ambil SSH Rsa Pub Kamu
- Copy Semua dan Paste ke https://app.hyperbolic.xyz/settings
- Scroll > Paste dan Save
- Done

![h11](https://github.com/user-attachments/assets/7ef851a2-9865-4c57-9040-8aaf2d1f82e4)

- Paste SSH GPU Hyperbolic Kamu di Powershell/CMD
- Example : `ssh ubuntu@sturdy-bousabanirus-Cakirae.1.cricket.hyperbolic.xyz -p 31716`
- Click `Yes`
- Masukan Password Saat Kamu Buat RSA tadi
- Tara, Sekarang GPU Kamu Sudah Berhasil di Gunakan

### 2. Cara Menggunakan GPU di VPS

![h1](https://github.com/user-attachments/assets/37e11a1c-dea9-4e09-ad3e-f9ac11ab304f)

- Buka VPS Kamu

```
ssh-keygen -t rsa -b 4096
```
```
/root/.ssh/id_rsa
```

- Masukan Password 2x

![h2](https://github.com/user-attachments/assets/68c41122-a0cd-44a7-ae7e-1caea462732d)

```
cat /root/.ssh/id_rsa.pub
```
![h9](https://github.com/user-attachments/assets/41f95a5c-f76d-47bc-a54e-e70c8c48b677)

- Ambil SSH Rsa Pub Kamu
- Copy Semua dan Paste ke https://app.hyperbolic.xyz/settings
- Scroll > Paste dan Save
- Done

![h3](https://github.com/user-attachments/assets/0e2eeab9-2f4c-45a0-b0cc-8589de2f529c)

- Click Home
- Cari GPU Yang Ingin Kamu Sewa
- Click `Rent`

![h4](https://github.com/user-attachments/assets/aa9e8e25-bf66-4c74-bd5a-c7c3ce90116c)

- Confirm Rental

![h5](https://github.com/user-attachments/assets/3a2d89cf-3f22-4be9-a6f0-76e0f8e6278d)
![h6](https://github.com/user-attachments/assets/38574c17-3192-41ca-a011-a99dcf53ae39)

- Click GPU Anda Yang Sudah Aktif
- Kamu Akan Melihat SSH Hyperbolic Yang Kamu Dapatkan
- Paste Ke VPS

![ss2](https://github.com/user-attachments/assets/ab4fd5ba-92a8-466c-910d-955dd2e90479)

- Click `Yes`
- Masukan Password SSH Rsa Kamu
- Tara Sudah Aktif Dan Dapatkan Kamu Gunakan Untuk Garap Node / Mining
- Selesai
















