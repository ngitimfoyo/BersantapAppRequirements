mongodb collections

1. Kategori: _id, Nama
2. Spot: _id, Nama, Alamat, Kontak, Deskripsi, Koordinat, Kategori, Review:{UserId, UserName, Rating, Komentar}
3. User: _id, UserId, UserName, Phone

sample document:
Spot = {
_id: 4534534534,
Nama: "Bengkel Eksotis",
Alamat: "Jl Harapan Palsu, Jakarta Utara",
Kontak: "0874 5454 98986;(021)8799 9998",
Deskripsi: "Service ringan;service berat;ganti oli;ganti kabel;permak;cat"
Koordinat: "-2,2342342434;3.23423424",
Kategory : "Bengkel",
Review: [{
  UserId: "encep@gmail.com",
  UserName: "Encep",
  Rating: 3,
  Komentar: "Bengkel bagus, murah"
 },
 {
  UserId: "vony@gmail.com",
  UserName: "Vony",
  Rating: 4,
  Komentar: "Tempatnya bersih, recomended deh"
 }]
}
