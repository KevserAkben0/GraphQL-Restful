# RESTful vs GraphQL API

## 1. Application Programming Interface (API) Nedir?

API, uygulamaların birbiriyle iletişim kurmasını sağlayan bir arayüzdür.  

- Client ile Server arasında köprü görevi görür  
- Modern web uygulamalarının temel bileşenidir  

---

# 2. RESTful API Nedir?

REST (Representational State Transfer), web servisleri tasarlamak için kullanılan mimari bir yaklaşımdır.

Özellikleri:

- HTTP metodları kullanılır (GET, POST, PUT, DELETE vb.)
- Stateless yapıya sahiptir (sunucu istemci durumunu saklamaz)

---

## 2.1 RESTful Avantajları

- Öğrenmesi kolaydır  
- Uzun süredir kullanıldığı için yaygındır  
- Standart bir yapıya sahiptir  
- Cache (önbellek) desteği güçlüdür  
- Basit mimariye sahiptir  

---

## 2.2 RESTful Dezavantajları

- Overfetching (gereksiz veri alma)  
- Underfetching (yetersiz veri alma)  
- Büyük projelerde endpoint sayısı artar  

---

# 3. GraphQL Nedir?

GraphQL, API’lerle veri alışverişi yapmak için kullanılan modern bir sorgulama dilidir.

3 ana bileşenden oluşur:

- Schema  
- Query  
- Resolver  

Özelliği:  
👉 İhtiyaç kadar veri almayı sağlar.

---

## 3.1 GraphQL Avantajları

- Overfetching yoktur  
- Tek endpoint kullanılır  
- Frontend tarafı daha esnektir  
- Büyük ve karmaşık projelerde güçlüdür  

---

## 3.2 GraphQL Dezavantajları

- Öğrenmesi daha zordur  
- Cache yönetimi zordur  
- Sunucuya daha fazla yük bindirebilir  
- Küçük projelerde gereksiz olabilir  

---

# 4. REST vs GraphQL Karşılaştırma

| Özellik | RESTful | GraphQL |
|---------|---------|---------|
| Veri Alma | Sabit endpoint | İhtiyaca göre veri |
| Endpoint Sayısı | Çok olabilir | Tek endpoint |
| Öğrenme | Kolay | Daha zor |
| Performans | Küçük projede iyi | Büyük projede iyi |
| Cache | Güçlü | Daha zor |

---

# Sonuç

RESTful API’ler basit ve standart çözümler sunarken,  
GraphQL özellikle büyük ve esnek veri ihtiyaçları olan projelerde daha avantajlıdır.

Projeye göre doğru yaklaşımı seçmek gerekir.

---
Endpoint-labs intern project

