## HAVA SICAKLIĞINA GÖRE ETKİNLİK ÖNERME
**KOŞULLAR :**
- Sıcaklık 5'ten küçük ise 'Kayak' yapmayı öner.
- Sıcaklık 5 ve 15 arasında ise 'Sinema' etkinliğini öner.
- Sıcaklık 10 ve 25 arasında ise 'Piknik' yapmayı öner.
- Sıcaklık 25'ten büyük ise 'Yüzme Havuzu' etkinliğini öner.

# ÖDEV
- Aynı örnek üzerinden if koşulları başka hangi şekilde oluşturulabilirdi farklı çözüm yolları bulunuz.(Çok uğraştım ama başka nasıl olabilir bulamadım. Bu ödev burada kalsın bulduğum zaman tekrardan geriye dönüp yapacağım:))

```
import java.util.Scanner;

public class sicaklikEtkinlikOlcer {
    public static void main(String[] args) {
        int head;
        Scanner input = new Scanner(System.in);

        System.out.print("Hava Sıcaklığını Giriniz : ");
        head = input.nextInt();

        if (head < 5){
            System.out.print("Kayak Yapabilirsiniz.");
        }else if (head < 25 ){
            if (head < 15){
                System.out.println("Sinemaya Gidebilirsiniz.");
            }
            if (head > 10){
                System.out.print("Pikniğe Gidebilirsiniz.");
            }

        }else {
            System.out.print("Yüzmeye Gidebilirsiniz.");
        }
    }
}
```
***
<a href="https://academy.patika.dev/profile">pAtİkA linkim</a>
