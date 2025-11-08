## 📌 Ringkasan Proyek
Proyek ini adalah aplikasi CRUD berbasis Java Swing yang terhubung ke database PostgreSQL menggunakan JPA. 

Aplikasi menggunakan JTabbedPane untuk memisahkan data seperti Data Mahasiswa dan Data Prodi, serta mendukung import CSV untuk input data otomatis.

## 🎯 Tujuan Utama

✅ Menerapkan CRUD dengan Swing, JPA, dan EntityManager.

📂 Memisahkan pengelolaan data menggunakan tab agar rapi dan mudah digunakan.

🔗 Mengimplementasikan relasi tabel menggunakan JPA.
📥 Mengimpor data CSV untuk mempercepat input.
🧩 Menggabungkan OOP, GUI, dan database dalam satu sistem terpadu.
🧠 Penjelasan Konsep Penting

## 1. 🔒 Persistence
Persistence adalah kemampuan aplikasi untuk menyimpan data secara permanen ke database agar tidak hilang saat program ditutup.

## 2. 🧩 JPA (Java Persistence API)
JPA mempermudah pengelolaan data dengan ORM, sehingga kita bisa bekerja dengan objek Java tanpa menulis SQL manual.

Komponen penting:
🛠️ EntityManager (CRUD)
⚙️ Persistence Unit (konfigurasi database)

## 3. 🏷️ Entity & Anotasi
Entity = kelas Java yang mewakili tabel database.

Anotasi penting:
@Entity 🧱
@Table 📋
@Id 🔑
@Column 📌

## 4. 🚀 EntityManager

Digunakan untuk operasi:
➕ persist() tambah data
✏️ merge() update data
❌ remove() hapus data
🔍 find() ambil data

## 5. 📊 Integrasi CSV
Aplikasi bisa membaca file CSV menggunakan JFileChooser sehingga pengguna dapat mengimpor data dalam jumlah besar secara otomatis. Ini membuat input data lebih cepat dan praktis.

## IMPLEMENTASI SISTEM CRUD MULTI-TABEL BERBASIS JAVA SWING MENGGUNAKAN JPA DAN TAB CONTAINER

<img width="445" height="361" alt="image" src="https://github.com/user-attachments/assets/d1747380-97b0-4568-832d-63a7b6181cd3" />

1.	Buat projek baru dengan nama PertemuanKeduabelas.

<img width="917" height="635" alt="image" src="https://github.com/user-attachments/assets/e78ee0ad-518b-45e2-b04e-0bdf27f238a8" />

3.	Buat class jframe dengan DataMahasiswa dan buat designnya.

<img width="404" height="294" alt="image" src="https://github.com/user-attachments/assets/80c2cc10-8fdd-4c7f-8352-6b4e4f7b16ca" /> .
<img width="449" height="221" alt="image" src="https://github.com/user-attachments/assets/89a332d2-4b32-4e5c-baed-881e3419167d" />

4.	Kemudian buat Jdialog untuk proses CRUD dan designnya.
a.	Insert Mahasiswa

<img width="430" height="294" alt="image" src="https://github.com/user-attachments/assets/a7e4f758-f3f7-43b2-8003-cd420209ec74" />.
<img width="384" height="300" alt="image" src="https://github.com/user-attachments/assets/f026de16-2940-4dd2-9d1d-27d977bdded1" />

b.	Update Mahasiswa

<img width="431" height="297" alt="image" src="https://github.com/user-attachments/assets/683c9f37-400f-4076-81bf-ee7ad4020700" />.
<img width="378" height="297" alt="image" src="https://github.com/user-attachments/assets/1ddae00c-73d1-460f-85b4-e0ed53c6350c" />

c.	Delete Mahasiswa

<img width="439" height="300" alt="image" src="https://github.com/user-attachments/assets/bef9daed-8b6e-497b-85a1-7ae4f34f1de7" />
<img width="369" height="290" alt="image" src="https://github.com/user-attachments/assets/bcbf9615-f3de-4a8f-b48a-b7965e874b5f" />

d.	Insert Program Studi

