- 👋 Hi, I’m @RajaAmbedkar
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
RajaAmbedkar/RajaAmbedkar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Exception in Tkinter callback
Traceback (most recent call last):
  File "C:\Python27\lib\lib-tk\Tkinter.py", line 1547, in __call__
    return self.func(*args)
  File "e:/Image-Encryption-and-Decryption-using-AES-algorithm-master/final.py", line 245, in image_open
    encrypt(filename,password)
  File "e:/Image-Encryption-and-Decryption-using-AES-algorithm-master/final.py", line 168, in encrypt
    obj = AES.new(password, AES.MODE_CBC, 'This is an IV456')     
  File "C:\Python27\lib\site-packages\Crypto\Cipher\AES.py", line 232, in new
    return _create_cipher(sys.modules[__name__], key, mode, *args, **kwargs)
  File "C:\Python27\lib\site-packages\Crypto\Cipher\__init__.py", line 79, in _create_cipher
    return modes[mode](factory, **kwargs)
  File "C:\Python27\lib\site-packages\Crypto\Cipher\_mode_cbc.py", line 293, in _create_cbc_cipher
    return CbcMode(cipher_state, iv)
  File "C:\Python27\lib\site-packages\Crypto\Cipher\_mode_cbc.py", line 97, in __init__
    c_uint8_ptr(iv),
  File "C:\Python27\lib\site-packages\Crypto\Util\_raw_api.py", line 242, in c_uint8_ptr
    raise TypeError("Object type %s cannot be passed to C code" % type(data))
TypeError: Object type <type 'unicode'> cannot be passed to C code



this  is the exception i face when i use the code with the complete requirements and it is colleting the RGB values and not encrypting and also not creating the encrypted files
