# Kitap Satış Platformu

Bu proje, kullanıcıların kayıt olup giriş yapabildiği, ardından adres bilgilerini girerek kitap siparişi verebildiği bir e-ticaret uygulamasıdır. Kullanıcılar kitapları inceleyebilir, sipariş oluşturabilir ve çıkış yapabilirler.

## Teknolojiler

### Backend (Java, Spring Boot)
- Spring Boot 3.x
- Spring Security
- Spring Data JPA
- Hibernate
- MySQL
- JWT (Kimlik Doğrulama)
- Stripe (Ödeme Entegrasyonu)
- Lombok

### Frontend (React)
- React 18
- Vite
- React Router DOM
- Redux Toolkit
- Axios
- Material UI / Bootstrap
- React Toastify
- Stripe Entegrasyonu

## Özellikler
- Kullanıcı kaydı ve girişi (JWT ile güvenli kimlik doğrulama)
- Kullanıcı adres bilgisi ekleme ve düzenleme
- Kitap bilgileri: kategori, fiyat, resim, açıklama vb.
- Kitap siparişi verme
- Sipariş takibi
- Güvenli çıkış yapma (logout)
- Stripe ile ödeme işlemleri

## Projeyi Çalıştırma

1. Projeyi klonlayın:
    ```bash
    git clone https://github.com/MohamedAbdullaElfaituri/BuyNow.git
    cd marketplace-main
    ```

2. Backend kısmını çalıştırın:
    ```bash
    cd backend
    ./mvnw spring-boot:run
    ```

3. Frontend kısmını çalıştırın:
    ```bash
    cd frontend
    npm install
    npm run dev
    ```
    
---

