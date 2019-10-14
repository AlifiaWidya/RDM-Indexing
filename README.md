# RDM-Indexing
### -> image-search-engine (Image Indexing)
   1. Clone terlebih dahulu. Syntax : 
      `git clone https://github.com/kudeh/image-search-engine.git`
   2. Lakukan Update. Syntax : 
      `sudo apt-get update`
   3. Lakukan Upgrade. Syntax : 
      `sudo apt-get upgrade`
   4. `sudo apt-get install python3-pip`
   5. Mulai jalankan program. Syntax :
      `cd image-search-engine/` lalu `pip3 install -r requirements.txt`
      `cd app` selanjutnya `python3 index.py --dataset static/images --index index.csv`
   7. cek hasil dengan menggunakan syntax `pico index.csv`
   8. Buka ./static/images untuk mengubah image anda
   
### -> Swish-e (Text Indexing)
   1. `sudo apt-get install swish-e`
   2. Modifikasi data dengan beberapa sintax, seperti yang terdapat pada screenshot
   3. `swish-e -c tugas.conf`
   4. untuk menjalankan program text indexing, gunakan syntax : `swish-e -w alifia`
