### **Skriptin Təsviri**

1. **`SOURCE_FOLDER`:** Ehtiyat nüsxəsinin alınacağı qovluğun tam yolu.
2. **`BACKUP_FOLDER`:** Nüsxənin saxlanacağı qovluğun tam yolu.
3. **`TIMESTAMP`:** Fayl adı üçün unikal tarix və saat yaradır.
4. **`zip`:** Qovluğu sıxışdırır və ehtiyat nüsxəni `.zip` faylı kimi saxlayır.
5. **Qovluq yoxlaması:** Backup üçün nəzərdə tutulan qovluq mövcud deyilsə, avtomatik olaraq yaradılır.
6. **Loglama:** Sıxışdırma zamanı çıxışları görünməz etmək üçün `> /dev/null 2>&1` əlavə edilir.

---

### **İşlədilməsi**

1. **Skripti fayl kimi saxlayın:** Faylı, məsələn, `backup.sh` adı ilə saxlayın.
```
nano backup.sh
```

