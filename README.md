# Plugin-Ongkos-Kirim
Cara mengaktifkan kolom "Alamat" pada Plugin-Ongkos-Kirim

Pilih <b>Plugin > Penyunting > Pilih 'Plugin Ongkos Kirim'</b>
Edit <b>'Classes' > 'class-pok-hooks-addresses.php'</b>

Pada baris 162, tambahkan Scripts berikut:
```php
$fields[ $type . '_address_1' ]['class']       = array();
$fields[ $type . '_address_2' ]['class']       = array();
```
Sekian, Terima Kasih :
