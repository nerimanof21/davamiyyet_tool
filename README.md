# AZTU Davamiyyət Məlumatlarını Çıxaran Python Skripti

Bu layihə, AZTU-nun tələbə portalına daxil olaraq davamiyyət məlumatlarını avtomatik olaraq əldə etmək üçün hazırlanmışdır. Kod, Selenium kitabxanasından istifadə edərək veb səhifədə avtomatik gəzinti edir və BeautifulSoup vasitəsilə məlumatları oxuyur.

## Tələblər

Bu skripti işlətmək üçün aşağıdakıları təmin etməlisiniz:

- **Python 3.7+**
- Aşağıdakı Python kitabxanaları:
  - `selenium`
  - `beautifulsoup4`

Həmçinin **Google Chrome** brauzerinin və onun uyğun ChromeDriver-in sisteminizdə quraşdırıldığından əmin olun.

## Quraşdırma

1. **Kodunuzu klonlayın və ya yükləyin:**
   ```bash
   git clone https://github.com/sizin-repo/aztu-davamiyyet.git
   cd aztu-davamiyyet
   ```

2. **Tələb olunan kitabxanaları quraşdırın:**
   ```bash
   pip install selenium beautifulsoup4
   ```


## İstifadə

1. Skripti işlədin:
   ```bash
   python script.py
   ```

2. Sizdən istifadəçi adı və şifrə daxil etməyiniz istənəcək:
   ```
   İstifadəçi adınızı daxil edin: **********
   Şifrənizi daxil edin: ***********
   ```

3. Skript, AZTU tələbə portalına daxil olaraq davamiyyət məlumatlarınızı avtomatik toplayacaq və terminalda göstərəcək:
   ```
   Davamiyyət Məlumatları:
   ------------------------------
   Tarix: 2023-12-20, Status: İştirak Edib
   Tarix: 2023-12-21, Status: İştirak Etməyib
   ```

## Kodun Strukturu

- **Selenium ilə avtomatlaşdırma:**
  Skript AZTU-nun tələbə portalında aşağıdakı addımları avtomatlaşdırır:
  - Giriş etmək
  - Fenlər və Python dərsinə keçid
  - Davamiyyət bölməsinə daxil olmaq

- **BeautifulSoup ilə məlumat toplama:**
  Davamiyyət məlumatları HTML səhifəsindən çıxarılır və formatlanmış şəkildə göstərilir.

## Xüsusi Qeyd

- **Şifrə və istifadəçi adı:** Skript birbaşa portalın giriş məlumatlarını tələb edir. Giriş məlumatlarınızı başqaları ilə paylaşmayın.
- **Məxfilik:** Bu kod yalnız şəxsi istifadəniz üçündür. Kodun istifadəsi zamanı şəxsi məlumatlarınızın təhlükəsizliyinə diqqət edin.

## Mümkün Təkmilləşdirmələr

- Məlumatların CSV və ya Excel faylı kimi saxlanılması.
- İştirak etmədiyiniz tarixlərin avtomatik e-poçt vasitəsilə göndərilməsi.
- UI interfeysi əlavə etmək.

## Problemlərin Həlli

**Xəta mesajı alırsınızsa:**
AZTU portalında dəyişiklik olmuş ola bilər. XPath-ləri yeniləmək üçün HTML kodunu yoxlayın.

**Dəstək üçün:**
Hər hansı sualınız olarsa, mənimlə əlaqə saxlayın.
