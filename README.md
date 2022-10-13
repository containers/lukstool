lukstool: offline encryption/decryption using LUKS formats
-
lukstool implements encryption and decryption using LUKSv1 and LUKSv2 formats.
Think of it as a clunkier cousin of gzip/bzip2/xz that doesn't actually produce
smaller output than input.

* The main goal is to be able to encrypt/decrypt when we don't have access to
  the Linux device mapper.
* If you can use cryptsetup instead, use cryptsetup instead.
