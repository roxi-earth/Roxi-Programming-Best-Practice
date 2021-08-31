# Remote Development Using SSH

Masuk kedalam **Visual Studio Code** selanjutnya tambahkan **Extension Remote - SSH** :

<img src="../Remote Development Using SSH/Remote-SSH.png" style="zoom:100%;" />

Selanjutnya tekan **CTRL+SHIFT+P** pilih **Open SSH Configuration File**:

<img src="../Remote Development Using SSH/Remote-SSH-Config.png" style="zoom:100%;" />

Setelah itu pilih lokasi konfigurasi file anda :

<img src="../Remote Development Using SSH/Remote-SSH-Configfile.png" style="zoom:100%;" />

Isi konfigurasi sebagai berikut :

```bash
# Read more about SSH config files: https://linux.die.net/man/5/ssh_config
Host aws-ec2
    HostName ec2-18-140-88-174.ap-southeast-1.compute.amazonaws.com
    User ubuntu
    IdentityFile F:\The-DevOps-Standard-Roxi\security\KeyForDevelopment.pem
```

Setelah itu tekan kembali **CTRL+SHIFT+P** pilih Connect to Host... :

<img src="../Remote Development Using SSH/Remote-SSH-Config.png" style="zoom:100%;" />

Jika berhasil maka anda bisa melihat isi **directory** dari **remote server**:

<img src="../Remote Development Using SSH/Remote-SSH-Success.png" style="zoom:100%;" />

Agar bisa melakukan perubahan pada **directory**, anda perlu login sebagai root untuk memberikan **permission** menggunakan perintah :

```bash
$ chown -R ubuntu .
```

