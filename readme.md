# Kedi Sahiplenme Uygulaması

Bu uygulama, farklı kedi türlerini listeler ve kullanıcılara sahiplenme talebi gönderme imkanı sunar.

## Nasıl Çalışır?

Uygulama, React kullanarak oluşturulmuştur ve kedi verilerini yerel olarak içermektedir. Kullanıcılar, kedi listesinden bir kedi seçebilir ve sahiplenme talebi gönderebilirler.

## Kod Açıklaması

```jsx
import { useState } from 'react'
import { cats } from './data'
import orderBy from 'lodash/orderBy'
import { AdoptCatForm } from './adopt-form'

import styles from './styles.module.scss'

export default function App() {
  // ... (Kodun geri kalanı)
}

export const AdoptCatForm = ({ cat }) => {
  // ... (Kodun geri kalanı)
}
```

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