<img width="438" height="298" alt="image" src="https://github.com/user-attachments/assets/6650d7b7-cfe0-494f-971c-25e6869fad53" />
<img width="381" height="236" alt="image" src="https://github.com/user-attachments/assets/ac7c0ca8-aa33-4b7f-8d19-16efe57f92ee" />

e.	Update Prodi

<img width="436" height="298" alt="image" src="https://github.com/user-attachments/assets/1a7e35c1-fd2f-4a67-b71f-16c48ed84531" />
<img width="389" height="237" alt="image" src="https://github.com/user-attachments/assets/f9ef6b48-19eb-44b3-8721-c36d7b834c5f" />

f.	Update Buku

<img width="442" height="300" alt="image" src="https://github.com/user-attachments/assets/e5c09146-4484-4691-980c-086163d95c12" />
<img width="388" height="237" alt="image" src="https://github.com/user-attachments/assets/19eaf7f9-5c1b-4a68-9e17-9e4ad2662788" />

4.	Kemudian, Buat jasper reportnya untuk mencetak laporannya.
a.	Mahasiswa

<img width="867" height="671" alt="image" src="https://github.com/user-attachments/assets/379aecda-f864-4cb6-8d7f-18b45b923ebb" />

b.	Prodi

<img width="861" height="687" alt="image" src="https://github.com/user-attachments/assets/c0eb8f84-7faa-417d-84b6-8316f2b111e2" />

5.	Buat Entity class, untuk menyambungkan ke database.

<img width="397" height="335" alt="image" src="https://github.com/user-attachments/assets/e30e9c83-7422-49c8-938c-2164c1f87630" />
<img width="446" height="299" alt="image" src="https://github.com/user-attachments/assets/adfea4d9-512d-450f-8a32-1d8ca5ef0c8f" />
<img width="383" height="258" alt="image" src="https://github.com/user-attachments/assets/d210cd75-8b59-4674-8f3f-3eb0b2ba2e4e" />
<img width="385" height="272" alt="image" src="https://github.com/user-attachments/assets/b5d7603d-672e-482a-b8ee-08a6d9388d0c" />
<img width="358" height="367" alt="image" src="https://github.com/user-attachments/assets/a44f1052-c93a-4b80-b7b8-c096014ebdf2" />

6.	Kemudian, pada class menuutama tambahkan kode.
a.	Import DataMahasiswa.java dan Import ReportConnection.java

<img width="538" height="398" alt="image" src="https://github.com/user-attachments/assets/f8f31bcf-a12d-4f94-99f2-8456fa732729" />

-	Import ReportConnection.java

<img width="581" height="198" alt="image" src="https://github.com/user-attachments/assets/5eb8ed51-fb7e-4e2a-8e48-6b38cd61c88f" />

b.	DataMahasiswa.java

<img width="724" height="420" alt="image" src="https://github.com/user-attachments/assets/a1600ae1-268a-46b6-a233-6444be6c87c4" />

c.	Connection JDBC untuk Print

<img width="599" height="369" alt="image" src="https://github.com/user-attachments/assets/2cbbe116-eab6-4243-9418-36c18c8ea48a" />

d.	LoadData

<img width="445" height="361" alt="image" src="https://github.com/user-attachments/assets/c9d77abe-2f6c-43ac-b7d5-fee74e25202b" />

e.	LoadKodeData

<img width="593" height="256" alt="image" src="https://github.com/user-attachments/assets/0eb476d7-0899-4959-ab8a-6776d08d758b" />

f.	Button Insert tabel Mahasiswa

private void btninset2ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        JDInsert1.setModal(true);
        JDInsert1.setSize(400, 300);
        JDInsert1.setLocationRelativeTo(this);
        JDInsert1.setVisible(true);
    }

g.	Button Update tabel Mahasiswa

<img width="561" height="328" alt="image" src="https://github.com/user-attachments/assets/e5b7fd5a-e2af-4008-a238-6b86185914b2" />

h.	Button Delete tabel Mahasiswa

<img width="565" height="384" alt="image" src="https://github.com/user-attachments/assets/deb7c297-2a54-4bf3-b4dd-637c494aa024" />

i.	Button Insert tabel Prodi

private void btninset2ActionPerformed(java.awt.event.ActionEvent evt) {                                          
        JDInsert2.setModal(true);
        JDInsert2.setSize(400, 300);
        JDInsert2.setLocationRelativeTo(this);
        JDInsert2.setVisible(true);
    }

