Site: https://buggy-e-commerce--leylamusazade99.replit.app/

TEST CASE ID: Login_01
TEST NAME: Login modulunun funksional testi
Describtion: Login modulunun yalnış və doğru məlumatlarla funksional testi
Pre condition: Sayta daxil olundu
Test case steps:
1. Press sign in button
2. Mövcud accountla sign in edin (Düzgün məlumatlar daxil olunmalıdır)
3. Mövcud olmayan accountla login edin (Yalnış məlumatlar daxil edilməlidir)
4. Log out edin
Expected results(Gözlənilən nəticə):
1. Sign in səhifəsi açılmalıdır
2. Sign in olunmaılıdır
3. Sign in olunmamalıdır
4. Log out etməlidir
Faktiki nəticə
1. Sign in səhifəsi açıldı
2. Sign in olundu
3. Sign in olundu
4. Log out etmir
Results
1. Passed
2. Passed
3. Failed
4. Failed
Qeyd: Test 50% keçdi. Login bölməsi üzərində yenidən işlər aparılmalıdır.

TEST CASE ID: Sign UP_01
TEST NAME: Sign UP modulunun testi
Describtion: Sign UP modulunun yalnış və düzgün məlumatlarla funksional testi
Pre Condition: Sing in səhifəsinə daxil olundu
Test case steps:
1. Account create düyməsinə basın
2. Düzgün məlumatlarla account yaratmaq
3. Yalnış məlumatlarlar və ya boş xanalarla account yaratmaqa çalışmaq
4. Account yaratdıqdan sonra account bölümünə keçid edib verilan məlumatları yoxlamaq
5. Verilən məlumatları dəyişdikdən sonra nəticəyə baxmaq ( Save changes )
Expected results:
1. Account yaratmaq üçün səhifə açılmalıdır
2. Account açılmalıdı
3. Account açılmamalıdır
4. Məlumatlar düzgün olmalıdır
5. Verilən məlumatlar dəyisməlidir
Faktiki nəticə
1. Səhifə açıldı
2. Account açıldı
3. Account açıldı
4. Məlumatlar düzgündür
5. Məlumatlar dəyişdi
Results
1. Passed
2. Passed
3. Failed
4. Passed
5. Passed
Qeyd: Phone number bölməsinə hərif yazmaq olur ve limitsiz doldurmaq olur. Confirm Password bölməsinə fərqli password yazmaq olur. Email indentifikasiyası var. Sign up bölməsi üzrə yenidən işlər aparılmaıdır

TEST CASE ID: Cart_01
TEST NAME: Cart (Səbət) bölməsinin testini aparmaq.
Describtion: Cart (Səbət) bölməsinin functional testi
Pre condtion: Sayta daxil olmaq 
Test case steps:
1. Bir neçə fərqli sayda və adla olan məhsulları səbətə elavə etmək
2. Səbət bölməsinə daxil olmaq
3. Əlavə olunan məhsulların düzgünlüyün yoxlamaq
4. Məhsulları səbətin daxilində silmək
5. Məhsulları səbətin daxilində əlavə etmək
6. Qiyməti yoxlamaq
Expected results:
1. Məhsullar səbətə elavə olundu
2. Daxil oldu
3. Məhsulların sayı və adları düzgündür
4. Məhsul silindi
5. Məhsul elavə olundu
6. Qiymət hesablaması düzgündür
Faktiki nəticə:
1. Məhsullar səbətə elavə olundu
2. Səbət bölməsinə daxil oldu
3. Sayı və adları düzgündür
4. Səbətdən silmək mümkündür amma mənfi rəqəmlərə kimi gedir
5. Səbətdə sayını artırmaq mümkündür
6. Məhsulların ayrica qiyməti düzgün hesablanır amma total qiymət (+tax and shipping) yalnış hesablanır
Results:
1. Passed
2. Passed
3. Passed
4. Failed
5. Passed
6. Failed
Qeyd: Qiymət və Məhsul silinməsi bölmələri düzəliş tələb edir

TEST CASE ID: Main Page_01
TEST NAME: Əsas səhifənin functional testi
Describtion: Əsas səhifədə category, axtarış, ümumi testlər
Pre conditions: Sayta daxil olmaq
Test cases:
1. Hər bir kateqoryadakı məhsullar uyğunluğu
2. Filtrasyia necə sıralayır
3. Məhsullara click etdikdən sonra açılan səhifəyə baxmaq
4. Məhsula baxdıqdan sonra əsas səhifəyə keçid etmək
Expected results:
1. Hər bir kateqoryaya uyğun məhsullar göstərilmalidir
2. Qiymət və rating üzrə düzgün sıralama olmalıdır
3. Açılan səhifədə məhsul və qiyməti üst-üstə düşməlidir
4. Əvvəlki səhifə açılmalıdır
Faktiki nəticə:
1. Hər bir kateqoryaya uyğun məhsullar göstərildi
2. Qiymət azalması üzrə sıralama düzgün aparıldı, Artması üzrə sıralama yalnış aparıldı, Rating üzrə düzgün sıralama aparıldı
3. Əsas səhifədəki məhsul və açılan səhifədəki məhsulun qiyməti və adı uyğundur
4. Əsas səhifəyə, əvvələ göndərir
Results
1. Passed
2. Failed
3. Passed
4. Failed
Qeyd: Əsas səhifədən məhsula keçid etdikdə səhifə ortadan açılır. Həmçinin səhifədə failed to find products yazısı gəlir. Saytın performance problemləri müşahidə olunur.
