# covid19-data-viz-Lao
ຂໍ້ມູນທັງໝົດອ້າງອີງຈາກ https://www.covid19.gov.la & https://www.facebook.com/CCEH.MoH.Lao/

ເບິ່ງ live demo:https://douangtavanh.com/projects/covid19-confirmed-cases-map/ & https://observablehq.com/@douangtavanh/visualization-covid-19-vaccination-data-laos


## Changelog

17 May 2021:
+ Removed data on 16 May 2021 as it is incorrect data. ref. (https://www.facebook.com/CIEH.MoH.Lao/photos/a.1580136645344357/4252839018074093/)

18 ເມສາ 2020:
+ ອັບເດດຟາຍທັງໝົດໃໝ່ໝົດ
+ ເພີ່ມ function ຂອງ Map ໂດຍການປ່ຽນໄປໃຊ້ Mapbox API ໃນການສະແດງແຜນທີ ແຕ່ຍັງຕ້ມແຜນທີ່ດ້ວຍ D3JS ຄືເກົ່າ
+ ເພີ່ມການສະແດງ case ທັງໝົດ ຕາມແຕ່ລະແຂວ
+ ເພີ່ມລະບຸຕໍາແໜ່ງໃກ້ຄຽງຂອງ case ແຕ່ລະ case ວ່າຢູ່ບ່ອນໃດ ໂດຍອີງໃສ່ບ້ານເປັນຫຼັກໃນການປັກໝຸດ



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


"Code with ❤️ & ☕️"
