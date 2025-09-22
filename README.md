# Postest-PBO-3

## Manajemen Tiket Event Cosplay

Program ini adalah aplikasi console berbasis Java untuk mengelola tiket acara cosplay.
Fitur utama program adalah CRUD (Create, Read, Update, Delete) dengan tambahan Search.

Program dikembangkan dengan tambahan:

- Encapsulation : atribut dibuat private, akses lewat getter & setter.

- Inheritance : terdapat satu superclass (Ticket) dan dua subclass (RegularTicket, VipTicket).

- Overriding : subclass menimpa method info() untuk menampilkan label sesuai jenis tiket.

**Encapsulation**

Semua atribut Ticket (id, name, date, status) dibuat private. Data hanya bisa diakses lewat getter & setter. Contoh:

<img width="450" height="450" alt="image" src="https://github.com/user-attachments/assets/1c22c5d4-af01-4f85-b366-d6355b07e582" />

**Inheritance**

RegularTicket dan VipTicket dibuat dengan extends Ticket. Keduanya mewarisi atribut dan method dari superclass.

<img width="537" height="41" alt="image" src="https://github.com/user-attachments/assets/6b88c707-3cdd-423a-94d9-65a82bb0bf49" />

<img width="491" height="28" alt="image" src="https://github.com/user-attachments/assets/0c1f7fec-e78c-457c-bddd-44fb8f393195" />

**Overriding**

Subclass RegularTicket dan VipTicket mewarisi Ticket lalu menimpa (override) method info() agar menambahkan label sesuai jenis tiket.

<img width="350" height="349" alt="image" src="https://github.com/user-attachments/assets/a515c927-712a-4879-bb7e-afbcae138500" />

<img width="350" height="352" alt="image" src="https://github.com/user-attachments/assets/5c8c11b9-28a2-48a6-95ba-847445cb4d62" />
