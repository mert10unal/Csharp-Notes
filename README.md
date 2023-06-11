# Csharp-Notes

Nesne-Class Nedir ?
Class'lar, nesnelerin nasıl oluşturulacağını ve nasıl davranacaklarını belirleyen bir dizi alan ve yöntem içerir. Alanlar, nesnenin durumunu temsil eden veri elemanlarıdır, yöntemler ise nesnenin davranışını tanımlar. Nesneler ise fonksiyonlar ve sınıf yapılarına göre içine farklı değerler alabilir. Örneğin araba classının içinde renk ve marka belirten iki fonksiyon olsun. Bu fonksiyonlar üzerinden markası Audi, rengi ise gri olan bir nesne tanımlanabilir.

Ctor Nedir ?
- Bir sınıf oluşturulduğunda otomatik olarak getirilen bir yapıdır. Ana classtan ayıran şey bir dönüş tipinin olmamasıdır fakat isimleri aynı olmalıdır. Ctorlar değer döndürmez. Bir ctorun avantajı, bir sınıfın nesnesi oluşturulduğunda çağrılmasıdır. Alanlar (Column Field) için başlangıç değerlerini ayarlamak için kullanılabilir (nesnenin bir değişkenine değer atama)


Inheritance
- Bir sınıfın başka sınıfın attributelerini yani özelliklerini miras edebilmesi olayıdır. Çok sık kullanırız çünkü hem daha az kod yazmış oluruz hem de ana classa bağlı olarak bir sürü sub-class oluşturabiliriz. Örneğin her aracın rengi ve tekeri vardır. Bu özellikler ana class’ta tanımlandıktan sonra bir daha tanımlanırsa kod uzar. Bunun yerine inheritance yöntemiyle bunu sağlayabiliriz
- Class B : variable type A


Polymorphism
- Esneklik ve kullanışlılık
- Araba classının farklı markalarda sub-classları olsun ve araba classının da Horsepower adında bir özelliği olsun. Bu özellik tüm arabalarda vardır fakat fakat içerdiği değer her sub-classa göre farklılık gösterir. Veya horsepower üzerinden işlem yapan bir fonksiyonumuz olsun. Bu fonksiyonda horsepower özelliğinin her subclassa göre farklı değer döndürmesi de polymorphisme örnek gösterilebilir.


Encapsulation
- Encapsulation is the concept of wrapping data into a single unit. It collects data members and member functions into a single unit called class. The purpose of encapsulation is to prevent alteration of data from outside. This data can only be accessed by getter functions of the class. A fully encapsulated class has getter and setter functions that are used to read and write data. This class does not allow data access directly

Abstraction
