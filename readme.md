1. The docker networkperintah adalah perintah utama untuk mengkonfigurasi dan mengelola jaringan kontainer


2. docker network lsperintah untuk melihat jaringan kontainer yang ada pada host Docker saat ini.
-->-->https://github.com/ryan0090/uas_tcc/blob/master/gambar/dockerls.PNG

3. The docker network inspectPerintah ini digunakan untuk melihat rincian konfigurasi jaringan. Rincian ini meliputi; nama, ID, driver, driver IPAM, info subnet, wadah terhubung, dan banyak lagi.
-->https://github.com/ryan0090/uas_tcc/blob/master/gambar/docker_nw.PNG

4. The docker infoperintah menunjukkan banyak informasi menarik tentang instalasi Docker.
-->

5. Setiap instalasi Docker yang bersih dilengkapi dengan jaringan yang disebut jembatan . Verifikasi ini dengan docker network ls.
-->

6. Instal brctlperintah dan gunakan untuk mendaftar jembatan Linux di host Docker . saya dapat melakukan ini dengan menjalankan sudo apt-get install bridge-utils.
-->

7. mendaftarkan docker
-->

8. melihat detail dari docker bridge
-->

9. membuat container baru
-->

10. melihat container baru
-->

11. melihat hubungan container
-->

12. memeriksa container baru pada docker
-->

13. ping IPv4
-->
-->

14. memastikan ID container dimulai pada langkah sebelumnya
-->

KONFIGURASI NAT
15. memulai container baru
-->

16. status container
-->

17. menghubungkan koneksi host docker
-->

18. menginisialisasi swarm baru
-->

19. verifikasi node swarm
-->

20. jaringan overlay
-->

21. verifikasi kesuksesan jaringan
-->

22. menjalankan dikedua terminal
-->

23. melihat detail dari overnet
-->

24. membuat layanan bernama myservice
-->

25. cek layanan yang dibuat
-->

26. running di node ke 2
-->

27. memlihat jaringan overnet di node 2
-->

TEST NETWORK

28. test overnet network
-->

29. untuk mendapatkan ID service
-->

test service discovery
30. masuk kembali ke container
-->

31. memeriksa service "myservice"
-->

32. menghapus layanan myservice
-->

33. melihat container yang sedang berjalan
-->

34. menghapus node 1 dan 2
-->

35. keluar dari node 2
-->https://github.com/ryan0090/uas_tcc/blob/master/gambar/keluarnode2.PNG
