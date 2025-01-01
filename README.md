# xxxx.AZ Vue.js və Node.js Layihəsi

Bu layihə Vue.js ilə hazırlanmış müasir bir istifadəçi interfeysi və Node.js əsaslı bir API ilə təchiz edilmişdir. Nginx vasitəsilə yerləşdirilib və HTTPS ilə qorunur.

## Xüsusiyyətlər

- **Vue.js**: Müasir və dinamik istifadəçi interfeysi yaradılması.
- **Node.js API**: Arxa planda güclü və etibarlı əməliyyatlar üçün.
- **Nginx**: Statik faylların və API sorğularının idarə edilməsi.
- **SSL/TLS dəstəyi**: Təhlükəsiz HTTPS bağlantısı.
- **Şəkil yükləmə və göstərmə**: `/uploads` və `/image` end-point-ləri ilə.

## Quraşdırma

### Tələb olunanlar

- **Node.js** (v14 və ya daha yüksək)
- **NPM** (və ya **Yarn**)
- **Nginx**
- **Certbot** (SSL üçün)

### Addımlar

1. **Layihə Deposu**nu Klonlayın:
    ```bash
    git clone https://github.com/istifadeciadi/layihe-adi.git
    cd layihe-adi
    ```

2. **API üçün Zəruri Paketləri Yükləyin:**
    ```bash
    cd server
    npm install
    ```

3. **Frontend üçün Zəruri Paketləri Yükləyin:**
    ```bash
    cd client
    npm install
    ```

4. **API-ni İşə Salın:**
    ```bash
    npm start
    ```

5. **Vue.js Tətbiqini Build Edin:**
    ```bash
    npm run build
    ```

6. **Nginx Konfiqurasiyası:**
    Nginx konfiqurasiya faylını redaktə edin:
    ```bash
    sudo nano /etc/nginx/nginx.conf
    ```
    Dəyişiklikləri etdikdən sonra Nginx-i yenidən başladın:
    ```bash
    sudo systemctl restart nginx
    ```

## İstifadə

1. **İstifadəçi İnterfeysi:** 
   Brauzerdə `https://xxxx.az` ünvanını açın.
2. **API:** 
   API sorğuları üçün `https://xxxx.az/api/` yolunu istifadə edin.

## Yol Xəritəsi

- [ ] İstifadəçi idarəetməsinin təkmilləşdirilməsi.
- [ ] Çoxdilli dəstək.
- [ ] Performans optimizasiyaları.

## Töhfə Vermək

Layihəyə töhfə vermək üçün **fork** yaradın və dəyişikliklərinizi **pull request** ilə göndərin.

## Lisenziya

Bu layihə [MIT Lisenziyası](LICENSE) ilə lisenziyalaşdırılıb.
