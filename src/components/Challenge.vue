<template>
  <div style="margin-bottom: 50px">
    <div
      class="display-3 ma-15 black--text"
      style="text-align: center; font-family: 'Signika Negative', sans-serif"
      font-weight-bold
    >
      Freelance Project Bidding
    </div>

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/1.png" height="960px"></v-img>

      <v-card-title>Vue JS Sederhana</v-card-title>

      <v-card-subtitle>
        Published Date: 13/09/2021 14:02:25 WIB <br />
        Published Budget: Rp 1.000.000,00 - Rp 2.000.000,00 <br />
        Finish Days: 30
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/past_projects/view/cfe218/vue-js-sederhana"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Halo worker bantu convert UI dari figma ke vue JS kebutuhan untuk
            UI development dengan API dummy data, wajib sertakan portofolio dan
            wa, bebas bekerja dari mana saja (remote) , di utamakan wilayah jawa
            timur agar mudah komunikasinya."
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <br /><br />

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/2.png" height="900px"></v-img>

      <v-card-title
        >Buat Web (Mobile Responsive) Untuk Dashboard Sederhana</v-card-title
      >

      <v-card-subtitle>
        Published Date: 17/09/2021 11:47:41 WIB <br />
        Published Budget: Rp 250.000,00 - Rp 500.000,00 <br />
        Finish Days: 4
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/past_projects/view/8ce618/buat-web-mobile-responsive-untuk-dashboard-sederhana"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Buat Web (mobile responsive) untuk dashboard sederhana: <br />
            1. Login <br />
            2. Tampil data sesuai dengan kepemilikannya (dalam bentuk table dan
            grafik summary singkat) seperti berikut : bahasa bebas namun kalau
            bisa lebih baik pakai vue js atau yang responsive lainnya diutamakan
            yang biayanya ga besar"
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <br /><br />

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/3.png" height="750px"></v-img>

      <v-card-title>Admin Copy Paste Untuk Jangka Panjang</v-card-title>

      <v-card-subtitle>
        Published Budget: Rp 150.000,00 - Rp 270.000,00 <br />
        Published Date: 14/10/2021 05:28:27 WIB <br />
        Select Deadline: 13/11/2021 05:28:27 WIB <br />
        Finish Days: 5
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/browse_projects/view/d4fe18/membutuhkan-admin-copy-paste-untuk-jangka-panjang-17-k"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Kita punya materi yang mau diposting ke website kita
            kekitaan.com/mau-tulisin-apa-hari-ini/ <br />

            Materi udah disiapkan tinggal copy paste aja <br />
            Silahkan bid untuk 300 materi copy paste ya <br />
            Nanti bid terpilih, ikuti panduan ini
            kekitaan.com/menulis-dapat-uang/"
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <br /><br />

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/4.png" height="700px"></v-img>

      <v-card-title>Frontend Vue Developer Website</v-card-title>

      <v-card-subtitle>
        Published Budget: Rp 2.000.000,00 - Rp 5.000.000,00 <br />
        Published Date: 05/10/2021 17:45:59 WIB <br />
        Select Deadline: 04/11/2021 17:45:59 WIB <br />
        Finish Days: 30
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/browse_projects/view/b8f618/butuh-segera-frontend-vue-developer-website"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Scope Of Work <br />
            - Membuat integrasi API dengan vue project <br />

            - Menconsume API 3rd Party kedalam project <br />

            <br />
            Spesifikasi <br />

            - Pengalaman dalam vue dan integrasi API minimal 1-2 tahun <br />

            - Dapat membaca dokumentasi 3rd party API <br />

            - Memahami git <br />

            - Dapat bekerja dengan cepat <br />

            - Bisa membuat SPA dalam Vue <br />

            <br />

            est. Waktu Pengerjaan 1 bulan"
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <br /><br />

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/5.png" height="700px"></v-img>

      <v-card-title>Hit API Ke frontend</v-card-title>

      <v-card-subtitle>
        Published Budget: Rp 500.000,00 - Rp 600.000,00 <br />
        Published Date: 03/10/2021 09:03:43 WIB <br />
        Select Deadline: 02/11/2021 09:03:43 WIB <br />
        Finish Days: 3
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/browse_projects/view/5ef018/bantu-hit-api-ke-frontend"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Saya ada web backend dan API dah ada, tolong bantu hit ke
            frontend."
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <br /><br />

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/6.png" height="700px"></v-img>

      <v-card-title>WordPress Dev - Aktivasi Blog</v-card-title>

      <v-card-subtitle>
        Published Budget: Rp 250.000,00 - Rp 1.000.000,00 <br />
        Published Date: 13/10/2021 15:41:30 WIB <br />
        Select Deadline: 12/11/2021 15:41:30 WIB <br />
        Finish Days: 7
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/browse_projects/view/71fe18/wordpress-dev-aktivasi-blog"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Perusahaan kami memiliki sebuah website berbasis WordPress. Kami
            membutuhkan WordPress Developer untuk : <br />
            - Melakukan aktivasi/penambahan halaman untuk blog artikel.
            <br />
            Website kami > https://barcodes.id/
            <br />
            <br />
            *Note : Harap pendaftar untuk menyertakan portofolio"
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>

    <br /><br />

    <v-card
      class="mx-auto"
      max-width="890"
      style="font-family: 'Signika Negative', sans-serif"
    >
      <v-img src="@/assets/7.png" height="666px"></v-img>

      <v-card-title>Membuat Web Toko Online Jual Beli</v-card-title>

      <v-card-subtitle>
        Published Budget: Rp 2.500.000,00 - Rp 3.500.000,00 <br />
        Published Date: 13/10/2021 16:55:13 WIB <br />
        Select Deadline: 12/11/2021 16:55:13 WIB <br />
        Finish Days: 30
      </v-card-subtitle>

      <v-card-actions>
        <v-btn
          href="https://projects.co.id/public/browse_projects/view/7dfe18/membuat-web-toko-online-jual-beli"
          color="blue-grey lighten-5"
        >
          Explore
        </v-btn>

        <v-spacer></v-spacer>

        <v-btn icon @click="show = !show">
          <v-icon>{{ show ? "mdi-chevron-up" : "mdi-chevron-down" }}</v-icon>
        </v-btn>
      </v-card-actions>

      <v-expand-transition>
        <div v-show="show">
          <v-divider></v-divider>
          <v-card-text>
            Project Owner: <br />
            "Selamat sore, saya mencari freelancer yang bisa membuat web toko
            online jual-beli menggunakan Codeigniter sesuai dengan design kami
            <br />
            <br />
            Fitur = <br />
            <br />
            Admin : <br />
            - Margin Harga jual (Yang tampil di web) <br />
            - Print Laporan : <br />
            - Penjualan/Keuntungan/ berdasarkan (Pengguna, Penjual, tanggal,
            Semua,Hari, Bulan) <br />
            - Pengguna<br />
            - Penjual<br />
            - Mengelola Pengguna<br />
            - Aktif/banned/Nonaktif<br />
            - Verifikasi Pengguna<br />
            - Mengelola Penjual<br />
            - Aktif/Banned/Nonaktif<br />
            - Verifikasi Penjual<br />
            - Mengelola profile Website<br />
            - Alamat<br />
            - Logo<br />
            - Email<br />
            - Halaman About<br />
            - Mengelola Kategori<br />
            - Membuat kategori<br />
            - Membuat subkategori<br />
            - Mengelola Pembelian<br />
            - Verifikasi Pembelian/Pembayaran<br />
            - Mengelola Notifikasi<br />
            - Pembelian<br />
            - Pembayaran<br />
            - Pengguna Baru<br />
            - Penjual Baru<br />
            - Menambah admin<br />
            - Staff<br />
            - Menelola Akses Staff<br />
            - Manage Raja Ongkir<br />
            - update API key<br />
            - Statistik<br />
            - Penjualan<br />
            - Keuntungan<br />
            - Kelola Banner<br />
            - Kelola Blog<br />
            - Membuat<br />
            - Membuat Kategori<br />
            - Mengelola Keluhan<br />
            - Melacak Keluhan Berdasarkan(Selesai/Open) <br />
            - Notifikasi admin berupa suara
            <br />
            <br />
            Pembeli :
            <br />
            - Riwayat Transaksi<br />
            - List favorit<br />
            - Daftar Akun<br />
            - Login<br />
            - Melakukan Transkasi<br />
            - Lacak Pesanan Via Raja Ongkir<br />
            - Notifikasi via Email dan Firebase<br />
            - Cetak Laporan :<br />
            a. Berdasarkan Tanggal/Bulan/Hari/Semuanya<br />
            b. Gagal/Refund/Berhasil<br />
            c. Format Excel/PDF<br />
            - Bisa Belanja di beberapa Penjual<br />
            - Melakukan return/pengembalian barang<br />
            - List Notifikasi yang sudah di baca atau belum<br />
            - Memberikan ulasan pada produk yang di beli<br />
            - Diskusi Produk<br />
            - Membuat Keluhan<br /><br />
            Penjual : <br />
            - CRUD Produk<br />
            - Menambah variant Opsional<br />
            - Notifikasi Produk Habis dan Sisa produk<br />
            - Statistik Penjualan<br />
            - Notifikasi Pembelian (Selesai, Masuk, Refund)<br />
            - Notifikasi Pembayaran ( Selesai, Diteruskan, gagal)<br />
            - Manage Profile<br />
            - Menerima email notifikasi pembelian/pembayaran<br />
            - Melacak Pesanan<br />
            - Mebalas Review/Diskusi<br />
            - List Produk<br />
            - Filter Produk yang<br />
            a. Terlaku<br />
            b. Sedikit<br />
            c. Stok habis<br />
            d. SKU<br />
            - Membuat Keluhan<br />
            <br />

            Front - End : <br />
            - Ikuti Sesuai template yang sudah kami sediakan "
          </v-card-text>
        </div>
      </v-expand-transition>
    </v-card>
  </div>
</template>

<script>
export default {
  name: "Challenge",
  data: () => ({
    show: false,
  }),
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Festive&family=Raleway:wght@600&family=Signika+Negative&family=Yanone+Kaffeesatz&display=swap");
</style>