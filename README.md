# II. Hafta Ödevleri

## Yeni bir GitHub repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?
> #### MIT Licence :
> En yaygın kullanılan lisans türlerinden biridir. MIT tarafından yayınlandığı için adı da aynı şekilde MIT olarak geçer. Çok kullanışlıdır. MIT licence sizi birçok konuda özgür kılar. Yani yazılıma ait kaynak kodu veya derlenmiş yazılımı istediğiniz gibi değiştirebilir, yayabilir, kullanabilirsiniz. Ticari olarak bile kullanımında herhangi bir sorun olmaz. Fakat sizi özgür kıldığı kadar yazılımı geliştirenleri de özgür kılar. Yani bir sorun çıkması durumunda geliştiriciler için herhangi bir yükümlülük söz konusu bile olamaz. Dolayısı ile MIT ile lisanslanmış bir yazılımı gönül rahatlığı ile kullanabilirsiniz. Sadece yazılımın buglardan temizlenmiş, yaygın bir kitle tarafından kullanılıyor olması sizi ilerde çıkabilecek yazılımsal sorunlar konusunda daha rahat ettirecektir.
> #### Apache Licence :
> Apache lisansının MIT’den bir farkı yok aslında. Sadece yazılımınızı dağıtırken kullandığınız Apache lisanslı ürünlerin lisanslarını da dağıtımınıza eklemeniz gerekiyor. Yani kısaca emeğe saygı konusu daha önemli tutulmuş bu lisansta.
> #### GNU General Public Licence :
> GNU lisansı da MIT gibi aynı şekilde size yazılımın kodlarına erişim konusunda herhangi bir kısıtlama getirmez. Fakat MIT lisansına göre kullanım açısından bazı kısıtlamalar getirir. Bu kısıtlamaların en önemlisi eğer yazılımında GNU lisansına sahip bir ürün kullandıysanız ve ürünü dağıtmaya başlarsanız sizin yazılımınız da GNU lisansına sahip olmalıdır. Yani yazılımın kendi geliştirdiğiniz kısımlarının da kaynak kodlarını paylaşmak zorundasınız. Dolayısı ile kaynak kodlarını paylaştığınız bir yazılımı ticari olarak satmak zor olacaktır.
Fakat MIT lisansı için aynı durum söz konusu değildir. MIT lisansına sahip bir ürünü kullanarak geliştirdiğiniz bir üründeki kendi kodlarınızı kimseyle paylaşmak zorunda değilsiniz. Yani kısaca GNU lisanslama konusunda kalıtsal davranır.

## Merge-Squash-Rebase arasındaki farklar nelerdir?
> Eğer tüm değişiklikleri görmek istiyorsanız merge yapmalısınız çünkü merge tüm değişiklikleri olduğu gibi korur. Eğer daha sade, anlaşılabilir ve lineer bir commit history istiyor iseniz rebase sizin için daha yaralı olacaktır. Ancak bir ekip olarak public repository üzerinde çalışıyor iseniz çok ama çok dikkatli olmalısınız. Rebase'i merge'e kıyasla revert etmenin çok ama çok daha zor olacağını da göz önünde bulundurmanız gerekir. Son olarak eğer branchinizi push yaptıysanız merge, yapmadıysanız rebase'i kullanmanız doğru olacaktır.

