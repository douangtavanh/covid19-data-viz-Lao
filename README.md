# covid19-data-viz-Lao
All the data comes from https://www.covid19.gov.la

4 April 2020 NOTE:
index.html
+ ອັບເດດ style file
+ເພີ່ມ font awesome ເພື່ອເພີ່ມ icon ຜູ້ຍິງ, ຜູ້ຊາຍ ໃນ tootltip

map folder
+ແກ້ໄຂຟາຍ LAO_ADM1.json ປ່ຽນຊື່ແຂວງເປັນພາສາລາວ
+ແກ້ໄຂຟາຍ mapTest ມາເປັນ file laoPDR
+ໃນຟາຍ laoPDR ການເພີ່ມຂໍ້ມູນແມ່ນ ໃຫ້ເພີ່ມເປັນໂຕເລກຂອງມື້ທີ່ມີການອັບເດດເລີຍກະໄດ້ ເຊິ່ງ pattern ການອັບເດດຂໍ້ມູນກໍ່ຄື: ອັບເດດຄັ້ງລະ 3 ຖັນເຂົ້າໃໝ່ຄື: ຖັນຈໍານວນຜູ້ຕິດເຊື້ອທັງໝົດ, ຜູ້ຍິງ, ຜູ້ຊາຍ. ໃສ່ຊື່ຕາມປີເດືອນວັນຄືແບບເຮົາໃສ່ກະໄດ້ ຫຼື ຈະໃສ່ຕາມທີ່ຄົນອ່ານງ່າຍກະໄດ້ ເພາະວ່າ ເຮົາໄດ້ສ້າງ function let drawLaosMap = (presentTotal, presentMale, presentFemale) ນີ້ໄວ້ແລ້ວ ເພື່ອບາດອັບເດດຈຶ່ງສະບາຍ ບໍ່ຕ້ອງໄປໄລ່ແກ້ໄຂທາງໃນເທື່ອລະອັນ

+ເພີ່ມ Function ໃນ Map
1. ໂຕເລກສະແດງຜູ້ຕິດເຊື້ອຈະປ່ຽນ ຖ້າແຂວງມີຜູ້ຕິດເຊື້ອ ສີໂຕໜັງສືຈະເປັນສີແດງ
2. ເພີ່ມຂໍ້ມູນ ຂອງຈໍານວນ ຜູ້ຍິງ ແລະ ຜູ້ຊາຍ
3. ປັບການສະແດງຂອງ tooltip ບໍ່ໃຫ້ມັນຕົກຫຼາຍ ແລະ ປັບໄປທາງຂວາເລັກນ້ອຍ