j.	Button Update tabel Prodi

<img width="526" height="318" alt="image" src="https://github.com/user-attachments/assets/b222eaf3-5462-4976-b861-08ef8121d2d4" />

k.	Button Delete tabel Prodi

<img width="514" height="358" alt="image" src="https://github.com/user-attachments/assets/5acee81e-8ed6-43d7-abd8-623fb8d10e52" />

l.	Button Upload tabel Mahasiswa

<img width="461" height="385" alt="image" src="https://github.com/user-attachments/assets/5fd92c20-7e9c-4789-91a0-8044a154fc9a" />
<img width="461" height="349" alt="image" src="https://github.com/user-attachments/assets/7a4f3182-4c2d-48ef-96dc-62f27b93ed40" />

m.	Button Upload Buku

<img width="411" height="358" alt="image" src="https://github.com/user-attachments/assets/5940a6de-637e-4153-9479-a83ccd284d27" />
<img width="434" height="365" alt="image" src="https://github.com/user-attachments/assets/2f77dca4-b5c5-4c3d-b1cb-7ab850eeade2" />

n.	Buttton Cetak tabel Mahasiswa

<img width="917" height="321" alt="image" src="https://github.com/user-attachments/assets/eab61e3f-2629-41dc-b6d7-b588cf0bd8ec" />

o.	Button Cetak tabel Prodi

<img width="917" height="338" alt="image" src="https://github.com/user-attachments/assets/a3ff0365-d379-480c-b80e-1d2932a5f92f" />

7.	Kemudian Pada Class Jdialog tambahkan code.
a.	JDinsert1 untuk tabel Mahasiswa

<img width="679" height="566" alt="image" src="https://github.com/user-attachments/assets/abe937fb-4ded-453c-b619-62a802b518b1" />

b.	JDUpdate1 untuk tabel Mahasiswa

<img width="378" height="369" alt="image" src="https://github.com/user-attachments/assets/c5daab61-3e35-4350-9ab3-22213d819134" />
<img width="451" height="339" alt="image" src="https://github.com/user-attachments/assets/8be4ab23-7f8b-40df-b018-8f3e859a80a4" />
<img width="457" height="304" alt="image" src="https://github.com/user-attachments/assets/da407dd8-a8dd-4700-9018-98e7588f87de" />

c.	JDDelete1 untuk tabel Mahasiswa

<img width="471" height="374" alt="image" src="https://github.com/user-attachments/assets/cf41e261-8ec0-422a-8536-2427dccd9c93" />
<img width="389" height="265" alt="image" src="https://github.com/user-attachments/assets/f73aece9-b10c-41a0-9997-7b944145af00" />

d.	JDInsert2 untuk tabel Prodi

<img width="433" height="382" alt="image" src="https://github.com/user-attachments/assets/4a39df7b-1190-4bcc-9dba-de43c324f130" />
<img width="396" height="105" alt="image" src="https://github.com/user-attachments/assets/f252354d-3449-42a7-9982-82edd122a1aa" />

e.	JDUpdate2 untuk tabel Prodi

<img width="398" height="337" alt="image" src="https://github.com/user-attachments/assets/b7f3cd0b-64c7-49af-9044-5f4942013c8d" />
<img width="410" height="335" alt="image" src="https://github.com/user-attachments/assets/4de57162-5000-4cbe-aef3-79beebb7fd85" />
}
        }

        JDUpdate2.dispose();
    }


f.	JDDelete2 untuk tabel Prodi

<img width="438" height="325" alt="image" src="https://github.com/user-attachments/assets/d3194ba5-292c-4b93-82a9-4465a0c12776" />
<img width="410" height="280" alt="image" src="https://github.com/user-attachments/assets/818ef30b-75d7-4740-befd-21c0fd5b0167" />

8.	Maka, Outputnya:

<img width="670" height="348" alt="image" src="https://github.com/user-attachments/assets/dff2a365-4345-4e60-b4b6-13197387e186" />
<img width="669" height="345" alt="image" src="https://github.com/user-attachments/assets/39e673d1-ea42-4ad0-8faa-29a765b3197e" />