## Agile-Scrum-Kanban kavramlarını araştırınız
> #### Agile :
> Agile modeli proje yönetimi, yazılım geliştirme sürecinde karşılaşılan problemleri çözmek üzere, tekrarlanan yazılım geliştirme modeli taban alınarak geliştirilmiş, sık aralıklarla parça parça yazılım teslimatını ve değişikliği teşvik eden bir yazılım geliştirme modelidir. Agile metodunun temel esasları şöyle sıralanabilir:
> - Deneysellik
> - Önceliklendirme
> - Kendi kendini örgütleme
> - Zaman çerçevesi
> - İş birliği
> #### Scrum :
> Agile proje yönetim metodolojilerinden biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bunu yaparken bütünü parçalayan; tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Bu anlamda ihtiyaca yönelik ve esnek bir yapısı vardır. Müşteri ihtiyacına göre şekillendiği için müşterinin geri bildirimine göre yapılanmayı sağlar. İletişim ve takım çalışması çok önemlidir. 3 temel prensip üzerine kurulmuştur;
> - Şeffaflık: Projenin ilerleyişi, sorunlar,gelişmeler herkes tarafından görülebilir olmalıdır.
> - Denetleme: Projenin ilerleyişi düzenli olarak kontrol edilir.
> - Uyarlama: Proje, yapılabilecek değişikliklere uyum sağlayabilmelidir.
> #### Kanban :
> Yalın Üretim tekniklerinden biri olup üretimi yönetmek için kullanılan görsel bir metottur. Çekme sistemi ile hangi ürünün ne zaman ve ne miktarda üretildiğini kontrol eder.

## Gang of Four(GOF) araştırınız.
>Eric Gamma, Richard Helm, Ralph Johnson ve John Vlissides 1995’te “Design Patterns : Elements of Reusable Object – Oriented Software” kitabını çıkardılar. Bu dörtlü ayrıca "Gang of Four" olarak da bilinir. Bu dörtlü kitaplarında 3 kategoride 23 farklı kalıba yer vermişlerdir. Aralarında en sık kullanılanlar şunlardır;
> - Creational: Nesneleri yaratmakta kullanılan 5 adet tasarım kalıbı.
> - Structural: Nesneler arasındaki yapıları ifade eden ilişkilerden 7 adet tasarım kalıbı
> - Behavioral: Nesnelerin çalışma zamanına ait davranışlarını değiştirmek için oluşturulan tasarımlardan 11 adet tasarım kalıbı

## Interface ve Abstract sınıflar arasındaki farklar nelerdir?
> #### Abstraction:
> OOP içerisindeki önemli kavramlardan birisidir. C#’taki soyutlama; diğer Object Oriented dillerde olduğu gibi iç detayları gizleyerek sadece işlevleri göstermeye denir.
> #### Interface:
> İçerisinde sadece kendisinden türeyecek olan sınıfların içini dolduracağı metod tanımlarının bulunduğu ve soyutlama yapmamıza olanak sağlayan bir yapıdır.
> #### Farklar:
> - Interface ve abstract class’lar new anahtar sözcüğü ile oluşturulamazlar.
> - Bir sınıf birden fazla interface’i kalıtım olarak alabilir ama bir sınıfa bir tane abstract class kalıtım alınabilir.
> - Interface içerisinde boş metodlar tanımlanabilir ama abstract class’larda hem boş metodlar tanımlanabilir hemde içi dolu metodlar tanımlabilir.
> - Abstract sınıflar içerisinde metod gövdeleri tanımlanıp özellik değerleri ayarlandığı için genellikle sonradan üzerine ek geliştirilmek yapmak için kullanılır ama interface de ise body ve değer set edilemediği için tamamen interface üzerinden tüm üyeleri implemente edilerek sıfırdan geliştirmeler yapılması gereken durumlarda kullanılır.
> - Abstract class’lar içerisinde sadece abstract olarak işaretlenmiş metod ve özellikler implement edilmek zorundadır fakat interface içerisindeki tüm özellik ve metodlar implement edilmek zorundadır.
> - Bir class bir tane abstract class’ı kalıtım olarak alabilir ama bir class istenilen sayıda interface’i kalıtım olarak alabilir.
> - Interface içerisinde özellik ve metodlarda erişim belirleyiciler kullanılmaz herşey public olarak kabul edilir fakat abstract sınıflarda kullanılabilir.
> - Abstract sınıflara diğer sınıf ve interface’ler kalıtım olarak geçilebilir fakat interface’e yine farklı interface’ler haricinde herhangi bir yapı kalıtım olarak geçilemez.



