class Person {
  String nama;
  int umur;

  Person(this.nama, this.umur);

  void greet(String greeting, String timeOfDay, String recipient) {
    print('$greeting, $recipient! selamat $timeOfDay! Nama saya adalah $nama, dan Umur saya $umur tahun.');
  }
  void updateprofil(String newnama, int newumur, String messumur) {
    nama = newnama;
    umur = newumur;
    print('$messumur: Profil diperbarui nama: $nama, umur: $umur'); }}

void main() {
  Person person = Person('Siti Hajar', 20);


  person.greet('Hey', 'Sore', 'Iti');

  person.updateprofil('Siti Hajar', 21 , 'Berhasil');
}
