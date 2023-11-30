# Kedi Sahiplenme Uygulaması

Bu uygulama, farklı kedi türlerini listeler ve kullanıcılara sahiplenme talebi gönderme imkanı sunar.

## Nasıl Çalışır?

Uygulama, React kullanarak oluşturulmuştur ve kedi verilerini yerel olarak içermektedir. Kullanıcılar, kedi listesinden bir kedi seçebilir ve sahiplenme talebi gönderebilirler.

## Kod Açıklaması

Bu uygulama, React kullanarak oluşturulmuş basit bir kedi sahiplenme uygulamasıdır. Temel olarak, kullanıcıların kedi listesinden bir kedi seçmelerine ve sahiplenme talebi göndermelerine olanak tanır. Aşağıda kodun bazı önemli kısımları açıklanmıştır:

- `useState` hook'u kullanılarak, uygulama içindeki dinamik durumları yönetmek için state'ler tanımlanmıştır. Örneğin, seçili kedi, sıralama tipi ve görüntüleme sayıları için state'ler bulunmaktadır.

- `orderBy` fonksiyonu, lodash kütüphanesinden kullanılarak, kedi listesini isme göre artan veya azalan şekilde sıralamak için kullanılmıştır.

- `ListItem` bileşeni, her bir kedi öğesini temsil eder. Kullanıcılar, bu öğelere tıklayarak kedi seçebilir ve bu öğe üzerinden kedinin profiline ulaşabilirler.

- Kullanıcı, seçili kedi üzerinden sahiplenme talebi gönderebilir. Bu, `AdoptCatForm` bileşeni ile gerçekleştirilir.

Bu proje üzerinden, React state yönetimi, bileşen iletişimi, lodash kütüphanesi kullanımı ve temel uygulama akışının nasıl tasarlanacağı konularında pratik yapılmıştır. Ayrıca, basit bir form kullanarak kullanıcı girişleri almak ve bunları işlemek gibi temel yetenekler de öğrenilmiştir.

Bu kod parçası, basit bir kedi sahiplenme uygulamasını içerir. Kullanıcılar, kedi listesinden bir kedi seçebilir ve sahiplenme talebi gönderebilirler.

## Kullanım

1. Kediler arasında gezinmek için liste üzerindeki kedi düğmelerine tıklayın.
2. Kedi seçtikten sonra, alt kısımda sahiplenme formu görünecektir.
3. Sahiplenme talebinde bulunmak için formu doldurun ve gönderin.

## Notlar

- Kedi listesi, uygulama içinde yerel olarak tanımlanmıştır.
- Kullanıcılar, kedi seçtikten sonra sahiplenme talebi gönderebilirler.
- Sıralama düğmesi, kedi listesini isme göre artan veya azalan şekilde sıralamak için kullanılabilir.

Uygulamanın geliştirilmesi veya özelleştirilmesi için kodu inceleyebilir ve ihtiyaca göre değişiklikler yapabilirsiniz.

```

```
