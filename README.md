# F# MessageBox Örnekleri

Bu örnek F# kodu, Windows Forms kütüphanesini kullanarak MessageBox oluşturmanın farklı yollarını gösterir. 

## Kullanım

Aşağıda, farklı senaryolarda MessageBox oluşturmanın 10 örneği yer almaktadır:

1. **Basit MessageBox Oluşturma**
    ```fsharp
    createSimpleMessageBox()
    ```

2. **İki Düğmeli MessageBox (OK ve Cancel)**
    ```fsharp
    createTwoButtonMessageBox()
    ```

3. **Hata Mesajı Veren MessageBox**
    ```fsharp
    createErrorMessageBox()
    ```

4. **Uyarı Mesajı Veren MessageBox**
    ```fsharp
    createWarningMessageBox()
    ```

5. **Soru Soran MessageBox**
    ```fsharp
    createQuestionMessageBox()
    ```

6. **Bilgi Veren MessageBox**
    ```fsharp
    createInfoMessageBox()
    ```

7. **Kullanıcıdan Metin Girişi Alan MessageBox**
    ```fsharp
    getUserInputMessageBox()
    ```

8. **Kullanıcının Seçimine Göre Mesaj Gösterme**
    ```fsharp
    showTextBasedOnUserChoice()
    ```

9. **Çoklu Seçenekler İçeren MessageBox**
    ```fsharp
    showMultipleOptions()
    ```

10. **Özel Başlık ve Düğme İsimleri Kullanan MessageBox**
    ```fsharp
    showCustomTitleAndButtons()
    ```

## Notlar

- MessageBox'lar Windows Forms kütüphanesine dayalıdır ve Windows ortamında çalışır.
- Kullanıcıdan metin girişi almak için `getUserInputMessageBox` örneğini kullanabilirsiniz.
- MessageBox'ların sonuçlarına göre işlemler yapmak için pattern matching kullanılabilir.

**Not:** Bu örnekler, F# Console uygulaması içinde çalışır. WPF veya Xamarin.Forms gibi diğer platformlarda farklı yaklaşımlar gerekebilir.

