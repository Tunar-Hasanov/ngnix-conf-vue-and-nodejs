# 🌐 XXXX.COM 🌟 Vue.js və Node.js Layihəsi

⚡ **XXXX.COM** - müasir dizayn və güclü arxa plan sistemi ilə təchiz edilmiş web tətbiqi! Bu layihə Vue.js ilə hazırlanmış istifadəçi interfeysi və Node.js əsaslı API ilə işləyir. 🔒 Nginx vasitəsilə təhlükəsiz HTTPS bağlantısı təmin edilir.

---

## 🚀 Xüsusiyyətlər

✅ **Müasir Texnologiyalar**: Vue.js və Node.js ilə qurulmuşdur.  
✅ **Nginx Yerləşdirmə**: Statik faylların sürətli və etibarlı idarəsi.  
✅ **Şəkil Yükləmə və Göstərmə**: `/uploads` və `/image` marşrutları ilə şəkillərin idarə olunması.  
✅ **Təhlükəsizlik**: SSL/TLS ilə HTTPS dəstəyi.  

---

## 🛠️ Quraşdırma

### ⚙️ Tələblər

- 📦 **Node.js** (v14 və ya daha yüksək)  
- 📂 **NPM** (və ya **Yarn**)  
- 🌐 **Nginx**  
- 🔑 **Certbot** (SSL üçün)

### 📋 Addımlar

1. 📂 **Layihə Deposu**nu Klonlayın:
    ```bash
    git clone https://github.com/Tunar-Hasanov/ngnix-conf-vue-and-nodejs.git
    cd layihe-adi
    ```

2. ⚙️ **API üçün Paketləri Quraşdırın**:
    ```bash
    cd server
    npm install
    ```

3. 🎨 **Frontend üçün Paketləri Quraşdırın**:
    ```bash
    cd client
    npm install
    ```

4. ▶️ **API-ni İşə Salın**:
    ```bash
    npm start
    ```

5. 🏗️ **Vue.js Tətbiqini Build Edin**:
    ```bash
    npm run build
    ```

6. 🌐 **Nginx Konfiqurasiyası**:
    Nginx konfiqurasiya faylını redaktə edin:
    ```bash
    sudo nano /etc/nginx/nginx.conf
    ```
    Dəyişiklikləri etdikdən sonra Nginx-i yenidən başladın:
    ```bash
    sudo systemctl restart nginx
    ```

---

## 📖 İstifadə

1. 🌍 **İstifadəçi İnterfeysi:** Brauzerdə `https://xxxx.com` ünvanını açın.  
2. 📡 **API:** API sorğuları üçün `https://xxxx.com/api/` yolunu istifadə edin.  

---

## 📌 Yol Xəritəsi

- [ ] 🧑‍💻 İstifadəçi idarəetməsinin təkmilləşdirilməsi.  
- [ ] 🌍 Çoxdilli dəstək.  
- [ ] 🚀 Performans optimizasiyaları.  

---

## 🤝 Töhfə Vermək

💡 Layihəyə töhfə vermək istəyirsiniz? **Fork** yaradın və dəyişikliklərinizi **Pull Request** ilə göndərin. 

---

## 📜 Lisenziya

📄 Bu layihə [MIT Lisenziyası](LICENSE) ilə lisenziyalaşdırılıb.

---

**💻 Hazırlayan:** [Tunar-Hasanov](https://github.com/Tunar-Hasanov)  
