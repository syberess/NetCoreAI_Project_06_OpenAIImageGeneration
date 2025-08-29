# 🖼️ NetCoreAI Project 06 - OpenAI Image Generation (DALL·E)

Bu proje, **.NET Console Application** kullanarak **OpenAI Image Generation API (DALL·E)** üzerinden görsel üretimi yapmaktadır.  
Kullanıcıdan alınan bir prompt (örn: *"a futuristic city in the clouds"*) API’ye gönderilir ve model tarafından görsel URL’si döndürülür.  

---

## 🛠️ Kullanılan Teknolojiler
- .NET 8 / 9 Console Application  
- OpenAI Image Generation API (`/v1/images/generations`)  
- Newtonsoft.Json (JSON serialize/deserialize)  
- HttpClient (API isteği için)  

---

## 📂 Proje Yapısı
- `Program.cs` → Kullanıcıdan prompt alır, API’ye gönderir ve dönen sonucu yazdırır.  
- `.csproj` → Proje yapılandırma dosyası  

---

## ⚙️ Kurulum ve Çalıştırma
1. Repo’yu klonla:
   git clone https://github.com/kullaniciadiniz/NetCoreAI_Project_06_OpenAIImageGeneration.git
   cd NetCoreAI_Project_06_OpenAIImageGeneration
Program.cs içinde kendi OpenAI API anahtarını ekle:
string apiKey = "YOUR_API_KEY";
Konsol uygulamasını çalıştır:
dotnet run
Örnek kullanım:
Example prompts:
> A cute robot reading a book in a library
Konsolda JSON çıktı olarak görsel URL’si dönecektir.

✨ Özellikler
✔️ Konsoldan prompt alma

✔️ OpenAI DALL·E API ile görsel üretme

✔️ JSON çıktısını konsola yazdırma

✔️ 1024x1024 çözünürlükte görsel oluşturma

﻿
