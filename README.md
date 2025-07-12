# 🏦 Console Banking System

A simple and secure console-based banking system built in Java.

## ✨ Features

- 🔐 **User Authentication** - Secure login with password hashing
- 💳 **Account Management** - Create and manage bank accounts
- 💰 **Transaction Operations** - Deposit, withdraw, and transfer money
- 👤 **Profile Management** - Update personal information and passwords
- 📊 **Transaction History** - View detailed transaction logs
- 💾 **Data Persistence** - Automatic data saving to files

## 🚀 Quick Start

### Prerequisites
- Java 8 or higher
- Git

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/ConsoleBankingSystem.git

# Navigate to project directory
cd ConsoleBankingSystem

# Compile the project
javac -d out src/*.java

# Run the application
java -cp out Main
```

## 📁 Project Structure

```
ConsoleBankingSystem/
├── src/
│   ├── Main.java              # Application entry point
│   ├── models/
│   │   ├── User.java          # User model
│   │   ├── Account.java       # Account model
│   │   └── Transaction.java   # Transaction model
│   ├── services/
│   │   ├── BankService.java   # Core banking operations
│   │   ├── FileService.java   # File I/O operations
│   │   └── UserProfileService.java # User profile management
│   └── ui/
│       └── Menu.java          # User interface
├── data/                      # Data storage directory
└── README.md
```

## 🎯 Usage

1. **Start the application** - Run `java -cp out Main`
2. **Register or Login** - Create a new account or sign in
3. **Choose operations** - Use the menu to perform banking tasks
4. **Manage your account** - View balance, make transactions, update profile

## 🔧 Main Features

### Banking Operations
- **Deposit**: Add money to your account
- **Withdraw**: Remove money from your account
- **Transfer**: Send money to other users
- **Balance Check**: View current account balance

### Profile Management
- **Update Information**: Change name, email, phone
- **Change Password**: Secure password updates
- **View Profile**: See your account details

### Security
- **Password Hashing**: Secure password storage
- **Input Validation**: Robust error handling
- **Data Encryption**: Protected file storage

## 🛠️ Technical Details

- **Language**: Java 8+
- **Architecture**: MVC pattern with service layer
- **Data Storage**: File-based persistence
- **Security**: SHA-256 password hashing

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


---

**Made with ❤️ for learning Java programming**

---

# 🏦 Konsol Bankacılık Sistemi

Java ile geliştirilmiş basit ve güvenli konsol tabanlı bankacılık sistemi.

## ✨ Özellikler

- 🔐 **Kullanıcı Kimlik Doğrulama** - Şifre hashleme ile güvenli giriş
- 💳 **Hesap Yönetimi** - Banka hesapları oluşturma ve yönetme
- 💰 **İşlem Operasyonları** - Para yatırma, çekme ve transfer
- 👤 **Profil Yönetimi** - Kişisel bilgileri ve şifreleri güncelleme
- 📊 **İşlem Geçmişi** - Detaylı işlem kayıtlarını görüntüleme
- 💾 **Veri Saklama** - Dosyalara otomatik veri kaydetme

## 🚀 Hızlı Başlangıç

### Gereksinimler
- Java 8 veya üzeri
- Git

### Kurulum
```bash
# Repository'yi klonlayın
git clone https://github.com/yourusername/ConsoleBankingSystem.git

# Proje dizinine gidin
cd ConsoleBankingSystem

# Projeyi derleyin
javac -d out src/*.java

# Uygulamayı çalıştırın
java -cp out Main
```

## 📁 Proje Yapısı

```
ConsoleBankingSystem/
├── src/
│   ├── Main.java              # Uygulama giriş noktası
│   ├── models/
│   │   ├── User.java          # Kullanıcı modeli
│   │   ├── Account.java       # Hesap modeli
│   │   └── Transaction.java   # İşlem modeli
│   ├── services/
│   │   ├── BankService.java   # Temel bankacılık işlemleri
│   │   ├── FileService.java   # Dosya I/O işlemleri
│   │   └── UserProfileService.java # Kullanıcı profil yönetimi
│   └── ui/
│       └── Menu.java          # Kullanıcı arayüzü
├── data/                      # Veri saklama dizini
└── README.md
```

## 🎯 Kullanım

1. **Uygulamayı başlatın** - `java -cp out Main` komutunu çalıştırın
2. **Kayıt olun veya giriş yapın** - Yeni hesap oluşturun veya giriş yapın
3. **İşlem seçin** - Bankacılık işlemleri için menüyü kullanın
4. **Hesabınızı yönetin** - Bakiye görüntüleme, işlem yapma, profil güncelleme

## 🔧 Ana Özellikler

### Bankacılık İşlemleri
- **Para Yatırma**: Hesabınıza para ekleme
- **Para Çekme**: Hesabınızdan para çekme
- **Transfer**: Diğer kullanıcılara para gönderme
- **Bakiye Sorgulama**: Mevcut hesap bakiyesini görüntüleme

### Profil Yönetimi
- **Bilgi Güncelleme**: Ad, e-posta, telefon değiştirme
- **Şifre Değiştirme**: Güvenli şifre güncellemeleri
- **Profil Görüntüleme**: Hesap detaylarınızı görme

### Güvenlik
- **Şifre Hashleme**: Güvenli şifre saklama
- **Girdi Doğrulama**: Sağlam hata yönetimi
- **Veri Şifreleme**: Korumalı dosya saklama

## 🛠️ Teknik Detaylar

- **Dil**: Java 8+
- **Mimari**: Servis katmanlı MVC deseni
- **Veri Saklama**: Dosya tabanlı kalıcılık
- **Güvenlik**: SHA-256 şifre hashleme

## 🤝 Katkıda Bulunma

1. Repository'yi fork edin
2. Özellik dalı oluşturun (`git checkout -b feature/harika-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Harika özellik ekle'`)
4. Dalı push edin (`git push origin feature/harika-ozellik`)
5. Pull Request açın

---

**Java programlama öğrenmek için ❤️ ile yapıldı** 
